#  Update

```
db.put(doc, [docId], [docRev], [options], [callback]);

db.get('jsoxford', function(err, doc) {
  if (err) { return console.log(err); }
  db.put({
    _id: 'jsoxford',
    _rev: doc._rev,
    talk: "No Service"
  }, function(err, response) {
    if (err) { return console.log(err); }
    // handle response
  });
});
```
