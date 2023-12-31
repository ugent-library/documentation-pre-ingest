---
description: >-
  Deze pagina beschrijft in grote lijnen de stappen in het pre-ingest werkproces
  dat we in de Universiteitsbibliotheek volgen.
---

# Overzicht

:construction: **Deze sectie is nog in opbouw**

## Intake (accesioning)

<table><thead><tr><th width="184">Kop</th><th>Item</th></tr></thead><tbody><tr><td>Start</td><td>Een archiefvormer neemt contact op met de Universiteitsbibliotheek voor het neerleggen van digital born materiaal.</td></tr><tr><td>Einde</td><td>Een geïdentificeerd pakket digitaal materiaal is overhandigd en wordt bewaard op een gekende, centrale plaats in de bibliotheek (fysieke drager of digitaal)</td></tr><tr><td>Beschrijving</td><td><p>Communicatie met de archiefvormer, maken van afspraken o.a.</p><ul><li>De wijze waarop het materiaal wordt overhandigd.</li><li>Klaren van rechten.</li><li>De structuur van het materiaal.</li><li>Voorzien van aanvullende metadata &#x26; contextuele informatie.</li><li>Het terug overhandigen van de fysieke drager.</li><li>Toegang tot het originele materiaal</li></ul><p>Het materiaal (1 of meerdere pakketten) krijgt een “intake nummer”.</p><p><br>Er wordt in het digitale klassement een dossier opgestart met alle relevante informatie gekoppeld aan dit “intake nummer”.<br></p><p>Er is een centraal register waarin het “intake nummer” wordt geregistreerd met basis-metadata. Er wordt een status toegekend en bijgehouden.</p></td></tr></tbody></table>

## Controle op virussen

<table><thead><tr><th width="184">Kop</th><th>Item</th></tr></thead><tbody><tr><td>Start</td><td>Een operator controleert het digitale materiaal op virussen en malware.</td></tr><tr><td>Einde</td><td>Aangetaste bestanden zijn geïdentificeerd. Er is een rapport met een aanbevolen aanpak.</td></tr><tr><td>Beschrijving</td><td><p>Een operator krijgt toegang tot het materiaal op een toegewezen werkstation en voert een virusscan uit. Op basis van het resultaat kiest de operator een aanpak:</p><ul><li>De bibliotheek neemt contact op met de archiefvormer om het pakket opnieuw aan te leveren.</li><li>Beschadigde bestanden worden in quarantaine geplaatst.</li><li>Enkel gezonde bestanden worden weerhouden.</li><li>Er wordt geprobeerd om bestanden te herstellen.</li></ul><p>In deze fase worden bestanden op de originele drager of originele locatie, en in hun originele vorm gecontroleerd. <br></p><p>Er wordt een rapport gemaakt dat bij de data wordt gehouden.</p></td></tr></tbody></table>

## Transfer naar een werklocatie

<table><thead><tr><th width="184">Kop</th><th>Item</th></tr></thead><tbody><tr><td>Start</td><td>De operator maakt een nieuwe directory aan in pre-ingest werklocatie.</td></tr><tr><td>Einde</td><td>Het digitale materiaal is in goede orde gekopieerd naar de werklocatie.</td></tr><tr><td>Beschrijving</td><td><p>In de werklocatie wordt een directory gemaakt met een unieke naam waarin het “intake nummer” voorkomt.</p><p></p><p>Het digitale materiaal kan op twee manieren vanaf de bron worden getransfereerd naar de werklocatie:</p><ul><li>Digitale bestanden worden stuk per stuk gekopieerd naar de werklocatie.</li><li>Er wordt een disk image gemaakt van het bestandsysteem waarop het digitale materiaal staat.</li></ul><p>De keuze hangt af van de aard van het aangeleverde digitale materiaal.<br><br>Tijdens de transfer zorgt de operator ervoor dat het materiaal bit-by-bit integraal wordt gekopieerd, maar ook dat eventuele technische metadata (permissies, creation/modified dates, bestandsindelingen,...) worden over genomen.</p></td></tr></tbody></table>

## Identificatie en validatie

<table><thead><tr><th width="184">Kop</th><th>Item</th></tr></thead><tbody><tr><td>Start</td><td>De operator maakt een analyse van het digitale materiaal.</td></tr><tr><td>Einde</td><td>Er is een manifest met een overzicht van alle bestanden, hun exacte locatie en de rapportage van formaat herkenning &#x26; validatie.</td></tr><tr><td>Beschrijving</td><td><p><em>Identificatie</em></p><p></p><p>De operator stelt (geautomatiseerd) een lijst op van alle overgedragen bestanden. Die lijst bevat metadata zoals bestandsnaam, locatie (file path), bestandsgrootte, file format, datum van creatie, datum van laatste aanpassing,...</p><p></p><p>Deze lijst vormt een weergave van de individuele bestanden in hun originele context.</p><p></p><p><em>Validatie</em></p><p></p><p>De operator valideert de formaten van alle bestanden in het manifest. Extra aandacht wordt gegeven aan …</p><ul><li>… bestanden waarvoor validatie faalt.</li><li>… bestanden waarvan het formaat niet geschikt is voor lange termijn bewaring.</li><li>… bestanden die geëncrypteerd zijn en niet kunnen worden uitgelezen zonder wachtwoord.</li></ul><p>De operator stelt een rapport op met een aanbeveling van te nemen acties.</p></td></tr></tbody></table>

## Schonen en ontdubbelen

<table><thead><tr><th width="184">Kop</th><th>Item</th></tr></thead><tbody><tr><td>Start</td><td>De operator voert een appreciatie uit van het digitale materiaal.</td></tr><tr><td>Einde</td><td>Een pakket bestanden bestemd voor opname in het digitale archief.</td></tr><tr><td>Beschrijving</td><td><p><em>Verwijderen niet-relevante systeembestanden</em></p><p></p><p>In sommige gevallen kan het aangeleverde digitale materiaal systeembestanden bevatten die geen inhoudelijke waarde hebben:</p><ul><li>Systeembestanden</li><li>Tijdelijke bestanden</li><li>Configuratie bestanden</li><li>Automatisch gegenereerde bestanden</li></ul><p><em>Ontdubbelen</em></p><p></p><p>Hetzelfde bestand kan op meerdere plaatsen in het bestandssysteem worden aangeleverd. </p><p></p><p>De operator maakt een analyse en bepaalt, rekening houdende met aspecten zoals archiefcontext, welke bestanden waardevol zijn om te weerhouden.</p></td></tr></tbody></table>

## Samenstellen SIP

<table><thead><tr><th width="184">Kop</th><th>Item</th></tr></thead><tbody><tr><td>Start</td><td>De operator start met het samenstellen van een SIP.</td></tr><tr><td>Einde</td><td>Er is een afgewerkte SIP.</td></tr><tr><td>Beschrijving</td><td><p>Een SIP (Submission Information Package) is een directory met te archiveren bestanden en metadata die volgens een specifieke structuur is opgebouwd.</p><p></p><p>Conversie</p><p></p><p>De operator converteert (een kopie van) de aangeleverde bestanden naar geschikte archiefformaten (bv. PDF/A)</p><p></p><p>Bestandsnamen</p><p></p><p>De operator past de bestandsnamen aan van (een kopie van) de aangeleverde bestanden.</p><p></p><p>Metadata</p><p></p><p>De operator voorziet een manifest bestand met basis-metadata<br></p><p>Rapportering</p><p></p><p>Tijdens het pre-ingest proces worden een aantal rapporten gegenereerd. Deze worden in het digitale klassement bij het intake-nummer bewaard, en ook mee in de SIP opgenomen.</p></td></tr></tbody></table>

## Opladen SIP

<table><thead><tr><th width="184">Kop</th><th>Item</th></tr></thead><tbody><tr><td>Start</td><td>De operator biedt de SIP aan in GREP.</td></tr><tr><td>Einde</td><td>De SIP is gearchiveerd in GREP.</td></tr><tr><td>Beschrijving</td><td><p>De operator plaatst de SIP in een gedeelde directory op een netwerklocatie. GREP zal deze via een geautomatiseerde job uitlezen en de geplaatste SIP’s verwerken.</p><p></p><p>De operator controleert in GREP of de SIP wordt geregistreerd. De operator volgt via de archiveringstatus in GREP op of de SIP ook succesvol door Meemoo is gearchiveerd.</p></td></tr></tbody></table>

