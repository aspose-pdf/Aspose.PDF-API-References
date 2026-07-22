---
title: "Aspose::Pdf::PageNumber-klass"
linktitle: "PageNumber"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PageNumber-klass. Representerar ett sidnummerformat som inkluderar ett index, totalt antal sidor och ett avgränsningstecken i C++."
type: docs
weight: 14100
url: /sv/cpp/aspose.pdf/pagenumber/
---
## PageNumber class


Representerar ett sidnummerformat som inkluderar ett index, totalt antal sidor och ett avgränsningstecken.

```cpp
class PageNumber : public System::Object
```

## Nested classes

* Class [PageIndex](./pageindex/)
* Class [PageTotalNum](./pagetotalnum/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Delimiter](./get_delimiter/)() const | Hämtar avgränsaren som används i sidnummerformatet. Den formaterade strängen kommer att uppdateras baserat på den angivna avgränsaren. |
| [get_Index](./get_index/)() const | Hämtar sidindexkomponenten i sidnummerformatet. Den formaterade strängen kommer att innehålla en platshållare för sidindexet. |
| [get_Offset](./get_offset/)() const | Hämtar förskjutningen som ska läggas till sidindexet. |
| [get_TotalNum](./get_totalnum/)() const | Hämtar komponenten för totalt antal sidor i sidnummerformatet. Den formaterade strängen kommer att innehålla en platshållare för totalt antal sidor. |
| [GetPageNumberString](./getpagenumberstring/)(int32_t, int32_t) | Returnerar en formaterad sträng som representerar sidnumret baserat på de aktuella inställningarna. |
| [PageNumber](./pagenumber/)() |  |
| [set_Delimiter](./set_delimiter/)(const System::String\&) | Anger avgränsaren som används i sidnummerformatet. Den formaterade strängen kommer att uppdateras baserat på den angivna avgränsaren. |
| [set_Index](./set_index/)(const System::SharedPtr\<PageNumber::PageIndex\>\&) | Anger sidindexkomponenten i sidnummerformatet. Den formaterade strängen kommer att innehålla en platshållare för sidindexet. |
| [set_Offset](./set_offset/)(int32_t) | Anger förskjutningen som ska läggas till sidindexet. |
| [set_TotalNum](./set_totalnum/)(const System::SharedPtr\<PageNumber::PageTotalNum\>\&) | Ställer in komponenten för det totala antalet sidor i sidnumreringsformatet. Den formaterade strängen kommer att innehålla en platshållare för det totala antalet sidor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
