+++
layout = 'about'
url = '/de/mitmachen/m-planer'
title = 'Als Planer:in bewerben'
+++

<div class="contact-content">
<p style="font-size: 30px; font-weight: bold;">Erfassungsformular <br> für Fachplaner:in im Bereich Denkmalpflege</p>

<br>
<br>

<!-- Contact form: replace the action URL with your Formspree endpoint (https://formspree.io/f/YOUR_FORM_ID) or follow the Netlify instructions below -->
<form id="contact-form" method="POST" action="https://formspree.io/f/mqedzqpl">
  <!-- Redirect to thank-you page after submission -->
  <input type="hidden" name="_next" value="/de/6-mitmachen/danke/">
<b>1. Fachplaner</b>

  <label for="firmenname">Firmenname *</label>
  <input id="firmenname" name="firmenname" type="text" required>

  <label for="strasse">Strasse, Hausnummer *</label>
  <input id="strasse" name="strasse" type="text" required>

  <label for="ort">Postleitzahl, Ort *</label>
  <input id="ort" name="ort" type="text" required>

  <label for="website">Website *</label>
  <input id="website" name="website" type="text" required>

  <br>
<b>2. Fachliche Qualifikation & Spezialisierung</b>

  <label for="fachliche-qualifikation">Fachliche Qualifikation / Berufsbezeichnung *</label>
  <input id="fachliche-qualifikation" name="fachliche-qualifikation" type="text" required>

  <label for="kammer">Zuständige Kammer/Verband *</label>
  <input id="kammer" name="kammer" type="text" required>

  <label for="spezialisierung">Spezialisierung</label>
  <input id="spezialisierung" name="spezialisierung" type="text"> 

  <label for="zertifikate">Zertifikate / Zusatzqualifikationen</label>
  <input id="zertifikate" name="zertifikate" type="text">   

  <br>
<b>3. Firmenprofil</b>

  <label for="leistungsumfang">Firmenprofil / Leistungsumfang *</label>
  <textarea id="leistungsumfang" name="leistungsumfang" rows="24" required></textarea>

  <br>


<b>4. Referenzprojekte Denkmalpflege</b>

Bitte geben Sie Informationen zu mindestens <u>einem</u> Projekt an.

<b>Projekt 1</b>

<label for="p1-projektname">Projektname *</label>
<input id="p1-projektname" name="p1-projektname" type="text" required>

<label for="p1-projektadresse">Projektadresse *</label>
<input id="p1-projektadresse" name="p1-projektadresse" type="text">

<label for="p1-projekt-leistungsumfang">Leistungen / Besonderheiten *</label>
<textarea id="p1-projekt-leistungsumfang" name="p1-projekt-leistungsumfang" rows="24" required></textarea>

<label for="p1-auszeichnungen">ggf. Auszeichnungen oder Anerkennungen</label>
<input id="p1-auszeichnungen" name="p1-auszeichnungen" type="text">

<b>Projekt 2 (optional)</b>

<label for="p2-projektname">Projektname</label>
<input id="p2-projektname" name="p2-projektname" type="text">

<label for="p2-projektadresse">Projektadresse</label>
<input id="p2-projektadresse" name="p2-projektadresse" type="text">

<label for="p2-projekt-leistungsumfang">Leistungen / Besonderheiten</label>
<textarea id="p2-projekt-leistungsumfang" name="p2-projekt-leistungsumfang" rows="24"></textarea>

<label for="p2-auszeichnungen">ggf. Auszeichnungen oder Anerkennungen</label>
<input id="p2-auszeichnungen" name="p2-auszeichnungen" type="text">

<b>Projekt 3 (optional)</b>

<label for="p3-projektname">Projektname</label>
<input id="p3-projektname" name="p3-projektname" type="text">

<label for="p3-projektadresse">Projektadresse</label>
<input id="p3-projektadresse" name="p3-projektadresse" type="text">

<label for="p3-projekt-leistungsumfang">Leistungen / Besonderheiten</label>
<textarea id="p3-projekt-leistungsumfang" name="p3-projekt-leistungsumfang" rows="24"></textarea>

<label for="p3-auszeichnungen">ggf. Auszeichnungen oder Anerkennungen</label>
<input id="p3-auszeichnungen" name="p3-auszeichnungen" type="text">


<b>5. Kontaktmöglichkeiten</b>

Kontaktperson

<label for="kontaktperson-name">Name *</label>
<input id="kontaktperson-name" name="kontaktperson-name" type="text" required>

<label for="kontaktperson-telfon">Telefon *</label>
<input id="kontaktperson-telefon" name="kontaktperson-telefon" type="text" required>

<label for="kontaktperson-e-mail">E-Mail *</label>
<input id="kontaktperson-e-mail" name="kontaktperson-e-mail" type="text" required>

<br>

<b>6. Anlagen</b>

Firmenlogo (max. 3 MB) *

<label for="portfolio">Firmenlogo (JPG/PNG)</label>
  <input type="file"
         name="attachments[]"
         id="firmenlogo"
         accept="image/*,.pdf"
         multiple>

Bild- und Plananlage für Best-Practice-Projekte *

<label for="fileLink">
 Laden Sie größere Dateien z. B. bei WeTransfer, Google Drive oder Dropbox hoch und fügen Sie den Download-Link hier ein. 

</label>
<input type="text" name="fileLink" id="fileLink"
       placeholder="https://…">
       <br>

Alternativ können Sie uns die Dateien auch per E-Mail an [info@erlebeerbe.com](mailto:info@erlebeerbe.com) zusenden.

<br>

<b>7. Einwilligung zur Veröffentlichung</b>

<label class="consent"><input type="checkbox" name="consent" required> Ich willige in die Aufnahme meiner Angaben in die Datenbank der Plattform Erlebe Erbe ein. Ich erkläre mich damit einverstanden, dass meine Daten, einschließlich der eingereichten Bilder und Unterlagen, im Rahmen der Aufgaben der Plattform veröffentlicht und verarbeitet werden. 
Ich versichere, dass ich über die erforderlichen Nutzungsrechte an allen eingereichten Bildern und Unterlagen verfüge, und bestätige, die <a href="/datenschutz/" target="_blank" rel="noopener noreferrer"> Datenschutzerklärung </a> gelesen und verstanden zu haben. *
</label>


Bitte stellen Sie sicher, dass die Bauherrschaft mit der Veröffentlichung der eingereichten Projektunterlagen einverstanden ist.
Gerne können Sie hierfür unsere Vorlage verwenden.
<a href="/files/erlebeErbe_Einverstaendniserklaerung_Eigentuemer.pdf" target="_blank" rel="noopener">
  PDF herunterladen.
</a>

<label class="consent-owner"><input type="checkbox" name="consent-owner" required> Ich bestätige, dass das Einverständnis der Eigentümerschaft zur Veröffentlichung vorliegt. *
</label>

  <button type="submit">Senden</button>
</form>

<p><small>* Pflichtfelder</small></p>

<script>
const form = document.getElementById('contact-form');
form.addEventListener('submit', async function(e) {
  e.preventDefault();
  const data = new FormData(form);
  const res = await fetch(form.action, {
    method: form.method,
    body: data,
    headers: { 'Accept': 'application/json' }
  });
  if (res.ok) {
    window.location.href = "/de/6-mitmachen/danke/";
  } else {
    alert("Fehler beim Senden. Bitte erneut versuchen.");
  }
});
</script>

</div>