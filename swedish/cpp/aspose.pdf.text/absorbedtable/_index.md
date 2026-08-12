---
title: "Aspose::Pdf::Text::AbsorbedTable class"
linktitle: "AbsorbedTable"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::AbsorbedTable class. Representerar en tabell som finns på sidan i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.text/absorbedtable/
---
## AbsorbedTable class


Representerar en tabell som finns på sidan.

```cpp
class AbsorbedTable : public Aspose::Pdf::Text::ITableElement,
                      public System::IComparable<System::SharedPtr<AbsorbedTable>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<AbsorbedTable\>) override | Jämför det aktuella [AbsorbedTable](./)-objektet med ett annat [AbsorbedTable](./)-objekt och returnerar ett heltal som indikerar om det aktuella objektet föregår, följer eller ligger på samma position i sorteringsordningen som det andra objektet. |
| [get_PageNum](./get_pagenum/)() const | Hämtar sidnumret för den sida som innehåller denna tabell. |
| [get_Rectangle](./get_rectangle/)() override | Hämtar rektangeln som beskriver tabellens position på sidan. |
| [get_RowList](./get_rowlist/)() | Hämtar en skrivskyddad IList som innehåller raderna i tabellen. |
## Se även

* Class [ITableElement](../itableelement/)
* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
