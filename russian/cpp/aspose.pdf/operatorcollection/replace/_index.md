---
title: "Aspose::Pdf::OperatorCollection::Replace метод"
linktitle: "Заменить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::OperatorCollection::Replace метод. Заменяет операторы в коллекции другими операторами в C++."
type: docs
weight: 1700
url: /ru/cpp/aspose.pdf/operatorcollection/replace/
---
## OperatorCollection::Replace method


Заменяет операторы в коллекции другими операторами.

```cpp
void Aspose::Pdf::OperatorCollection::Replace(const System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Operator>>> &operators)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| operators | const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\& | [Operators](../../../aspose.pdf.operators/) список, который заменит текущие операторы, содержащиеся в коллекции. Каждый оператор из списка должен иметь корректный индекс в диапазоне [1..N], где N — количество операторов в коллекции. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
