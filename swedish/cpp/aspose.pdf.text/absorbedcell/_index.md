---
title: "Aspose::Pdf::Text::AbsorbedCell-klass"
linktitle: "AbsorbedCell"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::AbsorbedCell-klass. Representerar en cell i en tabell som finns på sidan i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.text/absorbedcell/
---
## AbsorbedCell class


Representerar en cell i en tabell som finns på sidan.

```cpp
class AbsorbedCell : public Aspose::Pdf::Text::ITableElement,
                     public System::IComparable<System::SharedPtr<AbsorbedCell>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<AbsorbedCell\>) override | Jämför det aktuella [AbsorbedCell](./)-objektet med ett annat [AbsorbedCell](./)-objekt och returnerar ett heltal som indikerar om det aktuella objektet föregår, följer eller ligger på samma position i sorteringsordningen som det andra objektet. |
| [get_BorderInfo](./get_borderinfo/)() const | Returnerar kantinformation för cellen när egenskapen FlowEngine.TableAbsorber.UseFlowEngine är satt till true. |
| [get_ColSpan](./get_colspan/)() const | Returnerar antalet kolumner som cellen ska spänna över när egenskapen TableAbsorber.UseFlowEngine är satt till true. |
| [get_Rectangle](./get_rectangle/)() override | Hämtar rektangel som beskriver cellens position på sidan. |
| [get_TextFragments](./get_textfragments/)() const | Hämtar en samling av [TextFragment](../textfragment/)-objekt som beskriver texten som finns i cellen. |
## Se även

* Class [ITableElement](../itableelement/)
* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
