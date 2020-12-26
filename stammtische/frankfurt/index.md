---

layout: col-sidebar
title: OWASP Germany > Stammtische > Frankfurt

---

![OWASP_Frankfurt_Logo.jpg](assets/OWASP_Frankfurt_Logo.jpg width="100" "OWASP_Frankfurt_Logo.jpg")

## Current Events

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

## Upcoming Events

Please join our [OWASP Frankfurt Stammtisch Meetup Group](https://www.meetup.com/IT-Security-Stammtisch-Frankfurt-OWASP-u-w/) for timely updates on our OWASP Stammtisch Frankfurt Meetup:

Feel free to join our Meetup group for timely updates on meetings. The Meetup page is also usually a bit more up to date.

Anyone with an interest in our topics is welcome. All meetings are free and open. You do not have to be an OWASP member to attend. Referrals to this website or to individual meetings to colleagues or acquaintances are welcome.

<span style="font-size:120%;">

  * When? TBA
  * Where? Hotel Capri, Europa-Allee 42, 60327 Frankfurt am Main ([Google Maps](https://goo.gl/maps/jWuMLxsFCyp))
  * What? TBA

Please RSVP noncommittal so we can plan ahead:

Thanks!
</span>

## Information about Frankfurt Stammtisch Events

### When?

The last Wednesday of every second month @ 7:30pm

### Where?

Usually @ Hotel Capri - Announced on Meetup:
[Meetup](http://www.meetup.com/de/IT-Security-Stammtisch-Frankfurt-OWASP-u-w/).

### What?

We usually have one or two talks about a related topic to application
security and then finish the evening socializing at the local bar.

### Etiquette:

Well it's OWASP so please adhere to our [| Speaker
Agreement](https://www.owasp.org/index.php?title=Speaker_Agreement) and
avoid marketing stunts.

## Organization

### Call for Speakers and Volunteers

If you'd like to give a talk or volunteer for us, contact (Johannes dot
schoenborn aet owasp dot org). Thanks!
Call for speakers is open - please review and agree with the [OWASP
Speaker Agreement](Speaker_Agreement "wikilink").

As OWASP has also moved to Meetup, you'll now find us there:
[Meetup](http://www.meetup.com/de/IT-Security-Stammtisch-Frankfurt-OWASP-u-w/).

Please note that vendor pitches are not allowed, so please adhere to
using the OWASP presentation template:
[Presentation Template
Set](https://www.owasp.org/images/5/5d/PPT_2013_Toolbox.zip) and
[Presentation Set
Alternative](https://www.owasp.org/images/7/76/OWASP_Presentation_Template.zip)

# Previous Events

An overview of our past Frankfurt Stammtisch events since 2011.

## 2019

### **46. OWASP Stammtisch Frankfurt | 23.10.2019**
* Talk: **Reversing a Cobalt Strike Beacon**
* Location: Capri by Fraser (Europa-Allee 42, Frankfurt)

### **45. OWASP Stammtisch Frankfurt | 14.08.2019**
* Talk: **Let's hack! - An intro to Cobalt Strike**
* Location: Capri by Fraser (Europa-Allee 42, Frankfurt)

### **44. OWASP Stammtisch Frankfurt | 27.02.2019, 19:30h**
* Talk: **My favourite BBQ: Kerberoasting**
* Slides: [DOWNLOAD](https://www.owasp.org/images/4/4a/OWASP_Frankfurt_-44_Kerberoasting.pdf)
* Recording: [YOUTUBE](https://www.youtube.com/watch?v=WoqXAi5iHF4))
* Location: Exploit Labs will host us as Hotel Capri by Fraser (Europa-Allee 42, Frankfurt)

## 2018

### **43. OWASP Stammtisch Frankfurt | 07.11.2018, 19:30h**
* Keynote: **Jim Manico - Introduction to OWASP and Application Security Verification Standard 4.0**
* Slides: [DOWNLOAD](https://www.owasp.org/images/f/f8/Jim_Manico_-_Introduction_to_ASVS.pdf)
* Talk: **Daniel Gora - Gamification of Application Security with OWASP Cornucopia**
* Slides: [DOWNLOAD](https://www.owasp.org/images/1/10/OWASP_Stammtisch_Frankfurt_-_43.pdf)
* Talk: Cedric Klosa - My Ethical Hacking Success Story with
HackTheBox.eu
* Location: Exploit Labs will host us as Hotel Capri by Fraser (Europa-Allee 42, Frankfurt)

### **42. OWASP Stammtisch Frankfurt | 05.09.2018, 19:30h**
* Talk: **Johannes Schönborn - Getting Started with Ethical Hacking w/a Mentor**
* Slides: [DOWNLOAD](https://www.owasp.org/images/f/f5/OWASP_FFM_42_Getting_Started_with_Ethical_Hacking_wa_Mentor.pdf)
* Location: Blue Frost Security will once more host us at Hotel Capri

### **41. OWASP Stammtisch Frankfurt | 30.05.2018, 19:30h**
* Talk: **Michael Ritter - Active Directory Hacking**
* Slides: [DOWNLOAD](https://www.owasp.org/images/a/a4/OWASP_FFM_41_OffensiveActiveDirectory_101_MichaelRitter.pdf)
* Location: Blue Frost Security will once more host us at Hotel Capri

### **40. OWASP Stammtisch Frankfurt | 28.03.2018, 19:30h**
* Talk: **Kevin Ott - GoLang for Pentesting/Red Teaming**
* Slides: [DOWNLOAD](https://www.owasp.org/images/f/f3/OWASP_FFM_40_Offensive_Go_Kevin_Ott.pdf))
* Location: Blue Frost Security will once more host us at Hotel Capri

### **39. OWASP Stammtisch Frankfurt | 30.01.2018, 19:30h**
* Talk: **Sebastian Haas - Fun with Bashbunny**
* Slides: [DOWNLOAD](https://www.owasp.org/images/0/0c/OWASP_FFM_39_Fun_with_Bashbunny_Sebastian_Haas.pdf)
* Location: Blue Frost Security will once more host us at Hotel Capri

## 2017

### **38. OWASP Stammtisch Frankfurt | 29.11.2017, 19:30h**
* Talk: **Johannes Schönborn - Pentest vs. Red Team**
* Location: Blue Frost Security will once more host us at Hotel Capri!

### **37. OWASP Stammtisch Frankfurt | 20.9.2017, 19:30h**

* Talk: **Johannes Schönborn - Introduction to OWASP**
* Slides: ([DOWNLOAD](https://www.dropbox.com/s/7lw08ws7oinqeht/OWASP_Stammtisch%2337.pdf?dl=0))
* Location: Blue Frost Security will once more host us at Hotel Capri!

### **36. OWASP Stammtisch Frankfurt | 26.7.2017, 19:30h**

* Talk: **Christoph - A closer look at Bionic - a software quality assessment and security analysis of Android's foundation**
* Slides: [DOWNLOAD](https://www.owasp.org/images/5/54/Bionic_SQ.pdf)
* Location: Blue Frost Security will once more host us at Hotel Capri!

### **35. OWASP Stammtisch Frankfurt | 31.5.2017, 19:30h**

* Talk: **Privilege Escalation with strace and PowerShell**
* Location: Blue Frost Security will once more host us at Hotel Capri!

### **34. OWASP Stammtisch Frankfurt | 29.3.2017, 19:30h**

* Talk: **Hack of Disconnected Object", "Look Mom, I don't use Shellcode!**
* Location: Blue Frost Security will once more host us at Hotel Capri!

### **33. OWASP Stammtisch Frankfurt | 25.01.2017, 19:30h** 
* Talk: **Per Thorsheim on Passwords**
* Location: Blue Frost Security will once more host us at Hotel Capri!

## 2016

### **32. OWASP Stammtisch Frankfurt | 24.11.2016, 19:30h** 
* Talk: **Mobile Application Pentesting mit ein paar Anekdoten**
* Location: Exploit Labs, Friedrich-Ebert-Anlage 36, Frankfurt am Main

### **31. OWASP Stammtisch Frankfurt | 27.10.2016, 19:30h**
* Talk: **Eine Einführung: Angriffserkennung mit SIEM (Kathi)**
* Location: Exploit Labs, Friedrich-Ebert-Anlage 36, Frankfurt am Main

### **30. OWASP Stammtisch Frankfurt | 29.09.2016, 19:30h**
* Talk: **Community Live Hacking "your fav. challenge"**
* Location: DZ BANK AG, Mainzer Landstraße 58, 60325 Frankfurt am Main

### **29. OWASP Stammtisch Frankfurt | 30.06.2016, 19:30h**
* Talk: **Google-Hacking mit Florian Ammon**
* Location: DZ BANK AG, Mainzer Landstraße 58, 60325 Frankfurt am Main

### **28. OWASP Stammtisch Frankfurt | 30.06.2016, 19:30h** 
* Talk: **Community Live Hacking OWASP Juiceshop**
* Location: DZ BANK AG, Mainzer Landstraße 58, 60325 Frankfurt am Main

### **27. OWASP Stammtisch Frankfurt | 19.05.2016, 19:30h** 
* Talk: **Olaf Bormann - Anforderungen an das Application Security Management - Von der Anforderung bis zur Außerbetriebnahme**
* Location: DZ BANK AG, Mainzer Landstraße 58, 60325 Frankfurt am Main

### **26. OWASP Stammtisch Frankfurt | 28.04.2016, 19:30h**
* Talk: **Christian - DevOps & CI**
* Location: DZ BANK AG, Mainzer Landstraße 58, 60325 Frankfurt am Main

### **25. OWASP Stammtisch Frankfurt | 31.03.2016, 19:30h** 
* Talk: **Johannes Schönborn, Manuel Giesel - 1x1 Threat Intelligence**
* Location: DZ BANK AG, Mainzer Landstraße 58, 60325 Frankfurt am Main

### **24. OWASP Stammtisch Frankfurt | 25.02.2016, 19:30h**
* Talk: **Boban Krsic | "IT-Sicherheitsgesetz - und nun?"**
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/6/68/OWASP_Stammtisch_Frankfurt-IT-SiG-und-nun-2016.02.25.pdf)
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am Main

## 2015

### **23. OWASP Stammtisch Frankfurt | 28.01.2015, 19:30h**
* Talk: **Christoph | "Social Engineering"**
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/9/94/OWASP_Stammtisch_Frankfurt-Social_Engineering-2016.01.28.pdf)
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am
Main

### **22. OWASP Stammtisch Frankfurt | 26.11.2015, 19:30h**
* Talk: **Johannes Schönborn | "Faraday: Pentesting goes Multiplayer"**
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am
Main

### **21. OWASP Stammtisch Frankfurt | 29.10.2015, 19:30h**
* Talk: **Khalil Bijjou | "Web Application Firewall Bypassing - how to defeat the
blue team"** 
[DOWNLOAD](https://wiki.owasp.org/images/6/66/OWASP_Stammtisch_Frankfurt_-_Web_Application_Firewall_Bypassing_-_how_to_defeat_the_blue_team_-_2015.10.29.pdf)
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am Main

### **20. OWASP Stammtisch Frankfurt | 24.09.2015, 19:30h** 
* Talk: **Jan Philipp | "Security Challenges of Cloud Providers" ("Wie baue ich sichere Luftschlösser in den Wolken”)**
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/4/40/OWASP_Stammtisch_Frankfurt_-_Cloud_Provider_Challenges_-_2015.09.24.pdf)
* Location: Franklinstraße 50, 60486 Frankfurt am Main

### **19. OWASP Stammtisch Frankfurt | 27.08.2015, 19:30h** 
* Talk: **Manuel Giesel und Johannes Schönborn | "Lust und Frust bei der Netzwerk-Anomalieerkennung**
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am Main

### **18. OWASP Stammtisch Frankfurt | 30.07.2015, 19:30h**
* Talk: **Katharine Brylski | Ein Best-of-Konzept für Sicherheitsanalysen von Webanwendungen**
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/8/8e/OWASP_Stammtisch_Frankfurt_BestOfKonzept_Sicherheitsanalysen_Webanwendungen_20150730.pdf)
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am Main

### **17. OWASP Stammtisch Frankfurt | 25.06.2015, 19:30h**
* Talk: **Alexios Fakos | (Un)Sicherheit bei ihrer Applikation? Präventiv statt reaktiv**
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/4/44/OWASP_Stammtisch_Frankfurt_%28Un%29Sicherheit.bei.ihrer.Applikation_20150628.pdf)
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am Main

### **16. OWASP Stammtisch Frankfurt | 28.05.2015, 19:30h**
* Talk: **Marius Klimmek | Sowas wie Botnetze – Die dunkle Gefahr der Zombie Armee**
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/0/0c/OWASP_Stammtisch_Frankfurt_Botnetze-Presentation_20150525.pdf)
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am Main

### **15. OWASP Stammtisch Frankfurt | 30.04.2015, 19:30h** 
* Talk: **Daniel Zelle | Einführung und Überblick - Von Car2X- bis In-Vehicel-Security**
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/1/12/OWASP_Stammtisch_Frankfurt_Von_Car2X-_bis_In-Vehicle-Security_20150430.pdf)
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am
Main

### **14. OWASP Stammtisch Frankfurt | 26.03.2015, 19:30h**
* Talk: **Michael Ritter | Web Application Firewall Profiling**
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/b/bf/OWASP_Stammtisch_Frankfurt_WAF_Profiling_and_Evasion.pdf)
* Location: Franklinstraße 50, 60486 Frankfurt am Main

### **13. OWASP Stammtisch Frankfurt | 26.02.2015, 19:30h** 
* Talk: **Alexios Fakos | Polyglotte Angriffsvektoren**
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am
Main

### **12. OWASP Stammtisch Frankfurt | 29.01.2015, 19:30h**
* Talk: **Jan Philipp | SharePoint Sicherheit im 'schlüpfrigen' Griff**
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/6/6c/OWASP_Frankfurt_Stammtisch-SharePoint.Sicherheit.im.Griff-20150129.pdf)
* Location: Franklinstraße 50, 60486 Frankfurt am Main

## 2014

### **11. OWASP Stammtisch Frankfurt | 27.11.2014, 19:30h**
* Talk: **Johannes Schönborn | APT – the Good – the Bad, the Ugly**
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am Main

### **10. OWASP Stammtisch Frankfurt | 30.10.2014, 19:30h**
* Talk: **Alexander Klink | Denial of Service auf Applikationsebene**
* Note: _Stammtisch Frankfurt feierte sein Comeback!_
* Slides: [DOWNLOAD](https://wiki.owasp.org/images/7/73/OWASP_Frankfurt_Stammtisch-DoS.auf.Applikationsebene-20141030.pdf)
* Location: Tower 185, Friedrich-Ebert-Anlage 35-37, 60327 Frankfurt am Main

## 2013

### **3. Rhein-Main-OWASP-Stammtisch | 27.11.2013 at 19:00**
* Note: Stammtisch took place in the wine bar [Wangenrot](http://www.vinothek-wangenrot.de/weinbar-vinothek-mainz.html) at Stephansplatz 1 in Mainz

### **2. Rhein-Main-OWASP-Stammtisch  | 26.09.2013 at 19:00h**
* Note: The second Rhein Main Stammtisch took place at 19:00 in Frankfurt in [Vita Vera](http://www.ristorante-vitavera.de/1.html).

### **1. Rhein-Main-OWASP-Stammtisch The Frankfurt OWASP Stammtisch, 25.06.2013 at 19:00h**
* Note: renamed in Rhein Main Stammtisch and took place on  in
Frankfurt.

## 2012

### **6. OWASP Stammtisch Frankfurt | 21.11.2012 at 19:00**
* Note: The topic of the Stammtisch was the review of the German OWASP Day 2012 and took place in the [Vita Vera](http://www.ristorante-vitavera.de/1.html)

### **5. OWASP Stammtisch Frankfurt The 5th Frankfurt OWASP**
* Note: Stammtisch took place on 26.09.2012, 18:30 in the [Vita Vera](http://www.ristorante-vitavera.de/1.html). The topic was the exchange about security topics as well as common networking.

## 2011

### **4. OWASP Stammtisch Frankfurt The 4th Frankfurt OWASP**
* Note: The fourth OWASP Frankfurt Stammtisch took place on 23.11.2011 at [Depot 1899](http://www.depot1899.de/). Bars were tested in which one can hold perhaps also a lecture with following discussion.

### **3. OWASP Stammtisch Frankfurt The 3rd Frankfurt OWASP**
* Note: The third OWASP Stammtisch Frankfurt took place on 21.09.2011 in the [Arche Nova, Kasseler Str. 1a, Frankfurt a.M.](http://j.mp/piQdaP).
