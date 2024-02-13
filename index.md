---

layout: col-sidebar
title: OWASP Medellin
tags: Medellin
level: 0

region: South America

meetup-group: OWASP-Medellin-Chapter
country: Colombia


---
![Medellin](assets/images/logo.png)

El capitulo de OWASP medellin ha sido reactivado desde el 2019, estamos emocionados de poder compartir y ayudar a crecer a la comunidad, cualquier duda o inquietud no dudes en comunicarte con nosotros.

Si eres apasionado por la seguridad y estas interesado en compartir tus conocimientos, escribemos podrias ser un futuro referente en seguridad hispano-parlante, solo debes empezar por algun lugar; Nuestro capitulo de medellin podria ser un buen comienzo. !Te Esperamos!

### Próximos eventos en Meetup:
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

