---
title: Aspose::Pdf::DataEditor::DictionaryEditor::Remove method
linktitle: Remove
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DataEditor::DictionaryEditor::Remove method. Removes the first occurrence of a specific object from the DictionaryEditor in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## DictionaryEditor::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) method


Removes the first occurrence of a specific object from the [DictionaryEditor](../).

```cpp
bool Aspose::Pdf::DataEditor::DictionaryEditor::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<ICosPdfPrimitive>> &item) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\& | The object to remove from the [DictionaryEditor](../). |

### ReturnValue

true if item was successfully removed from the [DictionaryEditor](../); otherwise, false. This method also returns false if item is not found in the original [DictionaryEditor](../).

## See Also

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
## DictionaryEditor::Remove(const System::String\&) method


Removes the element with the specified key from the [DictionaryEditor](../).

```cpp
bool Aspose::Pdf::DataEditor::DictionaryEditor::Remove(const System::String &key) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | The key of the element to remove. |

### ReturnValue

True if the element is successfully removed; otherwise, false. This method also returns false if key was not found in the original dictionary or key the key is not editable

## See Also

* Class [String](../../../system/string/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
