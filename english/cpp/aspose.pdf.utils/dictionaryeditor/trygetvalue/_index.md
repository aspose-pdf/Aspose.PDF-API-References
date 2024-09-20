---
title: Aspose::Pdf::Utils::DictionaryEditor::TryGetValue method
linktitle: TryGetValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Utils::DictionaryEditor::TryGetValue method. For access to simple data type like string, name, bool, number. Returns null for other types in C++.'
type: docs
weight: 1600
url: /cpp/aspose.pdf.utils/dictionaryeditor/trygetvalue/
---
## DictionaryEditor::TryGetValue method


For access to simple data type like string, name, bool, number. Returns null for other types.

```cpp
bool Aspose::Pdf::Utils::DictionaryEditor::TryGetValue(const System::String &key, System::SharedPtr<PublicData::ICosPdfPrimitive> &value) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key value |
| value | System::SharedPtr\<PublicData::ICosPdfPrimitive\>\& | returns [ICosPdfPrimitive](../) for key or null. |

### ReturnValue

Returns true if [ICosPdfPrimitive](../) is like string, name, bool, number. Returns false for all other types.

## See Also

* Class [ICosPdfPrimitive](../../../aspose.pdf.utils.publicdata/icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::Utils](../../)
* Library [Aspose.PDF for C++](../../../)
