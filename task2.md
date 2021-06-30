# Aufgabe B: Eigene OER teilen

Wählen Sie Lehr-/Lernmaterial aus, das Sie selbst für eine Ihrer Lehrveranstaltungen erstellt haben. Bereiten Sie es ggf. auf, damit es den Merkmalen von OER entspricht und veröffentlichen Sie es anschließend im OER-Portal twillo.

In den folgenden neun Schritten erhalten Sie wichtige Hinweise bei der Aufgabenbearbeitung.

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
  <button aria-label="zu Schritt 1" class="accordion">Schritt 1: Material auswählen</button>
  <div class="panel">
   <p>Damit der zeitliche Bearbeitungsrahmen von 30 Minuten eingehalten wird, empfehlen wir solche Materialien aus dem eigenen bewährten Lehrmaterialfundus zu wählen, die vom Umfang her den Inhaltsytypen <b>kleinteiliges Lehrmaterial</b> oder <b>aufgabenorientiertes Lehrmaterial</b> entsprechen.
    
<b>Kleinteilige Lehrmaterialien sind beispielsweise:</b>
<li>ein Foliensatz</li>
<li>ein Skript</li>
<li>ein Schaubild</li>

<b>Aufgabenorientierte Materialien sind beispielsweise:</b>
<li>eine Probeklausur mit Musterlösungen oder Hilfestellungen</li>
<li>ein Arbeitsblatt mit Hilfestellungen</li>
<li>ein Quiz mit Lösungen</li>

> &#x1F4A1; Bei der Bereitstellung von aufgabenorientierten Materialien sollten sowohl die Aufgabe, die Übung, das Arbeitsblatt etc., als auch ergänzende Materialien wie z.B. Hilfestellung, (Muster-)Lösungen, bzw. Lösungswege oder Best-Practice-Beispiele bereitgestellt werden. Dies erleichtert anderen Lehrenden die Nachnutzung und Kontextualisierung der Materialien.
    </p>
  </div>
  <button aria-label="zu Schritt 2" class="accordion">Schritt 2: Urheberrechtliche Aspekte & Lizenzen beachten</button>
  <div class="panel">
   <p>Nachdem Sie nun eine Wahl getroffen haben, überprüfen Sie, ob sich <b>Inhalte oder Werke Dritter</b> in Ihrem Material befinden. Haben Sie beispielsweise Bilder verwendet, die urheberrechtlich geschützt sind oder CC-lizenzierte Texte eingebunden? 
  
###### Einbindung urheberrechtlich geschützter Inhalte

Die Verwendung von urheberrechtlichgeschützen Materialien im geringfügigen Umfang wie es im § 60 UrhG geregelt ist, ist bei der Veröffentlichung Ihres Materials als OER <b>nicht zulässig</b>. Diese Regelung gilt nur im Rahmen geschützter Lehrräume (z.B. Hörsaal/LMS). <br>
<b>Zitate</b> können, wenn Sie als solche gekennzeichnet sind, eingebunden werden. Hier gilt: Aussagen oder Bezugnahmen auf andere Quellen sind erlaubt, wenn sie zweckgemäß zum Einsatz kommen.

Das Zitatrecht (§ 51 UrhG) stellt eine gesetzliche Lizenz dar, die vertraglichen Lizenzen (z.B. CC-Lizenzen) vorgeht. Analog zur wissenschaftlichen Praxis müssen folgende Kriterien vorliegen:

 <li>der Zitatzweck liegt vor (inhaltlicher Zusammenhang)</li>
<li>der Umfang des Zitats ist durch den Zweck gerechtfertigt (Umfang des zitierten Werks ist nicht unangemessen groß)</li>
<li>die Quelle ist angegeben, § 63 UrhG (mind. Name des Urhebers und die Fundstelle)</li>
<li>das fremde Werk /die fremden Werkteile wurden nicht verändert, § 62 UrhG (Kürzungen bei umfangreichen Werken, kleinere Änderungen der Satzstruktur sind erlaubt, müssen aber kenntlich gemacht werden!)</li>

> &#9888;&#65039; Grundsätzlich gilt: Enthält Ihr Material urheberrechtlich geschützte Inhalte oder Werke, sollten Sie diese entfernen und ggf. nach Alternativen suchen. Eine Möglichkeit ist, sie durch CC-lizenierte Inhalte zu ersetzen.
     
###### Einbindung fremder OER in eigene Werke
     
Bei der Einbindung von CC-lizenzierten Materialien in Ihre eigenen Werke, müssen Sie kenntlich machen, dass es sich um fremde Inhalte handelt. Analog zur klassischen Zitation im wissenschaftlichen Arbeiten gibt es bei der Nachnutzung von OER bestimmte Vorgaben. In der sogenannten "TULLU-Regel" werden diese für Sie zusammengefasst:
<table id="invisible">
  <tr>
    <td valign="middle" text-align="middle" width="15%">
      <b><font size="10">T</font></b>
    </td>
    <td valign="middle" text-align="left" width="85%">
      Geben Sie den <b>TITEL</b> des Werks an, sofern dieser angegeben ist.
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
      <b><font size="10">+ B</font></b>
    </td>
    <td valign="middle" text-align="left" width="90%">
      Haben Sie eine <b>BEARBEITUNG</b> an dem Material vorgenommen, muss dies ebenfalls kenntlich gemacht werden.
    </td>
  </tr>
</table>
    
<figcaption style="text-align:center;font-size:14px;">Tabelle TULLU+B von twillo, basierend auf  <a aria-describedby="Link zur OER Infoseite, Tullu-Regel" href="https://open-educational-resources.de/oer-tullu-regel/">OER leichtgemacht mit der TULLU-Regel</a> von Jöran Muuß-Merholz und Sonja Borski  für <a aria-describedby="Link zur OER Infoseite" href="http://www.open-educational-resources.de/">OERinfo – Informationsstelle OER</a>, lizenziert unter <a aria-describedby="Link zur Creative Commons Seite" href="http://creativecommons.org/licenses/by/4.0/">CC BY (4.0)</a>.</a></figcaption>
<br>   
<br>
In folgendem Erklärvideos sehen Sie, wie mit <b>eingebundenen fremden Materialien</b> im eigenem Bildungsmaterial verfahren wird und was Sie beachten müssen, wenn Sie <b>fremde Materialien bearbeiten</b>.

<figure>
<video style="width:100%;" controls>
 <source src="videos/Lizenzangaben_bei_eingebundenen_fremden_Materialien.mp4" type="video/mp4" aria-label="Video zu Lizenzangaben bei eingebundenen fremden Materialien">
 </video>
 <figcaption style="text-align:center;font-size:14px;">Video 2: Lizenzangaben bei eingebundenen fremden Materialien von twillo, lizenziert unter <a href="https://creativecommons.org/licenses/by/4.0/">CC BY (4.0)</a></figcaption>
</figure>

<figure>
<video style="width:100%;" controls>
 <source src="videos/Lizenzangaben_bei_bearbeiteten_Materialien.mp4" type="video/mp4" aria-label="Video zu Lizenzangaben bei bearbeiteten Materialien">
 </video>
 <figcaption style="text-align:center;font-size:14px;">Video 3: Lizenzangaben bei bearbeiteten Materialien von twillo, lizenziert unter <a href="https://creativecommons.org/licenses/by/4.0/">CC BY (4.0)</a></figcaption>
</figure>  
  </div>
  <button aria-label="zu Schritt 3" class="accordion">Schritt 3: Lizenz und Lizenzversion wählen</button>
  <div class="panel">
   <p>In diesem Schritt müssen Sie auswählen, unter welche Creative Commons-Lizenz Sie Ihr Material stellen möchten. Überlegen Sie hierfür, welche Nutzungsrechte Sie anderen Personen einräumen möchten. Was ist Ihnen wichtig?<br>
     Denken Sie daran, dass Sie eine Lizenzierung nur dann vornehmen dürfen, wenn Sie Urheber:in des zu lizenzierenden Materials sind. Sollten mehrere Personen Urheber:innen sein oder Rechte an dem Material besitzen, muss gemeinsam über die Lizenzierung entschieden werden. 
<br>

> &#x1F4A1; <b>Je offener die Lizenz, desto einfacher ist die Nachnutzung</b>
> 
> Materialien mit einer möglichst offenen Lizenz (CC 0, CC BY und CC BY SA) sind auf twillo besonders willkommen, da diese eine einfache Verwendung, Veränderung und Weiterverbreitung ermöglichen und somit der grundsätzlichen Idee von OER entsprechen.
> 
> Materialien, deren CC-Lizenz die Module ND und/oder NC enthalten, sind weniger offen und können in der Nachnutzung Probleme hervorrufen. So kann es z.B. schwierig sein, Material ohne die Erlaubnis zur Anpassung in das individuelle Lehr-Lernsetting zu integrieren. Auch die klare Trennung eines nichtkommerziellen von einem kommerziellen Verwendungskontext kann problematisch sein.

Um Material zu lizenzieren, ist es ausreichend, einen Lizenzhinweis gut sichtbar an Ihrem Material anzubringen. Bei einem Skript können Sie ihn z.B. auf der ersten Seite positionieren, bei einen Foliensatz auf der Titel- oder auf der Abschlussfolie. 

<b>Folgende Punkte sind für eine korrekte Lizenzierung Ihres eigenen Materials zu beachten:</b><br>
<li><b>Lizenz und Lizenzversion:</b> Geben Sie die Lizenz und die Version an. Dabei reichen die gängigen Kürzel wie zum Beispiel "lizenziert unter CC BY 4.0" aus.</li>
     <li><b>Urheber:innenangaben:</b> Haben Sie sich für das Lizenzmodl <b>BY</b> entschieden, stellen Sie, sicher, dass die Namen aller Urheber:innen bzw. Rechteinhaber:innen an Ihrem Material angegeben sind. Auch der Name einer Organisation, Institution oder Projektgruppe ist zulässig, sofern diese die Rechte am Werk besitzt.</li>
<li><b>Titel des Werks:</b> Bei der Lizenzversionen 3.0 und Ihren Vorgängerversionen muss der Titel des Werks erkennbar sein. Ab der Lizenzversion 4.0 ist dies nicht mehr erforderlich</li>.
<br>
<br>
<b>Um dritten die Nachnutzung Ihres Materials zu erleichtern, können Sie zudem folgende Angaben in den Lizenzhinweis aufnehmen:</b><br> 
<li><b>Link zum Lizenztext:</b> Setzen Sie einen Verweis zu der Lizenz. Wenn kein Link möglich ist (z.B. bei gedruckten Materialien oder in Videos) kann der Link auch ausgeschrieben werden.
<li><b>Lizenzicon:</b> Für den Wiedererkennungswert kann das Lizenzicon mitgeführt werden. Auf der Webseite von Creative Commons können Sie das entsprechende Lizenzicon kopieren und neben dem Lizenzhinweis positionieren.</li>
<li><b>Ausnahmeregelungen oder weitere Hinweise</b>: Nehmen Sie ggf. Informationen auf, die Dritte bei der Nachnutzung Ihres Materials beachten müssen</li>

An folgendem Beispiel für einen ausführlichen Lizenzhinweis können Sie sich bei der Lizenzierung Ihrer eigenen Materialien orientieren.
      <br><br>
      <table id="invisible">
        <tr>
          <td width="12%">
            <img src="images/creative-commons_cc-by.svg" alt="Lizenz CC BY" title="Lizenz CC BY">
          </td>
          <td valign="middle" text-align="left" width="88%">
            Dieser digitale Leitfaden "Teilen von Bildungsmaterialien" des OER-Portals twillo ist - sofern nicht anders an einzelnen Inhalten angegeben - lizenziert unter <a aria-describedby="Link zur Lizenz" href="https://creativecommons.org/licenses/by/4.0/deed.de">CC BY 4.0</a> 
          </td>
        </tr>
      </table>


  Das folgende Video "Lizenzhinweise am eigenem Material" zeigt, worauf bei der Lizenzierung geachtet werden muss.

<figure>
<video style="width:100%;" controls>
 <source src="videos/Lizenzangaben an eigenen Bildungsmaterialien.mp4" type="video/mp4" aria-label="Video zu Lizenzangaben an eigenen Bildungsmaterialien">
 </video>
 <figcaption style="text-align:center;font-size:14px;">Video 1: Lizenzhinweise am eigenem Material</figcaption>
</figure>

&#9888;&#65039; <b>Nicht immer ist eine freie Lizenzwahl möglich:</b> \
Wenn Sie einzelne Inhalte oder Werke entsprechend der lizenzrechtlichen Vorgaben bearbeitet haben (z.B. Designanpassung oder inhaltliche Ergänzungen), dann kennzeichnen Sie dies im Lizenzhinweis und prüfen, welche Lizenzbedingungen am verwendeten Ursprungswerk gelten! Wenn Sie z.B. auf ein Material aufbauen, dass unter der Lizenz CC BY SA steht, dann müssen Sie das neu entstandene Werk ebenfalls unter dieser Lizenz stellen.
  </p>
  </div>
  <button aria-label="zu Schritt 4" class="accordion">Schritt 4: Bildungsmaterial im offenen Dateiformat speichern</button>
  <div class="panel">
   <p>In diesem Schritt überprüfen Sie, ob Ihr Material in einem offenen Dateiformat vorliegt. Durch die Verwendung von offenen oder weitverbreiteteten Formaten, ermöglichen Sie es Dritten Ihr Material herunterzuladen und es direkt zu bearbeiten. Überlegen Sie, ob Sie Ihr Material aus besonderen Gründen in mehreren Dateiformaten bereitstellen möchten (Layout, Kompatibilität, etc.)</p>
  </div>
  <button aria-label="zu Schritt 5" class="accordion">Schritt 5: Anmeldung auf twillo</button>
  <div class="panel">
   <p>Um das Material auf twillo einzustellen, melden Sie sich im Portal an.
    
Rufen Sie den Link <a aria-label="Link zum OER-Portal" href="https://www.twillo.de/oer/" target="_blank">twillo.de</a> auf und gehen Sie über den Punkt <b>Zum Portal</b> im Kopfmenü auf den Bereich <b>Einloggen</b>. Alternativ klicken Sie <a aria-label="Link zu Twillo" href="https://www.twillo.de/edu-sharing/components/login" target="_blank">hier</a>, um direkt auf die Anmeldemaske von twillo zu gelangen.

   Angehörigen von Hochschulen, die <a aria-label="Link zu DFN-AAI" href="https://www.dfn.de/dienstleistungen/dfnaai/" target="_blank">DFN-AAI</a> nutzen, ist ein direkter Einstieg ins OER-Portal ohne manuelle Registrierung möglich. Wählen Sie unter Einloggen hierfür die Option Zur Hochschulauswahl. Wählen Sie in der Liste Ihre Einrichtung/Institution und geben Sie in der Ihnen vertrauten Anmeldungsmaske die Kennung Ihres Hochschulaccounts ein (s. Abb. twillo-Anmeldung über DFN). Sie befinden sich nach Anmeldung in Ihrem Workspace, dort werden Ihre eingestellten Bildungsmaterialien abgelegt.
   
   <figure>
  <img src="images/twillo-Login-per-DFN.svg" alt="Abb.: Anmeldung DFN" title="Abbildung: Anmeldung DFN"/>
     <figcaption style="text-align:center;font-size:14px;">Abb. <i>twillo-Anmeldung über DFN</i></figcaption>
</figure>

  Das folgende Video veranschaulicht den Prozess der Anmeldung im Portal über DFN:
  <figure>
    <video style="width:100%;" controls>
      <source src="videos/DFN_Zugang.mp4" type="video/mp4" aria-label"Video: Zugang zum Twillo-Portal">
    </video>
    <figcaption style="text-align:center;font-size:14px;">Video 4: Twillo-Zugang über DFN</figcaption>
  </figure>
  </p>
  </div>
  <button aria-label="zu Schritt 6" class="accordion">Schritt 6: Material einstellen</button>
  <div class="panel">
  <p>Der Einstellungsprozess wird, nachdem Sie auf die Buttonfläche <b>NEU</b> geklickt haben, durch Dialoge unterstützt. Wählen Sie <b>neues Material</b> aus und laden Sie Ihr Material hoch oder verlinken es. Verlinkungen sind dann möglich, wenn Sie das Material bereits auf anderen Plattformen (z.B. YouTube, Wikipedia, GitHub/GitLab etc.) veröffentlicht haben. Wenn Sie den Vorgang gespeichert haben, dann befindet sich das Material in Ihrem <b>Workspace</b>.
  
Sie haben jederzeit die Möglichkeit, Änderungen in den Beschreibungen vorzunehmen, Materialien zu ergänzen oder zu ersetzen. Dies erfolgt über das Kontextmenü (drei Punkte) unter <b>Info bearbeiten</b>.

&#x1F4A1; Bis zur aktiven Freigabe (Schritt 9) bleibt ihr Material nur für Sie sichtbar.</p>
  </div>
  <button aria-label="zu Schritt 7" class="accordion">Schritt 7: Bildungsmaterial auffindbar machen</button>
  <div class="panel">
   <p>Beschreiben Sie das Material möglichst mit den Informationen, die Sie am Material finden.
    <figure>
      <img src="images/Navigation_twillo.svg" alt="Abb.: Screenshot Navigation twillo" title="Abbildung: Screenshot Navigation twillo "/>
      <figcaption style="text-align:center;font-size:14px;">Abb. <i>Screenshot Navigation twillo</i> </figcaption>
    </figure>
     Im Abschnitt <b>Lizenz</b> geben Sie die Urheber*innen an. Dort sollte, wenn Sie sich für ein Lizenzmodul mit der Attribution <b>BY</b> entschieden haben, der Reiter <b>Autoren & Beteiligte</b> gewählt werden. Den Reiter Freihe Urheberangabe sollten Sie nur dann anwählen, wenn Sie ihr Material unter der Lizenz CC 0 veröffentlichen möchten.
    <figure>
      <img src="images/Urheberangabe_Autoren und Beteiligte_twillo.svg" alt="Abb.: Screenshot Urheberangabe twillo " title="Abbildung: Screenshot Urheberangabe twillo "/>
      <figcaption style="text-align:center;font-size:14px;">Abb. <i>Screenshot Urheberangabe twillo</i></figcaption>
    </figure>
Damit die Lizenz auch maschinell ausgelesen werden kann, muss nun auch hier die Lizenzangabe festgelegt werden. Hierfür öffnen Sie den Bereich Lizenz verwalten und wählen die gewünschte Lizenz mit Lizenzversion.
     <figure>
      <img src="images/Screenshot_Lizenzangabe_twillo.svg" alt="Abb.: Screenshot Lizenzangabe twillo" title="Abbildung: Screenshot Lizenzangabe twillo"/>
      <figcaption style="text-align:center;font-size:14px;">Abb. <i>Screenshot Lizenzangabe twillo</i></figcaption>
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
>   <img src="images/Screenshot_Serienfunktion.svg" alt="Abb.: Screenshot Serienfunktion twillo " title="Abbildung: Screenshot Serienfunktion twillo "/>
>    <figcaption style="text-align:center;font-size:14px;">Abb. <i>Screenshot Serienfunktion twillo</i></figcaption>
> </figure>

Geben Sie auch das entsprechende <b>Fach-/ Sachgebiet</b> an und legen Sie <b>Schlagworte</b> fest, um die Auffindbarkeit Ihres Material in der  zielgerichteten Suche zu erhöhen.</p>
  </div>
  <button aria-label="zu Schritt 8" class="accordion">Schritt 8: Bildungsmaterial kontextualisieren</button>
  <div class="panel">
  <p>Im Abschnitt <b>Didaktik</b> können Sie weitere didaktische Kontextinformationen für Nutzer*innen des Portals angeben. Die hier ausgewählten Beschreibungskategorien können insbesondere bei der zielgerichteten Materialsuche für den eigenen Lehrkontext behilflich sein.

<ul>
  <li>Geben Sie an, in welchem <b>Veranstaltungsformat</b> Ihr Material erprobt oder für welchen Kontext es konzipiert wurde.</li>
  <br>
  <li>Geben Sie an, für welche <b>Nivea</b>ustufe bzw. Zielgruppe Ihr Material primär entworfen wurde. Diese Angabe schließt eine Verwendung mit anderen Zielgruppen nicht aus.</li>
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
</ul></p>
  </div>
  <button aria-label="zu Schritt 9" class="accordion">Schritt 9: Material freigeben</button>
  <div class="panel">
   <p>Erst mit der Freigabe veröffentlichen Sie Ihr Material auf twillo. Hierfür gibt es zwei Wege.

Entweder Sie aktivieren Sie im Abschnitt Lizenz den Schalter <b>Objekt mit dieser Lizenz veröffentlichen</b>
<br>
<br>
<b>oder</b>
<br>
<br>
Sie gehen über das Kontextmenü zum Punkt <b>Freigeben</b> und aktivieren in der Freigabemaske den Schalter <b>Material öffentlich freigeben</b>. Sie haben in dieser Maske auch die Möglichkeit, das Material zunächst nur für ausgewählte Personen freizugeben.</li>
</ol>

Falls Sie unsicher sind, können Sie z.B. alle Teilnehmer*innen aus dem Workshop einladen und das Material nur mit diesem Kreis teilen.

<figure>
  <img src="images/Freigabe_twillo.svg" alt="Abb.: Screenshot Freigabe twillo " title="Abbildung: Screenshot Freigabe twillo "/>
  <figcaption style="text-align:center;font-size:14px;">Abb. <i>Screenshot Freigabe twillo</i></figcaption>
</figure>
  </p>
  </div>
</div>

<br>
<form action="#/motivation_b.md">
 <button aria-label="Button: fertig" type="submit">Fertig</button>
</form>
