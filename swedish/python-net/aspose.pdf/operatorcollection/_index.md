---
title: "OperatorCollection"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen representerar en samling av operatorer"
type: docs
weight: 1010
url: /sv/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

Klassen representerar en samling av operatorer

Typen OperatorCollection exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| is_fast_text_extraction_mode | Indikerar huruvida samlingen är begränsad till snabb textutvinning |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Hämtar operatorn efter dess index. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| insert(index, op) | Infogar operator i samlingen. |
| insert(at, ops) | Infoga operatorer på den angivna positionen. |
| insert(at, ops) | Infogar operator i samlingen. |
| delete(index) | Tar bort operator från samlingen. |
| delete(ops) | Tar bort operatorer från samlingen. |
| delete(list) | Ingen |
| add(ops) | Lägg till operatorer i slutet av innehållsoperatorerna. |
| add(ops) | Lägger till en ny operator i samlingen. |
| suppress_update() | Undertrycker uppdatering av innehållsdata.<br/>            Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |
| resume_update() | Återupptar dokumentuppdatering.<br/>            Uppdaterar innehållsströmmen om det finns några väntande ändringar. |
| cancel_update() | Avbryter den senaste uppdateringen.<br/>            Denna metod kan anropas när förändringen inte ska utlösa en innehållsuppdatering. |
| accept(visitor) | Accepterar IOperatorSelector visitor-objekt för att bearbeta operatorer. |
| replace(operators) | Ersätt operatorer i samlingen med andra operatorer. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

