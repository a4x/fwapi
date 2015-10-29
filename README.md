
# **Players**
----

**List players**
----
  Returns list of players - use this endpoint for autocomplete

* **URL**

  `GET /players?search=:search&embed=:embed`

*  **URL Params**

   `search=[string] (optional)`
   `embed=[string] (optional)`
   `per_page=[integer] (optional)`
   `page=[integer] (optional)`

* **Success Response:**

  * **Code:** 200 OK

    **Content:**
``` json
{
  "data":[
    {
      "id": 5678,
      "opta_id": "p59936",
      "first_name": "Wojciech",
      "last_name": "Szczesny",
      "known_name": "Unknown",
      "birth_date": "1990-04-18",
      "birth_place": "Warszawa",
      "first_nationality": "Poland",
      "weight": 84,
      "height": 196,
      "jersey_num": 1,
      "position": "Goalkeeper",
      "real_position": "Goalkeeper",
      "real_position_side": "Unknown",
      "join_date": "2008-07-01",
      "country": "Poland",
      "preferred_foot": "Left",
      "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
      "twitter": "13szczesny13",
      "instagram": "wojciechszczesny1",
      "team_id": 1234,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      }
    },{
      "id": 5678,
      "opta_id": "p59936",
      "first_name": "Wojciech",
      "last_name": "Szczesny",
      "known_name": "Unknown",
      "birth_date": "1990-04-18",
      "birth_place": "Warszawa",
      "first_nationality": "Poland",
      "weight": 84,
      "height": 196,
      "jersey_num": 1,
      "position": "Goalkeeper",
      "real_position": "Goalkeeper",
      "real_position_side": "Unknown",
      "join_date": "2008-07-01",
      "country": "Poland",
      "preferred_foot": "Left",
      "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
      "twitter": "13szczesny13",
      "instagram": "wojciechszczesny1",
      "team_id": 1234,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      }
    },{
      "id": 5678,
      "opta_id": "p59936",
      "first_name": "Wojciech",
      "last_name": "Szczesny",
      "known_name": "Unknown",
      "birth_date": "1990-04-18",
      "birth_place": "Warszawa",
      "first_nationality": "Poland",
      "weight": 84,
      "height": 196,
      "jersey_num": 1,
      "position": "Goalkeeper",
      "real_position": "Goalkeeper",
      "real_position_side": "Unknown",
      "join_date": "2008-07-01",
      "country": "Poland",
      "preferred_foot": "Left",
      "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
      "twitter": "13szczesny13",
      "instagram": "wojciechszczesny1",
      "team_id": 1234,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      }
    },{
      "id": 5678,
      "opta_id": "p59936",
      "first_name": "Wojciech",
      "last_name": "Szczesny",
      "known_name": "Unknown",
      "birth_date": "1990-04-18",
      "birth_place": "Warszawa",
      "first_nationality": "Poland",
      "weight": 84,
      "height": 196,
      "jersey_num": 1,
      "position": "Goalkeeper",
      "real_position": "Goalkeeper",
      "real_position_side": "Unknown",
      "join_date": "2008-07-01",
      "country": "Poland",
      "preferred_foot": "Left",
      "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
      "twitter": "13szczesny13",
      "instagram": "wojciechszczesny1",
      "team_id": 1234,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      }
    },{
      "id": 5678,
      "opta_id": "p59936",
      "first_name": "Wojciech",
      "last_name": "Szczesny",
      "known_name": "Unknown",
      "birth_date": "1990-04-18",
      "birth_place": "Warszawa",
      "first_nationality": "Poland",
      "weight": 84,
      "height": 196,
      "jersey_num": 1,
      "position": "Goalkeeper",
      "real_position": "Goalkeeper",
      "real_position_side": "Unknown",
      "join_date": "2008-07-01",
      "country": "Poland",
      "preferred_foot": "Left",
      "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
      "twitter": "13szczesny13",
      "instagram": "wojciechszczesny1",
      "team_id": 1234,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      }
    }
  ],
  "meta": {
    "pagination":{
      "total":10,
      "count":5,
      "per_page":5,
      "current_page":1,
      "total_pages":2,
      "links":{
        "next":"http://api.xxx.com/players?page=2"
      }
    }
  }
}
```

**Show player**
----
Show a player

* **URL**

  `GET /players/:player_id?embed=:embed`

* **Success Response:**

* **Code:** 200 OK

**Content:**
```json
{
  "id": 5678,
  "opta_id": "p59936",
  "first_name": "Wojciech",
  "last_name": "Szczesny",
  "known_name": "Unknown",
  "birth_date": "1990-04-18",
  "birth_place": "Warszawa",
  "first_nationality": "Poland",
  "weight": 84,
  "height": 196,
  "jersey_num": 1,
  "position": "Goalkeeper",
  "real_position": "Goalkeeper",
  "real_position_side": "Unknown",
  "join_date": "2008-07-01",
  "country": "Poland",
  "preferred_foot": "Left",
  "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
  "twitter": "13szczesny13",
  "instagram": "wojciechszczesny1",
  "team_id": 1234,
  "team": {
    "id": 1234,
    "opta_id": "t3",
    "name": "Arsenal",
    "country": "England",
    "city": "London",
    "postal_code": "N5 1BU",
    "short_club_name": "Arsenal",
    "street": "75 Drayton Park",
    "web_address": "http://www.arsenal.com",
    "founded": "1886",
    "SYMID": "ARS",
    "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
    "stadium": "Emirates Stadium",
    "transfers_in": 11,
    "transfers_out": 11,
    "instagram": "@loremipsum",
    "twitter": "@loremipsum"
  }
}
```

# **Articles**
----

**List articles**
----
  List articles from Radar API.
  Bodies might be trimmed to 500 words.

* **URL**

  `GET /articles`

*  **URL Params**

   `player_id=[integer] (optional)`
   `team_id=[integer] (optional)`
   `per_page=[integer] (optional)`
   `page=[integer] (optional)`

* **Success Response:**

  * **Code:** 200 OK

    **Content:**
``` json
{
  "data":[
    {
      "id": 1234,
      "headline": "Lorem ipsum dolor sit amet",
      "body": "Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet...",
      "image": "http://i.telegraph.co.uk/multimedia/archive/03119/real-madrid-logo_3119467a.jpg",
      "url": "http://i.telegraph.co.uk/multimedia/archive/03119",
      "relevancy_score": 3,
      "type": "Facebook",
      "platform": "Facebook",
      "domain": "???",
      "language": "???"
    },{
      "id": 1234,
      "headline": "Lorem ipsum dolor sit amet",
      "body": "Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet...",
      "image": "http://i.telegraph.co.uk/multimedia/archive/03119/real-madrid-logo_3119467a.jpg",
      "url": "http://i.telegraph.co.uk/multimedia/archive/03119",
      "relevancy_score": 3,
      "type": "Facebook",
      "platform": "Facebook",
      "domain": "???",
      "language": "???"
    },{
      "id": 1234,
      "headline": "Lorem ipsum dolor sit amet",
      "body": "Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet...",
      "image": "http://i.telegraph.co.uk/multimedia/archive/03119/real-madrid-logo_3119467a.jpg",
      "url": "http://i.telegraph.co.uk/multimedia/archive/03119",
      "relevancy_score": 3,
      "type": "Facebook",
      "platform": "Facebook",
      "domain": "???",
      "language": "???"
    },{
      "id": 1234,
      "headline": "Lorem ipsum dolor sit amet",
      "body": "Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet...",
      "image": "http://i.telegraph.co.uk/multimedia/archive/03119/real-madrid-logo_3119467a.jpg",
      "url": "http://i.telegraph.co.uk/multimedia/archive/03119",
      "relevancy_score": 3,
      "type": "Facebook",
      "platform": "Facebook",
      "domain": "???",
      "language": "???"
    },{
      "id": 1234,
      "headline": "Lorem ipsum dolor sit amet",
      "body": "Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet",
      "image": "http://i.telegraph.co.uk/multimedia/archive/03119/real-madrid-logo_3119467a.jpg",
      "url": "http://i.telegraph.co.uk/multimedia/archive/03119",
      "relevancy_score": 3,
      "type": "Facebook",
      "platform": "Facebook",
      "domain": "???",
      "language": "???"
    }
  ],
  "meta": {
    "pagination":{
      "total":10,
      "count":5,
      "per_page":5,
      "current_page":1,
      "total_pages":2,
      "links":{
        "next":"http://api.xxx.com/players/xxx/teams?page=2"
      }
    }
  }
}
```

**Show article**
----
  Show one article from Radar API.

* **URL**

  `GET /articles/:article_id`

*  **URL Params**

   `article_id=[integer] (required)`

* **Success Response:**

  * **Code:** 200 OK

    **Content:**
``` json
{
  "id": 1234,
  "headline": "Lorem ipsum dolor sit amet",
  "body": "Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet",
  "image": "http://i.telegraph.co.uk/multimedia/archive/03119/real-madrid-logo_3119467a.jpg",
  "url": "http://i.telegraph.co.uk/multimedia/archive/03119",
  "relevancy_score": 3,
  "type": "Facebook",
  "platform": "Facebook",
  "domain": "???",
  "language": "???"
}
```

# **Teams**
----

**List teams**
----
  List teams

* **URL**

  `GET /teams?search=:search`

*  **URL Params**

   `search=[string] (optional)`

* **Success Response:**

  * **Code:** 200 OK

    **Content:**
``` json
{
  "data":[
    {
      "id": 1234,
      "opta_id": "t3",
      "name": "Arsenal",
      "country": "England",
      "city": "London",
      "postal_code": "N5 1BU",
      "short_club_name": "Arsenal",
      "street": "75 Drayton Park",
      "web_address": "http://www.arsenal.com",
      "founded": "1886",
      "SYMID": "ARS",
      "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
      "stadium": "Emirates Stadium",
      "transfers_in": 11,
      "transfers_out": 11,
      "instagram": "@loremipsum",
      "twitter": "@loremipsum"
    },{
      "id": 1234,
      "opta_id": "t3",
      "name": "Arsenal",
      "country": "England",
      "city": "London",
      "postal_code": "N5 1BU",
      "short_club_name": "Arsenal",
      "street": "75 Drayton Park",
      "web_address": "http://www.arsenal.com",
      "founded": "1886",
      "SYMID": "ARS",
      "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
      "stadium": "Emirates Stadium",
      "transfers_in": 11,
      "transfers_out": 11,
      "instagram": "@loremipsum",
      "twitter": "@loremipsum"
    },{
      "id": 1234,
      "opta_id": "t3",
      "name": "Arsenal",
      "country": "England",
      "city": "London",
      "postal_code": "N5 1BU",
      "short_club_name": "Arsenal",
      "street": "75 Drayton Park",
      "web_address": "http://www.arsenal.com",
      "founded": "1886",
      "SYMID": "ARS",
      "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
      "stadium": "Emirates Stadium",
      "transfers_in": 11,
      "transfers_out": 11,
      "instagram": "@loremipsum",
      "twitter": "@loremipsum"
    },{
      "id": 1234,
      "opta_id": "t3",
      "name": "Arsenal",
      "country": "England",
      "city": "London",
      "postal_code": "N5 1BU",
      "short_club_name": "Arsenal",
      "street": "75 Drayton Park",
      "web_address": "http://www.arsenal.com",
      "founded": "1886",
      "SYMID": "ARS",
      "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
      "stadium": "Emirates Stadium",
      "transfers_in": 11,
      "transfers_out": 11,
      "instagram": "@loremipsum",
      "twitter": "@loremipsum"
    },{
      "id": 1234,
      "opta_id": "t3",
      "name": "Arsenal",
      "country": "England",
      "city": "London",
      "postal_code": "N5 1BU",
      "short_club_name": "Arsenal",
      "street": "75 Drayton Park",
      "web_address": "http://www.arsenal.com",
      "founded": "1886",
      "SYMID": "ARS",
      "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
      "stadium": "Emirates Stadium",
      "transfers_in": 11,
      "transfers_out": 11,
      "instagram": "@loremipsum",
      "twitter": "@loremipsum"
    }
  ],
  "meta": {
    "pagination":{
      "total":10,
      "count":5,
      "per_page":5,
      "current_page":1,
      "total_pages":2,
      "links":{
        "next":"http://api.xxx.com/players/xxx/teams?page=2"
      }
    }
  }
}
```

**Show team**
----
  Show team

* **URL**

  `GET /teams/:team_id`

*  **URL Params**

   `team_id=[integer] (required)`

* **Success Response:**

  * **Code:** 200 OK

    **Content:**
``` json
{
  "id": 1234,
  "opta_id": "t3",
  "name": "Arsenal",
  "country": "England",
  "city": "London",
  "postal_code": "N5 1BU",
  "short_club_name": "Arsenal",
  "street": "75 Drayton Park",
  "web_address": "http://www.arsenal.com",
  "founded": "1886",
  "SYMID": "ARS",
  "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
  "stadium": "Emirates Stadium",
  "transfers_in": 11,
  "transfers_out": 11,
  "instagram": "@loremipsum",
  "twitter": "@loremipsum"
}
```

# **Whispers**
----

**List whispers**
----
  List whispers - can be filtered for a player or a team
  By default, result is ordered by FW index, desc.
  By default, only whisper score and player_id / team_id are returned, use 'embed=players,teams' to get full objects

* **URL**

  `GET /whispers?team_id=:team_id&player_id=:player_id&embed=:embed&per_page=:per_page&page=:page`

*  **URL Params**

   `team_id=[integer] (optional)`
   `player_id=[integer] (optional)`
   `embed=[string] (optional) use embed=players to get full players objects`
   `per_page=[integer] (optional)`
   `page=[integer] (optional)`

* **Success Response:**

  * **Code:** 200 OK

    **Content:**
``` json
{
  "data":[
    {
      "id": 1234,
      "fw_index": 3.2,
      "team_id" : 7890,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      },
      "player_id" : 4567,
      "player" : {
        "id": 5678,
        "opta_id": "p59936",
        "first_name": "Wojciech",
        "last_name": "Szczesny",
        "known_name": "Unknown",
        "birth_date": "1990-04-18",
        "birth_place": "Warszawa",
        "first_nationality": "Poland",
        "weight": 84,
        "height": 196,
        "jersey_num": 1,
        "position": "Goalkeeper",
        "real_position": "Goalkeeper",
        "real_position_side": "Unknown",
        "join_date": "2008-07-01",
        "country": "Poland",
        "preferred_foot": "Left",
        "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
        "twitter": "13szczesny13",
        "instagram": "wojciechszczesny1",
        "team_id": 1234,
        "team": {
          "id": 1234,
          "opta_id": "t3",
          "name": "Arsenal",
          "country": "England",
          "city": "London",
          "postal_code": "N5 1BU",
          "short_club_name": "Arsenal",
          "street": "75 Drayton Park",
          "web_address": "http://www.arsenal.com",
          "founded": "1886",
          "SYMID": "ARS",
          "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
          "stadium": "Emirates Stadium",
          "transfers_in": 11,
          "transfers_out": 11,
          "instagram": "@loremipsum",
          "twitter": "@loremipsum"
        }
      }
    },{
      "id": 1234,
      "fw_index": 3.2,
      "team_id" : 7890,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      },
      "player_id" : 4567,
      "player" : {
        "id": 5678,
        "opta_id": "p59936",
        "first_name": "Wojciech",
        "last_name": "Szczesny",
        "known_name": "Unknown",
        "birth_date": "1990-04-18",
        "birth_place": "Warszawa",
        "first_nationality": "Poland",
        "weight": 84,
        "height": 196,
        "jersey_num": 1,
        "position": "Goalkeeper",
        "real_position": "Goalkeeper",
        "real_position_side": "Unknown",
        "join_date": "2008-07-01",
        "country": "Poland",
        "preferred_foot": "Left",
        "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
        "twitter": "13szczesny13",
        "instagram": "wojciechszczesny1",
        "team_id": 1234,
        "team": {
          "id": 1234,
          "opta_id": "t3",
          "name": "Arsenal",
          "country": "England",
          "city": "London",
          "postal_code": "N5 1BU",
          "short_club_name": "Arsenal",
          "street": "75 Drayton Park",
          "web_address": "http://www.arsenal.com",
          "founded": "1886",
          "SYMID": "ARS",
          "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
          "stadium": "Emirates Stadium",
          "transfers_in": 11,
          "transfers_out": 11,
          "instagram": "@loremipsum",
          "twitter": "@loremipsum"
        }
      }
    },{
      "id": 1234,
      "fw_index": 3.2,
      "team_id" : 7890,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      },
      "player_id" : 4567,
      "player" : {
        "id": 5678,
        "opta_id": "p59936",
        "first_name": "Wojciech",
        "last_name": "Szczesny",
        "known_name": "Unknown",
        "birth_date": "1990-04-18",
        "birth_place": "Warszawa",
        "first_nationality": "Poland",
        "weight": 84,
        "height": 196,
        "jersey_num": 1,
        "position": "Goalkeeper",
        "real_position": "Goalkeeper",
        "real_position_side": "Unknown",
        "join_date": "2008-07-01",
        "country": "Poland",
        "preferred_foot": "Left",
        "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
        "twitter": "13szczesny13",
        "instagram": "wojciechszczesny1",
        "team_id": 1234,
        "team": {
          "id": 1234,
          "opta_id": "t3",
          "name": "Arsenal",
          "country": "England",
          "city": "London",
          "postal_code": "N5 1BU",
          "short_club_name": "Arsenal",
          "street": "75 Drayton Park",
          "web_address": "http://www.arsenal.com",
          "founded": "1886",
          "SYMID": "ARS",
          "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
          "stadium": "Emirates Stadium",
          "transfers_in": 11,
          "transfers_out": 11,
          "instagram": "@loremipsum",
          "twitter": "@loremipsum"
        }
      }
    },{
      "id": 1234,
      "fw_index": 3.2,
      "team_id" : 7890,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      },
      "player_id" : 4567,
      "player" : {
        "id": 5678,
        "opta_id": "p59936",
        "first_name": "Wojciech",
        "last_name": "Szczesny",
        "known_name": "Unknown",
        "birth_date": "1990-04-18",
        "birth_place": "Warszawa",
        "first_nationality": "Poland",
        "weight": 84,
        "height": 196,
        "jersey_num": 1,
        "position": "Goalkeeper",
        "real_position": "Goalkeeper",
        "real_position_side": "Unknown",
        "join_date": "2008-07-01",
        "country": "Poland",
        "preferred_foot": "Left",
        "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
        "twitter": "13szczesny13",
        "instagram": "wojciechszczesny1",
        "team_id": 1234,
        "team": {
          "id": 1234,
          "opta_id": "t3",
          "name": "Arsenal",
          "country": "England",
          "city": "London",
          "postal_code": "N5 1BU",
          "short_club_name": "Arsenal",
          "street": "75 Drayton Park",
          "web_address": "http://www.arsenal.com",
          "founded": "1886",
          "SYMID": "ARS",
          "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
          "stadium": "Emirates Stadium",
          "transfers_in": 11,
          "transfers_out": 11,
          "instagram": "@loremipsum",
          "twitter": "@loremipsum"
        }
      }
    },{
      "id": 1234,
      "fw_index": 3.2,
      "team_id" : 7890,
      "team": {
        "id": 1234,
        "opta_id": "t3",
        "name": "Arsenal",
        "country": "England",
        "city": "London",
        "postal_code": "N5 1BU",
        "short_club_name": "Arsenal",
        "street": "75 Drayton Park",
        "web_address": "http://www.arsenal.com",
        "founded": "1886",
        "SYMID": "ARS",
        "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
        "stadium": "Emirates Stadium",
        "transfers_in": 11,
        "transfers_out": 11,
        "instagram": "@loremipsum",
        "twitter": "@loremipsum"
      },
      "player_id" : 4567,
      "player" : {
        "id": 5678,
        "opta_id": "p59936",
        "first_name": "Wojciech",
        "last_name": "Szczesny",
        "known_name": "Unknown",
        "birth_date": "1990-04-18",
        "birth_place": "Warszawa",
        "first_nationality": "Poland",
        "weight": 84,
        "height": 196,
        "jersey_num": 1,
        "position": "Goalkeeper",
        "real_position": "Goalkeeper",
        "real_position_side": "Unknown",
        "join_date": "2008-07-01",
        "country": "Poland",
        "preferred_foot": "Left",
        "headshot-image": "http://essentiallysports.com/wp-content/uploads/2015/01/Szczesny.jpg",
        "twitter": "13szczesny13",
        "instagram": "wojciechszczesny1",
        "team_id": 1234,
        "team": {
          "id": 1234,
          "opta_id": "t3",
          "name": "Arsenal",
          "country": "England",
          "city": "London",
          "postal_code": "N5 1BU",
          "short_club_name": "Arsenal",
          "street": "75 Drayton Park",
          "web_address": "http://www.arsenal.com",
          "founded": "1886",
          "SYMID": "ARS",
          "badge": "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/440px-Arsenal_FC.svg.png",
          "stadium": "Emirates Stadium",
          "transfers_in": 11,
          "transfers_out": 11,
          "instagram": "@loremipsum",
          "twitter": "@loremipsum"
        }
      }
    }
  ],
  "meta": {
    "pagination":{
      "total":10,
      "count":5,
      "per_page":5,
      "current_page":1,
      "total_pages":2,
      "links":{
        "next":"http://api.xxx.com/whispers?page=2"
      }
    }
  }
}
```
