# Furious Snake

Ett intensivt spel för två spelare där strategi och snabba reflexer avgör vem som vinner. Spelarna styr varsin orm i en värld fylld med faror och bonusar.

## Länk till spelet
[Testa spelet](https://oop-p5-game.vercel.app/)

## Spelbeskrivning

I Furious Snake tävlar två spelare mot varandra. Varje spelare styr en orm med målet att överleva och nå mållinjen före sin motståndare. Samtidigt måste de undvika faror och samla bonusar för att öka sina chanser att vinna.

### Grundläggande spelmekanik

*   **Ormens livskraft och egenskaper:**
    *   Startliv: 3 hjärtan
    *   Minimalt liv: 1 hjärta (0 hjärtan = Game Over)
    *   Maximalt liv: 10 hjärtan
    *   Egenskap: Fast form och längd på ormen
    *   Poängsystem: Spelare tjänar poäng så länge den håller sig vid liv. När spelaren tar en stjärna ökar poängen x2 under 10 sekunder.

*   **Spelomgångens längd:**
    *   Spelet har en fast bana med en startposition för ormarna och en mållinje. Spelet varar tills dess att en av spelarna gått i mål, eller att en av spelarna förlorar alla sina liv och får Game Over, eller går in i ett Tetrishinder eller i sidoväggen och får Game Over.

*   **Spelstart:**
    *   Spelet börjar när spelarna valt nivå i startmenyn (genom att klicka på Easy/Medium/Hard) och sedan klickat på Start Game-knappen. De kommer då vidare till en nedräkning från 3 för att kunna förbereda sig och fokusera.

*   **Spelavslut:**
    *   När en spelare får Game Over genom att förlora alla sina liv, eller får Game Over genom att gå in i en sidovägg eller ett Tetrishinder.

### Vinnare

*   **Vid Game Over:** När någon av spelarna krockar med Tetrishinder eller gråa väggen förlorar denna spelare och vinnaren är motståndaren.
*   **Vid mållinjen:** Vinnare är den spelare som når och träffar mållinjen först.
*   **Poäng:** Poängen som samlats in per sekund och ökats genom infångade stjärnor visas upp på Game Over / Winner-skärmarna, och syftet med dessa poäng är inte att utse en vinnare utan för att kunna ha rekord för sig själv och sin motspelare.

### Power-Ups och faror

*   **Faror:**
    *   **TetrisBlock:** Effekt: Game Over
    *   **Wall:** Effekt: Game Over
    *   **Ghost:** Effekt: -1 hjärta (om du är på spöket), -5 poäng (om du är i närheten av spöket)
    *   **Plant:** Effekt: -2 hjärtan

*   **Power-Ups:**
    *   **Stjärna:** Effekt: 2x poäng (under 10 sekunder)
    *   **Hjärta:** Effekt: +1 liv

### Strategi

*   **Resurshantering:** Balansera risken att samla power-ups mot att förlora liv.
*   **Positionering:** Planera din rutt för att undvika spöket medan du jagar power-ups.
*   **Timing:** Beräkna när det är värt att ta skada för att nå bättre position eller få extra poäng.

## Medutvecklare ❤️

*   Wilma
*   Tomas
*   Ahmad
*   Elnur
