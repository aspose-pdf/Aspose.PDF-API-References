---
title: "Aspose::Pdf::Annotations::AnnotationCollection класс"
linktitle: "AnnotationCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::AnnotationCollection класс. Класс, представляющий коллекцию аннотаций в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.annotations/annotationcollection/
---
## AnnotationCollection class


Класс, представляющий коллекцию аннотаций.

```cpp
class AnnotationCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Annotation>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<AnnotationSelector\>\&) | Принимает посетителя для обработки аннотации. |
| [Add](./add/)(const System::SharedPtr\<Annotation\>\&, bool) | Добавляет аннотацию в коллекцию. Если страница повернута, то прямоугольник аннотации будет пересчитан соответствующим образом. |
| [Add](./add/)(const System::SharedPtr\<Annotation\>\&) override | Добавляет аннотацию в коллекцию. |
| [Clear](./clear/)() override | Удаляет все аннотации из коллекции. |
| [Contains](./contains/)(const System::SharedPtr\<Annotation\>\&) const override | Проверяет, принадлежит ли указанная аннотация коллекции. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Annotation\>\>, int32_t) override | Копирует массив аннотаций в коллекцию. |
| [Delete](./delete/)(int32_t) | Удаляет аннотацию из коллекции по индексу. |
| [Delete](./delete/)() | Удаляет все аннотации из коллекции. |
| [Delete](./delete/)(const System::SharedPtr\<Annotation\>\&) | Удаляет указанную аннотацию из коллекции. |
| [FindByName](./findbyname/)(const System::String\&) | Возвращает аннотацию по её имени. |
| [get_Count](./get_count/)() const override | Получает количество аннотаций в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Получает значение, указывающее, синхронизирован ли доступ к [Aspose.Pdf.Annotations.AnnotationCollection](./) (потокобезопасный). |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект, который можно использовать для синхронизации доступа к [Aspose.Pdf.Annotations.AnnotationCollection](./). |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель коллекции. |
| [idx_get](./idx_get/)(int32_t) | Индекс элемента для получения. |
| [Remove](./remove/)(const System::SharedPtr\<Annotation\>\&) override | Удаляет указанную аннотацию из коллекции. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
