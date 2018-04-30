# Pirates Vs Knights
Created by **Gabriel Sansigolo**<br>

![image](https://github.com/GSansigolo/The-Last-Wards/blob/master/README.md%20Files/PRODUCTION.png?raw=true)<br><br>
Pirates vs Knights is a fantasy card game design by Gabriel Sansigolo, played in draft form the focus of the game is do actions and answers while battling. In this repository, you can find all files related to the non-digital and digital version.<br><br>

![image](https://github.com/GSansigolo/The-Last-Wards/blob/master/README.md%20Files/CREATOR.png?raw=true)<br><br>
**Gabriel Sansigolo** is taking master's degree in Applied Computation by the National Institute of Space Research. Technologist in Analysis and Development of Systems. Has IT Technician for Internet. Has experience in the area of Computer Science. Editor of the magazine 'Investida', Colorist and Game Writer. Currently works in the game The Last Wards and in the podcasts Esper Show and SDL Cast.<br>

**Issuu:** https://issuu.com/gabsansigolo <br>
**Amazon:** https://goo.gl/pX4aqo <br>
**Artstation:** https://www.artstation.com/gsansigolo <br>
**Blog:** https://viveiroartificial.blogspot.com <br>
**Twitter:** https://twitter.com/G_Sansigolo<br><br>

![image](https://github.com/GSansigolo/The-Last-Wards/blob/master/README.md%20Files/DEVELOP.png?raw=true)
<br><br>
Here you can see some examples, in json, of the cards. <br>
**Character Card:**
```json
 {
    "id": "2",
    "title": "Gravos",
    "color": "Blue",
    "type": "Character Card",
    "text": "Whenever this character is target of an action card, choose one: Receive +1{At} or Receive +1{Sh}.",
    "cbs-attack": "3",
    "cbs-armor": "4",
    "cbs-life": "2"
},
```

**Action Card:**
```json
  {
    "id": "12",
    "title": "Attack",
    "color": "Green",
    "type": "Action Card",
    "text": "You can attack with target character this turn. The damage is based on the character base status."
},
```

**Discard Card:**
```json
  {
    "id": "36",
    "title": "Discard",
    "color": "Magenta",
    "type": "Discard Card",
    "text": "If you discard this card you may draw card."
  },
```

**Draft Card:**
```json
  {
    "id": "35",
    "title": "Draft",
    "color": "Purple",
    "type": "Draft Card",
    "text": "Draft this card face up, if you do, you may draw a extra card in your first hand in the game.{This card don't have  effect in the game}."
},
```
