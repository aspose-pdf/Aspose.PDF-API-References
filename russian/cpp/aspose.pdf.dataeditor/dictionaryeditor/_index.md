---
title: "Класс Aspose::Pdf::DataEditor::DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::DataEditor::DictionaryEditor. Класс для доступа к древовидному словарю документа (словарю документа, словарю страниц, словарю ресурсов) в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class


Класс для доступа к древовидному словарю документа (словарь документа, словарь страниц, словарь ресурсов).

```cpp
class DictionaryEditor : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<ICosPdfPrimitive>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<ICosPdfPrimitive\>\&) override | Установите [ICosPdfPrimitive](../icospdfprimitive/) в словарь. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Установите [ICosPdfPrimitive](../icospdfprimitive/) в словарь. |
| [Clear](./clear/)() override | Удаляет все элементы из [DictionaryEditor](./). |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) const override | Определяет, содержит ли [DictionaryEditor](./) конкретное значение. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Определяет, содержит ли [DictionaryEditor](./) элемент с указанным ключом. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\>, int32_t) override | Копирует элементы [DictionaryEditor](./) в [Array](../../aspose.pdf/xmpfieldtype/), начиная с определённого индекса [Array](../../aspose.pdf/xmpfieldtype/). |
| [DictionaryEditor](./dictionaryeditor/)(const System::SharedPtr\<Page\>\&) | ArgumentNullException |
| [DictionaryEditor](./dictionaryeditor/)(const System::SharedPtr\<Document\>\&) | ArgumentNullException |
| [DictionaryEditor](./dictionaryeditor/)(const System::SharedPtr\<Resources\>\&) | ArgumentNullException |
| [get_AllKeys](./get_allkeys/)() const | Полный набор ключей. Содержит редактируемые и не редактируемые ключи. |
| [get_Count](./get_count/)() const override | Возвращает количество элементов, содержащихся в [DictionaryEditor](./). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Возвращает значение, указывающее, является ли [DictionaryEditor](./) только для чтения. |
| [get_Keys](./get_keys/)() const override | [Collection](../../aspose.pdf/collection/) редактируемых ключей. |
| [get_Values](./get_values/)() const override | Возвращает [ICollection](../../system.collections.generic/icollection/icollection/), содержащий значения из [DictionaryEditor](./). |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель, который проходит по коллекции. |
| [idx_get](./idx_get/)(const System::String\&) const override | Получает элемент с указанным ключом. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>) override | Устанавливает элемент с указанным ключом. |
| [Remove](./remove/)(const System::String\&) override | Удаляет элемент с указанным ключом из [DictionaryEditor](./). |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Удаляет первое вхождение конкретного объекта из [DictionaryEditor](./). |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>\&) const override | Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов. |
## См. также

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::DataEditor](../)
* Library [Aspose.PDF for C++](../../)
