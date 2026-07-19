---
title: "Метод Aspose::Pdf::OperatorCollection::Insert"
linktitle: "Вставить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::OperatorCollection::Insert. Вставляет операторы в указанную позицию в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf/operatorcollection/insert/
---
## OperatorCollection::Insert(int32_t, const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) method


Вставляет операторы в указанную позицию.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t at, const System::ArrayPtr<System::SharedPtr<Operator>> &ops)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| в | int32_t | Индекс, с которого начинается вставка операторов. |
| операции | const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\& | Массив операторов для вставки. Каждый оператор может иметь любой индекс (по умолчанию -1), потому что их индексы автоматически корректируются, начиная с *at*. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Insert(int32_t, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) method


Вставляет операторы в указанную позицию.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t at, const System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Operator>>> &ops)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| в | int32_t | Индекс, с которого начинается вставка операторов. |
| операции | const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\& | Массив операторов для вставки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Insert(int32_t, System::SharedPtr\<Operator\>) method


Вставляет оператор в коллекцию.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t index, System::SharedPtr<Operator> op) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int32_t | Индекс, где должен быть добавлен новый оператор |
| op | System::SharedPtr\<Operator\> | [Operator](../../operator/) который будет вставлен |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
