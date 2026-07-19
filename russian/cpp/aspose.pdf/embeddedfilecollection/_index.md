---
title: "Класс Aspose::Pdf::EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::EmbeddedFileCollection. Класс, представляющий коллекцию вложенных файлов в C++."
type: docs
weight: 4300
url: /ru/cpp/aspose.pdf/embeddedfilecollection/
---
## EmbeddedFileCollection class


Класс, представляющий коллекцию вложенных файлов.

```cpp
class EmbeddedFileCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FileSpecification>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FileSpecification\>\&) override | Добавляет спецификацию вложенного файла в коллекцию. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<FileSpecification\>\&) | Добавляет файл во вложенные файлы с указанным ключом. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FileSpecification\>\>, int32_t) override | Копирует массив объектов [FileSpecification](../filespecification/) в коллекцию. |
| [Delete](./delete/)(const System::String\&) | Удалить вложенный файл по имени. |
| [Delete](./delete/)() | Удалить все вложенные файлы из документа. |
| [DeleteByKey](./deletebykey/)(const System::String\&) | Удаляет файл из коллекции по его ключу. |
| [FindByName](./findbyname/)(const System::String\&) | Возвращает вложенный файл по его имени. |
| [get_Count](./get_count/)() const override | Получает количество вложенных файлов в коллекции. |
| [get_IsSynchronized](./get_issynchronized/)() | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (потокобезопасный). |
| [get_Keys](./get_keys/)() | Возвращает список ключей вложений файлов. |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает вложенный файл по его индексу. |
| [idx_get](./idx_get/)(const System::String\&) | Получает вложенный файл по его имени. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
