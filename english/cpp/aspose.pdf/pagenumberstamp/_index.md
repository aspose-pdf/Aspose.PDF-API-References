---
title: Aspose::Pdf::PageNumberStamp class
linktitle: PageNumberStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageNumberStamp class. Represents page number stamp and used to number pages in C++.'
type: docs
weight: 14400
url: /cpp/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class


Represents page number stamp and used to number pages.

```cpp
class PageNumberStamp : public Aspose::Pdf::TextStamp
```

## Methods

| Method | Description |
| --- | --- |
| [get_Format](./get_format/)() const | String value for stamping page numbers. Value must include char '#' which is replaced with the page number in the process of stamping. |
| [get_NumberingStyle](./get_numberingstyle/)() const | Numbering style which used by this stamp. |
| [get_StartingNumber](./get_startingnumber/)() const | Gets value of the number of starting page. Other pages will be numbered starting from this value. |
| [PageNumberStamp](./pagenumberstamp/)(System::String) | Initializes a new instance of the [PageNumberStamp](./) class. |
| [PageNumberStamp](./pagenumberstamp/)() | Initializes a new instance of the [PageNumberStamp](./) class. Format is set to "#". |
| [PageNumberStamp](./pagenumberstamp/)(System::SharedPtr\<Facades::FormattedText\>) | Creates [PageNumberStamp](./) by formatted text. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Adds page number. |
| [set_Format](./set_format/)(System::String) | String value for stamping page numbers. Value must include char '#' which is replaced with the page number in the process of stamping. |
| [set_NumberingStyle](./set_numberingstyle/)(Aspose::Pdf::NumberingStyle) | Numbering style which used by this stamp. |
| [set_StartingNumber](./set_startingnumber/)(int32_t) | Sets value of the number of starting page. Other pages will be numbered starting from this value. |
## See Also

* Class [TextStamp](../textstamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
