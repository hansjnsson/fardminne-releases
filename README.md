# Färdminne — utgåvor

Färdminne förvandlar råmaterial från en resa till tre filmer: en kort, en lång och en
komplett. Allt sker lokalt på datorn — materialet lämnar den aldrig.

Här ligger installationsprogrammen. Källkoden ligger i ett eget repo.

## Hämta appen

**[Ladda ner senaste versionen](https://github.com/hansjnsson/fardminne-releases/releases/latest)**

Ladda ner `Fardminne-Setup-<version>.exe` och kör den. Installationen sker per användare,
så inget administratörslösenord behövs. Du får välja var appen ska ligga.

Appen behöver ingenting förinstallerat — allt den använder följer med.

## Windows varnar första gången

Appen är inte signerad med ett certifikat, så Windows SmartScreen säger *"Windows
skyddade din dator"*. Det betyder inte att något är fel med filen, bara att den saknar
ett certifikat som kostar några tusen om året.

Klicka **Mer info** och sedan **Kör ändå**.

## Uppdateringar sköter sig själva

Du installerar en gång. Därefter letar appen efter nya versioner när den startar, hämtar
dem i bakgrunden och installerar dem när du stänger appen. Du behöver inte hålla koll på
den här sidan.

Är en uppdatering hämtad står det en rad om det i appen, och du kan installera den direkt
om du hellre vill det.

## Vilken version kör jag?

Versionsnumret står bredvid appens namn, uppe till vänster. Ta med det om du rapporterar
något som inte fungerar — utan det går det inte att säga vilket bygge felet gäller.

## Vad som får plats

| | |
|---|---|
| Nedladdning | ~180 MB |
| Installerat | ~570 MB |

Det mesta är FFmpeg, ExifTool och Electron, som alla följer med så att ingenting behöver
installeras separat.

## Licenser

Färdminne använder **FFmpeg**, byggt av [gyan.dev](https://www.gyan.dev/ffmpeg/builds/)
med `--enable-gpl --enable-version3`, vilket gör binären **GPLv3**.

GPLv3 kräver att källkoden till exakt det bygget är tillgänglig från samma ställe som
nedladdningen. Källarkiven finns hos gyan.dev och länkas i varje utgåva.

Licenstexterna följer med i installationen, under `licences/`. Fullständig
komponentförteckning ligger i `licences/THIRD-PARTY.md` i det du installerar.

Musiken som följer med appen är licensierad under Pixabay Content License. Den ingår i
det som byggs, men levereras aldrig som spelbara filer.
