# Systemutveckling i praktiken och GitHub

Inlämningsuppgift 2 i kursen *Introduktion till .NET*.

## Vattenfall och agil metodik

Vattenfall är en utvecklingsmodell där man planerar ett projekt i sin helhet och arbetar enligt en planerad följd.
I ett agilt arbetssätt arbetar teamet istället med korta iterationer där enskilda funktioner och ändringar presenteras för användarna med oftare.

Vattenfallsmetodiken lämpar sig för projekt där det finns en tydlig, fast kravbild som inte väntas förändras under projektets gång. Agila arbetssätt lämpar sig bra när kravbilden inte är lika tydlig och man förväntar sig att behöva ändra riktning efter återkoppling från användare.

Vi kan förställa oss att projekt A gäller ett lagersystem som ska migrera orderdata enligt fasta, dokumenterade regler och kraven förväntas inte förändras. Här är vattenfallsmodellen ett bra och effektivt alternativ eftersom tydliga krav gör planering, dokumentation och ordningsföljd mer förutsägbara.

Projekt B är å andra sidan en Instagram-liknande applikation där det är oklart vilka nya funktioner som användarna vill ha. Här är det bättre med ett agilt arbetssätt eftersom varje implementerad funktion kan presenteras för användare så att teamet kan samla återkoppling och anpassa nästa iteration.

Det kan dock hända att betydande krav tillkommer sent, även i projekt A. Då är vattenfallsteamet vanligen mindre flexibelt än det agila eftersom utvecklingsmodellen inte är utformad för sena kravändringar. Det kan medföra omarbete och höga kostnader. Det agila teamet i projekt B kan också möta risker, till exempel om de saknar ett tydligt övergripande mål och återkopplingen tvingar dem till ständiga omprioriteringar. Risken är att kostnaderna stiger, att de levererar en undermålig slutprodukt eller att slutleveransen uteblir helt.

## Git-commits

En commit är en ögonblicksbild av det stageade innehållet i din projektmapp, som sparats i versionshistoriken.`git add` placerar den aktuella versionen av innehållet i staging area och väljer vad som ska ingå i nästa commit. `git commit` skapar och registrerar ögonblicksbilden av det stageade innehållet i den lokala historiken. Commit skiljer sig från en vanlig filsparning genom att ändringen även sparas i versionshistoriken medan en ändring i en sparad fil endast är tillgänglig i arbetsmappen. En push laddar även upp nya lokala commits till repositoryt på GitHub och uppdaterar den aktuella branchen.

Commits är viktiga för att kunna spåra ändringar och gå tillbaka i versionshistoriken om man stöter på problem under projektet. Exempel: vid ett tillfälle i utvecklingen av en specifik funktion kraschar programmet. Teamet kan granska versionshistoriken och identifiera efter vilken commit som kraschen uppstod. Identifieringen underlättas av tydligt avgränsade commits och beskrivande meddelanden. Därefter kan de granska koden och lösa problemet.

## Samarbete med GitHub

Svar:

## Arbetsflöde

Varje fråga har behandlats på en separat branch och slagits ihop med
`main` genom en pull request.