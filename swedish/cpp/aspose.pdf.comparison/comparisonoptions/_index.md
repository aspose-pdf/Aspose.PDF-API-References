---
title: "Aspose::Pdf::Comparison::ComparisonOptions klass"
linktitle: "ComparisonOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::ComparisonOptions klass. Representerar en klass för PDF-dokumentjämförelsesalternativ i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class


Representerar en klass för alternativ för PDF‑dokumentjämförelse.

```cpp
class ComparisonOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ComparisonOptions](./comparisonoptions/)() | Skapar en [ComparisonOptions](./) klassinstans. |
| [get_EditOperationsOrder](./get_editoperationsorder/)() const | Hämtar och anger ordningen för redigeringsoperationerna. |
| [get_ExcludeAreas1](./get_excludeareas1/)() const | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med [ExcludeTables](../). Detta alternativ kan inte ställas in tillsammans med [ExtractionArea](../)-alternativet. |
| [get_ExcludeAreas2](./get_excludeareas2/)() const | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med [ExcludeTables](../). Detta alternativ kan inte ställas in tillsammans med [ExtractionArea](../)-alternativet. |
| [get_ExcludeTables](./get_excludetables/)() const | Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte ställas in tillsammans med [ExtractionArea](../)-alternativet. Standardvärdet är **false**. |
| [get_ExtractionArea](./get_extractionarea/)() const | Hämta och ange det rektangulära området där sidornas text kommer att jämföras. Detta alternativ kan inte ställas in tillsammans med [ExcludeTables](../), [ExcludeAreas1](../) och [ExcludeAreas2](../)-alternativen. |
| [set_EditOperationsOrder](./set_editoperationsorder/)(Aspose::Pdf::Comparison::EditOperationsOrder) | Hämtar och anger ordningen för redigeringsoperationerna. |
| [set_ExcludeAreas1](./set_excludeareas1/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med [ExcludeTables](../). Detta alternativ kan inte ställas in tillsammans med [ExtractionArea](../)-alternativet. |
| [set_ExcludeAreas2](./set_excludeareas2/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med [ExcludeTables](../). Detta alternativ kan inte ställas in tillsammans med [ExtractionArea](../)-alternativet. |
| [set_ExcludeTables](./set_excludetables/)(bool) | Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte ställas in tillsammans med [ExtractionArea](../)-alternativet. Standardvärdet är **false**. |
| [set_ExtractionArea](./set_extractionarea/)(const System::SharedPtr\<Rectangle\>\&) | Hämta och ange det rektangulära området där sidornas text kommer att jämföras. Detta alternativ kan inte ställas in tillsammans med [ExcludeTables](../), [ExcludeAreas1](../) och [ExcludeAreas2](../)-alternativen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
