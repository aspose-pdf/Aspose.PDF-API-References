---
title: Aspose::Pdf::Comparison::ComparisonOptions class
linktitle: ComparisonOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::ComparisonOptions class. Represents a PDF document comparison options class in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class


Represents a PDF document comparison options class.

```cpp
class ComparisonOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [ComparisonOptions](./comparisonoptions/)() | Creates a [ComparisonOptions](./) class instance. |
| [get_EditOperationsOrder](./get_editoperationsorder/)() const | Gets and sets the edit operations order. |
| [get_ExcludeAreas1](./get_excludeareas1/)() const | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with [ExcludeTables](../). This option can't be setted along with [ExtractionArea](../) option. |
| [get_ExcludeAreas2](./get_excludeareas2/)() const | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with [ExcludeTables](../). This option can't be setted along with [ExtractionArea](../) option. |
| [get_ExcludeTables](./get_excludetables/)() const | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with [ExtractionArea](../) option. The default value is **false**. |
| [get_ExtractionArea](./get_extractionarea/)() const | Get and set the rectangular area in which the text of pages will be compared. This option can't be setted along with [ExcludeTables](../), [ExcludeAreas1](../) and [ExcludeAreas2](../) options. |
| [set_EditOperationsOrder](./set_editoperationsorder/)(Aspose::Pdf::Comparison::EditOperationsOrder) | Gets and sets the edit operations order. |
| [set_ExcludeAreas1](./set_excludeareas1/)(System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>) | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with [ExcludeTables](../). This option can't be setted along with [ExtractionArea](../) option. |
| [set_ExcludeAreas2](./set_excludeareas2/)(System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>) | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with [ExcludeTables](../). This option can't be setted along with [ExtractionArea](../) option. |
| [set_ExcludeTables](./set_excludetables/)(bool) | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with [ExtractionArea](../) option. The default value is **false**. |
| [set_ExtractionArea](./set_extractionarea/)(System::SharedPtr\<Rectangle\>) | Get and set the rectangular area in which the text of pages will be compared. This option can't be setted along with [ExcludeTables](../), [ExcludeAreas1](../) and [ExcludeAreas2](../) options. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
