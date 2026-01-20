---
title: Aspose::Pdf::Text::FontCollection::Contains method
linktitle: Contains
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::FontCollection::Contains method. Determines whether the collection contains a specific value in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.text/fontcollection/contains/
---
## FontCollection::Contains(const System::SharedPtr\<Font\>\&) const method


Determines whether the collection contains a specific value.

```cpp
bool Aspose::Pdf::Text::FontCollection::Contains(const System::SharedPtr<Font> &item) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::SharedPtr\<Font\>\& | The object to locate in the collection |

### ReturnValue

true if item is found in the collection; otherwise, false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontCollection::Contains(const System::String\&) const method


Checks if font exists in font collection.

```cpp
bool Aspose::Pdf::Text::FontCollection::Contains(const System::String &name) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const System::String\& | [Font](../../font/) name. |

### ReturnValue

True in case collection contains the font with specified name.

## See Also

* Class [String](../../../system/string/)
* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
