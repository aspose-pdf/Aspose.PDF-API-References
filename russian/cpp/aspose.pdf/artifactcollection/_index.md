---
title: "Класс Aspose::Pdf::ArtifactCollection"
linktitle: "ArtifactCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::ArtifactCollection. Класс представляет коллекцию артефактов в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf/artifactcollection/
---
## ArtifactCollection class


Класс представляет коллекцию артефактов.

```cpp
class ArtifactCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Artifact>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Artifact\>\&) override | Добавляет артефакты в коллекцию. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Artifact\>\>, int32_t) override | Копирует коллекцию в массив. |
| [Delete](./delete/)(const System::SharedPtr\<Artifact\>\&) | Удаляет указанный артефакт. |
| [Delete](./delete/)(int32_t) | Удаляет артефакт по его индексу. |
| [FindByValue](./findbyvalue/)(const System::String\&, const System::String\&) | Находит артефакты по пользовательскому значению. |
| [get_Count](./get_count/)() const override | Получает количество артефактов в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Определяет, является ли коллекция только для чтения. Всегда возвращает false. |
| [get_IsSynchronized](./get_issynchronized/)() | Синхронизирован ли этот объект. |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект синхронизации коллекции. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель для коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает артефакт по индексу. Индекс начинается с 1. |
| [Update](./update/)(const System::SharedPtr\<Artifact\>\&) | Обновляет артефакт в коллекции. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
