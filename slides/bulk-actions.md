#  Bulk Actions

Create
```
db.bulkDocs(docs, [options], [callback]);
db.bulkDocs([
  {event: "JSOxford",}, {event : "Render"}
], function(err, response) {
  if (err) { return console.log(err); }
  // handle result
});
```

Read
```
db.allDocs([options], [callback]);
db.allDocs({
  include_docs: true,
  attachments: true
}, function(err, response) {
  if (err) { return console.log(err); }
  // handle result
});
```
