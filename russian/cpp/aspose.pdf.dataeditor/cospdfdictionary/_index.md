---
title: "Aspose::Pdf::DataEditor::CosPdfDictionary класс"
linktitle: "CosPdfDictionary"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::DataEditor::CosPdfDictionary класс. Класс для доступа к словарю объекта в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class


Класс для доступа к словарю объекта.

```cpp
class CosPdfDictionary : public Aspose::Pdf::DataEditor::CosPdfPrimitive,
                         public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<ICosPdfPrimitive>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<ICosPdfPrimitive\>\&) override | Установите [ICosPdfPrimitive](../icospdfprimitive/) в словарь. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Установите [ICosPdfPrimitive](../icospdfprimitive/) в словарь. |
| [Clear](./clear/)() override | Удаляет все элементы из [CosPdfDictionary](./). |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) const override | Определяет, содержит ли [CosPdfDictionary](./) конкретное значение. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Определяет, содержит ли [CosPdfDictionary](./) элемент с указанным ключом. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\>, int32_t) override | Копирует элементы [CosPdfDictionary](./) в [Array](../../aspose.pdf/xmpfieldtype/), начиная с определённого индекса [Array](../../aspose.pdf/xmpfieldtype/). |
| [CosPdfDictionary](./cospdfdictionary/)(const System::SharedPtr\<Resources\>\&) | Создаёт словарь из ресурсов. |
| static [CreateEmptyDictionary](./createemptydictionary/)(const System::SharedPtr\<Page\>\&) | Создаёт пустой словарь, который будет прикреплён к странице. |
| static [CreateEmptyDictionary](./createemptydictionary/)(const System::SharedPtr\<Document\>\&) | Создает пустой словарь, который будет прикреплен к документу. |
| [get_AllKeys](./get_allkeys/)() const | Полный набор ключей. Содержит редактируемые и не редактируемые ключи. |
| [get_Count](./get_count/)() const override | Получает количество элементов, содержащихся в [CosPdfDictionary](./). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли [CosPdfDictionary](./) только для чтения. |
| [get_Keys](./get_keys/)() const override | [Collection](../../aspose.pdf/collection/) редактируемых ключей. |
| [get_Values](./get_values/)() const override | Получает [ICollection](../../system.collections.generic/icollection/icollection/), содержащий значения в [CosPdfDictionary](./). |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель, который проходит по коллекции. |
| [idx_get](./idx_get/)(const System::String\&) const override | Получает элемент с указанным ключом. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>) override | Устанавливает элемент с указанным ключом. |
| [Remove](./remove/)(const System::String\&) override | Удаляет элемент с указанным ключом из [CosPdfDictionary](./). |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Удаляет первое вхождение конкретного объекта из [CosPdfDictionary](./). |
| [ToCosPdfDictionary](./tocospdfdictionary/)() override | Пытается привести этот экземпляр к [CosPdfDictionary](./). |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>\&) const override | Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов. |
## См. также

* Class [CosPdfPrimitive](../cospdfprimitive/)
* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::DataEditor](../)
* Library [Aspose.PDF for C++](../../)
