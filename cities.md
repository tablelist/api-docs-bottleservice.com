## Cities

Use the cities endpoint to get a list of all cities that are available on the Tablelist Platform:

### Request

```js
GET https://api.tablelist.com/city?version=2.33.0&limit=100&sort=-name
```

### Response

```js
[{
  "id":"301072f4d252999a",
  "name":"Boston",
  "slugName":"bos",
  "displayName":"Boston, MA",
  "deleted":false,
  "enable":true,
  "rewards":false,
  "comingSoon":false,
  "feedEnable":true,
  "location":[-71.0597732,42.3584308],
  "membershipLevel":0,
  "events":true,
  "neighborhoods":["Back Bay","Beacon Hill","Financial District","Seaport","Theatre District","Cambridge","North End","Methuen","Fenway","West End"],
  "_id":"301072f4d252999a",
  "modified":1520444850501,
  "state":"MA",
  "timezone":"America/New_York",
  "created":1385998538727,
  "slug_name":"boston",
  "images":[{
    "deleted":false,
    "modified":1520444850490,
    "created":1393285919658,
    "xlarge":"https://s3.amazonaws.com/tablelist-images/22/ac/22ac03b5-c7046556-large.jpg",
    "filename":"https://s3.amazonaws.com/tablelist-images/4b/c4/4bc4f7a9-d8ae26f6-original.jpg",
    "small":"https://s3.amazonaws.com/tablelist-images/94/1c/941ce49c-10fb9f14-small.jpg",
    "medium":"https://s3.amazonaws.com/tablelist-images/f0/17/f0171631-c71b9b4b-medium.jpg",
    "large":"https://s3.amazonaws.com/tablelist-images/22/ac/22ac03b5-c7046556-large.jpg",
    "primary":false,
    "_id":"89c92fc99a5066e4",
    "id":"89c92fc99a5066e4"
  },{
    "deleted":false,
    "modified":1520444850499,
    "created":1393285941406,
    "large":"https://s3.amazonaws.com/tablelist-images/7d/03/7d0382cb-c8f9b3da-large.jpg",
    "filename":"https://s3.amazonaws.com/tablelist-images/50/ca/50ca65ff-84e20458-original.jpg",
    "primary":false,
    "xlarge":"https://s3.amazonaws.com/tablelist-images/7d/03/7d0382cb-c8f9b3da-large.jpg",
    "small":"https://s3.amazonaws.com/tablelist-images/14/c9/14c9c0f0-b7ac5216-small.jpg",
    "medium":"https://s3.amazonaws.com/tablelist-images/58/15/5815c295-c6a931f0-medium.jpg",
    "_id":"4f0a65e44c287682",
    "id":"4f0a65e44c287682"
  },{
    "deleted":false,
    "modified":1520444850500,
    "created":1435861496457,
    "_id":"8c5a45e6fffbf5c6",
    "primary":false,
    "small":"https://images.tablelist.com/23/b4/23b43cca-dbdcbbb4-small.jpg",
    "medium":"https://images.tablelist.com/7f/5e/7f5ea5a4-0da065a5-medium.jpg",
    "large":"https://images.tablelist.com/ed/b7/edb77d1c-87b399e5-large.jpg",
    "filename":"https://tablelist-images.s3.amazonaws.com/data/D655-F870-376A-e796f85c.jpg",
    "xlarge":"https://tablelist-images.s3.amazonaws.com/data/D655-F870-376A-e796f85c.jpg?w=1200&fm=jpg&q=50",
    "id":"8c5a45e6fffbf5c6"
  },{
    "deleted":false,
    "modified":1520444850500,
    "created":1472678675620,
    "primary":true,
    "filename":"https://moth.imgix.net/1d860533-e5c0-ffc7-0cdc82a4c89f.jpg",
    "_id":"a1d7ed8888dd972b",
    "xlarge":"https://moth.imgix.net/1d860533-e5c0-ffc7-0cdc82a4c89f.jpg?w=1200&fm=jpg&q=50",
    "large":"https://moth.imgix.net/1d860533-e5c0-ffc7-0cdc82a4c89f.jpg?w=1200&fm=jpg&q=50",
    "medium":"https://moth.imgix.net/1d860533-e5c0-ffc7-0cdc82a4c89f.jpg?w=800&fm=jpg&q=50",
    "small":"https://moth.imgix.net/1d860533-e5c0-ffc7-0cdc82a4c89f.jpg?w=320&fm=jpg&q=50",
    "id":"a1d7ed8888dd972b"
  }]
}]
```
