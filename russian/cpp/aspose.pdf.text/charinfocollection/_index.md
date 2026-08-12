---
title: "Aspose::Pdf::Text::CharInfoCollection класс"
linktitle: "CharInfoCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::CharInfoCollection класс. Представляет коллекцию объектов CharInfo в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class


Представляет коллекцию объектов [CharInfo](../charinfo/).

```cpp
class CharInfoCollection : public System::Collections::Generic::ICollection<System::SharedPtr<CharInfo>>
```

## Методы

| Метод | Описание |
| --- | --- |
|  | [Add](./add/)(const System::SharedPtr\<CharInfo\>\&) override | [Collection](../../aspose.pdf/collection/) только для чтения, бросает NotImplementedException |
. |
| [Clear](./clear/)() override | [Collection](../../aspose.pdf/collection/) только для чтения. Всегда бросает NotImplementedException. |
| [Contains](./contains/)(const System::SharedPtr\<CharInfo\>\&) const override | Определяет, содержит ли коллекция определённое значение. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<CharInfo\>\>, int32_t) override | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [get_Count](./get_count/)() const override | Возвращает количество элементов объектов [CharInfo](../charinfo/), фактически содержащихся в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [get_SyncRoot](./get_syncroot/)() const | Возвращает объект, который может использоваться для синхронизации доступа к коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для всей коллекции. |
| [idx_get](./idx_get/)(int32_t) | Возвращает элемент [CharInfo](../charinfo/) по указанному индексу. |
|  | [Remove](./remove/)(const System::SharedPtr\<CharInfo\>\&) override | [Collection](../../aspose.pdf/collection/) только для чтения, бросает NotImplementedException |
. |
## Примечания


Обеспечивает доступ к информации о позиционировании символов текстового сегмента.
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
