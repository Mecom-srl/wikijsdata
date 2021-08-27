---
title: Norme e leggi
description: Norme e leggi
published: true
date: 2021-08-27T19:02:27.928Z
tags: 
editor: markdown
dateCreated: 2021-08-27T14:50:34.421Z
---

```plantuml
@startwbs
skinparam defaultTextAlignment center

<style>
wbsDiagram {
  // all lines (meaning connector and borders, there are no other lines in WBS) are black by default
  Linecolor black
  arrow {
    // note that connector are actually "arrow" even if they don't look like as arrow
    // This is to be consistent with other UML diagrams. Not 100% sure that it's a good idea
    // So now connector are green
    LineColor green
  }
  :depth(0) {
      BackgroundColor white
      RoundCorner 0
      LineColor black
  }
    :depth(1) {
      BackgroundColor white
      LineColor blue
      LineStyle 0
      LineThickness 1.5
  }
    :depth(2) {
      LineStyle 0
            LineColor blue
      LineThickness 1.5
			 BackgroundColor white

  }
}
</style>

* <size:15><b>Direzione</b></size> \nFrancesco Mescalchin
** <size:15><b>Amministrazione</b></size> \nMichela Zorzi
** <size:15><b>Sistema informatico</b></size> \nMarco Mescalchin
** <size:15><b>Rspp</b></size> \nMario Ariotti
** <size:15><b>Medico Competente</b></size> \nBernardo Bonato
** <size:15><b>Acquisti</b></size> \nGiorgia Cattapan
** <size:15><b>Qualità tempi metodi</b></size> \nManuel Pasquetto
** <size:15><b>Pianificazione produzione</b></size> \nFrancesco Cinetto
** <size:15><b>Produzione</b></size> \nRiccardo Mescalchin
*** <size:15><b>Piegatura</b></size> \nLuca Demo
*** <size:15><b>Fresatura</b></size> \nMirko Martini
*** <size:15><b>Taglio laser</b></size> \nManuel Pasquetto
*** <size:15><b>Saldatura</b></size> \nGabriel Badiu
*** <size:15><b>Attrezzeria</b></size> \nSimone Zoccarato
*** <size:15><b>Stampaggio</b></size> \nMichele Piccini
*** <size:15><b>Tornitura</b></size> \nClaudio Martini
@endwbs

```

