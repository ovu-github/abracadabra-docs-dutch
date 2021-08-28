# __Lenen__
### <font color="gray">Deze pagina beschrijft de BORROW webpagina.</font><br/><br/>


[__Abracadabra__](https://docs.abracadabra.money/) gebruikt Kashi uitleentechnologie om geisoleerde uitleenmarkten leveren, die gebruikers in staat stellen om hun eigen risicotolerantie aan te passen afhankelijk van het onderpand waar gebruikers voor kiezen. Om meer te lezen over hoe geisoleerde uitleenmarkten en Kashi werken, en waarom ze verschillen van de traditionele uitleenprotocols, kan je [__deze__](https://docs.sushi.com/faq-1/kashi-bentobox-faq) referentie gebruiken.
 <br/><br/>
 
 ## __Onderpand inleggen en MIM lenen__

Navigeer naar [__abracadabra.money__](https://abracadabra.money/) en click __BORROW__.
 <br/><br/>
![name](https://gblobscdn.gitbook.com/assets%2F-Mc9U0yE30Tc9xb3mVGA%2F-McCaPMXj6Wy1FtLuGsj%2F-McCbRqCMmJAuJDZxYtY%2Fimage.png?alt=media&token=9ae57aab-3e6d-46a9-8a11-6b52678b2d5c)
 <br/><br/>
Het borrow-gedeelte van de website toont een verscheidenheid aan ibTKNS die gebruikt kunnen worden als onderpand. Here zijn een aantal voorbeelden:
 <br/><br/>
![name](https://gblobscdn.gitbook.com/assets%2F-Mc9U0yE30Tc9xb3mVGA%2F-Mc_TgUG3v65S9ilMwxL%2F-Mc_Twj8s0u-KpCtyEa9%2FScreenshot%202021-06-19%20at%2019.15.01.png?alt=media&token=b2582a3c-032b-4934-b11c-9345b3104ba0)

Bovenaan de afbeelding vind je:
 
 * __COMPONENT__ - Dit zijn de componenten die je als onderpand kan gebruiken om MIM's te lenen.
 * __Total Value Locked (TVL)__ - Dit toont de totale waarde van alle componenten die door alle gebruikers in de markt zijn ingelegd.
 * __LEFT TO BORROW__ - Dit toont hoeveel MIM's er nog beschikbaar zijn om te lenen als je die component gebruikt. Zodra dit de nul bereikt, kan je geen nieuwe hefboompositie of nieuwe leningen openen. Om meer MIM te lenen dienen gebruikers te wachten tot de desbetreffende markt aangevuld wordt!
* __INTEREST__ - Dit is de jaarlijkse percentage waarmee je schuld elk jaar zal groeien.
* __LIQUIDATION FEE__ - Dit is korting die de schuldeiser zal krijgen wanneer je positie geincasseerd wordt als je gemarkeerd voor incassering.

Om wat MIM's te lenen, click simpelweg ergens in het frame van het component die je als onderpand wil gebruiken. _We zullen yvUSDT als voorbeeld nemen._

![name](https://miro.medium.com/max/876/0*WGeM1bxDHGIepuiC)

Wanneer je component eenmaal geselecteerd is, komt het __BORROW/REPAY__ gedeelte tevoorschijn.
 <br/><br/>
![name](https://gblobscdn.gitbook.com/assets%2F-Mc9U0yE30Tc9xb3mVGA%2F-McCQ0Aqm8os1SpzNVt-%2F-McC_FmwhnFoU96AQ1cy%2Fimage.png?alt=media&token=600ae928-c90b-4947-9579-39249b8a51ed)
 <br/><br/>
Laten we eerst beginnen met het eerste scherm en de twee knoppen hierboven.  
 <br/><br/>
 ![name](https://miro.medium.com/max/548/0*9jQidm607uPTELlZ)
 <br/><br/>
Deze twee knoppen wisselen het frame simpelweg tussen MIM's lenen of terug te betalen.
 <br/><br/>
![name](https://miro.medium.com/max/549/1*ETjt9R6W-IoCzHAv5d5lmw.jpeg)

Eerst kies je hoeveel yvUSDT je als onderpand zal gebruiken. Daarna beslis je hoeveel MIM geleend zal worden door het getal in te typen of de percentageknoppen hieronder te gebruiken.
 <br/><br/>
De lichtblauwe __SAFE__ indicatie helpt ons door te waarschuwen wanneer we instellingen hebben gekozen die te riskant zijn. De __LIQUIDATION PRICE__ zal de prijs weergeven waarop we gemarkeerd worden voor incassering.
 <br/><br/>
 ## __Liquidation Price__
 
![name](https://gblobscdn.gitbook.com/assets%2F-Mc9U0yE30Tc9xb3mVGA%2F-Mc_Gz4aYkBy_Z_uMprV%2F-Mc_MmK9gvVrieLQytBV%2F1_0_GIF_2.gif?alt=media&token=90758c2e-2e23-4486-bf9c-86e9d20e469c)
<br/><br/>
Een incasseringsprijs van $0.71 houdt in dat wanneer je rentedragende token daalt tot of onder $0.71, je positie het risico loopt neemt om geincasseerd te worden. De getoonde incasseringsprijs is altijd gelinkt aan de rentedragende token die gebruikt wordt om MIM te lenen. Je kan meer over incassaties lezen in het deel van deze Wiki die er volledig op gericht is. Als je al een positie open hebt, let erop om de updated Total Liquidation price van die positie te controleren in het __MY OPEN POSITION__ gedeelte.
<br/><br/>
 ## __Update Price__

![name](https://miro.medium.com/max/167/0*1HHOuTPw9itxjRsX)

Deze checkbox stelt gebruikers in staat tegen een klein bedrag aan gas Abracadabra de laatste oracle prijs te laten ophalen voor het component die ze gebruiken om MIM te lenen. Hou rekening met het feit dat elke keer dat iemand met een van onze markten in aanraking komt met deze checkbox aangevinkt, de meest up to date prijs opgehaald zal worden van de oracle en weergegeven zal worden in de UI voor alle gebruikers.
<br/><br/>
_We zijn nu aan het kijken om dit proces te automatiseren, blijf hangen!_

![name](https://miro.medium.com/max/267/0*hHY9BF5EdqVTTGgF)

Wanneer we klaar zijn, kunnen we de __ADD COLLATERAL AND BORROW__ knop indrukken. Dit zal de ibTKNs vanuit onze portemonnee naar het contract verplaatsen, en de respectievelijke MIM tokens in onze portemonnee stoppen.
<br/><br/>
 ## __Managing Positions__

Open posities kunnen in hetzelfde scherm beheerd worden dat ook gebruikt wordt om oorspronkelijk een positie te openen. Hier kunnen we:

* Onderpand toevoegen
* Meer MIM lenen (veronderstellende je nog niet aan de max zit)
* Terugbetalen van geleende MIM
* Onderpand verwijderen (gebaseerd op het huidige schuldniveau / onderpand ratio)
<br/><br/>
 ## __Mijn open positie__

Aan de rechterkant, zal je een frame genaamd __MY OPEN POSITION__ die dynamische informatie weergeeft die belangrijk is voor deze specifieke positie. Als je een positie opent met andere componenten zullen deze getallen meebewegen. Let op dat elke keer dat je je positie aanpast (onderpand toevoegen of meer MIM's lenen) deze getallen zullen aanpassen. De incassatieprijs die hier wordt weergegeven is degeen die bepaalt wanneer je totale positie geincasseerd zal wordenone that will decide when your total position gets liquidated or not.
<br/><br/>
![name](https://gblobscdn.gitbook.com/assets%2F-Mc9U0yE30Tc9xb3mVGA%2F-McCHpW-h8Pfr7vBDldq%2F-McCL3akbwzzAPiFFyiO%2Fimage.png?alt=media&token=c2df355f-6e4b-4660-a88a-354ea4decdb2)

Het volgende stuk beschrijft wat welke parameter inhoudt.
* __Collateral deposited__ - Dit is de hoeveelheid tokens die je in deze positie hebt zitten.
* __Collateral value__ - Dit is de totale waarde in USD van alle componenten die je voor deze positie hebt aangeleverd
* __MIM borrowed__ - Dit is de totale waarde en hoeveelheid van de MIM die je geleend hebt. Het protocol veronderstelt altijd dat 1 MIM gelijkstaat aan 1 USD
* __Liquidation price__ - This is the price of the component at which your position will be flagged for liquidation. 
* __MIM left to borrow__ - This is how many MIMs you may still borrow before have reached your maximum allowance. To adjust this allowance you may either repay or add collateral.
* __1MIM = 1USD__ - This static number reminds the user that the protocol always considers 1MIM to equal 1USD.
* __1yvUSDT = 1.0097MIM__ - This is current price of our component, (in this case yvUSDT). If this number equals the Liquidation price, you will be flagged for liquidation.

## __De MANA Balk__
![name](https://gblobscdn.gitbook.com/assets%2F-Mc9U0yE30Tc9xb3mVGA%2F-McCHpW-h8Pfr7vBDldq%2F-McCOGsJ07bhqh1YHGBO%2Fimage.png?alt=media&token=f94f5ab5-455c-4094-90fd-e729370e9383)

This balk geeft gebruikers een visuele representatie van de status van hun huidige posities. Wederom, deze balk is geisoleerd van de overige componenten en puur voor het component van de pagina die op dit moment openstaat.

Hier zijn een aantal factoren:
* Een volle balk betekent dat het erg veilig is, en een lege balk betekent dat deze positie voor incassering gemarkeerd is.
* Als je onderpand inlegt maar geen MIM's leent zal de balk vol zijn.

__NOTE: Voor onderpanden op basis van stable coins zijn gebaseerd, is de balk tienmaal vergroot om zuiverder het risico niveau weer te geven.__
<br/><br/>
![name](https://gblobscdn.gitbook.com/assets%2F-Mc9U0yE30Tc9xb3mVGA%2F-McCQ0Aqm8os1SpzNVt-%2F-McCWIYTQdPXyekkV1YE%2Fimage.png?alt=media&token=9ddacc6d-096e-4545-bb92-2ee0b8714dec)
<br/><br/>
Dit aantal toont met hoeveel de prijs van je onderpand moet dalen voordat je ter incassatie wordt gemarkeerd

## __Andere menu's__

![name](https://gblobscdn.gitbook.com/assets%2F-Mc9U0yE30Tc9xb3mVGA%2F-McCQ0Aqm8os1SpzNVt-%2F-McCXEgFNoD2TZGVZeZ8%2Fimage.png?alt=media&token=61cbd0b8-b485-48be-acc2-0df9780e1370)

Dit menu geeft simpelweg je tokenbalans in de huidige aangesloten portemonnee weer.

![name](https://gblobscdn.gitbook.com/assets%2F-Mc9U0yE30Tc9xb3mVGA%2F-McCQ0Aqm8os1SpzNVt-%2F-McCX_ugrflZ9lunug_L%2Fimage.png?alt=media&token=69a037bd-4ee3-4988-8d76-7647dd64f05e)

Dit scherm toont de statische parameters voor dit onderpandtype. Deze getallen blijven constant tenzij het bestuur ervoor kiest om ze te wijzigen.

* __Maximum collateral ratio__ - De maximale onderpand ratio geeft de hoeveelheid schuld weer die een gebruiker kan lenen voor de geselecteerde onderpandstoken.
* __Liquidation fee__ - Dit is de korting die een incasseur krijgt wanneer deze je onderpand gemarkeerd voor incassatie opkoopt.
* __Borrow fee__ - Deze kosten worden aan je schuld toegevoegd elke keer wanneer je MIM leent. Bijvoorbeeld, als je 1000 MIM's leent zal je schuld toenemen met 1000.5 MIM's maar ontvang je eigenlijk 1000 MIM. Deze 0.5 MIM's zullen verdeeld worden over de sSPELL houders.
* __Interest__ - Dit is het jaarlijkse percentage waarmee je schuld elk jaar zal toenemen. De rente wordt later verdeeld over sSPELL houders.




