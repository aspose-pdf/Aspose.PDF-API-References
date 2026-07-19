---
title: "Aspose::Pdf::FileSpecificationComparer class"
linktitle: "FileSpecificationComparer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::FileSpecificationComparer class. Представляет класс сравнения для спецификации файла. Сравниватель сравнивает согласно спецификации, используя список полей для сортировки в определении коллекции. Согласно спецификации, сортировка выполняется по значениям элементов коллекции. Если словарь элементов коллекции отсутствует, сортировка выполняется по значениям Params в C++."
type: docs
weight: 5600
url: /ru/cpp/aspose.pdf/filespecificationcomparer/
---
## FileSpecificationComparer class


Представляет класс сравнения для спецификации файла. Сравниватель сравнивает согласно спецификации, используя список полей для сортировки в определении коллекции. Согласно спецификации, сортировка выполняется по значениям элементов коллекции. Если словарь элементов коллекции отсутствует, сортировка выполняется по значениям Params.

```cpp
class FileSpecificationComparer : public System::Collections::Generic::IComparer<System::SharedPtr<FileSpecification>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Compare](./compare/)(const System::SharedPtr\<FileSpecification\>\&, const System::SharedPtr\<FileSpecification\>\&) const override | Сравнивает две спецификации файлов согласно определению коллекции, используя указанную сортировку. |
| [FileSpecificationComparer](./filespecificationcomparer/)(const System::SharedPtr\<CollectionSort\>\&) | Создаёт сравниватель спецификации файлов. |
## См. также

* Class [IComparer](../../system.collections.generic/icomparer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
