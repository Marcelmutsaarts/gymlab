# Gymlab

Leeromgeving voor lesorganisatie in het bewegingsonderwijs, voor ALO-studenten. Proof of concept.

- `index.html`: overzicht met tien onderwerpen (organiseren, begeleiden, didactiek) op een plattegrond van een gymzaal.
- `zaal.html`: **De Zaal**, het 3-vakkensysteem als 3D-simulatie.

## De Zaal

1. **Inrichten**: zet in een gymlokaal van 22 × 14 m toestellen neer (springkast, bok, minitrampoline, banken, balk, ringen, touwen, wandrek, mikken). Je kiest per toestel de variant en de mat. Valzones, uitloop, wachtrijen en looproutes zijn zichtbaar. Een live veiligheidscheck meldt kritieke punten en aandachtspunten.
2. **Lesgeven**: een gesimuleerde klas (groep 3–8, 18–32 leerlingen, met drukke, voorzichtige, dromerige en sterke leerlingen en een leerling met DCD) krijgt uitleg, werkt drie rondes in de vakken en draait door. Je versleept de docent, ziet het blikveld en kiest of je hulpverleent. Wachten leidt tot onrust. Wie onrustig is en niet gezien wordt, gaat rommelen. Incidenten buiten je blikveld merk je te laat op.
3. **Lesrapport**: scores voor bewegen, veiligheid, overzicht en rust, met een balansscore, tips en een vergelijking met de vorige poging.

Verder zijn er acht uitlegpunten (uitleg, praktijk, rekenen, denkvraag), zeven missies volgens RTTI, geluid en een presentatiestand.

Het is een leermodel. Gedrag, risico's en tijden zijn vereenvoudigd om het effect van keuzes zichtbaar te maken.

## Techniek

Statische HTML zonder build-stap. 3D met three.js r147 via jsDelivr. Geen cookies voor tracking, geen accounts, niets opgeslagen (alleen een vlag in de browser dat de uitleg al getoond is).
