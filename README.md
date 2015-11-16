# **Players JSON API**
----

**List players**
----
  Returns list of players - use this endpoint for autocomplete

* **URL**

  `GET /players?search=:search&embed=:embed&per_page=:page&page=:page`

*  **URL Params**

   `search=[string] (optional)`
   `embed=[string] (optional)` can be team or whispers, or both CSV
   `per_page=[integer] (optional)`
   `page=[integer] (optional)`

* **Success Response:**

  * **Code:** 200 OK

    **Content:**
``` json
{
   "data":[
      {
         "id":15,
         "first_name":"Jack",
         "last_name":"Wilshere",
         "known_name":"",
         "birth_date":"1992-01-01",
         "birth_place":"",
         "first_nationality":"",
         "weigth":68,
         "height":172,
         "jersey_num":10,
         "position":"Midfielder",
         "real_position":"Attacking Midfielder",
         "real_position_side":"Left",
         "join_date":"2008-07-01",
         "country":"England",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":1,
         "slug":"jack-wilshere",
         "team":{
            "id":1,
            "name":"Arsenal",
            "slug":"arsenal",
            "country":"England",
            "city":"London",
            "postal_code":null,
            "short_club_name":"Arsenal",
            "street":"75 Drayton Park",
            "web_address":"http:\/\/www.arsenal.com",
            "founded":1886,
            "SYMID":null,
            "badge":null,
            "stadium":"Emirates Stadium",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[
            {
               "id":1,
               "fw_index":"3",
               "team_id":1,
               "player_id":15,
               "team":{
                  "id":1,
                  "name":"Arsenal",
                  "slug":"arsenal",
                  "badge":null
               }
            }
         ]
      },
      {
         "id":37,
         "first_name":"Jed",
         "last_name":"Steer",
         "known_name":"",
         "birth_date":"1992-09-23",
         "birth_place":"",
         "first_nationality":"",
         "weigth":89,
         "height":188,
         "jersey_num":13,
         "position":"Goalkeeper",
         "real_position":"Goalkeeper",
         "real_position_side":"Unknown",
         "join_date":"2013-07-01",
         "country":"England",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":2,
         "slug":"jed-steer",
         "team":{
            "id":2,
            "name":"Aston Villa",
            "slug":"aston-villa",
            "country":"England",
            "city":"",
            "postal_code":null,
            "short_club_name":"Aston Villa",
            "street":"",
            "web_address":"",
            "founded":1874,
            "SYMID":null,
            "badge":null,
            "stadium":"Villa Park",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[

         ]
      },
      {
         "id":41,
         "first_name":"Joe",
         "last_name":"Bennett",
         "known_name":"",
         "birth_date":"1990-03-28",
         "birth_place":"",
         "first_nationality":"",
         "weigth":74,
         "height":183,
         "jersey_num":3,
         "position":"Defender",
         "real_position":"Full Back",
         "real_position_side":"Left",
         "join_date":"2012-08-31",
         "country":"England",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":2,
         "slug":"joe-bennett",
         "team":{
            "id":2,
            "name":"Aston Villa",
            "slug":"aston-villa",
            "country":"England",
            "city":"",
            "postal_code":null,
            "short_club_name":"Aston Villa",
            "street":"",
            "web_address":"",
            "founded":1874,
            "SYMID":null,
            "badge":null,
            "stadium":"Villa Park",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[

         ]
      },
      {
         "id":43,
         "first_name":"Jores",
         "last_name":"Okore",
         "known_name":"",
         "birth_date":"1992-08-11",
         "birth_place":"",
         "first_nationality":"",
         "weigth":80,
         "height":183,
         "jersey_num":5,
         "position":"Defender",
         "real_position":"Central Defender",
         "real_position_side":"Centre",
         "join_date":"2013-06-13",
         "country":"Denmark",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":2,
         "slug":"jores-okore",
         "team":{
            "id":2,
            "name":"Aston Villa",
            "slug":"aston-villa",
            "country":"England",
            "city":"",
            "postal_code":null,
            "short_club_name":"Aston Villa",
            "street":"",
            "web_address":"",
            "founded":1874,
            "SYMID":null,
            "badge":null,
            "stadium":"Villa Park",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[

         ]
      },
      {
         "id":64,
         "first_name":"Jordan",
         "last_name":"Bowery",
         "known_name":"",
         "birth_date":"1991-07-02",
         "birth_place":"",
         "first_nationality":"",
         "weigth":76,
         "height":185,
         "jersey_num":21,
         "position":"Forward",
         "real_position":"Striker",
         "real_position_side":"Centre",
         "join_date":"2012-08-31",
         "country":"England",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":2,
         "slug":"jordan-bowery",
         "team":{
            "id":2,
            "name":"Aston Villa",
            "slug":"aston-villa",
            "country":"England",
            "city":"",
            "postal_code":null,
            "short_club_name":"Aston Villa",
            "street":"",
            "web_address":"",
            "founded":1874,
            "SYMID":null,
            "badge":null,
            "stadium":"Villa Park",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[

         ]
      },
      {
         "id":68,
         "first_name":"Joe",
         "last_name":"Lewis",
         "known_name":"",
         "birth_date":"1987-10-06",
         "birth_place":"",
         "first_nationality":"",
         "weigth":85,
         "height":198,
         "jersey_num":32,
         "position":"Goalkeeper",
         "real_position":"Goalkeeper",
         "real_position_side":"Unknown",
         "join_date":"2012-07-01",
         "country":"England",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":3,
         "slug":"joe-lewis",
         "team":{
            "id":3,
            "name":"Cardiff City",
            "slug":"cardiff-city",
            "country":"England",
            "city":"",
            "postal_code":null,
            "short_club_name":"Cardiff",
            "street":"",
            "web_address":"",
            "founded":1899,
            "SYMID":null,
            "badge":null,
            "stadium":"Cardiff City Stadium",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[

         ]
      },
      {
         "id":75,
         "first_name":"John",
         "last_name":"Brayford",
         "known_name":"",
         "birth_date":"1987-12-29",
         "birth_place":"",
         "first_nationality":"",
         "weigth":71,
         "height":173,
         "jersey_num":12,
         "position":"Defender",
         "real_position":"Full Back",
         "real_position_side":"Right",
         "join_date":"2013-07-26",
         "country":"England",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":3,
         "slug":"john-brayford",
         "team":{
            "id":3,
            "name":"Cardiff City",
            "slug":"cardiff-city",
            "country":"England",
            "city":"",
            "postal_code":null,
            "short_club_name":"Cardiff",
            "street":"",
            "web_address":"",
            "founded":1899,
            "SYMID":null,
            "badge":null,
            "stadium":"Cardiff City Stadium",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[

         ]
      },
      {
         "id":85,
         "first_name":"Jordon",
         "last_name":"Mutch",
         "known_name":"",
         "birth_date":"1991-12-02",
         "birth_place":"",
         "first_nationality":"",
         "weigth":65,
         "height":175,
         "jersey_num":18,
         "position":"Midfielder",
         "real_position":"Central Midfielder",
         "real_position_side":"Left\/Centre",
         "join_date":"2012-06-22",
         "country":"England",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":3,
         "slug":"jordon-mutch",
         "team":{
            "id":3,
            "name":"Cardiff City",
            "slug":"cardiff-city",
            "country":"England",
            "city":"",
            "postal_code":null,
            "short_club_name":"Cardiff",
            "street":"",
            "web_address":"",
            "founded":1899,
            "SYMID":null,
            "badge":null,
            "stadium":"Cardiff City Stadium",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[

         ]
      },
      {
         "id":99,
         "first_name":"Jamal",
         "last_name":"Blackman",
         "known_name":"",
         "birth_date":"1993-10-27",
         "birth_place":"",
         "first_nationality":"",
         "weigth":82,
         "height":196,
         "jersey_num":46,
         "position":"Goalkeeper",
         "real_position":"Goalkeeper",
         "real_position_side":"Unknown",
         "join_date":"2011-10-29",
         "country":"England",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":4,
         "slug":"jamal-blackman",
         "team":{
            "id":4,
            "name":"Chelsea",
            "slug":"chelsea",
            "country":"England",
            "city":"London",
            "postal_code":null,
            "short_club_name":"Chelsea",
            "street":"Fulham Road",
            "web_address":"http:\/\/www.chelseafc.com",
            "founded":1905,
            "SYMID":null,
            "badge":null,
            "stadium":"Stamford Bridge",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[

         ]
      },
      {
         "id":104,
         "first_name":"John",
         "last_name":"Terry",
         "known_name":"",
         "birth_date":"1980-12-07",
         "birth_place":"",
         "first_nationality":"",
         "weigth":90,
         "height":187,
         "jersey_num":26,
         "position":"Defender",
         "real_position":"Central Defender",
         "real_position_side":"Centre",
         "join_date":"1997-08-01",
         "country":"England",
         "preferred_foot":"",
         "headshot_img":null,
         "twitter":null,
         "instagram":null,
         "team_id":4,
         "slug":"john-terry",
         "team":{
            "id":4,
            "name":"Chelsea",
            "slug":"chelsea",
            "country":"England",
            "city":"London",
            "postal_code":null,
            "short_club_name":"Chelsea",
            "street":"Fulham Road",
            "web_address":"http:\/\/www.chelseafc.com",
            "founded":1905,
            "SYMID":null,
            "badge":null,
            "stadium":"Stamford Bridge",
            "nb_transfers_in":0,
            "nb_transfers_out":0,
            "instagram":null,
            "twitter":null
         },
         "whispers":[

         ]
      }
   ],
   "meta":{
      "pagination":{
         "total":10,
         "count":10,
         "per_page":10,
         "current_page":1,
         "total_pages":1,
         "links":[

         ]
      }
   }
}
```

**Show player**
----
Show a player

* **URL**

  `GET /players/:player_id_or_slug?embed=:embed`

*  **URL Params**

   `embed=[string] (optional)` can be team or whispers, or both CSV

* **Success Response:**

* **Code:** 200 OK

**Content:**
```json
{
   "data":{
      "id":15,
      "first_name":"Jack",
      "last_name":"Wilshere",
      "known_name":"",
      "birth_date":"1992-01-01",
      "birth_place":"",
      "first_nationality":"",
      "weigth":68,
      "height":172,
      "jersey_num":10,
      "position":"Midfielder",
      "real_position":"Attacking Midfielder",
      "real_position_side":"Left",
      "join_date":"2008-07-01",
      "country":"England",
      "preferred_foot":"",
      "headshot_img":null,
      "twitter":null,
      "instagram":null,
      "team_id":1,
      "slug":"jack-wilshere",
      "team":{
         "id":1,
         "name":"Arsenal",
         "slug":"arsenal",
         "country":"England",
         "city":"London",
         "postal_code":null,
         "short_club_name":"Arsenal",
         "street":"75 Drayton Park",
         "web_address":"http:\/\/www.arsenal.com",
         "founded":1886,
         "SYMID":null,
         "badge":null,
         "stadium":"Emirates Stadium",
         "nb_transfers_in":0,
         "nb_transfers_out":0,
         "instagram":null,
         "twitter":null
      },
      "whispers":[
         {
            "id":1,
            "fw_index":"3",
            "team_id":1,
            "player_id":15,
            "team":{
               "id":1,
               "name":"Arsenal",
               "slug":"arsenal",
               "badge":null
            }
         }
      ]
   }
}
```

# **Articles API**
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
         "id":23186803055,
         "type":"social",
         "language":"English",
         "url":"http:\/\/ct.moreover.com\/?a=23186803055&p=1tt&v=1&x=tXUp9xwcpnjtcJ-0PzAutw",
         "headline":"Funeral of Slain New York City Officer Draws Thousands",
         "images":[

         ],
         "body":"Funeral of Slain New York City Officer Draws Thousands\rTweet\r');\rCreated: 10\/28\/2015 8:59 PM KAALtv.com\rBy: MICHAEL BALS...",
         "created_at":"2004-07-30T03:33:20+0000"
      }
   ],
   "meta":{
      "pagination":{
         "total":1,
         "count":1,
         "per_page":10,
         "current_page":1,
         "total_pages":1,
         "links":[

         ]
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
   "data":{
      "id":23186803055,
      "type":"social",
      "language":"English",
      "url":"http:\/\/ct.moreover.com\/?a=23186803055&p=1tt&v=1&x=tXUp9xwcpnjtcJ-0PzAutw",
      "headline":"Funeral of Slain New York City Officer Draws Thousands",
      "images":[

      ],
      "body":"Funeral of Slain New York City Officer Draws Thousands\rTweet\r');\rCreated: 10\/28\/2015 8:59 PM KAALtv.com\rBy: MICHAEL BALS...",
      "created_at":"2004-07-30T03:33:20+0000"
   }
}
```

# **Teams API**
----

**List teams**
----
  List teams

* **URL**

  `GET /teams?search=:search&embed=:embed`

*  **URL Params**

   `search=[string] (optional)`
   `embed=[string] (optional) can be players or whispers, or both CSV`

* **Success Response:**

  * **Code:** 200 OK

    **Content:**
``` json
{
   "data":[
      {
         "id":1,
         "name":"Arsenal",
         "slug":"arsenal",
         "country":"England",
         "city":"London",
         "postal_code":null,
         "short_club_name":"Arsenal",
         "street":"75 Drayton Park",
         "web_address":"http:\/\/www.arsenal.com",
         "founded":1886,
         "SYMID":null,
         "badge":null,
         "stadium":"Emirates Stadium",
         "nb_transfers_in":0,
         "nb_transfers_out":0,
         "instagram":null,
         "twitter":null,
         "players":[
            {
               "id":2,
               "first_name":"Emiliano",
               "last_name":"Viviano",
               "known_name":"",
               "birth_date":"1985-12-01",
               "birth_place":"Fiesole",
               "first_nationality":"Italy",
               "weigth":88,
               "height":195,
               "jersey_num":13,
               "position":"Goalkeeper",
               "real_position":"Goalkeeper",
               "real_position_side":"Unknown",
               "join_date":"2013-09-02",
               "country":"Italy",
               "preferred_foot":"Left",
               "headshot_img":null,
               "twitter":null,
               "instagram":null,
               "team_id":1,
               "slug":"emiliano-viviano"
            },
            {
               "id":3,
               "first_name":"Lukasz",
               "last_name":"Fabianski",
               "known_name":"",
               "birth_date":"1985-04-18",
               "birth_place":"",
               "first_nationality":"",
               "weigth":83,
               "height":190,
               "jersey_num":21,
               "position":"Goalkeeper",
               "real_position":"Goalkeeper",
               "real_position_side":"Unknown",
               "join_date":"2007-05-26",
               "country":"Poland",
               "preferred_foot":"",
               "headshot_img":null,
               "twitter":null,
               "instagram":null,
               "team_id":1,
               "slug":"lukasz-fabianski"
            }
         ],
         "whispers":[
            {
               "id":1,
               "fw_index":"3",
               "team_id":1,
               "player_id":15,
               "player":{
                  "id":15,
                  "first_name":"Jack",
                  "last_name":"Wilshere",
                  "known_name":"",
                  "headshot_img":null,
                  "slug":"jack-wilshere"
               }
            }
         ]
      },
      {
         "id":2,
         "name":"Aston Villa",
         "slug":"aston-villa",
         "country":"England",
         "city":"",
         "postal_code":null,
         "short_club_name":"Aston Villa",
         "street":"",
         "web_address":"",
         "founded":1874,
         "SYMID":null,
         "badge":null,
         "stadium":"Villa Park",
         "nb_transfers_in":0,
         "nb_transfers_out":0,
         "instagram":null,
         "twitter":null,
         "players":[
            {
               "id":36,
               "first_name":"Brad",
               "last_name":"Guzan",
               "known_name":"",
               "birth_date":"1984-09-09",
               "birth_place":"",
               "first_nationality":"",
               "weigth":94,
               "height":193,
               "jersey_num":1,
               "position":"Goalkeeper",
               "real_position":"Goalkeeper",
               "real_position_side":"Unknown",
               "join_date":"2008-08-01",
               "country":"USA",
               "preferred_foot":"",
               "headshot_img":null,
               "twitter":null,
               "instagram":null,
               "team_id":2,
               "slug":"brad-guzan"
            },
            {
               "id":37,
               "first_name":"Jed",
               "last_name":"Steer",
               "known_name":"",
               "birth_date":"1992-09-23",
               "birth_place":"",
               "first_nationality":"",
               "weigth":89,
               "height":188,
               "jersey_num":13,
               "position":"Goalkeeper",
               "real_position":"Goalkeeper",
               "real_position_side":"Unknown",
               "join_date":"2013-07-01",
               "country":"England",
               "preferred_foot":"",
               "headshot_img":null,
               "twitter":null,
               "instagram":null,
               "team_id":2,
               "slug":"jed-steer"
            }
         ],
         "whispers":[

         ]
      },
      {
         "id":19,
         "name":"West Bromwich Albion",
         "slug":"west-bromwich-albion",
         "country":"England",
         "city":"",
         "postal_code":null,
         "short_club_name":"West Brom",
         "street":"",
         "web_address":"",
         "founded":1878,
         "SYMID":null,
         "badge":null,
         "stadium":"The Hawthorns",
         "nb_transfers_in":0,
         "nb_transfers_out":0,
         "instagram":null,
         "twitter":null,
         "players":[
            {
               "id":535,
               "first_name":"Ben",
               "last_name":"Foster",
               "known_name":"",
               "birth_date":"1983-04-03",
               "birth_place":"",
               "first_nationality":"",
               "weigth":79,
               "height":188,
               "jersey_num":1,
               "position":"Goalkeeper",
               "real_position":"Goalkeeper",
               "real_position_side":"Unknown",
               "join_date":"2012-07-30",
               "country":"England",
               "preferred_foot":"",
               "headshot_img":null,
               "twitter":null,
               "instagram":null,
               "team_id":19,
               "slug":"ben-foster"
            },
            {
               "id":536,
               "first_name":"Boaz",
               "last_name":"Myhill",
               "known_name":"",
               "birth_date":"1982-11-09",
               "birth_place":"",
               "first_nationality":"",
               "weigth":91,
               "height":191,
               "jersey_num":13,
               "position":"Goalkeeper",
               "real_position":"Goalkeeper",
               "real_position_side":"Unknown",
               "join_date":"2010-07-30",
               "country":"Wales",
               "preferred_foot":"",
               "headshot_img":null,
               "twitter":null,
               "instagram":null,
               "team_id":19,
               "slug":"boaz-myhill"
            },
            {
               "id":537,
               "first_name":"Luke",
               "last_name":"Daniels",
               "known_name":"",
               "birth_date":"1988-01-05",
               "birth_place":"",
               "first_nationality":"",
               "weigth":81,
               "height":185,
               "jersey_num":19,
               "position":"Goalkeeper",
               "real_position":"Goalkeeper",
               "real_position_side":"Unknown",
               "join_date":"2004-07-01",
               "country":"England",
               "preferred_foot":"",
               "headshot_img":null,
               "twitter":null,
               "instagram":null,
               "team_id":19,
               "slug":"luke-daniels"
            }
         ],
         "whispers":[

         ]
      }
   ],
   "meta":{
      "pagination":{
         "total":3,
         "count":3,
         "per_page":10,
         "current_page":1,
         "total_pages":1,
         "links":[

         ]
      }
   }
}
```

# **Whispers API**
----

**List whispers**
----
  List whispers
  By default, result is ordered by FW index, desc.
  By default, only whisper score and player_id / team_id are returned, use 'embed=players,teams' to get full objects

* **URL**

  `GET /whispers?embed=:embed&per_page=:per_page&page=:page`

*  **URL Params**

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
         "id":1,
         "fw_index":"3",
         "team_id":1,
         "player_id":15,
         "player":{
            "id":15,
            "first_name":"Jack",
            "last_name":"Wilshere",
            "known_name":"",
            "headshot_img":null,
            "slug":"jack-wilshere"
         },
         "team":{
            "id":1,
            "name":"Arsenal",
            "slug":"arsenal",
            "badge":null
         }
      }
   ],
   "meta":{
      "pagination":{
         "total":1,
         "count":1,
         "per_page":10,
         "current_page":1,
         "total_pages":1,
         "links":[

         ]
      }
   }
}
```
