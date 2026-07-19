---
title: "Метод Aspose::Pdf::DataEditor::CosPdfDictionary::Remove"
linktitle: "Remove"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::DataEditor::CosPdfDictionary::Remove метод. Удаляет первое вхождение конкретного объекта из CosPdfDictionary в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## CosPdfDictionary::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) method


Удаляет первое вхождение конкретного объекта из [CosPdfDictionary](../).

```cpp
bool Aspose::Pdf::DataEditor::CosPdfDictionary::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<ICosPdfPrimitive>> &item) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\& | Объект, который нужно удалить из [CosPdfDictionary](../). |

### ReturnValue

true, если элемент был успешно удалён из [CosPdfDictionary](../); иначе — false. Этот метод также возвращает false, если элемент не найден в исходном [CosPdfDictionary](../).

## См. также

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [CosPdfDictionary](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
## CosPdfDictionary::Remove(const System::String\&) method


Удаляет элемент с указанным ключом из [CosPdfDictionary](../).

```cpp
bool Aspose::Pdf::DataEditor::CosPdfDictionary::Remove(const System::String &key) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | const System::String\& | Ключ элемента, который нужно удалить. |

### ReturnValue

True, если элемент был успешно удалён; иначе — false. Этот метод также возвращает false, если ключ не найден в оригинальном словаре или ключ не редактируемый.

## См. также

* Class [String](../../../system/string/)
* Class [CosPdfDictionary](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
