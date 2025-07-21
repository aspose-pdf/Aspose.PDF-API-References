---
title: Aspose::Pdf::DataEditor::CosPdfDictionary::TryGetValue method
linktitle: TryGetValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DataEditor::CosPdfDictionary::TryGetValue method. For access to simple data type like string, name, bool, number. Returns null for other types in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary::TryGetValue method


For access to simple data type like string, name, bool, number. Returns null for other types.

```cpp
bool Aspose::Pdf::DataEditor::CosPdfDictionary::TryGetValue(const System::String &key, System::SharedPtr<ICosPdfPrimitive> &value) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key value |
| value | System::SharedPtr\<ICosPdfPrimitive\>\& | returns [ICosPdfPrimitive](../../icospdfprimitive/) for key or null. |

### ReturnValue

Returns true if [ICosPdfPrimitive](../../icospdfprimitive/) is like string, name, bool, number. Returns false for all other types.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [CosPdfDictionary](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
