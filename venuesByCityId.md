## Venues By City ID

Use the venue by city ID endpoint to get a list of venues in a particular city. You can use this to setup a page similar to this one on the Tablelist website: https://www.tablelist.com/nyc/discover/.

### Request

```js
GET https://api.tablelist.com/city/{{ cityId }}/venue
```

### Response

```js
[{
  "publish":{
    "tablelist":true
  },
  "location":{
    "address":{
      "address":"1234 Soldiers Field Road",
      "city":"Boston",
      "state":"MA",
      "country":"United States",
      "zip":"02135"
    },
    "geo":[],
    "city":"301072f4d252999a",
    "timezone":"America/New_York"
  },
  "rating":{
    "ratingAverage":0,
    "ratingTotal":0,
    "ratingCount":0
  },
  "details":{
    "cover":{
      "alwaysCharges":false,
      "sometimesCharges":false
    },
    "pricing":{
      "negotiable":false,
      "offerSpecials":false
    },
    "bestNights":[],
    "description":"<p>Casa Cana is a Latin kitchen, patio &amp; rum bar that features innovative New Latin cuisine, or as the Latin Americans locals call it, &#8220;Nuevo Latino.&#8221;</p><p>This style of cooking uses traditional ingredients and a plethora of textures, colors, and flavors that when combined, create a cuisine that is unique to South and Central America, and it&#8217;s Latin neighbors in the Caribbean.</p><p><br/></p><p>The feeling of &#8220;SOMOS FIESTA&#8221; is echoed throughout, as the bar and patio are fueled by the creative cocktail list that takes inspiration from all over Latin America.</p><p><br/></p><p>The restaurant is a celebration of Latin culture and style. It offers a taste of Havana&#8217;s high-life, and honors it&#8217;s heritage with a sense of nostalgia through food, drink, music, and joy.</p>","shortDescription":"“A culinary exploration of the other Americas”",
    "policies":[],
    "menus":[],
    "floorPlans":[]
  },
  "deleted":false,
  "phone":"6174155402",
  "email":null,
  "currencyCode":"USD",
  "languageCode":"en",
  "favoriteCount":0,
  "special":false,
  "accessLevel":0,
  "inventoryTimeframe":7,
  "inventorySortOrder":"PRICE_LOW_TO_HIGH",
  "_id":"8931dfc0b8dcaa14",
  "name":"Cas Cana Boston",
  "slug":"cas-cana-boston",
  "website":"https://casacanaboston.com/",
  "type":"Lounge",
  "subtype":null,
  "images":[{
    "deleted":false,
    "modified":1556724682143,
    "created":1556724682142,
    "filename":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png",
    "primary":true,"_id":"e793d36e487134f8",
    "xlarge":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png?w=1200&fm=jpg&q=50",
    "large":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png?w=1200&fm=jpg&q=50",
    "medium":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png?w=800&fm=jpg&q=50",
    "small":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png?w=320&fm=jpg&q=50",
    "id":"e793d36e487134f8"
  }],
  "schedule":[{
    "closed":true,
    "hours":[],
    "day":1,
    "id":null
  },{
    "closed":true,
    "hours":[],
    "day":2,
    "id":null
  },{
    "closed":true,
    "hours":[],
    "day":3,
    "id":null
  },{
    "closed":true,
    "hours":[],
    "day":4,
    "id":null
  },{
    "closed":true,
    "hours":[],
    "day":5,
    "id":null
  },{
    "closed":true,
    "hours":[],
    "day":6,
    "id":null
  },{
    "closed":true,
    "hours":[],
    "day":0,
    "id":null
  }],
  "tags":[{
    "key":"VENUE_TYPE",
    "name":"Lounge",
    "value":"VENUE_TYPE_LOUNGE",
    "id":"VENUE_TYPE_LOUNGE"
  }],
  "modified":1556724691531,
  "created":1556724596488,
  "seoPathname":"cas-cana-boston-boston-8931dfc0b8dcaa14",
  "enable":true,
  "currencySymbol":"$",
  "primaryImage":{
    "deleted":false,
    "modified":1556724682143,
    "created":1556724682142,
    "filename":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png",
    "primary":true,
    "_id":"e793d36e487134f8",
    "xlarge":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png?w=1200&fm=jpg&q=50",
    "large":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png?w=1200&fm=jpg&q=50",
    "medium":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png?w=800&fm=jpg&q=50",
    "small":"https://moth.imgix.net/7af8bcb6-ae6b-23e9-ad1ac0b46483.png?w=320&fm=jpg&q=50",
    "id":"e793d36e487134f8"
  }
}]
```
