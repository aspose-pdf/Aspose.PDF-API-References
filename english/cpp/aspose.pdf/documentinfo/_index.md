---
title: Aspose::Pdf::DocumentInfo class
linktitle: DocumentInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DocumentInfo class. Represents meta information of PDF document in C++.'
type: docs
weight: 4400
url: /cpp/aspose.pdf/documentinfo/
---
## DocumentInfo class


Represents meta information of PDF document.

```cpp
class DocumentInfo : public System::Collections::Generic::Dictionary<System::String, System::String>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::String\&) override | Adds an element with the specified key and value into the collection. |
| [Clear](./clear/)() override | Clears the document info. |
| [ClearCustomData](./clearcustomdata/)() | Clears custom data only, leaves all other predefined values (Title, Author, etc.). |
| [DocumentInfo](./documentinfo/)(System::SharedPtr\<Document\>) | Initialize [DocumentInfo](./) instance. |
| [get_Author](./get_author/)() | Gets document author. |
| [get_CreationDate](./get_creationdate/)() | Gets the date of document creation. |
| [get_CreationTimeZone](./get_creationtimezone/)() | Time zone of creation date. |
| [get_Creator](./get_creator/)() | Gets document creator. |
| [get_Keywords](./get_keywords/)() | Gets or set the keywords of the document. |
| [get_ModDate](./get_moddate/)() | Gets the date of document modification. |
| [get_ModTimeZone](./get_modtimezone/)() | Time zone of modification date. |
| [get_Producer](./get_producer/)() | Gets the document producer. |
| [get_Subject](./get_subject/)() | Gets the subject of the document. |
| [get_Title](./get_title/)() | Gets document title. |
| [get_Trapped](./get_trapped/)() | Gets the trapped flag. |
| [idx_get](./idx_get/)(const System::String\&) const override | Gets the value associated with the specified key. |
| [idx_set](./idx_set/)(const System::String\&, System::String) override | Sets the value associated with the specified key. |
| static [IsPredefinedKey](./ispredefinedkey/)(System::String) | Determines if the key is predefined (Title, Author, etc.), not custom. |
| [Remove](./remove/)(System::String) | Removes the element with the specified key from the collection. |
| [set_Author](./set_author/)(System::String) | Sets document author. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Sets the date of document creation. |
| [set_CreationTimeZone](./set_creationtimezone/)(System::TimeSpan) | Time zone of creation date. |
| [set_Creator](./set_creator/)(System::String) | Sets document creator. |
| [set_Keywords](./set_keywords/)(System::String) | Gets or set the keywords of the document. |
| [set_ModDate](./set_moddate/)(System::DateTime) | Sets the date of document modification. |
| [set_ModTimeZone](./set_modtimezone/)(System::TimeSpan) | Time zone of modification date. |
| [set_Producer](./set_producer/)(System::String) | Sets the document producer. |
| [set_Subject](./set_subject/)(System::String) | Sets the subject of the document. |
| [set_Title](./set_title/)(System::String) | Sets document title. |
| [set_Trapped](./set_trapped/)(System::String) | Sets the trapped flag. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
