---
ID: 233
post_title: PlugIn Tippy
author: widi
post_excerpt: ""
layout: post
permalink: >
  https://cms-test.fwidmann.net/plugin-tippy/
published: true
post_date: 2020-11-01 14:32:09
---
<!-- wp:heading -->
<h2>Tippy - Tooltips</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Das PlugIn ermöglicht eine Art von "Tooltips" in den Seiten. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Auszug aus der Beschreibung: "<em>Simple plugin to display tooltips within your WordPress blog.</em>"</p>
<!-- /wp:paragraph -->

<!-- wp:more -->
<!--more-->
<!-- /wp:more -->

<!-- wp:paragraph -->
<p>Wird bei Alpenverein Rottenburg auf der Seite "Mitgliedschaft" verwendet, um ganz unten beim Text "Was kostet die Mitgliedschaft?" ein PopUp-Fenster einzublenden. Das Fenster wird aber am SmartPhone etwas komisch angezeigt.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":5} -->
<h5>Tippy mit statischem Text</h5>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Bisher wurde der Text als statischer Text in die jeweilige Seite eingetragen. Das führt dazu, dass dieselben Texte mehrfach in der Website enthalten sind. Beispielsweise tauchen die Mitgliedsbeiträge auch auf der Seite "Mitgliedschaft &gt; Mitgliederbeiträge" auf.</p>
<!-- /wp:paragraph -->

<!-- wp:shortcode /-->

<p>[tippy title="<a title="Was kostet die Mitgliedschaft?" href="https://dav-rottenburg.de/mitgliedschaft/mitgliedsbeitraege/">Was kostet die Mitgliedschaft?</a>" ](gültig ab 01.01.2017)</p>
<table width="500" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="80%" valign="top"><strong>A-Mitglieder</strong><p></p>
<p style="padding-left: 30px;"><em>Mitglieder ab dem vollendeten 25. Lebensjahr</em></p>
</td>
<td width="20%" valign="top">
<p align="right">53,00 €</p>
</td>
</tr>
<tr>
<td valign="top"><strong>B-Mitglieder</strong><p></p>
<p style="padding-left: 30px;"><em>Ehe-/Lebenspartner eines A-Mitglieds mit gleichem Wohnort und Beitragseinzugskonto</em></p>
<p style="padding-left: 30px;"><em>Senioren ab dem 70. Lebensjahr auf Antrag</em></p>
<p style="padding-left: 30px;"><em>aktive Bergwachtmitglieder auf Nachweis</em></p>
</td>
<td valign="top">
<p align="right">32,00 €</p>
</td>
</tr>
<tr>
<td valign="top"><strong>C-Mitglieder</strong><p></p>
<p style="padding-left: 30px;"><em>Gastmitglieder, die einer anderen Sektion des DAV als A-, B- oder Junior-Mitglied angehören</em></p>
</td>
<td valign="top">
<p align="right">15,00 €</p>
</td>
</tr>
<tr>
<td valign="top"><strong>Junioren</strong><p></p>
<p style="padding-left: 30px;"><em>Mitglieder vom vollendeten 18. bis zum vollendeten 25. Lebensjahr</em></p>
</td>
<td valign="top">
<p align="right">32,00 €</p>
</td>
</tr>
<tr>
<td valign="top"><strong>Jugendliche</strong><p></p>
<p style="padding-left: 30px;"><em>Jugendliche vom vollendeten 14. bis zum vollendeten 18. Lebensjahr, wenn die Eltern nicht Mitglied sind</em></p>
</td>
<td valign="top">
<p align="right">12,00 €</p>
</td>
</tr>
<tr>
<td valign="top"><strong>Kinder</strong><p></p>
<p style="padding-left: 30px;"><em>bis zum vollendeten 14. Lebensjahr, wenn die Eltern nicht Mitglied sind</em></p>
</td>
<td valign="top">
<p align="right">12,00 €</p>
</td>
</tr>
<tr>
<td valign="top"><strong>Familien</strong><p></p>
<p style="padding-left: 30px;"><em>bestehend aus A- und B-Mitgliedschaft sowie Alleinerziehende/r auf Antrag mit ihren/seinen Kindern und Jugendlichen bis zum vollendeten 18. Lebensjahr</em></p>
</td>
<td valign="top">
<p align="right">85,00 €</p>
</td>
</tr>
<tr>
<td colspan="2" valign="top">
<p align="left"><strong>Aufnahmegebühren</strong> <em>werden nicht erhoben.</em></p>
</td>
</tr>
</tbody>
</table>
<hr>
<p><strong><span style="background-color: #ffff35; border: 1px solid #e5d02d; padding: 2px 5px; border-radius: 3px;">Unterjährige Mitgliedschaft</span></strong></p>
<p style="text-align: justify;">Ab 2018 besteht bei der Sektion Rottenburg die Möglichkeit, eine Mitgliedschaft ab dem 1. September des jeweiligen Jahres zu erwerben. Der Mitgliedsbeitrag reduziert sich dabei für das Jahr der Beitrittserklärung um 50% des Normalbeitrags. Ab dem darauf folgenden Jahr wird jedoch der volle Mitgliedsbeitrag fällig.<br>[/tippy]</p>

<!-- wp:heading {"level":5} -->
<h5>Tippy mit verlinkter Seite</h5>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Es müsste auch möglich sein, bei Tippy einen Link auf eine andere Seite anzugeben. Dann stehen im gezeigten Beispiel die Mitgliedsbeiträge nur auf einer Seite, nicht auf mehreren.</p>
<!-- /wp:paragraph -->

<!-- wp:separator -->
<hr class="wp-block-separator"/>
<!-- /wp:separator -->

<!-- wp:shortcode -->
[tippy title="title" headertitle="headertitle" href="https://dav-rottenburg.de/mitgliedschaft/mitgliedsbeitraege/"]Das ist der Text[include-page id="/beitraege"][/tippy]
<!-- /wp:shortcode -->

<!-- wp:separator -->
<hr class="wp-block-separator"/>
<!-- /wp:separator -->