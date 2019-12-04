# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
```
http://www.catfact.info/
snippet
{
    "fact" : {
        "details" : "All cats are lactose-intolerant"
    }

}
```
1. A list of 150 random users in English.

```
https://randomuser.me/

snippet for generator
$.ajax({
  url: 'https://randomuser.me/api/',
  dataType: 'json',
  success: function(data) {
    console.log(data);
  }
});
{
  "results": [
    {
      "gender": "male",
      "name": {
        "title": "mr",
        "first": "brad",
        "last": "gibson"
      },
      "location": {
        "street": "9278 new road",
        "city": "kilcoole",
        "state": "waterford",
        "postcode": "93027",
        "coordinates": {
          "latitude": "20.9267",
          "longitude": "-7.9310"
        },
        "timezone": {
          "offset": "-3:30",
          "description": "Newfoundland"
        }
      },
      "email": "brad.gibson@example.com",
      "login": {
        "uuid": "155e77ee-ba6d-486f-95ce-0e0c0fb4b919",
        "username": "silverswan131",
        "password": "firewall",
        "salt": "TQA1Gz7x",
        "md5": "dc523cb313b63dfe5be2140b0c05b3bc",
        "sha1": "7a4aa07d1bedcc6bcf4b7f8856643492c191540d",
        "sha256": "74364e96174afa7d17ee52dd2c9c7a4651fe1254f471a78bda0190135dcd3480"
      },
      "dob": {
        "date": "1993-07-20T09:44:18.674Z",
        "age": 26
      },
      "registered": {
        "date": "2002-05-21T10:59:49.966Z",
        "age": 17
      },
      "phone": "011-962-7516",
      "cell": "081-454-0666",
      "id": {
        "name": "PPS",
        "value": "0390511T"
      },
      "picture": {
        "large": "https://randomuser.me/api/portraits/men/75.jpg",
        "medium": "https://randomuser.me/api/portraits/med/men/75.jpg",
        "thumbnail": "https://randomuser.me/api/portraits/thumb/men/75.jpg"
      },
      "nat": "IE"
    }
  ],
  "info": {
    "seed": "fea8be3e64777240",
    "results": 1,
    "page": 1,
    "version": "1.3"
  }
}
```
1. All the repos on Github with Pursuit their name

```
```
1. All the JavaScript repos on Github with Pursuit in their name

1. All the Swift repos on Github with Pursuit in their name

1. A list of all Pokemon
```
https://pokeapi.co/

snippet
{
  "count": 964,
  "next": "https://pokeapi.co/api/v2/pokemon?offset=20&limit=20",
  "previous": null,
  "results": [
    {
      "name": "bulbasaur",
      "url": "https://pokeapi.co/api/v2/pokemon/1/"
    },
    {
      "name": "ivysaur",
      "url": "https://pokeapi.co/api/v2/pokemon/2/"
    },
    {
      "name": "venusaur",
      "url": "https://pokeapi.co/api/v2/pokemon/3/"
    },
    {
      "name": "charmander",
      "url": "https://pokeapi.co/api/v2/pokemon/4/"
    },
    {
      "name": "charmeleon",
      "url": "https://pokeapi.co/api/v2/pokemon/5/"
    },
    {
      "name": "charizard",
      "url": "https://pokeapi.co/api/v2/pokemon/6/"
    },
    {
      "name": "squirtle",
      "url": "https://pokeapi.co/api/v2/pokemon/7/"
    },
    {
      "name": "wartortle",
      "url": "https://pokeapi.co/api/v2/pokemon/8/"
    },
    {
      "name": "blastoise",
      "url": "https://pokeapi.co/api/v2/pokemon/9/"
    },
    {
      "name": "caterpie",
      "url": "https://pokeapi.co/api/v2/pokemon/10/"
    },
    {
      "name": "metapod",
      "url": "https://pokeapi.co/api/v2/pokemon/11/"
    },
    {
      "name": "butterfree",
      "url": "https://pokeapi.co/api/v2/pokemon/12/"
    },
    {
      "name": "weedle",
      "url": "https://pokeapi.co/api/v2/pokemon/13/"
    },
    {
      "name": "kakuna",
      "url": "https://pokeapi.co/api/v2/pokemon/14/"
    },
    {
      "name": "beedrill",
      "url": "https://pokeapi.co/api/v2/pokemon/15/"
    },
    {
      "name": "pidgey",
      "url": "https://pokeapi.co/api/v2/pokemon/16/"
    },
    {
      "name": "pidgeotto",
      "url": "https://pokeapi.co/api/v2/pokemon/17/"
    },
    {
      "name": "pidgeot",
      "url": "https://pokeapi.co/api/v2/pokemon/18/"
    },
    {
      "name": "rattata",
      "url": "https://pokeapi.co/api/v2/pokemon/19/"
    },
    {
      "name": "raticate",
      "url": "https://pokeapi.co/api/v2/pokemon/20/"
    }
  ]
}
```
1. A list of all items in Fortnite

```
https://docs.fortniteapi.com/?version=latest

snippet
{
    "data": [
        {
            "itemId": "2fad344-834e456-dcf643d-91f9712",
            "lastUpdate": 1553386039,
            "store": {
                "isFeatured": true,
                "isRefundable": true,
                "cost": "1500"
            },
            "item": {
                "name": "Beastmode",
                "description": "Gassed up and ready to roar.",
                "type": "outfit",
                "rarity": "epic",
                "images": {
                    "icon": "https://fortnite-public-files.theapinetwork.com/outfit/c567e52c290292c99c7c9b44dd36827c.png",
                    "featured": "https://fortnite-public-files.theapinetwork.com/featured/2fad344-834e456-dcf643d-91f9712.png",
                    "background": "https://fortnite-public-files.theapinetwork.com/image/2fad344-834e456-dcf643d-91f9712.png",
                    "information": "https://fortnite-public-files.theapinetwork.com/image/2fad344-834e456-dcf643d-91f9712/icon.png"
                },
                "obtained_type": "vbucks",
                "ratings": {
                    "avgStars": 3.66,
                    "totalPoints": 597,
                    "numberVotes": 163
                }
            }
        },
        {
            /*/ SAME STRUCTURE AS ABOVE /*/
        }
    ]
}
```

1. A list of all Game of Thrones Episodes.
```
no list of episodes but i found character list
https://github.com/jeffreylancaster/game-of-thrones/blob/master/data/characters.json
snippet
{
"characters":[
   {
      "characterName":"Addam Marbrand",
      "characterLink":"/character/ch0305333/",
      "actorName":"B.J. Hogg",
      "actorLink":"/name/nm0389698/"
   },
   {
      "characterName":"Aegon Targaryen",
      "houseName":"Targaryen",
      "royal":true,
      "parents":[
         "Elia Martell",
         "Rhaegar Targaryen"
      ],
      "siblings":[
         "Rhaenys Targaryen",
         "Jon Snow"
      ],
      "killedBy":[
         "Gregor Clegane"
      ]
   },
   {
      "characterName":"Aeron Greyjoy",
      "houseName":"Greyjoy",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzI5MDg0ZDAtN2Y2ZC00MzU1LTgyYjQtNTBjYjEzODczZDVhXkEyXkFqcGdeQXVyNTg0Nzg4NTE@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzI5MDg0ZDAtN2Y2ZC00MzU1LTgyYjQtNTBjYjEzODczZDVhXkEyXkFqcGdeQXVyNTg0Nzg4NTE@._V1_.jpg",
      "characterLink":"/character/ch0540081/",
      "actorName":"Michael Feast",
      "actorLink":"/name/nm0269923/",
      "siblings":[
         "Balon Greyjoy",
         "Euron Greyjoy"
      ],
      "nickname":"Damphair"
   },
   {
      "characterName":"Aerys II Targaryen",
      "houseName":"Targaryen",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMWQzOWViN2ItNDZhOS00MmZlLTkxZTYtZDg5NGUwMGRmYWZjL2ltYWdlL2ltYWdlXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMWQzOWViN2ItNDZhOS00MmZlLTkxZTYtZDg5NGUwMGRmYWZjL2ltYWdlL2ltYWdlXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0541362/",
      "actorName":"David Rintoul",
      "actorLink":"/name/nm0727778/",
      "nickname":"The Mad King",
      "royal":true,
      "killed":[
         "Brandon Stark",
         "Rickard Stark"
      ],
      "servedBy":[
         "Arthur Dayne",
         "Jaime Lannister"
      ],
      "parentOf":[
         "Daenerys Targaryen",
         "Rhaegar Targaryen",
         "Viserys Targaryen"
      ],
      "siblings":[
         "Rhaella Targaryen"
      ],
      "marriedEngaged":[
         "Rhaella Targaryen"
      ],
      "killedBy":[
         "Jaime Lannister"
      ]
   },
   {
      "characterName":"Akho",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BOGE4ZDZmOGUtNGE4Ny00Y2VmLThiOGItMjk3Y2U0ZDY3OWQxXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BOGE4ZDZmOGUtNGE4Ny00Y2VmLThiOGItMjk3Y2U0ZDY3OWQxXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0544520/",
      "actorName":"Chuku Modu",
      "actorLink":"/name/nm6729880/",
      "killedBy":[
         "Daario Naharis"
      ]
   },
   {
      "characterName":"Alliser Thorne",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjAxMjExMjA3M15BMl5BanBnXkFtZTcwMjI1ODg5NA@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjAxMjExMjA3M15BMl5BanBnXkFtZTcwMjI1ODg5NA@@._V1_SY1000_CR0,0,666,1000_AL_.jpg",
      "characterLink":"/character/ch0246938/",
      "actorName":"Owen Teale",
      "actorLink":"/name/nm0853583/",
      "killed":[
         "Jon Snow"
      ],
      "killedBy":[
         "Jon Snow"
      ]
   },
   {
      "characterName":"Alton Lannister",
      "houseName":"Lannister",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTU0NTU1NTAzOF5BMl5BanBnXkFtZTcwNzA2NDk4OA@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTU0NTU1NTAzOF5BMl5BanBnXkFtZTcwNzA2NDk4OA@@._V1_.jpg",
      "characterLink":"/character/ch0305012/",
      "actorName":"Karl Davies",
      "actorLink":"/name/nm0203801/",
      "killedBy":[
         "Jaime Lannister"
      ]
   },
   {
      "characterName":"Alys Karstark",
      "characterLink":"/character/ch0576836/",
      "actorName":"Megan Parkinson",
      "actorLink":"/name/nm8257864/",
      "parents":[
         "Harald Karstark"
      ]
   },
   {
      "characterName":"Amory Lorch",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BOTVmY2M2YmUtY2JkYS00NjIyLWFhYTAtNTNlZmI4ODdiNmE5XkEyXkFqcGdeQXVyMjg2MTMyNTM@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BOTVmY2M2YmUtY2JkYS00NjIyLWFhYTAtNTNlZmI4ODdiNmE5XkEyXkFqcGdeQXVyMjg2MTMyNTM@._V1_.jpg",
      "characterLink":"/character/ch0305002/",
      "actorName":"Fintan McKeown",
      "actorLink":"/name/nm0571654/",
      "killed":[
         "Yoren"
      ],
      "killedBy":[
         "Jaqen H'ghar"
      ]
   },
   {
      "characterName":"Anguy",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNmRhY2M4YmItNjc2Yi00ZDc0LWE5NmUtNGE5OWE0YTQ2YjY3XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNmRhY2M4YmItNjc2Yi00ZDc0LWE5NmUtNGE5OWE0YTQ2YjY3XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0316930/",
      "actorName":"Philip McGinley",
      "actorLink":"/name/nm1528121/"
   },
   {
      "characterName":"Archmaester Marwyn",
      "characterLink":"/character/ch0578265/",
      "actorName":"Jim Broadbent",
      "actorLink":"/name/nm0000980/"
   },
   {
      "characterName":"Areo Hotah",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNWFkNTAwNzctOGQ2ZS00OTMyLWE3NDYtOGUwM2E1MzVlYjI0XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNWFkNTAwNzctOGQ2ZS00OTMyLWE3NDYtOGUwM2E1MzVlYjI0XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0507107/",
      "actorName":"Deobia Oparei",
      "actorLink":"/name/nm0649046/",
      "killedBy":[
         "Tyene Sand"
      ],
      "serves":[
         "Doran Martell"
      ]
   },
   {
      "characterName":"Armeca",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BZmQyMGVlMDctYWFhMi00YzMyLTlkZDgtOWNmZTY3NmZkYzZlXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BZmQyMGVlMDctYWFhMi00YzMyLTlkZDgtOWNmZTY3NmZkYzZlXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0305014/",
      "actorName":"Sahara Knite",
      "actorLink":"/name/nm1783582/"
   },
   {
      "characterName":"Arthur",
      "characterLink":"/character/ch0305326/",
      "actorName":"Nathanael Saleh",
      "actorLink":"/name/nm8127149/"
   },
   {
      "characterName":"Arthur Dayne",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BODczZDUxYmQtMzk1MC00ZTUwLTk1MjAtZDJlODViMWFhOGU5XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BODczZDUxYmQtMzk1MC00ZTUwLTk1MjAtZDJlODViMWFhOGU5XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0540097/",
      "actorName":"Luke Roberts",
      "actorLink":"/name/nm1074361/",
      "kingsguard":true,
      "killedBy":[
         "Howland Reed",
         "Eddard Stark"
      ],
      "serves":[
         "Aerys II Targaryen"
      ]
   },
   {
      "characterName":"Arya Stark",
      "houseName":"Stark",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTk5MTYwNDc0OF5BMl5BanBnXkFtZTcwOTg2NDg1Nw@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTk5MTYwNDc0OF5BMl5BanBnXkFtZTcwOTg2NDg1Nw@@._V1_SY1000_CR0,0,665,1000_AL_.jpg",
      "characterLink":"/character/ch0158604/",
      "actorName":"Maisie Williams",
      "actorLink":"/name/nm3586035/",
      "siblings":[
         "Robb Stark",
         "Sansa Stark",
         "Bran Stark",
         "Rickon Stark"
      ],
      "killed":[
         "Red Keep Stableboy",
         "Frey Soldier #1",
         "Polliver",
         "Rorge",
         "Ghita",
         "Meryn Trant",
         "The Waif",
         "Black Walder Rivers",
         "Lothar Frey",
         "Walder Frey",
         "Petyr Baelish",
         "The Night King",
         "White Walker",
         "Viserion"
      ],
      "parents":[
         "Eddard Stark",
         "Catelyn Stark"
      ],
      "guardedBy":[
         "Nymeria"
      ]
   },
   {
      "characterName":"Baby Sam",
      "characterLink":"/character/ch0547881/",
      "actors":[
         {
            "actorName":"William Wilson",
            "actorLink":"/name/nm8251159/",
            "seasonsActive":[
               7
            ]
         },
         {
            "actorName":"James Wilson",
            "actorLink":"/name/nm8251160/",
            "seasonsActive":[
               7
            ]
         }
      ],
      "parents":[
         "Samwell Tarly",
         "Gilly"
      ]
   },
   {
      "characterName":"Balon Greyjoy",
      "houseName":"Greyjoy",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTUxNjkwODczN15BMl5BanBnXkFtZTcwODMwNTgzNw@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTUxNjkwODczN15BMl5BanBnXkFtZTcwODMwNTgzNw@@._V1_SY1000_CR0,0,637,1000_AL_.jpg",
      "characterLink":"/character/ch0292152/",
      "actorName":"Patrick Malahide",
      "actorLink":"/name/nm0538869/",
      "killedBy":[
         "Euron Greyjoy"
      ],
      "parentOf":[
         "Yara Greyjoy",
         "Theon Greyjoy"
      ],
      "siblings":[
         "Euron Greyjoy",
         "Aeron Greyjoy"
      ]
   },
   {
      "characterName":"Baratheon Guard",
      "houseName":"Baratheon",
      "characterLink":"/character/ch0350989/",
      "actorName":"Phil Barnhill",
      "actorLink":"/name/nm4207240/"
   },
   {
      "characterName":"Barristan Selmy",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTUyMTE0NjUxNV5BMl5BanBnXkFtZTcwOTA1ODg5NA@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTUyMTE0NjUxNV5BMl5BanBnXkFtZTcwOTA1ODg5NA@@._V1_SX1500_CR0,0,1500,999_AL_.jpg",
      "characterLink":"/character/ch0241346/",
      "actorName":"Ian McElhinney",
      "actorLink":"/name/nm0568400/",
      "killedBy":[
         "Sons of the Harpy"
      ],
      "serves":[
         "Daenerys Targaryen"
      ]
   },
   {
      "characterName":"Benjen Stark",
      "houseName":"Stark",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjFiY2M5MjgtZmRiMS00ZTAyLTk2Y2UtMjdjZTRkZmVlYTMyXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjFiY2M5MjgtZmRiMS00ZTAyLTk2Y2UtMjdjZTRkZmVlYTMyXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0153996/",
      "actorName":"Joseph Mawle",
      "actorLink":"/name/nm1152798/",
      "parents":[
         "Rickard Stark"
      ],
      "siblings":[
         "Brandon Stark",
         "Lyanna Stark",
         "Eddard Stark"
      ],
      "killedBy":[
         "Wights"
      ]
   },
   {
      "characterName":"Beric Dondarrion",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjQwMTEwNTg2MF5BMl5BanBnXkFtZTgwNTAxODYxOTE@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjQwMTEwNTg2MF5BMl5BanBnXkFtZTgwNTAxODYxOTE@._V1_SY1000_CR0,0,665,1000_AL_.jpg",
      "characterLink":"/character/ch0305320/",
      "actors":[
         {
            "actorName":"Richard Dormer",
            "actorLink":"/name/nm0233807/",
            "seasonsActive":[
               3,
               6,
               7,
               8
            ]
         },
         {
            "actorName":"David Michael Scott",
            "actorLink":"/name/nm2364108/",
            "seasonsActive":[
               1
            ]
         }
      ],
      "killedBy":[
         "Sandor Clegane",
         "Wights"
      ]
   },
   {
      "characterName":"Bianca",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BYWJhYjcxYzgtMDlhZi00OGNhLWE0NzAtMWFhMDJlYTZmYzY2XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BYWJhYjcxYzgtMDlhZi00OGNhLWE0NzAtMWFhMDJlYTZmYzY2XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0541364/",
      "actorName":"Eline Powell",
      "actorLink":"/name/nm4730958/"
   },
   {
      "characterName":"Biter",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNWVjOWFjNGEtYzc0MC00YjkzLTkxM2QtN2Y1MmU4NzIzOTEyXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNWVjOWFjNGEtYzc0MC00YjkzLTkxM2QtN2Y1MmU4NzIzOTEyXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0305028/",
      "actorName":"Gerard Jordan",
      "actorLink":"/name/nm0429956/",
      "killedBy":[
         "Sandor Clegane"
      ]
   },
   {
      "characterName":"Black Lorren",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNjg5ZGZjZDUtZmJmNC00MjQ5LWJhZDAtOTc0MzYzNTNkMTZiXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNjg5ZGZjZDUtZmJmNC00MjQ5LWJhZDAtOTc0MzYzNTNkMTZiXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0266524/",
      "actorName":"Forbes KB",
      "actorLink":"/name/nm1978998/"
   },
   {
      "characterName":"Black Walder Rivers",
      "houseName":"Frey",
      "characterLink":"/character/ch0014591/",
      "actorName":"Tim Plester",
      "actorLink":"/name/nm1043031/",
      "killed":[
         "Catelyn Stark"
      ],
      "killedBy":[
         "Arya Stark"
      ],
      "parents":[
         "Walder Frey"
      ]
   },
   {
      "characterName":"Bobono",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BZWRmNWVhNTctOGJlZC00ZjVlLThkY2MtODU3Y2I2Njc1YzZjL2ltYWdlXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BZWRmNWVhNTctOGJlZC00ZjVlLThkY2MtODU3Y2I2Njc1YzZjL2ltYWdlXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0541790/",
      "actorName":"Leigh Gill",
      "actorLink":"/name/nm5279916/"
   },
   {
      "characterName":"Bowen Marsh",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNmRkMDYxYjQtYTBjZi00NDZlLThmNGMtYzlhNGI1ZDE5NTJmXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNmRkMDYxYjQtYTBjZi00NDZlLThmNGMtYzlhNGI1ZDE5NTJmXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0305036/",
      "actorName":"Michael Condron",
      "actorLink":"/name/nm1638006/",
      "killed":[
         "Jon Snow"
      ],
      "killedBy":[
         "Jon Snow"
      ]
   },
   {
      "characterName":"Brandon Stark",
      "houseName":"Stark",
      "killedBy":[
         "Aerys II Targaryen"
      ],
      "parents":[
         "Rickard Stark"
      ],
      "siblings":[
         "Lyanna Stark",
         "Benjen Stark",
         "Eddard Stark"
      ]
   },
   {
      "characterName":"Bran Stark",
      "houseName":"Stark",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTA1NTg0NTI3MTBeQTJeQWpwZ15BbWU3MDEyNjg4OTQ@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTA1NTg0NTI3MTBeQTJeQWpwZ15BbWU3MDEyNjg4OTQ@._V1_SX1500_CR0,0,1500,999_AL_.jpg",
      "characterLink":"/character/ch0234897/",
      "actorName":"Isaac Hempstead Wright",
      "actorLink":"/name/nm3652842/",
      "royal":true,
      "siblings":[
         "Robb Stark",
         "Sansa Stark",
         "Arya Stark",
         "Rickon Stark"
      ],
      "parents":[
         "Eddard Stark",
         "Catelyn Stark"
      ],
      "guardedBy":[
         "Summer"
      ]
   },
   {
      "characterName":"Brea",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTUxMzc4MjE3N15BMl5BanBnXkFtZTgwMDg0Njc5NTE@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTUxMzc4MjE3N15BMl5BanBnXkFtZTgwMDg0Njc5NTE@._V1_SX1777_CR0,0,1777,999_AL_.jpg",
      "characterLink":"/character/ch0539337/",
      "actorName":"Gemita Samarra",
      "actorLink":"/name/nm5106314/"
   },
   {
      "characterName":"Brienne of Tarth",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTYzNDY4NzgzOV5BMl5BanBnXkFtZTcwNDM5ODg4OQ@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTYzNDY4NzgzOV5BMl5BanBnXkFtZTcwNDM5ODg4OQ@@._V1_.jpg",
      "characterLink":"/character/ch0254503/",
      "actorName":"Gwendoline Christie",
      "actorLink":"/name/nm3729225/",
      "kingsguard":true,
      "killed":[
         "Soldier Tom",
         "Stannis Baratheon",
         "Bolton Officer"
      ],
      "serves":[
         "Renly Baratheon",
         "Catelyn Stark",
         "Sansa Stark",
         "Bran Stark"
      ],
      "servedBy":[
         "Podrick Payne"
      ]
   },
   {
      "characterName":"Bronn",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTY0MzI5MjY1OV5BMl5BanBnXkFtZTcwODM1ODg4OQ@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTY0MzI5MjY1OV5BMl5BanBnXkFtZTcwODM1ODg4OQ@@._V1_.jpg",
      "characterLink":"/character/ch0241345/",
      "actorName":"Jerome Flynn",
      "actorLink":"/name/nm0283492/",
      "killed":[
         "Vardis Egen",
         "Matthos Seaworth",
         "Lead Dornish Guard"
      ],
      "marriedEngaged":[
         "Lollys Stokeworth"
      ]
   },
   {
      "characterName":"Brother Ray",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTAwNjU5MTY3NzleQTJeQWpwZ15BbWU4MDIwODkwMTkx._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTAwNjU5MTY3NzleQTJeQWpwZ15BbWU4MDIwODkwMTkx._V1_SY1000_CR0,0,1502,1000_AL_.jpg",
      "characterLink":"/character/ch0541878/",
      "actorName":"Ian McShane",
      "actorLink":"/name/nm0574534/",
      "killedBy":[
         "Lem Lemoncloak"
      ]
   },
   {
      "characterName":"Brynden Tully",
      "houseName":"Tully",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BOTg5ZDIwOWUtMjQ1OS00YjgxLThmMDgtOWUwZjQ4MzE3ZDhlXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BOTg5ZDIwOWUtMjQ1OS00YjgxLThmMDgtOWUwZjQ4MzE3ZDhlXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0381563/",
      "actorName":"Clive Russell",
      "actorLink":"/name/nm0751085/",
      "nickname":"Blackfish",
      "siblings":[
         "Hoster Tully"
      ]
   },
   {
      "characterName":"Captain of the Archers",
      "characterLink":"/character/ch0540864/",
      "actorName":"Michael Grennell",
      "actorLink":"/name/nm1214477/"
   },
   {
      "characterName":"Catelyn Stark",
      "houseName":[
         "Stark",
         "Tully"
      ],
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTY2ODc4MTkxMV5BMl5BanBnXkFtZTcwNjM3MTg4OQ@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTY2ODc4MTkxMV5BMl5BanBnXkFtZTcwNjM3MTg4OQ@@._V1_SY1000_CR0,0,915,1000_AL_.jpg",
      "characterLink":"/character/ch0145135/",
      "actorName":"Michelle Fairley",
      "actorLink":"/name/nm0265610/",
      "killed":[
         "Joyeuse Erenford"
      ],
      "killedBy":[
         "Black Walder Rivers"
      ],
      "parents":[
         "Hoster Tully"
      ],
      "parentOf":[
         "Robb Stark",
         "Sansa Stark",
         "Arya Stark",
         "Bran Stark",
         "Rickon Stark"
      ],
      "siblings":[
         "Lysa Arryn",
         "Edmure Tully"
      ],
      "marriedEngaged":[
         "Eddard Stark",
         "Brandon Stark"
      ]
   },
   {
      "characterName":"Catspaw Assassin",
      "characterLink":"/character/ch0305046/",
      "actorName":"Lalor Roddy",
      "actorLink":"/name/nm0734498/",
      "killedBy":[
         "Summer"
      ]
   },
   {
      "characterName":"Cersei Lannister",
      "houseName":[
         "Lannister",
         "Baratheon"
      ],
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTgzNTAxNjExMl5BMl5BanBnXkFtZTcwMDEwNzI4OQ@@._V1._CR954,56,605,670._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTgzNTAxNjExMl5BMl5BanBnXkFtZTcwMDEwNzI4OQ@@._V1._CR954,56,605,670_.jpg",
      "characterLink":"/character/ch0159526/",
      "actorName":"Lena Headey",
      "actorLink":"/name/nm0372176/",
      "parents":[
         "Tywin Lannister"
      ],
      "parentOf":[
         "Joffrey Baratheon",
         "Myrcella Baratheon",
         "Tommen Baratheon"
      ],
      "royal":true,
      "siblings":[
         "Jaime Lannister",
         "Tyrion Lannister"
      ],
      "marriedEngaged":[
         "Robert Baratheon"
      ],
      "killed":[
         "Lancel Lannister",
         "High Sparrow",
         "Loras Tyrell",
         "Mace Tyrell",
         "Margaery Tyrell",
         "Kevan Lannister",
         "Tyene Sand"
      ],
      "killedBy":[
         "Roof collapse"
      ]
   },
   {
      "characterName":"Child of the Forest",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BOTdjYmYxNjctODU1OC00NzIwLTk0ODktNDc3NzA2MzRhYzIwXkEyXkFqcGdeQXVyNTcxMzMwNTA@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BOTdjYmYxNjctODU1OC00NzIwLTk0ODktNDc3NzA2MzRhYzIwXkEyXkFqcGdeQXVyNTcxMzMwNTA@._V1_.jpg",
      "characterLink":"/character/ch0414315/",
      "actorName":"Alice Hewkin",
      "actorLink":"/name/nm2456829/"
   },
   {
      "characterName":"Citadel Maester",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTg3NDA1Nzc5Nl5BMl5BanBnXkFtZTgwMjIwNTgyOTE@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTg3NDA1Nzc5Nl5BMl5BanBnXkFtZTgwMjIwNTgyOTE@._V1_SY1000_CR0,0,1502,1000_AL_.jpg",
      "characterLink":"/character/ch0478670/",
      "actorName":"Frank Hvam",
      "actorLink":"/name/nm0404809/"
   },
   {
      "characterName":"Colen of Greenpools",
      "characterLink":"/character/ch0350989/",
      "actorName":"Darren Killeen",
      "actorLink":"/name/nm4007028/"
   },
   {
      "characterName":"Craster",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMzZiNjZiMGItNTQ2Yi00MGU3LWFjMTktNzlmNDFlYzA3MjY3XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMzZiNjZiMGItNTQ2Yi00MGU3LWFjMTktNzlmNDFlYzA3MjY3XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0300218/",
      "actorName":"Robert Pugh",
      "actorLink":"/name/nm0700059/",
      "killedBy":[
         "Karl Tanner"
      ]
   },
   {
      "characterName":"Daario Naharis",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BY2ExMDJmNzMtMDVmZi00MDNlLWI1NzYtOTkxOTdlOWU4YzE4XkEyXkFqcGdeQXVyNTcxMzMwNTA@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BY2ExMDJmNzMtMDVmZi00MDNlLWI1NzYtOTkxOTdlOWU4YzE4XkEyXkFqcGdeQXVyNTcxMzMwNTA@._V1_SY1000_CR0,0,665,1000_AL_.jpg",
      "characterLink":"/character/ch0335040/",
      "actors":[
         {
            "actorName":"Ed Skrein",
            "actorLink":"/name/nm4534098/",
            "seasonsActive":[
               3
            ]
         },
         {
            "actorName":"Michiel Huisman",
            "actorLink":"/name/nm0401264/",
            "seasonsActive":[
               4,
               5,
               6
            ]
         }
      ],
      "killed":[
         "Mero",
         "Prendahl na Ghezn",
         "Oznak zo Pahl",
         "Mossador",
         "Iggo",
         "Akho"
      ],
      "serves":[
         "Daenerys Targaryen"
      ]
   },
   {
      "characterName":"Daenerys Targaryen",
      "houseName":"Targaryen",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjA4MzIxMTQwMF5BMl5BanBnXkFtZTcwMzY2NDg1Nw@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjA4MzIxMTQwMF5BMl5BanBnXkFtZTcwMzY2NDg1Nw@@._V1_SY1000_CR0,0,810,1000_AL_.jpghttps://images-na.ssl-images-amazon.com/images/M/MV5BMTgwNzIxMTU1OV5BMl5BanBnXkFtZTcwNzI2ODg5NA@@._V1._SX100_SY140_.jpg",
      "characterLink":"/character/ch0158597/",
      "actorName":"Emilia Clarke",
      "actorLink":"/name/nm3592338/",
      "royal":true,
      "parents":[
         "Aerys II Targaryen",
         "Rhaella Targaryen"
      ],
      "siblings":[
         "Rhaegar Targaryen",
         "Viserys Targaryen"
      ],
      "killed":[
         "Khal Drogo",
         "Mirri Maz Duur",
         "Doreah",
         "Xaro Xhoan Daxos",
         "Khal Rhalko",
         "Khal Brozho",
         "Khal Qorro",
         "Khal Forzho",
         "Khal Moro",
         "Dothraki Bloodrider #1",
         "Dothraki Bloodrider #2",
         "Randyll Tarly",
         "Dickon Tarly",
         "Eleanor",
         "Eleanor's Daughter",
         "Lord Varys"
      ],
      "servedBy":[
         "Barristan Selmy",
         "Daario Naharis",
         "Grey Worm",
         "Jorah Mormont",
         "Missandei",
         "Tyrion Lannister"
      ],
      "parentOf":[
         "Rhaego"
      ],
      "marriedEngaged":[
         "Khal Drogo"
      ],
      "guardedBy":[
         "Drogon",
         "Rhaegal",
         "Viserion"
      ],
      "killedBy":[
         "Jon Snow"
      ]
   },
   {
      "characterName":"Dagmer Cleftjaw",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BYWRlYzI5ZTQtODU0My00MWUyLWExNTMtNGQ4OTIwYzE2YzFiXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BYWRlYzI5ZTQtODU0My00MWUyLWExNTMtNGQ4OTIwYzE2YzFiXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0304762/",
      "actorName":"Ralph Ineson",
      "actorLink":"/name/nm0408591/"
   },
   {
      "characterName":"Daisy",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMDk2ODRhNzItOGZhNi00YTUyLThkMzctMDQ2Zjg5MzY1NTI2XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMDk2ODRhNzItOGZhNi00YTUyLThkMzctMDQ2Zjg5MzY1NTI2XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0305015/",
      "actorName":"Maisie Dee",
      "actorLink":"/name/nm3996678/"
   },
   {
      "characterName":"Davos Seaworth",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNTMwODc0NzI4Ml5BMl5BanBnXkFtZTcwNzY3NDk4OQ@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNTMwODc0NzI4Ml5BMl5BanBnXkFtZTcwNzY3NDk4OQ@@._V1_.jpg",
      "characterLink":"/character/ch0255396/",
      "actorName":"Liam Cunningham",
      "actorLink":"/name/nm0192377/",
      "serves":[
         "Stannis Baratheon",
         "Jon Snow"
      ],
      "parentOf":[
         "Matthos Seaworth"
      ]
   },
   {
      "characterName":"Dickon Tarly",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzk1YjNlZGQtNTU0MC00OGZmLThhYTQtZDM1ZjI2OGNlZGQxXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzk1YjNlZGQtNTU0MC00OGZmLThhYTQtZDM1ZjI2OGNlZGQxXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0541363/",
      "actors":[
         {
            "actorName":"Freddie Stroma",
            "actorLink":"/name/nm2238815/",
            "seasonsActive":[
               6
            ]
         },
         {
            "actorName":"Tom Hopper",
            "actorLink":"/name/nm2584392/",
            "seasonsActive":[
               7
            ]
         }
      ],
      "killedBy":[
         "Daenerys Targaryen"
      ],
      "parents":[
         "Randyll Tarly",
         "Melessa Tarly"
      ],
      "siblings":[
         "Samwell Tarly",
         "Talla Tarly"
      ]
   },
   {
      "characterName":"Dongo the Giant",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNTRjNGYxNWItYmRhNS00MDY3LWFmZTItMzYzNTEwMjg3YTA1XkEyXkFqcGdeQXVyNDUzOTQ5MjY@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNTRjNGYxNWItYmRhNS00MDY3LWFmZTItMzYzNTEwMjg3YTA1XkEyXkFqcGdeQXVyNDUzOTQ5MjY@._V1_.jpg",
      "characterLink":"/character/ch0510932/",
      "actorName":"Ian Whyte",
      "actorLink":"/name/nm1613839/",
      "killedBy":[
         "Night's Watchman"
      ]
   },
   {
      "characterName":"Donnel Waynwood",
      "characterLink":"/character/ch0544229/",
      "actorName":"Alisdair Simpson",
      "actorLink":"/name/nm1368037/"
   },
   {
      "characterName":"Dontos Hollard",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzUzYzg5NGUtOWE5Zi00Y2MwLTg2YzQtMDZlOWE1NDZjZmFkXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzUzYzg5NGUtOWE5Zi00Y2MwLTg2YzQtMDZlOWE1NDZjZmFkXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0305031/",
      "actorName":"Tony Way",
      "actorLink":"/name/nm0915453/",
      "killedBy":[
         "Petyr Baelish"
      ]
   },
   {
      "characterName":"Doran Martell",
      "houseName":"Martell",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BZWU5NzJkNWMtYTM4MS00YmE2LWExYmItNDNiOTE3YzI5YzAxXkEyXkFqcGdeQXVyNDUzOTQ5MjY@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BZWU5NzJkNWMtYTM4MS00YmE2LWExYmItNDNiOTE3YzI5YzAxXkEyXkFqcGdeQXVyNDUzOTQ5MjY@._V1_SY1000_CR0,0,913,1000_AL_.jpg",
      "characterLink":"/character/ch0468006/",
      "actorName":"Alexander Siddig",
      "actorLink":"/name/nm0796502/",
      "killedBy":[
         "Ellaria Sand"
      ],
      "parentOf":[
         "Trystane Martell"
      ],
      "siblings":[
         "Elia Martell",
         "Oberyn Martell"
      ]
   },
   {
      "characterName":"Doreah",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjEzNWJmNzYtZjFhYy00NmI5LWFkOWUtOWQ0ZjUzZDYwYjM1XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjEzNWJmNzYtZjFhYy00NmI5LWFkOWUtOWQ0ZjUzZDYwYjM1XkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0248504/",
      "actorName":"Roxanne McKee",
      "actorLink":"/name/nm1861467/",
      "killed":[
         "Irri"
      ],
      "killedBy":[
         "Daenerys Targaryen"
      ]
   },
   {
      "characterName":"Dothraki Bloodrider #1",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTQ2Mzk1MzczMl5BMl5BanBnXkFtZTgwNDQyODAxODE@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTQ2Mzk1MzczMl5BMl5BanBnXkFtZTgwNDQyODAxODE@._V1_SY1000_CR0,0,1502,1000_AL_.jpg",
      "characterLink":"/character/ch0542918/",
      "actorName":"Diogo Sales",
      "actorLink":"/name/nm6088160/",
      "killedBy":[
         "Daenerys Targaryen"
      ]
   },
   {
      "characterName":"Dothraki Bloodrider #2",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTQ2Mzk1MzczMl5BMl5BanBnXkFtZTgwNDQyODAxODE@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTQ2Mzk1MzczMl5BMl5BanBnXkFtZTgwNDQyODAxODE@._V1_SY1000_CR0,0,1502,1000_AL_.jpg",
      "characterLink":"/character/ch0542918/",
      "actorName":"Junade Khan",
      "actorLink":"/name/nm2999602/",
      "killedBy":[
         "Daenerys Targaryen"
      ]
   },
   {
      "characterName":"Drennan",
      "characterLink":"/character/ch0305030/",
      "actorName":"David Coakley",
      "actorLink":"/name/nm2231505/",
      "killedBy":[
         "Osha"
      ]
   },
   {
      "characterName":"Drogon",
      "houseName":"Targaryen",
      "siblings":[
         "Rhaegal",
         "Viserion"
      ],
      "guardianOf":[
         "Daenerys Targaryen"
      ],
      "killed":[
         "Pyat Pree",
         "Kraznys mo Nakloz",
         "Zalla"
      ]
   },
   {
      "characterName":"Drowned Priest",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BOGEwMjRhYzgtYjY1YS00MjhlLTllYjYtNWQzOGQxOTE3ZDczXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BOGEwMjRhYzgtYjY1YS00MjhlLTllYjYtNWQzOGQxOTE3ZDczXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0411375/",
      "actorName":"Jonathan Ryan",
      "actorLink":"/name/nm0752638/"
   },
   {
      "characterName":"Eddard Stark",
      "houseName":"Stark",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BODcwMjg0MDQ5MF5BMl5BanBnXkFtZTcwMTk2NDk4OQ@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BODcwMjg0MDQ5MF5BMl5BanBnXkFtZTcwMTk2NDk4OQ@@._V1_SY1000_CR0,0,827,1000_AL_.jpg",
      "characterLink":"/character/ch0154681/",
      "actorName":"Sean Bean",
      "actorLink":"/name/nm0000293/",
      "nickname":"Ned",
      "guardianOf":[
         "Jon Snow"
      ],
      "siblings":[
         "Brandon Stark",
         "Benjen Stark",
         "Lyanna Stark"
      ],
      "parents":[
         "Rickard Stark"
      ],
      "killed":[
         "Arthur Dayne",
         "Will",
         "Lady",
         "Gerold Hightower"
      ],
      "allies":[
         "Howland Reed",
         "Robert Baratheon"
      ],
      "guardedBy":[
         "Jon Arryn"
      ],
      "killedBy":[
         "Ilyn Payne"
      ],
      "marriedEngaged":[
         "Catelyn Stark"
      ],
      "parentOf":[
         "Robb Stark",
         "Sansa Stark",
         "Arya Stark",
         "Bran Stark",
         "Rickon Stark"
      ]
   },
   {
      "characterName":"Eddison Tollett",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTY1MjQ4ODAwNV5BMl5BanBnXkFtZTcwMTc5NDk4OQ@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTY1MjQ4ODAwNV5BMl5BanBnXkFtZTcwMTc5NDk4OQ@@._V1_.jpg",
      "characterLink":"/character/ch0305008/",
      "actorName":"Ben Crompton",
      "actorLink":"/name/nm0174005/",
      "killedBy":[
         "Wight"
      ]
   },
   {
      "characterName":"Edmure Tully",
      "houseName":"Tully",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BYjEzNThlMmQtMDgzYi00MTQ5LTllMzQtNDZjY2JiMTVhNmNkXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BYjEzNThlMmQtMDgzYi00MTQ5LTllMzQtNDZjY2JiMTVhNmNkXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0316931/",
      "actorName":"Tobias Menzies",
      "actorLink":"/name/nm0580014/",
      "marriedEngaged":[
         "Roslin Frey"
      ],
      "siblings":[
         "Catelyn Stark",
         "Lysa Arryn"
      ]
   },
   {
      "characterName":"Ellaria Sand",
      "houseName":"Martell",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNWQ0ZDE5NDUtNDVmZi00ZTI5LTkyOTgtNDhiNjMwZjY3ZjgwXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNWQ0ZDE5NDUtNDVmZi00ZTI5LTkyOTgtNDhiNjMwZjY3ZjgwXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0309687/",
      "actorName":"Indira Varma",
      "actorLink":"/name/nm0890055/",
      "killed":[
         "Myrcella Baratheon",
         "Doran Martell"
      ],
      "parentOf":[
         "Tyene Sand"
      ],
      "marriedEngaged":[
         "Oberyn Martell"
      ]
   },
   {
      "characterName":"Elia Martell",
      "houseName":"Martell",
      "royal":true,
      "marriedEngaged":[
         "Rhaegar Targaryen"
      ],
      "parentOf":[
         "Rhaenys Targaryen",
         "Aegon Targaryen"
      ],
      "killedBy":[
         "Gregor Clegane"
      ],
      "siblings":[
         "Doran Martell",
         "Oberyn Martell"
      ]
   },
   {
      "characterName":"Eon Hunter",
      "characterLink":"/character/ch0305321/",
      "actorName":"Barrington Cullen",
      "actorLink":"/name/nm4473207/"
   },
   {
      "characterName":"Euron Greyjoy",
      "houseName":"Greyjoy",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzg1MTJhMjMtMmY4Yy00NTU2LTliZWUtNjM4YzAxY2M3ZDBkXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzg1MTJhMjMtMmY4Yy00NTU2LTliZWUtNjM4YzAxY2M3ZDBkXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0518715/",
      "actorName":"Pilou Asbæk",
      "actorLink":"/name/nm1561982/",
      "killed":[
         "Balon Greyjoy",
         "Obara Sand",
         "Nymeria Sand",
         "Rhaegal"
      ],
      "siblings":[
         "Balon Greyjoy",
         "Aeron Greyjoy"
      ],
      "killedBy":[
         "Jaime Lannister"
      ]
   },
   {
      "characterName":"Faceless Man",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjI4ODYxODI0MF5BMl5BanBnXkFtZTgwMDk4NDY0NTE@._V1_UX214_CR0,0,214,317_AL_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjI4ODYxODI0MF5BMl5BanBnXkFtZTgwMDk4NDY0NTE@._V1_SY1000_CR0,0,665,1000_AL_.jpg",
      "characterLink":"/character/ch0259179/",
      "actorName":"Cedric Henderson",
      "actorLink":"/name/nm2406775/"
   },
   {
      "characterName":"Farlen",
      "characterLink":"/character/ch0305027/",
      "actorName":"Peter Ballance",
      "actorLink":"/name/nm0050520/"
   },
   {
      "characterName":"Gared",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNGYxZjljZTctZjIxYy00YmUwLTk3MDgtZWIyZjhkNDgwYTZiXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNGYxZjljZTctZjIxYy00YmUwLTk3MDgtZWIyZjhkNDgwYTZiXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_.jpg",
      "characterLink":"/character/ch0171395/",
      "actorName":"Dermot Keaney",
      "actorLink":"/name/nm0443825/",
      "killedBy":[
         "White Walker"
      ]
   },
   {
      "characterName":"Gatins",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzIwZmJkNDktZWMwMC00ZGNlLWJkNWYtN2ZmOWEzNDFiNWMyXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BNzIwZmJkNDktZWMwMC00ZGNlLWJkNWYtN2ZmOWEzNDFiNWMyXkEyXkFqcGdeQXVyMjk3NTUyOTc@._V1_SX1777_CR0,0,1777,999_AL_.jpg",
      "characterLink":"/character/ch0523969/",
      "actorName":"Ricky Champ",
      "actorLink":"/name/nm2307468/",
      "killedBy":[
         "Sandor Clegane"
      ]
   },
   {
      "characterName":"Gendry",
      "houseName":"Baratheon",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTcxNzYwMTk4MV5BMl5BanBnXkFtZTcwNDg1ODg4OQ@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTcxNzYwMTk4MV5BMl5BanBnXkFtZTcwNDg1ODg4OQ@@._V1_SY1000_CR0,0,846,1000_AL_.jpg",
      "characterLink":"/character/ch0300040/",
      "actorName":"Joe Dempsie",
      "actorLink":"/name/nm1478079/",
      "parents":[
         "Robert Baratheon"
      ],
      "killed":[
         "Kevin Eldon",
         "Laurence Spellman"
      ]
   },
   {
      "characterName":"Gerold Hightower",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BODc3OTIzYmEtYjk2Yy00NTgwLTk4OWMtMjlmMmJmNDE5OGU2XkEyXkFqcGdeQXVyNjU5MTM2ODI@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BODc3OTIzYmEtYjk2Yy00NTgwLTk4OWMtMjlmMmJmNDE5OGU2XkEyXkFqcGdeQXVyNjU5MTM2ODI@._V1_.jpg",
      "characterLink":"/character/ch0540530/",
      "actorName":"Eddie Eyre",
      "actorLink":"/name/nm6793798/",
      "killedBy":[
         "Eddard Stark"
      ]
   },
   {
      "characterName":"Ghost",
      "houseName":"Stark",
      "siblings":[
         "Grey Wind",
         "Lady",
         "Nymeria",
         "Summer",
         "Shaggydog"
      ],
      "guardianOf":[
         "Jon Snow"
      ],
      "killed":[
         "Rast"
      ]
   },
   {
      "characterName":"Gilly",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTYzOTQxMTA3MF5BMl5BanBnXkFtZTcwODM5NDk4OQ@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMTYzOTQxMTA3MF5BMl5BanBnXkFtZTcwODM5NDk4OQ@@._V1_SY1000_CR0,0,760,1000_AL_.jpg",
      "characterLink":"/character/ch0306819/",
      "actorName":"Hannah Murray",
      "actorLink":"/name/nm2356940/",
      "marriedEngaged":[
         "Samwell Tarly"
      ],
      "parentOf":[
         "Baby Sam"
      ],
      "parents":[
         "Craster"
      ]
   },
   {
      "characterName":"Goldcloak",
      "characterLink":"/character/ch0305037/",
      "actorName":"Alan Paris",
      "actorLink":"/name/nm3354768/"
   },
   {
      "characterName":"Goldcloak",
      "characterLink":"/character/ch0305037/",
      "actorName":"Sam Callis",
      "actorLink":"/name/nm0130538/"
   },
   {
      "characterName":"Goldcloak #1",
      "characterLink":"/character/ch0305037/",
      "actorName":"Nikovich Sammut",
      "actorLink":"/name/nm2089809/"
   },
   {
      "characterName":"Goldcloak #2",
      "characterLink":"/character/ch0305037/",
      "actorName":"Seamus Kelly",
      "actorLink":"/name/nm4440118/"
   },
   {
      "characterName":"Grand Maester Pycelle",
      "characterImageThumb":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjEyNDA4MzQ3MF5BMl5BanBnXkFtZTcwNTM3ODg4OQ@@._V1._SX100_SY140_.jpg",
      "characterImageFull":"https://images-na.ssl-images-amazon.com/images/M/MV5BMjEyNDA4MzQ3MF5BMl5BanBnXkFtZTcwNTM3ODg4OQ@@._V1_.jpg",
      "characterLink":"/character/ch0232836/",
      "actorName":"Julian Glover",
      "actorLink":"/name/nm0002103/",
      "killedBy":[
         "Little Birds"
      ]
   },
   {
      "characterName":"Great Master #1",
      "characterLink":"/character/ch0525536/",
      "actors":[
         {
            "actorName":"Emilio Doorgasingh",
            "actorLink":"/name/nm0233266/",
            "seasonsActive":[
               4
            ]
         },
         {
            "actorName":"Gianpiero Cognoli",
            "actorLink":"/name/nm2483357/",
            "seasonsActive":[
               5
            ]
         }
      ],
      "killedBy":[
         "Rebel Slaves",
         "Viserion",
         "Rhaegal"
      ]
   },
   {
      "characterName":"Great Master #2",
      "characterLink":"/character/ch0525536/",
      "actors":[
         {
            "actorName":"Derek Horsham",
            "actorLink":"/name/nm2471942/",
            "seasonsActive":[
               4
            ]
         },
         {
            "actorName":"Bobby Asghar",
            "actorLink":"/name/nm6800489/",
            "seasonsActive":[
               5
            ]
         }
      ]
   },
   {
      "characterName":"Great Master #3",
      "characterLink":"/character/ch0525536/",
      "actorName":"Peter Silverleaf",
      "actorLink":"/name/nm0798872/"
   },
   {
      "characterName":"Great Master #4",
      "characterLink":"/character/ch0525536/",
      "actorName":"Davor Jozinovic",
      "actorLink":"/name/nm7318132/"
   },
   {
      "characterName":"Great Master #5",
      "characterLink":"/character/ch0525536/",
      "actorName":"Ivan Peric",
      "actorLink":"/name/nm3005802/"
   },
   {
      "characterName":"Great Master #6",
      "characterLink":"/character/ch0525536/",
      "actorName":"Hadi Kermani",
      "actorLink":"/name/nm7318134/"
   },
   {
      "characterName":"Great Master #7",
      "characterLink":"/character/ch0525536/",
      "actorName":"Tonci Banov",
      "actorLink":"/name/nm7318135/"
   },
   {
   ```
   
1. A list of all songs with "Love" in the title.
```
```

1. All information about Petyr Baelish from the Game of Thrones books
```
https://anapioficeandfire.com/Documentation
snippet 
{
  "url": "https://www.anapioficeandfire.com/api/characters/823",
  "name": "Petyr Baelish",
  "culture": "Valemen",
  "born": "In 268 AC, at the Fingers",
  "died": "",
  "titles": [
    "Master of coin (formerly)",
    "Lord Paramount of the Trident",
    "Lord of Harrenhal",
    "Lord Protector of the Vale"
  ],
  "aliases": [
    "Littlefinger"
  ],
  "father": "",
  "mother": "",
  "spouse": "https://www.anapioficeandfire.com/api/characters/688",
  "allegiances": [
    "https://www.anapioficeandfire.com/api/houses/10",
    "https://www.anapioficeandfire.com/api/houses/11"
  ],
  "books": [
    "https://www.anapioficeandfire.com/api/books/1",
    ...
  ],
  "povBooks": [],
  "tvSeries": [
    "Season 1",
    "Season 2",
    "Season 3",
    "Season 4",
    "Season 5"
  ],
  "playedBy": [
    "Aidan Gillen"
  ]
}
```
1. All the movies Leonardo Dicaprio has acted in
```
not found
```

# Part Two

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200 
```
ok success status response code
```
1. 301
```
 Multiple Choices redirect status response code indicates that the request has more than one possible responses. The user-agent or the user should choose one of them. 
```
1. 400
```
Bad Request error is an HTTP status code that means that the request you sent to the website server, often something simple like a request to load a web page, was somehow incorrect.
```
1. 401
```
Unauthorized Error is an HTTP response status code indicating that the request sent by the client could not be authenticated. ... Conversely, a 401 Unauthorized Error indicates that the requested resource is restricted and requires authentication, but the client failed to provide any such authentication
```

1. 403
```
Forbidden client error status response code indicates that the server understood the request but refuses to authorize it.
```
1. 404
```
Not Found client error response code indicates that the server can't find the requested…Links which lead to a 404 page are often called broken or dead links
```
1. 418
ok this is cute! 😂
```
I'm a teapot client error response code indicates that the server refuses to brew coffee because it is a teapot. This error is a reference to Hyper Text Coffee Pot Control Protocol which was an April Fools' joke in 1998.
```
1. 500
```
he 500 Internal Server Error is a very general HTTP status code that means something has gone wrong on the website's server, but the server could not be more specific on what the exact problem is.
```

For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat



