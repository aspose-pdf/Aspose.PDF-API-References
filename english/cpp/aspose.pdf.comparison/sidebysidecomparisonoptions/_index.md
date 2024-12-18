---
title: Aspose::Pdf::Comparison::SideBySideComparisonOptions class
linktitle: SideBySideComparisonOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::SideBySideComparisonOptions class. Represents an options class for comparing documents with side-by-side output in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class


Represents an options class for comparing documents with side-by-side output.

```cpp
class SideBySideComparisonOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AdditionalChangeMarks](./get_additionalchangemarks/)() const | Get and set the property that determines whether additional change markers are displayed. If set, displays change marks that are not on the current page but are present on another page. If the change lacates between words, the mark may not be positioned exactly relative to the whitespace character. The default value is **false**. |
| [get_ComparisonArea1](./get_comparisonarea1/)() const | Get and set the comparison area. Used for the first page or document in the comparison method. This option can't be setted along with [ExcludeTables](../), [ExcludeAreas1](../) and [ExcludeAreas2](../) options. |
| [get_ComparisonArea2](./get_comparisonarea2/)() const | Get and set the comparison area. Used for the second page or document in the comparison method. This option can't be setted along with [ExcludeTables](../), [ExcludeAreas1](../) and [ExcludeAreas2](../) options. |
| [get_ComparisonMode](./get_comparisonmode/)() const | Gets and sets a comparison mode. The default value is [SideBySideComparison::ComparisonMode::IgnoreSpaces](../). |
| [get_ExcludeAreas1](./get_excludeareas1/)() const | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with [ExcludeTables](../). This option can't be setted along with [ComparisonArea1](../) option. |
| [get_ExcludeAreas2](./get_excludeareas2/)() const | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with [ExcludeTables](../). This option can't be setted along with [ComparisonArea2](../) option. |
| [get_ExcludeTables](./get_excludetables/)() const | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with [ComparisonArea1](../) and [ComparisonArea2](../). The default value is **false**. |
| [set_AdditionalChangeMarks](./set_additionalchangemarks/)(bool) | Get and set the property that determines whether additional change markers are displayed. If set, displays change marks that are not on the current page but are present on another page. If the change lacates between words, the mark may not be positioned exactly relative to the whitespace character. The default value is **false**. |
| [set_ComparisonArea1](./set_comparisonarea1/)(System::SharedPtr\<Rectangle\>) | Get and set the comparison area. Used for the first page or document in the comparison method. This option can't be setted along with [ExcludeTables](../), [ExcludeAreas1](../) and [ExcludeAreas2](../) options. |
| [set_ComparisonArea2](./set_comparisonarea2/)(System::SharedPtr\<Rectangle\>) | Get and set the comparison area. Used for the second page or document in the comparison method. This option can't be setted along with [ExcludeTables](../), [ExcludeAreas1](../) and [ExcludeAreas2](../) options. |
| [set_ComparisonMode](./set_comparisonmode/)(Aspose::Pdf::Comparison::ComparisonMode) | Gets and sets a comparison mode. The default value is [SideBySideComparison::ComparisonMode::IgnoreSpaces](../). |
| [set_ExcludeAreas1](./set_excludeareas1/)(System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>) | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with [ExcludeTables](../). This option can't be setted along with [ComparisonArea1](../) option. |
| [set_ExcludeAreas2](./set_excludeareas2/)(System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>) | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with [ExcludeTables](../). This option can't be setted along with [ComparisonArea2](../) option. |
| [set_ExcludeTables](./set_excludetables/)(bool) | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with [ComparisonArea1](../) and [ComparisonArea2](../). The default value is **false**. |
| [SideBySideComparisonOptions](./sidebysidecomparisonoptions/)() | Creates an instance of [SideBySideComparisonOptions](./) class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
