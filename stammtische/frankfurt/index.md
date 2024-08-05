---

layout: col-sidebar
title: OWASP Germany > Stammtische > Frankfurt

---

<img align="center" src="assets/OWASPFrankfurtBanner.png" width="900">

## Introduction

Welcome to [OWASP Frankfurt Chapter](https://owasp.org/www-chapter-frankfurt/), a regional City Chapter within the [OWASP Germany Chapter](https://owasp.org/www-chapter-germany/). We serve the Rhine-Main region as a platform to discuss and share topics all around application and information security.

Anyone with an interested and enthusiastic about application security is welcome. All meetings are free and open. You do not have to be an OWASP member.

Referrals to this website or to individual meetings to colleagues or acquaintances are welcome.

## Upcoming Events 
Any events are going to be announced via our [OWASP Frankfurt Meetup Group](https://www.meetup.com/owasp-frankfurt/). We usually have a key note and 1-2 (lightning) talks that related to information and application security.

Refer to our [Upcoming Events Page](https://owasp.org/www-chapter-frankfurt/#div-nextevent) or [LinkedIn](https://www.linkedin.com/company/owasp-frankfurt/) for further information.

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
