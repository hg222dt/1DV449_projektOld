#Projektbeskrivning Webbteknik II
Microkartan är en site som ska göra att studenter runt om i landet lättare ska kunna hitta och tipsa om offentliga matplatser med microvågsugnar. Grundidén är därför att skapa en webbplats, där användare själva kan tipsa om offentliga microvågsugnar på specifika platser runt om i landet, vilka sedan placeras ut på en karta. Användare av siten kan sedan även se alla tips på en karta, samt även filtrera resultaten genom att använda sig av geo-baserade data från användarens enhet. Varje matplast kan även rendera en diskussionstråd, i syfte att varsegöra användaren om alla faktorer kring matplatsen, exempelvis om den är ren, liten, kall, bra ljudvolym, korta köer mm.
Webbplatsens design kommer att skapas med hjälp ut av css och SASS och den kommer att i den mån det är möjligt att jobba med geolocation.

####APIer
Jag hade tänkt använda mig av google maps api för att skapa kart-funktionalitet, både i syfte att placera ut nya uppgifter om matplatser, men även för att tillskansa sig redan utplacerade matplatser. 

För diskussionsfunktionaliteten ska ett API till diskussionsverktyget Disquss att användas. Med denna tjänst kan användaren kommentera fritt på siten, med bilder och annan funktionalitet, exempelvis betygssättning av kommentarer.

För att kunna lägga till matplatser och kommentera krävs det att man har loggat in via en webbplatsens OAuth-koppling.


