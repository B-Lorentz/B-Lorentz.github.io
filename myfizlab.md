---
layout: default
title: "Fizika Laboratórium I/Fizikai Alapmérések - Nemhivatalos honlap"
stysh: /assets/css/cou_style.css
---
## A labor célja
A tantárgy elsődleges célja a fizika egyes alaptörvényeit demonstráló kísérletek
elvégzése, értelmezése, illetve dokumentálása.
A fizikai alapjelenségek megértése mellett a tárgy további célja a jegyzőkönyvkészítés
elsajátítása, valamint alapvető fizikai eszközök (például: csavarmikrométer, tolómérő,
analitikai mérleg, Mohr-Westphal mérleg) használatának bemutatása. Tanárszakos
hallgatók esetében a laboratóriumi gyakorlatok keretében szerzett ismeretek és a mérések
felhasználhatók a középiskolai tanítás során is.

## Tantárgy tartalma
Alapvető mérőeszközök és mérési eljárások megismerése és használata. Mechanikai
anyagjellemzők mérése többféle módszerrel, ismert fizikai összefüggések, törvények
igazolása, előzetesen nem ismert mechanikai jelenségre vonatkozó összefüggések
meghatározása és értelmezése. Mérési adatok kézi, illetve számítógépes kiértékelése, a
hibabecslés és hibaszámítás alapjai, mérési eredmények prezentálása, jegyzőkönyv
készítése.

## Oktatók
+ [Zavaczki Csilla Erika](https://telefonkonyv.elte.hu/reszletes_szemely.php?szemely_id=4317)
+ [Dr. Bagoly Zsolt](https://ttk.elte.hu/munkatarsak/bagoly-zsolt-dr)
+ [Dr. Stéger József](https://stegerjozsef.web.elte.hu/)
+ [Szommer Péter](https://physics.elte.hu/ANY_szommer)

## Helyszín
ELTE Lágymányosi Campus - Északi tömb
Budapest, Pázmány Péter stny. 1/A, 1117
2.77 terem
![Északi tömb][building]

[building]: /lagymanyos.jpg

## Mérések

<table>
  <tr>
    <th> Mérés neve </th>
    <th> Mérési leírás</th>
    <th> Az én jegyzőkönyvem</th>
  </tr>
  {% for item in site.data.labs %}
  <tr>
    <td>{{item.name}}</td>
    <td><a href="{{ item.descr }}" download>
      Letölthető
    </a> </td>
    <td><a href="{{ item.rep }}" download>
      Letölthető
    </a></td>
  </tr>
  {% endfor %}
</table>
### [Hivatalos honlap](http://metal.elte.hu/fiz_lab/)
