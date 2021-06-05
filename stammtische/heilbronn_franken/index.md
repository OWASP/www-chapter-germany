---

layout: col-sidebar
title: OWASP Germany > Stammtische > Heilbronn
meetup-group: OWASP-Germany-Chapter-Stammtisch-Heilbronn-Franken

---

## Herzlich willkommen beim OWASP Stammtisch Heilbronn-Franken!

Liebe IT Security-Interessierte,

unser OWASP Stammtisch findet in unregelmäßigen Abständen immer donnerstags, um 18:30 Uhr am [Campus Sontheim](https://www.hs-heilbronn.de/kontakt) der Hochschule Heilbronn statt. Parkplätze sind abends kostenlos und in ausreichender Anzahl vorhanden. Jeder mit Interesse an unseren Themen ist herzlich willkommen. Alle Treffen sind frei und offen. Man muss kein OWASP-Mitglied sein. Wir freuen uns immer über bekannte und neue Gesicht von nah und fern. Hinweise auf diese Webseite oder auf einzelne Treffen sind jederzeit gern gesehen.

Nach dem Fachvortrag gehen wir für gewöhnlich immer noch in das nahe gelegene [Clocks](https://www.clocks-heilbronn.de/), um uns dort in lockerer Runde bei leckerem Essen und kühlen Getränken näher kennenzulernen (donnerstags ist wie der Zufall so will immer Burgertag 😀).

### Anstehende Stammtische
Wenn es die Infektionslage zulässt, planen wir für Herbst 2021 wieder erste Präsenztreffen 🤞. Diese werden hier per [Meetup](https://www.meetup.com/de-DE/OWASP-Germany-Chapter-Stammtisch-Heilbronn-Franken/) und über die [OWASP Germany-Mailingliste](https://groups.google.com/a/owasp.org/forum/#!forum/germany-chapter) vorab angekündigt.

{% include chapter_events.html group=page.meetup-group %}


<script type='text/javascript'>
  $(function(){
    $(".timeclass").hover(function() {
      utc_str = $(this).text();
      ndx = utc_str.indexOf(':');
      st_hour_str = utc_str.substring(0, ndx);
      st_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0);
      start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);

      ndx = utc_str.lastIndexOf(':');
      end_hour_str = utc_str.substring(ndx - 2, ndx - 1);
      end_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0);
      end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);
      popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET);
      $(this).prop('title', popstr);
    });
  });


</script>


### Vergangene Stammtische

| Nr. (Datum)  | Thema | Referent |
| ------------- | ------------- |------------- |
|\#008 (28.11.2019) | Drum prüfe, wer sich bindet: JSON Web Tokens und deren Sicherheit | Andreas Mayer |
|\#007 (26.09.2019) | Smarte und vernetzte medizinische Helferlein - Eine Gefahr für unsere Daten?! | Cord Lissek |
|\#006 (25.04.2019) | Über die Verbreitung von verwundbaren Bibliotheken in Open Source-Projekten | Maximilian Westers |
|\#005 (25.10.2018) | Über die Sicherheit medizinischer Geräte - Das Spiel mit der Zeit | Julian Suleder |
|\#004 (12.07.2018) | Abhör-Alptraum: GPS-Smartwatch für Kinder und Senioren lässt sich von Fremden belauschen | Christopher Dreher |
| \#003 (05.06.2018) | Error by Design: Über die Probleme von Sicherheitsmaßnahmen auf Client-Seite am Beispiel mobiler Apps | Andreas Kurtz |
| \#002 (22.02.2018) | Über die Sicherheit von Web Single Sign-On | Andreas Mayer |
| \#001 (25.09.2017) | How does 🙈 or 💩 affect our S�curity? | Christopher Dreher |
