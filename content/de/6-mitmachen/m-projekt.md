+++
layout = 'about'
url = '/de/mitmachen/m-projekt'
title = 'Projekt einreichen'
+++

Werden Sie Teil einer wachsenden Community, die zeigt, was in der nachhaltigen Sanierung denkmalgeschützter Gebäude möglich ist.

<div style="background-color: #f5f5f5; padding: 20px; margin: 20px 0; border-radius: 8px;">
  <h2 id="funktioniert" style="margin-top: 0;">So funktioniert es</h2>

  <u>Schritt 1</u> <br>
  Füllen Sie das <a href="#erfassungsformular">Online-Formular</a> aus und stellen Sie Ihr Projekt vor.

  <u>Schritt 2</u> <br>
  Nach einer kurzen Prüfung durch das Erlebe-Erbe-Team erhalten Sie einen Upload-Link für Bilder und Pläne.
  Über diesen Link können Sie Ihre Unterlagen einfach hochladen.

  <u>Schritt 3</u> <br>
  Nach der Freigabe wird Ihr Eintrag auf der Plattform veröffentlicht.

  <br>
  <strong>Die Teilnahme ist kostenlos.</strong>
</div>

<br>
<br>
<br>

<div class="contact-content">
<p id="erfassungsformular" style="font-size: 30px; font-weight: bold;">Erfassungsformular für Best-Practice-Projekt <br>im Bereich Denkmalpflege</p></p>

<div style="background-color: #f5f5f5; padding: 20px; margin: 20px 0; border-radius: 8px;">
  <strong>Es gibt keine Pflichtfelder. Sie entscheiden selbst, welche Informationen Sie teilen möchten.</strong>

  <p>Jede Information trägt dazu bei, Erfahrungen zu teilen und anderen Orientierung für ihre eigenen Sanierungsprojekte zu geben.</p>
</div>

<!-- Contact form: replace the action URL with your Formspree endpoint (https://formspree.io/f/YOUR_FORM_ID) or follow the Netlify instructions below -->
<form id="projekt-form" method="POST" action="https://formspree.io/f/xbdakeqa">
 
  <!-- Redirect to thank-you page after submission -->
  <input type="hidden" name="_next" value="/de/6-mitmachen/danke/">

  <b>1. Projektbeschreibung</b>

  <label for="1.1-Projektname">1.1 Projektname</label>
  <input id="1.1-Projektname" name="1.1-Projektname" type="text">

  <label for="1.2-Beschreibung-Maßnahme">1.2 Beschreibung der Maßnahme</label>
  <textarea id="1.2-Beschreibung-Maßnahme" name="1.2-Beschreibung-Maßnahme" rows="24"></textarea>

  <label for="1.3-Geschichte-Objekt">1.3 Geschichte des Objekts</label>
  <textarea id="1.3-Geschichte-Objekt" name="1.3-Geschichte-Objekt" rows="24"></textarea>

<br>

<b>2. Energetische Sanierung</b>

  <label for="2.1-Beschreibung">2.1 Kurze Beschreibung</label>
  <textarea id="2.1-Beschreibung" name="2.1-Beschreibung" rows="24"></textarea>

  <label for="2.2-U-Werte">2.2 U-Werte der Bauteile</label>
  <textarea id="2.2-U-Werte" name="2.2-U-Werte" rows="24"></textarea>

  <label for="2.3-Heiztechnik">2.3 Heiztechnik (Heizung, Warmwasser)</label>
  <textarea id="2.3-Heiztechnik" name="2.3-Heiztechnik" rows="6"></textarea>

  <label for="2.4-Art-Lueftung">2.4 Art der Lüftung</label>
  <textarea id="2.4-Art-Lueftung" name="2.4-Art-Lueftung" rows="6"></textarea>

  <label for="2.5-Primaerenergiebedarf">2.5 Primärenergiebedarf</label>
  <input id="2.5-Primaerenergiebedarf" name="2.5-Primärenergiebedarf" type="text">

  <label for="2.6-Endenergiebedarf">2.6 Endenergiebedarf</label>
  <input id="2.6-Endenergiebedarf" name="2.6-Endenergiebedarf" type="text">

  <label for="2.7-Treibhausgasemissionen">2.7 Treibhausgasemissionen</label>
  <input id="2.7-Treibhausgasemissionen" name="2.7-Treibhausgasemissionen" type="text">

<br>

<b>3. Fakten</b>

  <label for="3.1-Bauherr">3.1 Bauherr</label>
  <input id="3.1-Bauherr" name="3.1-Bauherr" type="text">

  <label for="3.2-Baujahr">3.2 Baujahr</label>
  <input id="3.2-Baujahr" name="3.2-Baujahr" type="text">

  <label for="3.3-Wohnflaeche">3.3 Wohnfläche</label>
  <input id="3.3-Wohnflaeche" name="3.3-Wohnflaeche" type="text">

  <label for="3.4-Fertigstellung-Sanierung">3.4 Fertigstellung Sanierung</label>
  <input id="3.4-Fertigstellung-Sanierung" name="3.4-Fertigstellung-Sanierung" type="text">

  <label for="3.5-Baukosten">3.5 Baukosten</label>
  <input id="3.5-Baukosten" name="3.5-Baukosten" type="text">

  <label for="3.6-Foerdermittel">3.6 Fördermittel</label>
  <input id="3.6-Foerdermittel" name="3.6-Foerdermittel" type="text">

  <br>

<b>4. Projektbeteiligten</b>

<u>4.1 Planer</u> <br>

  <label for="f411-Architekten">4.1.1 Architekten</label>
  <input id="f411-Architekten" name="f411-Architekten" type="text">

  <label for="f42-Tragwerksplanung">4.1.2 Tragwerksplanung</label>
  <input id="f42-Tragwerksplanung" name="f42-Tragwerksplanung" type="text">

  <label for="f43-HLS-Planung">4.1.3 HLS-Planung</label>
  <input id="f43-HLS-Planung" name="f43-HLS-Planung" type="text">

  <label for="f44-Energieberatung">4.1.4 Energieberatung</label>
  <input id="f44-Energieberatung" name="f44-Energieberatung" type="text">

  <label for="f45-Andere">4.1.5 Andere</label>
  <textarea id="f45-Andere" name="f45-Andere" rows="6"></textarea>

<u>4.2 Ausführende Firmen</u> <br>

  <label for="f421-Ausfuehrende-Firmen">4.2.1 Ausführende Firmen</label>
  <textarea id="f421-Ausfuehrende-Firmen" name="f421-Ausfuehrende-Firmen" rows="6"></textarea>

  <br>

<b>5. Verwendete Produkten</b>

  <label for="f51-Verwendete-Produkten">5.1 Verwendete Produkten</label>
  <textarea id="f51-Verwendete-Produkten" name="f51-Verwendete-Produkten" rows="6"></textarea>

  <br>

<b>6. Bild- und Plananlage</b>

<u>Direkt-Upload (optional)</u> <br>
Laden Sie Ihre Dateien direkt im Formular hoch (max. 3 MB).

<label for="portfolio">Dateien hochladen</label>
  <input type="file"
         name="attachments[]"
         id="file"
         accept="image/*,.pdf"
         multiple>

<u>Weitere Dateien</u> <br>
Nach Prüfung Ihrer Angaben erhalten Sie einen persönlichen Upload-Link (Dropbox), über den Sie zusätzliche Unterlagen einfach und ohne Registrierung hochladen können.

<u>Hinweis</u> <br>
Bitte laden Sie alle relevanten Materialien hoch (Fotos, Pläne, Dokumentation) und benennen Sie die Dateien eindeutig.


<br>

<b>7. Einwilligung zur Veröffentlichung *</b>

<label class="consent"><input type="checkbox" name="consent" required> Ich willige in die Aufnahme meiner Angaben in die Datenbank der Plattform Erlebe Erbe ein. Ich erkläre mich damit einverstanden, dass meine Daten, einschließlich der eingereichten Bilder und Unterlagen, im Rahmen der Aufgaben der Plattform veröffentlicht und verarbeitet werden. 
Ich versichere, dass ich über die erforderlichen Nutzungsrechte an allen eingereichten Bildern und Unterlagen verfüge, und bestätige, die <a href="/datenschutz/" target="_blank" rel="noopener noreferrer"> Datenschutzerklärung </a> gelesen und verstanden zu haben. *
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