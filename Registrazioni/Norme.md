---
title: Norme e leggi
description: Norme e leggi
published: true
date: 2021-08-27T16:02:32.609Z
tags: 
editor: markdown
dateCreated: 2021-08-27T14:50:34.421Z
---

```plantuml
@startuml
!include <C4/C4_Container>
!include <office/Users/mobile_user.puml>
!define osaPuml https://raw.githubusercontent.com/Crashedmind/PlantUML-opensecurityarchitecture2-icons/master
!include osaPuml/Common.puml
!include osaPuml/User/all.puml

SHOW_PERSON_SPRITE("osa_user_green_architect")

HIDE_STEREOTYPE()

!$COLOR_REL_LINE = "#8073ac"
UpdateRelStyle($lineColor=$COLOR_REL_LINE, $textColor=$COLOR_REL_TEXT)

Person(Direzione, "Direzione Generale","Francesco Mescalchin")
Person(Amministrazione, "Amministrazione","Michela Zorzi")
Person(Sistema, "Sistema informatico","Marco Mescalchin")
Person(Rspp, "Rspp","Mario Ariotti")
Person(Medico, "Medico Competente","Bernardo Bonato")
Person(Acquisti, "Acquisti","Giorgia Cattapan")
Person(Qualità, "Qualità tempi metodi","Manuel Pasquetto")
Person(Pianificazione, "Pianificazione produzione","Francesco Cinetto")
Person(Produzione, "Produzione","Riccardo Mescalchin")
Person(Piegatura, "Piegatura","Luca Demo")
Person(Fresatura, "Fresatura","Mirko Martini")
Person(Taglio, "Taglio laser","Manuel Pasquetto")
Person(Saldatura, "Saldatura","Gabriel Badiu")
Person(Attrezzeria, "Attrezzeria","Simone Zoccarato")
Person(Stampaggio, "Stampaggio","Michele Piccini")
Person(Tornitura, "Tornitura","Claudio Martini")

Rel(Direzione, Amministrazione,)
Rel(Direzione, Sistema,)
Rel(Direzione, Rspp,)
Rel(Direzione, Medico,)
Rel(Direzione, Acquisti,)
Rel(Direzione, Qualità,)
Rel(Direzione, Pianificazione,)
Rel(Direzione, Produzione,)
Rel(Produzione, Piegatura,)
Rel(Produzione, Fresatura,)
Rel(Produzione, Taglio,)
Rel(Produzione, Saldatura,)
Rel(Produzione, Attrezzeria,)
Rel(Produzione, Stampaggio,)
Rel(Produzione, Tornitura,)

@enduml
```