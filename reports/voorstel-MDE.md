# Project Voorstel

***Apex Legends Local Stats***

Apex Legends is een schooter game.
Het spel heeft ook een API waar je requests naar kunt sturen.
Ik wil een app maken die informatie ophaalt van Apex Legends zodat je als speler op een mooi overzichtelijke manier kunt zien welke vooruitgang je geboekt hebt wanneer je speelt.
Het is dan ook leuk om deze data in verschillende aspecten te bekijken.

Je kan een speler aanmaken en hierbij een naam invoeren, als de naam bestaat word de speler aangemaakt.
Je kan meerdere spelers bijhouden bij de spelers page, je kan ze ook verwijderen waarbij de lokale data ook zal verwijderd worden.
Een speler is een soort profiel waarbij je kunt kiezen om te updaten of automatische updates aanzetten.
Hierbij word er steeds contact opgenomen met de API en zal de informatie local opgeslagen worden.
Met meerdere pagina's zal je kunnen zien hoeveel kills je hebt gemaakt overtijd, etc..
Je kan de data ook offline bekijken maar updates zijn uitgeschakeld.
Ik zou ook de mogelijkheid willen geven om te updaten wanneer de app aanstaat op de achtergrond om dan push notifications te geven wanneer je gewonnen hebt bijvoorbeeld.

Ik ben van plan te gaan voor Android en iOS support.
Ik geloof dat we hier spreken van Online Fetch, Offline CRUD.
2D Graphics voor mooiere weergave van de data en push notification wanneer de app loopt op de achtergrond.

---

>Dit is hoe de hoofdpagina eruit zou zien.
![Profiles v1](/reports/wireframes/profiles-1.png)

>Dit hoe het scherm er ongeveer uit zou zien als je op de plus klikt voor een nieuw profiel aan te maken.
![Add profile](/reports/wireframes/new-profile.png)

>Nieuw profiel aanmaken maar dan ingevuld.
![Add profile](/reports/wireframes/new-profile-filled.png)

>Als we dan opslaan ziet het profielen tablad er zo uit.
![Profiles v2](/reports/wireframes/profiles-2.png)

>Bij het klikken op instellingen kunnen we verschillende dingen aanpassen.
>Dit ziet er dan ook ongeveer het zelfde uit als het aanmaken.
![Edit profile](/reports/wireframes/edit-profile.png)

>Bekijk brengt ons bij de stats categories, vanuit hier kunnen we specifieker data bekijken.
![Choose category](/reports/wireframes/choose-category.png)

>De categories brengen ons naar Recent matches, Account stats en Legend stats.
>Recent matches tonen de recente matches, hier kan dan ook nog interessante informatie weergegeven worden.
![Recent matches](/reports/wireframes/recent-matches.png)

>Account stats toont informatie over het gehele account, hierbij ook extra diagrammen.
![Account stats](/reports/wireframes/account-stats.png)

>En dan als laatste voor je kunt terug keren, Legend stats, hier kun je per Legend je stats bekijken.
>Dit is nog veel interessanter omdat dit veel minder algemeen is.
![Legends stats](/reports/wireframes/legend-stats.png)
