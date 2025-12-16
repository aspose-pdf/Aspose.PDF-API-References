---
title: Aspose::Pdf::PageNumber class
linktitle: PageNumber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageNumber class. Represents a page number format that includes an index, total number of pages, and a delimiter in C++.'
type: docs
weight: 14300
url: /cpp/aspose.pdf/pagenumber/
---
## PageNumber class


Represents a page number format that includes an index, total number of pages, and a delimiter.

```cpp
class PageNumber : public System::Object
```

## Nested classes

* Class [PageIndex](./pageindex/)
* Class [PageTotalNum](./pagetotalnum/)
## Methods

| Method | Description |
| --- | --- |
| [get_Delimiter](./get_delimiter/)() const | Gets the delimiter used in the page number format. The formatted string will be updated based on the specified delimiter. |
| [get_Index](./get_index/)() const | Gets the page index component of the page number format. The formatted string will include a placeholder for the page index. |
| [get_Offset](./get_offset/)() const | Gets the offset to be added to the page index. |
| [get_TotalNum](./get_totalnum/)() const | Gets the total number of pages component of the page number format. The formatted string will include a placeholder for the total number of pages. |
| [GetPageNumberString](./getpagenumberstring/)(int32_t, int32_t) | Returns a formatted string representing the page number based on the current settings. |
| [PageNumber](./pagenumber/)() |  |
| [set_Delimiter](./set_delimiter/)(System::String) | Sets the delimiter used in the page number format. The formatted string will be updated based on the specified delimiter. |
| [set_Index](./set_index/)(System::SharedPtr\<PageNumber::PageIndex\>) | Sets the page index component of the page number format. The formatted string will include a placeholder for the page index. |
| [set_Offset](./set_offset/)(int32_t) | Sets the offset to be added to the page index. |
| [set_TotalNum](./set_totalnum/)(System::SharedPtr\<PageNumber::PageTotalNum\>) | Sets the total number of pages component of the page number format. The formatted string will include a placeholder for the total number of pages. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
