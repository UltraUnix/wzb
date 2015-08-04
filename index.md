---
title       : Work in Progress 
subtitle    : Kommunale Wahlerfolgsunterschiede der NPD in Sachsen
author      : Reinhold Melcher
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---

<p><font size="6"; color = darkred>Ausgang: Wahlerfolg der NPD variiert zwischen Gemeinden</font></p>
</br>
<p><font size="4">Kommunale Verteilung des Zweitstimmenanteils der NPD zur Bundestagswahl 2013</font></p>
<iframe src="http://ultraunix.github.io/npd_map/" width="700" height="400" name="line" frameborder="0"></iframe>

--- 
 
<p><font size="6"; color = darkred>Zielstellungen und Fragen</font></p>
</br>
<ol>
<li><p style="text-align:left"><font size="5">Warum variiert der Wahlerfolg?</font></p>
<ul>
<li><p><font size="4">Empiriedefizit für (ost-)deutschen Kontext und speziell für Sachsen</font></p></li>
<li><p><font size="4">Generelle Vernachlässigung der kommunalen Ebene zur Erklärung rechtsextremer Wahlerfolge</font></p></li>
</ul></li>
</br>
<li><p style="text-align:left"><font size="5">Berücksichtigung des Raumbezugs bei Makrountersuchungen notwendig?</font></p> 
<ul>
<li><p><font size="4">Wirkungsweise von Erklärungsfaktoren in Abhängigkeit der politischen Ebene</font></p></li>
<li><p><font size="4">Methodische Berücksichtigung räumlicher Autokorrelation</font></p></li>   
</ul></li>
</ol>

--- &twocol

<p><font size="6"; color = darkred>Wie erklären sich die Unterschiede?</font></p>
</br>
*** =left
<p style="text-align:left"><font size="5">Materialistische Erklärungen</font></p> 
- <p><font size="4">Arbeitslosigkeit (+)</font></p>
- <p><font size="4">Ökonomische Situation (-)</font></p>
- <p><font size="4">Kriminalität (+)</font></p>
- <p><font size="4">Kriminalität in Grenznähe (+)</font></p>

*** =right
<p style="text-align:left"><font size="5">Kulturelle Erklärungen</font></p> 
- <p><font size="4">Ausländeranteil (-)</font></p>
- <p><font size="4">Urbanisierungsgrad (-)</font></p>
- <p><font size="4">Religiöse Prägung (-)</font></p>
- <p><font size="4">Sozialkapital (-)</font></p>
- <p><font size="4"; color = red>Männeranteil (+)</font></p>

*** =fullwidth

---
<style type="text/css">
p {margin-bottom: -10px;}
</style>

<p><font size="6"; color = darkred>Daten und Operationalisierung</font></p>
</br>
<ul>
<li><p><font size="4">Erstellung eines <b>Makrodatensatzes</b> basierend auf 438 sächsischen Gemeinden</font></p></li>
<li><p><font size="4"><b>Bundesagentur für Arbeit:</b> Arbeitslosigkeit</font></p></li>
<li><p><font size="4"><b>Sächsisches Innenministerium:</b> Kriminalitätsrate pro 1000 Einwohner</font></p></li>
<li><p><font size="4"><b>Statistisches Landesamt Sachsen:</b></font></p></li>
<ul>
   <li><p><font size="4">Zweitstimmenanteil der NPD zur Bundestagswahl 2013</font></p></li> 
   <li><p><font size="4">Ökonomische Situation über Steuereinnahmekraft pro Kopf</font></p></li>
   <li><p><font size="4">Ausländeranteil</font></p></li> 
   <li><p><font size="4">Urbanisierungsgrad über Einwohner je Quadratkilometer Nutzfläche</font></p></li>
   <li><p><font size="4">Männeranteil</font></p></li> 
</ul></li>  
<li><p><font size="4"><b>Vereinsregister:</b> Sozialkapital über Vereinsdichte</font></p></li>
<li><p><font size="4"><b>Zensus 2011:</b></font></p></li>
<ul>
   <li><p><font size="4">Katholikenanteil</font></p></li>
   <li><p><font size="4">Protestantenanteil</font></p></li>
</ul></li>  
</ul>

---

<p><font size="6"; color = darkred>Berechnung der Grenzdistanz auf Raumdatenbasis</font></p>
</br>
</br>
<center><img src="https://dl.dropboxusercontent.com/u/94863207/map2.png" width="592" height="448"></center>

---

<p><font size="6"; color = darkred>Bivariate Untersuchung der Zusammenhänge</font></p>
</br>
</br>
<center><img src="https://dl.dropboxusercontent.com/u/94863207/Bivariate%20Untersuchung.png" width="399" height="471"></center>

---

<p><font size="6"; color = darkred>Schätzungsergebnisse des räumlichen Fehlermodells</font></p>
</br>
<center><img src="https://dl.dropboxusercontent.com/u/94863207/beta_ols.png" width="774" height="509"></center>

---

<p><font size="6"; color = darkred>Interaktion Kriminalität und Grenzdistanz</font></p>
</br>
<center><img src="https://dl.dropboxusercontent.com/u/94863207/interaktion_sem.png" width="757" height="505"></center>

--- 

<p><font size="6"; color = darkred>Zusammenfassung der Hypothesentests</font></p>
</br>
<center><img src="https://dl.dropboxusercontent.com/u/94863207/Ergebnisse%20der%20Hypothesentests.png" width="447" height="509p><font size=""></center>

--- 

<p><font size="6"; color = darkred>Erkenntnisse</font></p>
</br>
<ol>
<li><p><font size="5">Mehr <b>Raumbezug</b> bei theoretischer Begründung von Erklärungsfaktoren</font></p></li>
</br>
<li><p><font size="5"><b>Räumliche Autokorrelation</b> berücksichtigen</font></p></li>
</br>
<li><p><font size="5">Stärkere Berücksichtigung von <b>Grenzdistanzen</b> und des <b>Männeranteils</b> zur Erklärung des Wahlerfolges rechtsextremer Parteien</font></p></li>
</ol>

---

<p><font size="6"; color = darkred>Work in Progress am 04.08.2015</font></p>
</br>
### Kommunale Wahlerfolgsunterschiede der NPD in Sachsen
</br>
## Vielen Dank für die Aufmerksamkeit!

---

<p><font size="6"; color = darkred>Anhang deskriptive Statisitik</font></p>
</br>
<center><img src="https://dl.dropboxusercontent.com/u/94863207/deskription.png" width="720" height="511"></center>

