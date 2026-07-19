---
title: "Aspose::Pdf::DataEditor::DictionaryEditor::TryGetValue method"
linktitle: "TryGetValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::DataEditor::DictionaryEditor::TryGetValue method. Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor::TryGetValue method


Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов.

```cpp
bool Aspose::Pdf::DataEditor::DictionaryEditor::TryGetValue(const System::String &key, System::SharedPtr<ICosPdfPrimitive> &value) const override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | const System::String\& | Значение ключа |
| value | System::SharedPtr\<ICosPdfPrimitive\>\& | возвращает [ICosPdfPrimitive](../../icospdfprimitive/) для ключа или null. |

### ReturnValue

Возвращает true, если [ICosPdfPrimitive](../../icospdfprimitive/) является строкой, именем, bool или числом. Возвращает false для всех остальных типов.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
