---
title: "Aspose::Pdf::DataEditor::DictionaryEditor::Remove метод"
linktitle: "Remove"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::DataEditor::DictionaryEditor::Remove метод. Удаляет первое вхождение конкретного объекта из DictionaryEditor в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## DictionaryEditor::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) method


Удаляет первое вхождение конкретного объекта из [DictionaryEditor](../).

```cpp
bool Aspose::Pdf::DataEditor::DictionaryEditor::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<ICosPdfPrimitive>> &item) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\& | Объект, который нужно удалить из [DictionaryEditor](../). |

### ReturnValue

true, если элемент был успешно удалён из [DictionaryEditor](../); иначе — false. Этот метод также возвращает false, если элемент не найден в оригинальном [DictionaryEditor](../).

## См. также

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
## DictionaryEditor::Remove(const System::String\&) method


Удаляет элемент с указанным ключом из [DictionaryEditor](../).

```cpp
bool Aspose::Pdf::DataEditor::DictionaryEditor::Remove(const System::String &key) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | const System::String\& | Ключ элемента, который нужно удалить. |

### ReturnValue

True, если элемент был успешно удалён; иначе — false. Этот метод также возвращает false, если ключ не найден в оригинальном словаре или ключ не редактируемый.

## См. также

* Class [String](../../../system/string/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
