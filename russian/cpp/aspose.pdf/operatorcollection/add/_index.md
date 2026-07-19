---
title: "Aspose::Pdf::OperatorCollection::Add method"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::OperatorCollection::Add method. Добавляет операторы в конец операторов содержимого в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf/operatorcollection/add/
---
## OperatorCollection::Add(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) method


Добавляет операторы в конец операторов содержимого.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::ArrayPtr<System::SharedPtr<Operator>> &ops)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| операции | const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\& | Массив операторов для добавления. Каждый оператор может иметь любой индекс (по умолчанию -1), потому что они попадают в конец операторов содержимого, т.е. индексы назначаются автоматически. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::SharedPtr\<Operator\>\&) method


Добавляет новый оператор в коллекцию.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<Operator> &op) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| op | const System::SharedPtr\<Operator\>\& | [Operator](../../operator/) который должен быть добавлен |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\&) method


Добавляет в коллекцию все операторы из другой коллекции.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Operator>>> &ops)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| операции | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\& | Коллекция, содержащая операторы, которые будут добавлены. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
