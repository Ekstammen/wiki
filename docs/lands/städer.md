# Städer/Land
Väldigt kortfattat så går lands ut på att skapa ett område/land och bygga en stad.
Staden kommer sedan att kosta pengar att utöka samt daglig skatt att ha staden igång.

Spelare kan sedan gå med i staden och hyra tomter att bygga på som ägaren av staden väljer ut.
På så sätt rullar ekonomin, spelaren betalar skatt till staden och staden betalar skatt till servern.

Att skapa ett nytt land / stad kostar 4000 mynt och man får då tillgång till en så kallad chunk.
En chunk är ett område på 16x16 block från lägsta punkt till högsta.

Till en början kan man köpa ett fåtal områden men när man ökar i [rank](ranker.md) så får man tillgång till fler.
Man får också tillgång till att bjuda in fler spelare när man klättrar i [rank](ranker.md).


## Skatter
Varje land betalar skatt till servern, kostnaden ligger på 50 mynt per claimad chunk.
Varje invånare i landet betalar skatt till landet + eventuell hyra av tomt, denna skatten bestämmer ägaren men max är 1000 mynt om dagen.

### Bankrutt 
Om ett land inte kan betala sin skatt så kommer servern att ta bort så många chunks staden inte kan betala för.
Tex om varje chunk kostar 50 mynt och landet har claimat 100 chunks så kostar detta 500 om dagen.
Om landet bara har 450 mynt i sin bank så kommer en chunk att bli vildmark, staden förlorar alltså en chunk.

Om en spelare inte kan betala sin skatt till staden så kickas hen och förlorar sin eventuella tomt.


### Lista på kostnader
* Skapa stad: 4000 mynt.
* Claima en chunk: 1500 mynt.
* Skatt till servern: 50 mynt per chunk.
* Byta namn på en stad: 1000 mynt.
* Ändra stadens spawnposition: 400 mynt.
* Byta ägare på en stad: 10 000 mynt.

## Inaktivitet
Om ägaren av ett land / en stad är inaktiv i 90 dagar så flagga den som inaktiv.
Det innebär att servern kommer försöka att tillsätta den med näst högst rank i staden som ny ägare och om det inte finns någon kommer landet att tas bort.

Om en invånare är inaktiv i 90 dagar så kommer hen att tas bort från staden och spelarens statistik nollställs.


## Snabbfakta
- Man kan ha max 14 bokstäver i ett stadsnamn.
- Teleporteringstider via städernas olika teleportsystem är tre sekunder.
- Det måste vara minst 50 chunks mellan två länder.
- En spelare måste vara trusted/invånare i en stad för att sätta ett hem där (/sethome).
- Man kan inte sälja en tomt, bara hyra.
- Monster och djur som spawnar i wild kan alltid gå in i en stad. 
- En ny stad är skattebefriad i två dagar.