#  PUT Create

```
db.put(doc, [docId], [docRev], [options], [callback]);

var doc = {
  _id: "jsoxford",
  event: "JSOxford",
  type: "Meetup",
  date: "2015-02-17"
}
db.put(doc, function(err, response) {
  if (err) { return console.log(err); }
  // handle response
});
```
