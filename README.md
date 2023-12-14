# AirbeanExam

Här är länken till vår figma-skiss: [https://www.figma.com/file/92FGatTHBYzNSnibJt6iev/AirbeansExam?type=whiteboard&node-id=0-1&t=vk5ItjExxETFS2Mf-0 ](https://www.figma.com/file/92FGatTHBYzNSnibJt6iev/AirbeansExam?type=whiteboard&node-id=0-1&t=2nWtUEEYzL8Fuly5-0)

## Decomposition
Vi delade upp Airbeans olika processer i 7 olika delar med namnen: **Gränssnittsdesign, Användarprofil, Produkter, Kundservice, Varukorg, Orderhantering** och **Betalningshantering**.

#### Gränssnittsdesign
Förklarar de olika delarna som bildar webbappens gränssnitt så som responsivitet, färg och typsnitt. 
#### Användarprofil 
Innehåller de delar som är kopplade till en profil så som inloggning, att skapa ett konto, orderhistorik samt att produkter sparas i varukogen. 
#### Produkter
I denna del har vi lagt de komponenter som har med produkterna att göra så som produktkatalog och produktsök, dessa är kopplade till databasen där produkterna är registrerade.
#### Kundservice
Vår kundservice innehåller en FAQ-sida samt ett kontaktformulär där man kan nå oss. FAQ-sidan ansåg vi behövdes då vi misstänkte att det skulle kunna komma mycket frågor kring leveransen med drönare och hur den går till. 
#### Varukorg 
Varukorgen innehåller möjligheten att lätt ta bort samt lägga till varor för att förenkla handlingen. Totalpriset är också en viktig del i informationen som presenteras här. 
#### Orderhantering 
I orderhanteringen ingår alla de delar som innefattar beställningen:
* Att ta in information från varukorgen.
* Ge information om leverans - som sker antingen genom en interaktiv karta där man väljer leveransadress alt, egen upphämtning.
* Ange information om betalning.
* Ge bekräftelse på att beställning genomförts.
#### Betalningshantering
Visar på att betalning sker, dock inget vi går in närmare på då det sker av extern aktör. 


## Pattern recognition
För att identifiera återkommande moment utgick vi bland annat ifrån vår decomposition och kunde där hitta gemensamma mönster och gemensamma nämnare t.ex. i **design, datahantering, navigering, flöde, produktvisningar, varukorgens funktion** samt **profilanvändningen**. Genom att sammanfatta dessa aspekter skapas en helhetsbild av hur man som användare agerar, navigerar och identifieras inom Airbean. Dessa kan i sin tur kan leda till förbättringar av användarupplevelsen och effektiviseringar av processer.


## Abstraction
I Abstraction har vi haft som syfte att förenklat processerna genom att ta bort onödiga detaljer. **Köpprocessen, leveransalternativ, betalning, databashantering, profilhantering, användaren** och **produkten** är de delar vi primärt såg som relevanta och som de större övergripande processerna i webbapplicationen. Rubrikerna **Användaren** och **Produkten** är två exempel på hur en förenkling gentemot datorn kan se ut. Genom att undersöka denna förenkling av processerna är det sedan även lättare att skala upp/skala ner/hitta lösningar på problem. 


## Algorithm design
I vår Algorithm design har vi följt flödet i beställningsprocessen från start till mål. Den börjar med att man kommer in på webbapplicationen för att sedan gå vidare till produktlistan (alt. val att söka efter produkt). Man väljer kaffestorlek och eventuella tillägg (t.ex. allergier) innan man lägger produkten i varukorgen. Sedan får man allternativet att fortsätta handla eller gå vidare till betalning. Innan betalningen kommer frågan om man är inloggad, om inte kommer tre olika alternativ; *logga in*, *skapa konto* eller *fortsätt som gäst*. När detta val är utfört kommer man vidare till leveransalternativen som är via drönare alt. att hämta kaffet själv på plats. Därefter kommer betalningen, om verifiering inte går igenom behöver annan betalningsinformation anges. Om betalning går igenom sker köp och bekräftelse skickas. Detta är en övergripande process av flödet så som vi ser det.





