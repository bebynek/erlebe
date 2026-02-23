+++
layout = 'about'
url = '/de/mitmachen/m-interview'
title = 'Gesichter der Denkmalpflege'
+++

Gesichter der Denkmalpflege ist eine Interviewreihe, die die Menschen in den Mittelpunkt stellt, die hinter den Denkmälern und der Denkmalpflege stehen: Bauherren, Planer, Handwerker, Restauratoren, Hersteller von Bauprodukten. In kurzen Porträts geben sie Einblicke in ihre Motivation, ihre Arbeit und ihre größten Herausforderungen.

Die Interviews werden auf der Plattform Erlebe Erbe sowie in unseren Social-Media-Kanälen und im Newsletter veröffentlicht.


<div style="background-color: #f5f5f5; padding: 20px; margin: 20px 0; border-radius: 8px;">
  <h2 id="funktioniert" style="margin-top: 0;">So funktioniert es</h2>

  <u>Schritt 1</u> <br>
  Beantworten Sie bitte mindestens zwei der unten stehenden Fragen. Es steht Ihnen frei, die Fragen auszuwählen, die Sie beantworten möchten.

  Das Interview kann auch persönlich oder per Videokonferenz durchgeführt werden. 
  
  Bei Interesse schreiben Sie bitte an: info@erlebeerbe.com.

  <u>Schritt 2</u> <br>
  Nach dem Absenden des Formulars erhalten Sie einen persönlichen Upload-Link. Laden Sie bitte über diesen Link ein Foto von Ihnen ein.

  <u>Schritt 3</u> <br>
  Nach dem Erhalt des Bildmaterials wird das Intrview auf der Plattform veröffentlicht.

  <br>
  <strong>Die Teilnahme ist kostenlos.</strong>
</div>

<div class="contact-content">
<p style="font-size: 30px; font-weight: bold; ">Interview-Reihe <br>Gesichter der Denkmalpflege</p></p>

<br>

<!-- Contact form: replace the action URL with your Formspree endpoint (https://formspree.io/f/YOUR_FORM_ID) or follow the Netlify instructions below -->
<form id="planer-form" method="POST" action="https://formspree.io/f/mpqjlekq">
  <!-- Redirect to thank-you page after submission -->
  <input type="hidden" name="_next" value="/de/6-mitmachen/danke/">
<b>1. Angaben zur Person</b>

  <label for="name">Name *</label>
  <input id="name" name="name" type="text" required>

  <label for="rolle">Rolle / Tätigkeit * <br>z.B. Architekt:in, Restaurator:in, Handerwerker:in, Bauherr:in</label>
  <input id="rolle" name="rolle" type="text" required>

  <label for="firma">Unternehmen / Organisation</label>
  <input id="firma" name="firma" type="text">

  <label for="standort">Standort</label>
  <input id="standort" name="standort" type="text">

  <label for="website">Website</label>
  <input id="website" name="website" type="text">

  <label class="consent"><input type="checkbox" name="consent-verlinkung"> Ich möchte mit meiner Website / meinem Profil verlinkt werden.
</label>

  <br>
  <br>

<b>2. Kontakt (nicht öffentlich)</b>

  <label for="mail">E-Mail *</label>
  <input id="website" name="website" type="text" required>

  <label for="telefon">Telefon</label>
  <input id="telefon" name="telefon" type="text">

  <br>
  <br>

<b>3. Interview</b>

  <label for="f1">3.1. Wie berücksichtigen Sie in Ihrer Planung / Arbeit den Denkmalschutz, was ist Ihnen besonders wichtig?</label>
  <textarea id="f1" name="f1" rows="12"></textarea>

  <label for="f2">3.2. Was war bei Ihren Arbeiten mit denkmalgeschützten Gebäuden die größte Herausforderung und wie haben Sie sie gelöst?</label>
  <textarea id="f2" name="f2" rows="12"></textarea>

  <label for="f3">3.3. Welche Rolle spielen moderne Technologien, wie z.B. digitale Planungswerkzeuge bei der Sanierung von Denkmäler?</label>
  <textarea id="f3" name="f3" rows="12"></textarea>

  <label for="f4">3.4. Welche Entwicklungen oder Trends in der Denkmalpflege sehen Sie kritisch oder positiv?</label>
  <textarea id="f4" name="f4" rows="12"></textarea>

  <label for="f5">3.5. Haben Sie ein bestimmtes Projekt, das Sie als besonders gelungen im Bereich der Denkmalpflege betrachten?</label>
  <textarea id="f5" name="f5" rows="12"></textarea>

  <label for="f6">3.6. Was würden Sie Bauherren bei der Planung einer Sanierungsmaßnahme empfehlen?</label>
  <textarea id="f6" name="f6" rows="12"></textarea>  

<br>
<br>

<b>4. Bild</b>

<u>Dateien hochladen</u> <br>
Nach dem Absenden des Formulars erhalten Sie einen persönlichen Upload-Link (Dropbox), über den Sie ein Foto von Ihnen einfach und ohne Registrierung hochladen können.

<br>
<br>

<b>5. Einwilligung zur Veröffentlichung</b>

<label class="consent"><input type="checkbox" name="consent" required> Ich willige in die Aufnahme meiner Angaben in die Datenbank der Plattform Erlebe Erbe ein. Ich erkläre mich damit einverstanden, dass meine Daten, einschließlich der eingereichten Bilder, im Rahmen der Aufgaben der Plattform veröffentlicht und verarbeitet werden. 
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