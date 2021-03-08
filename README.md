<p align="center">
	<img src="https://img.shields.io/badge/PATCH-v%2011.5.1-green.svg" alt="for humans">
</p>

# League of Legends - List of champions for the store (in human format)

All champions from
```
http://ddragon.leagueoflegends.com/cdn/11.5.1/data/en_US/champion.json
```
with dependences to (Splashes,Loading screens,Avatars)
```
http://ddragon.leagueoflegends.com/cdn/11.5.1/data/en_US/champion/ChampionName.json
```

#### Preview:

```javascript
{
    "data": [
        {
            "key": "266",
            "name": "Aatrox",
            "skins": [
            {
                "num": "0",
                "skin_id": "266000",
                "chromas": false,
                "name": "default",
                "splash": "http://ddragon.leagueoflegends.com/cdn/img/champion/splash/Aatrox_0.jpg",
                "loading": "http://ddragon.leagueoflegends.com/cdn/img/champion/loading/Aatrox_0.jpg"
            },
            {
                "num": "1",
                "skin_id": "266001",
                "chromas": false,
                "name": "Justicar Aatrox",
                "splash": "http://ddragon.leagueoflegends.com/cdn/img/champion/splash/Aatrox_1.jpg",
                "loading": "http://ddragon.leagueoflegends.com/cdn/img/champion/loading/Aatrox_1.jpg"
            },
            // ...
            // ...
            // ...
            ],
            "square":
            {
                "link": "http://ddragon.leagueoflegends.com/cdn/11.5.1/img/champion/Aatrox.png"
            }
        }
        // ...
        // ...
        // ...
    ]
}
```