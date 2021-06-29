# Aufgabe A: Bestehende OER teilen

Führen Sie eine Internetrecherche durch und identifizieren Sie hochwertige Lehrmaterialien, die den Merkmalen von OER entsprechen. Veröffentlichen Sie diese anschließend im OER-Portal twillo.

In den folgenden acht Schritten erhalten Sie wichtige Hinweise für die Aufgabenbearbeitung.

<b>Los geht's!</b><br><br>

<!-- Script fürs Accordion -->
<script>
var acc = document.getElementsByClassName("accordion");

for (var i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    var panel = this.nextElementSibling;
    /* if panel already open */
    if (panel.style.maxHeight) {
      this.classList.toggle('activeA', false);
    	panel.style.maxHeight = null;
      return;
    }
    /* else */
  	 for (var j = 0; j < acc.length; j++) {
    	acc[j].classList.toggle('activeA', false)
    	var p = acc[j].nextElementSibling;
    	p.style.maxHeight = null;
    }
    this.classList.toggle('activeA', true);
    panel.style.maxHeight = panel.scrollHeight + "px";

  });
}
</script>

<div>
  <button aria-label="zu Schritt 1" class="accordion">Schritt 1: Material finden</button>
  <div class="panel">
   <p> Recherchieren Sie im Internet nach interessanten Lehr-/Lernmaterialien ihres Faches/ihrer Disziplin, die CC-lizenziert sind. Legen Sie ein besonderes Augenmerk darauf, dass eine kostenfreie Verwendung, Veränderung und Weiterverbreitung des Materials zulässig ist.

Sie können für Ihre Internetrecherche z.B. Suchmaschinen nutzen, die explizit auf das Auffinden von OER ausgerichtet sind oder Internetseiten wählen, die offen lizenzierte Materialien bereitstellen. Dies sind z.B. 
   
  <ul>
    <li> OERSI (<a aria-label="Link zur OERSI-Seite" href="http://oersi.de/" target="_blank">oersi.de</a>, derzeit in der Beta-Phase)</li>
    <li> OERhörnchen (<a aria-label="Link zur OER-Hörnchen-Seite" href="http://oerhoernchen.de/" target="_blank">oerhoernchen.de</a>)</li>
    <li> CCsearch (<a aria-label="Link zur CC-Search-Seite" href="http://ccsearch.creativecommons.org/" target="_blank">ccsearch.creativecommons.org</a>)</li>
    <li> Wikimedia Commons (<a aria-label="Link zu Wikimedia Commons" href="http://commons.wikimedia.org/" target="_blank">commons.wikimedia.org</a>)</li>
    <li> X5GON (<a aria-label="Link zur X5GON-Seite" href="http://discovery.x5gon.org/" target="_blank">discovery.x5gon.org</a>, derzeit in der Beta-Phase)</p>
  </ul>
  Selbstverständlich können Sie für Ihre Recherche auch die üblichen Suchmaschinen oder Plattformen (z.B. Google und YouTube) nutzen. Um den Prozess zu vereinfachen, richten Sie Ihre Suche gezielt auf eine gewünschte Lizenz aus.

  <b>Google:</b> Geben Sie Ihren Suchbegriff ein und starten Sie die Suche. Wählen Sie anschließend unter <b>Einstellungen</b>, die <b>erweiterte Suche</b> aus (s. Abb. 11). Es öffnet sich ein neues Fenster. Hier können Sie die Ergebnisse Ihrer Suche im Bereich "Nutzungsrechte" entlang der von Ihnen gewünschten Lizenzierung eingrenzen (s. Abb. 12).
  <figure>
    <img src="images/Google_Suche_1.svg" alt="Abb. 11: Screenshot einer Googlesuche" title="Abbildung 11: Screenshot Google-Suche"/>
    <figcaption style="text-align:center;font-size:14px;">Abb. 11: Screenshot Google-Suche</figcaption>
  </figure>
  <figure>
    <img src="images/Google_Suche_2.svg" alt="Abb. 12: Screenshot einer Googlesuche mit Filter" title="Abb. 12.: Screenshot Google-Suchfilter"/>
    <figcaption style="text-align:center;font-size:14px;">Abb. 12.: Screenshot Google-Suchfilter</figcaption>
  </figure>
  <b>Youtube</b>: Geben Sie ihren Suchbegriff ein und starten Sie die Suche. Wählen Sie anschließend die Option <b>Filter</b> und schränken Sie die Ergebnisse im Bereich <b>Eigenschaften</b> durch die Wahl der Option <b>Creative Commons</b> ein (s. Abb. 13).
  <figure>
    <img src="images/YouTube.svg" alt="Abb. 13: Screenshot Youtube-Suchfilter" title="Abbildung 13: Screenshot YouTube-Suchfilter"/>
    <figcaption style="text-align:center;font-size:14px;">Abb. 13: Screenshot YouTube-Suchfilter</figcaption>
  </figure>
  </div>
  <button aria-label="zu Schritt 2" class="accordion">Schritt 2: Urheberrechtliche Aspekte & Lizenzen beachten</button>
  <div class="panel">
    <p>Haben Sie Material gefunden, das Sie gern auf twillo bereitstellen möchten, prüfen Sie, ob dieses den Merkmalen von OER entspricht. Beginnen Sie mit der Lizenz: Ein eindeutiger <b>Lizenzhinweis</b> sollte direkt am Material oder als begleitende Information gespeichert sein. Damit Sie das gefundene Material auf twillo teilen können, muss der Lizenzhinweis zumindest eine Information zu der <b>Lizenz</b> und der <b>Lizenzversion</b> (z.B. 2.0, 3.0 oder 4.0) enthalten, unter der das Material veröffentlicht wurde. Enthält die Lizenz das Modul <b>BY</b> müssen auch die Autor:innen ersichtlich sein. 
   
> &#128161; <b>Je offener die Lizenz, desto einfacher ist die Nachnutzung</b>
>
> Alle Materialien, die CC-lizenziert sind, dürfen Sie grundsätzlich im Portal einstellen. Materialien mit einer möglichst offenen Lizenz (CC 0, CC BY und CC BY SA) sind besonders willkommen, da diese eine einfache Verwendung, Veränderung und Weiterverbreitung ermöglichen und somit der grundsätzlichen Idee von OER entsprechen.
>
> Materialien, deren CC-Lizenz die Module ND und/oder NC enthalten, sind weniger offen und können in der Nachnutzung Probleme hervorrufen. So kann es z.B. schwierig sein, Material ohne die Erlaubnis zur Anpassung in das individuelle Lehr-Lernsetting zu integrieren. Auch die klare Trennung eines nichtkommerziellen von einem kommerziellen Verwendungskontext kann problematisch sein.
      
<b>Exkurs: Einbindung fremder OER in eigene Werke</b>

> Binden Sie OER anderer Urheber:innen bzw. Rechteinhaber:innen in eigene Werke ein, müssen Sie dies kenntlich machen.
<table id="invisible">
  <tr>
    <td valign="middle" text-align="middle" width="15%">
      <b><font size="10">T</font></b>
    </td>
    <td valign="middle" text-align="left" width="85%">
      Geben Sie den TITEL des Werks an, sofern dieser angegeben ist.
      <br>
      <i class="fa fa-info-circle" style="color:black"></i> In der Version 4.0 der CC-Lizenzen ist der Titel eine optionale (jedoch empfohlene) Angabe.
    </td>
  </tr>
  <tr>
    <td valign="middle" text-align="middle" width="15%">
      <b><font size="10">U</font></b>
    </td>
    <td valign="middle" text-align="left" width="85%">
      Nennen Sie den/die <b>URHEBER*IN(NEN)</b>/Rechteinhaber*in(nen). Auch Gruppen, Organisationen oder Institutionen können hier genannt werden. Orientieren Sie sich bei der Angabe daran, wie der*die Urheber*in(nen) in dem Material bezeichnet ist/sind.
    </td>
  </tr>
  <tr>
    <td valign="middle" text-align="middle" width="10%">
      <b><font size="10">L</font></b>
    </td>
    <td valign="middle" text-align="left" width="90%">
      Machen Sie eine Angabe zu der <b>LIZENZ</b> und der <b>LIZENZVERSION</b>. Übernehmen Sie diese Angaben genauso, wie an dem Material, das Sie nutzen, angegeben. Hierzu zählt ggf. auch die Angabe, ob es ich um eine an die Gesetzgebung eines Landes angepasste Version der Lizenz handelt.
      <br>
      <i class="fa fa-info-circle" style="color:black"></i> CC-Lizenztexte durchlaufen stetig Revisionsprozesse und werden sukzessive aktualisiert. Aus diesem Grund bestehen unterschiedlichen <b>Lizenzversionen</b> (2.0, 3.0 bzw. 4.0). Durch die Angabe der Lizenzversion machen Sie deutlich, auf welchen Stand des Lizenztextes Sie sich genau beziehen.
    </td>
  </tr>
  <tr>
    <td valign="middle" text-align="middle" width="10%">
      <b><font size="10">L</font></b>
    </td>
    <td valign="middle" text-align="left" width="90%">
      Setzen Sie einen <b>LINK</b> zu dem Lizenztext. Sollte eine Verlinkung nicht möglch sein, muss der Link ausgeschrieben werden.
    </td>
  </tr>
  <tr>
    <td valign="middle" text-align="middle" width="10%">
      <b><font size="10">U</font></b>
    </td>
    <td valign="middle" text-align="left" width="90%">
      Machen Sie eine Angabe zu dem <b>URSPRUNGSORT</b>, d.h. verlinken Sie z.B. die Internetseite, auf der Sie das Material gefunden haben. Ein solcher Hinweis ermöglicht es Nachnutzer*innen z.B. den Kontext des Originalwerks nachzuvollziehen.
    </td>
  </tr>
  <tr>
    <td valign="middle" text-align="middle" width="10%">
      <b><font size="10">+B</font></b>
    </td>
    <td valign="middle" text-align="left" width="90%">
      Haben Sie eine <b>BEARBEITUNG</b> an dem Material vorgenommen, muss dies ebenfalls kenntlich gemacht werden.
    </td>
  </tr>
</table>

<font size="3">Tabelle TULLU+B von twillo, basierend auf  <a aria-describedby="Link zur OER Infoseite, Tullu-Regel" href="https://open-educational-resources.de/oer-tullu-regel/">OER leichtgemacht mit der TULLU-Regel</a> von Jöran Muuß-Merholz und Sonja Borski  für <a aria-describedby="Link zur OER Infoseite" href="http://www.open-educational-resources.de/">OERinfo – Informationsstelle OER</a>, lizenziert unter <a aria-describedby="Link zur Creative Commons Seite" href="http://creativecommons.org/licenses/by/4.0/">CC BY (4.0)</a>.</font>
    </p>
  </div>
  <button aria-label="zu Schritt 3" class="accordion">Schritt 3: Dateiformat prüfen</button>
  <div class="panel">
   <p>Wenden Sie sich in diesem Schritt dem Dateiformat zu. Prüfen Sie, ob das Dokument in einem offenen Dateiformat vorliegt, das eine direkte Bearbeitung erlaubt.

  Sollte dies nicht der Fall sein, überführen Sie das gewählte Material in ein offeneres Dateiformat - <b>sofern es die Lizenz erlaubt</b>. Sollte die Lizenz das Modul <b>ND</b> enthalten, ist jegliche Form der Bearbeitung ausgeschlossen - dies gilt auch für die Konvertierung in ein anderes Format.

  Wenn Sie das Material in ein offenes Format überführen konnten/durften, stellen Sie am besten sowohl die konvertierte Datei (z.B. Word), als auch die Originaldatei (z.B. PDF) in das Portal. Auf diese Weise können Sie z.B. das Layout und Design des Originalwerks zur Veranschaulichung erhalten und gleichzeitig die Beabreitung der Inhalte ermöglichen.

  Wie Sie die das Material auf twillo teilen, erfahren Sie in den nächsten Schritten.</p>
  </div>
  <button aria-label="zu Schritt 4" class="accordion">Schritt 4: Anmeldung auf twillo</button>
  <div class="panel">
   <p>Um das Material auf twillo einzustellen, melden Sie sich im Portal an.
     
Rufen Sie den Link <a aria-label="Link zum OER-Portal" href="https://www.twillo.de/oer/" target="_blank">twillo.de</a> auf und gehen Sie über den Punkt <b>Zum Portal</b> im Kopfmenü auf den Bereich <b>Einloggen</b>. Alternativ klicken Sie <a aria-label="Link zu Twillo" href="https://www.twillo.de/edu-sharing/components/login" target="_blank">hier</a>, um direkt auf die Anmeldemaske von twillo zu gelangen.

   Angehörigen von Hochschulen, die <a aria-label="Link zu DFN-AAI" href="https://www.dfn.de/dienstleistungen/dfnaai/" target="_blank">DFN-AAI</a> nutzen, ist ein direkter Einstieg ins OER-Portal ohne manuelle Registrierung möglich (s. Abb. 16). Wählen Sie unter Einloggen hierfür die Option <b>Zur Hochschulauswahl</b>. Wählen Sie in der Liste Ihre Einrichtung/Institution und geben Sie in der Ihnen vertrauten Anmeldungsmaske die Kennung Ihres Hochschulaccounts ein. Sie befinden sich nach Anmeldung in Ihrem Workspace, dort werden Ihre eingestellten Bildungsmaterialien abgelegt (s. Abb.16).
   
<figure>
  <img src="images/twillo-Login-per-DFN.svg" alt="Abb. 16: Anmeldung DFN" title="Abbildung 16: Anmeldung DFN"/>
  <figcaption style="text-align:center;font-size:14px;">Abb. 16: twillo-Anmeldung über DFN</figcaption>
</figure>

  Das folgende Video veranschaulicht den Prozess der Anmeldung im Portal über DFN:
  <figure>
    <video style="width:100%;" controls>
      <source src="videos/DFN_Zugang.mp4" type="video/mp4" aria-label="Video: Bei Twillo anmelden">
    </video>
    <figcaption style="text-align:center;font-size:14px;">Video 2: Twillo-Zugang über DFN</figcaption>
  </figure>
  </p>
  </div>
  <button aria-label="zu Schritt 5" class="accordion">Schritt 5: Material einstellen</button>
  <div class="panel">
   <p>Sie haben auf twillo grundsätzlich die Möglichkeit, Materialien zu verlinken oder hochzuladen. 

  Der Einstellungsprozess wird, nachdem Sie auf die Buttonfläche <b>NEU</b> geklickt haben, durch Dialoge unterstützt. Wählen Sie <b>neues Material</b> aus und laden Sie Ihr Material hoch oder verlinken Sie es. Eine <b>Verlinkung</b> bietet sich immer dann an, wenn das Material, das Sie bereitstellen möchten, bereits online verfügbar ist und auf der Originalseite direkt genutzt werden kann (z.B. ein Selbstlernkurs in LiaScript, ein Lernvideo im TIB AV-Portal oder Youtube).

  Sobald Sie den Vorgang speichern, befindet sich das Material in Ihrem <b>Workspace</b>.

&#128161; Bis zur aktiven Freigabe (Schritt 9) bleibt das Material nur für Sie sichtbar.

  Unabhängig davon, ob Sie Material verlinkt oder hochgeladen haben, folgt im nächsten Schritt die Angabe von Metadaten. Diese dienen zum einen der Beschreibung der Materialien und sorgen zum anderen dafür, dass das Material gefunden werden kann.
  </p>
  </div>
  <button aria-label="zu Schritt 6" class="accordion">Schritt 6: Bildungsmaterial auffindbar machen</button>
  <div class="panel">
   <p>Beschreiben Sie das Material möglichst mit den Informationen, die Sie am Material finden.
     
<figure>
  <img src="images/Navigation_twillo.svg" alt="Abb. 17: Screenshot Navigation twillo" title="Abbildung 17: Screenshot Navigation twillo "/>
  <figcaption style="text-align:center;font-size:14px;">Abb. 17: Screenshot Navigation twillo </figcaption>
</figure>

Im Abschnitt <l>Lizenz</l> übernehmen Sie genau die Lizenz, die das Material aufweist. Geben Sie bei der Urheberangabe im Reiter <l>Autoren und Beteiligte</l> auch die Autor/*innen als Urheber/*inen an. Sollte es sich um ein gemeinfreies Werk oder CC 0-lizenziertes Werk handeln, können Sie den Namen, sofern bekannt, unter <l>freie Urheberangabe</l> oder <l>Autoren & Beteiligte</l> angeben.

<figure>
  <img src="images/Urheberangabe_Autoren und Beteiligte_twillo.svg" alt="Abb. 18: Screenshot Urheberangabe twillo " title="Abbildung 18: Screenshot Urheberangabe twillo "/>
  <figcaption style="text-align:center;font-size:14px;">Abb. 18: Screenshot Urheberangabe twillo </figcaption>
</figure>

###### Klassifizierungen

Die Einordnung der Bildungsmaterialien in einen der fünf <b>Inhaltstypen</b> liefert eine grobe Beschreibung über die Ausrichtung und den Umfang der Materialien, während die Angabe <b>Materialart</b> die (Medien-)Formate der Materialien detaillierter beschreibt. Beide Angaben können die Auffindbarkeit der Bildungsmaterialien erhöhen.

> &#128161; Funktionen im Portal
> <br>
> <br>
> <b>Kleinteilige Lehrmaterialien</b><br>
> können als einzelne Materialien bereitgestellt werden. Mit der <b>Serienfunktion</b> können entweder weitere Dateiformate oder dazugehörige Materialien (beim Erklärvideo bspw. Storyboard, Tonspur) ergänzt werden.
> <br>
> <br>
> <b>Aufgabenorientierte Materialien</b><br>
> zusätzliche Materialien zum Aufgabenelement, etwa Musterlösungen, Best-Practice-Beispiele oder dokumentierte Hilfestellungen, können mit der <b>Serienfunktion</b> ergänzt werden.
> <figure>
>   <img src="images/Screenshot_Serienfunktion.svg" alt="Abb. 19: Screenshot Serienfunktion twillo " title="Abb. 19: Screenshot Serienfunktion twillo "/>
>    <figcaption style="text-align:center;font-size:14px;">Abb. 19: Screenshot Serienfunktion twillo</figcaption>
> </figure>

Geben Sie auch das entsprechende <b>Fach-/ Sachgebiet</b> an und legen Sie <b>Schlagworte</b> fest, um die Auffindbarkeit Ihres Material in der  zielgerichteten Suche zu erhöhen.
  </p>
  </div>
  <button aria-label="zu Schritt 7" class="accordion">Schritt 7: Bildungsmaterial kontextualisieren</button>
  <div class="panel">
    <p>Im Abschnitt <b>Didaktik</b> können Sie weitere didaktische Kontextinformationen für Nutzer*innen des Portals angeben. Die hier ausgewählten Beschreibungskategorien können insbesondere bei der zielgerichteten Materialsuche für den eigenen Lehrkontext behilflich sein.

<ul>
  <li>Geben Sie an, in welchem <b>Veranstaltungsformat</b> Ihr Material erprobt oder für welchen Kontext es konzipiert wurde.</li>
  <br>
  <li>Geben Sie an, für welches <b>Niveau</b> bzw. für welche Zielgruppe Ihr Material primär entworfen wurde. Diese Angabe schließt eine Verwendung mit anderen Zielgruppen nicht aus.</li>
  <br>
  <li>Das Metadatum didaktische <b>Funktion</b> zeigt an, worauf und auf welche Lernhandlung das Bildungsmaterial primär zielt:</li>
  <ul>
    <li>Vermittlung von Lehrinhalten (rezipieren)</li>
    <li>Erarbeitung/Vertiefung von Lehrinhalten (aktiv aneignen)</li>
    <li>Einübung spezifischer Inhalte (routinisieren)</li>
    <li>Herstellung eigener Inhalte/Artefakte (erschaffen)</li>
    <li>Reflexion der (Lern-)Prozesse (beurteilen)</li>
  </ul>
  <br>
  <li><b>Erfahrungsbericht:</b> Beschreiben Sie den konkreten Einsatz des Materials. Mögliche Leitfragen für die Freitextangabe könnten sein:</li>
  <ol>
    <li>Setzt das Bildungsmaterial Vorwissen bei Lernenden voraus? <l>z. B. Für diese vertiefende Übung sind Grundkenntnisse der Algebra notwendig.</l></li>
    <li>Intendiert das Bildungsmaterial ein bestimmtes Lernziel?  <l>z. B. Die Studierenden sollen anhand des Planspiels erlerntes theoretisches Fachwissen spielerisch auf Praxisbeispiele anwenden und damit ihre Fach- und Methodenkompetenzen vertiefen.</l></li>
    <li>In welchem Lehr- bzw. Lernkontext haben Sie das Material bereits verwendet? <l>z. B. Diese Karikatur habe ich als stillen Impuls in meinem Seminar angewendet um in das Thema einzuführen.</l></li>
    <li>In welchem Lehr- bzw. Lernkontext könnte das Material noch verwendet werden? <l>z. B. Die Karikatur kann darüber hinaus als ein Beispiel für Pressefreiheit innerhalb eines Folieninputs verwendet werden.</l></li>
  </ol>
</ul>
  </p>
  </div>
  <button aria-label="zu Schritt 8" class="accordion">Schritt 8: Material freigeben</button>
  <div class="panel">
   <p>Erst mit der Freigabe veröffentlichen Sie Ihr Material auf twillo. Hierfür gibt es zwei Wege.

Entweder Sie aktivieren im Abschnitt Lizenz den Schalter <b>Objekt mit dieser Lizenz veröffentlichen </b>

<b>oder</b>

Sie gehen Sie über das Kontextmenü zum Punkt <b>Freigeben</b> und aktivieren in der Freigabemaske den Schalter <b>Material öffentlich freigeben</b>. Sie haben in dieser Maske auch die Möglichkeit, das Material zunächst nur für ausgewählte Personen freizugeben.

Falls Sie unsicher sind, können Sie z.B. alle Teilnehmer\*innen aus dem Workshop einladen und das Material nur mit diesem Kreis teilen.

<figure>
  <img src="images/Freigabe_twillo.svg" alt="Abb. 19: Screenshot Freigabe twillo " title="Abbildung 19: Screenshot Freigabe twillo "/>
   <figcaption style="text-align:center;font-size:14px;">Abb. 19: Screenshot Freigabe twillo</figcaption>
</figure>
  </p>
  </div>
</div>

<br>
<form action="#/motivation_a.md">
 <button aria-label="Button: Fertig" type="submit">Fertig</button>
</form>

