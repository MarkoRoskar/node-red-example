# Navodila za Namestitev in Zagon Node-RED

## Namestitev Node-RED

1. **Namestitev Node.js in npm**: Če še nimate nameščenega Node.js in npm, sledite navodilom na [uradni spletni strani Node.js](https://nodejs.org/) za namestitev na vaš sistem.

2. **Namestitev Node-RED**: Ko imate nameščen Node.js, lahko namestite Node-RED z uporabo npm. V ukazno vrstico vnesite:
npm install -g --unsafe-perm node-red
Ta ukaz bo namestil Node-RED globalno na vašem sistemu.

3. **Zagon Node-RED**: Po uspešni namestitvi vnesite v ukazno vrstico:
node-red
Node-RED bo zagnan in pripravljen za uporabo.

## Uvoz hello-world.json

1. **Prenos hello-world.json datoteke**: Prenesite hello-world.json datoteko na vaš računalnik in si jo zapomnite mesto, kamor ste jo shranili.

2. **Uvoz v Node-RED**: Odprite brskalnik in pojdite na [http://localhost:1880](http://localhost:1880) (privzeti naslov za lokalno nameščen Node-RED). V urejevalniku toka (flow editor) izberite meni v zgornjem desnem kotu in izberite možnost "Import". Nato izberite datoteko `hello-world.json` in jo uvozite.

## Zagon hello-world tok

1. **Deployanje toka**: Po uspešnem uvozu `hello-world.json` datoteke boste videli tok "hello-world" v urejevalniku toka. Da začnete izvajati ta tok, kliknite gumb "Deploy" v zgornjem desnem kotu urejevalnika toka.

2. **Preverjanje delovanja**: Po uspešnem deployu bo tok "hello-world" pripravljen za uporabo. Preverite rezultate v konzoli Node-RED ali v primeru hello-world toku, preverite konzolo brskalnika za prikaz sporočila "Hello, world!".

