---
title: "System::Xml::XPath::XPathNodeIterator класс"
linktitle: "XPathNodeIterator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNodeIterator класс. Предоставляет итератор для выбранного набора узлов в C++."
type: docs
weight: 600
url: /ru/cpp/system.xml.xpath/xpathnodeiterator/
---
## XPathNodeIterator class


Предоставляет итератор по выбранному набору узлов.

```cpp
class XPathNodeIterator : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XPath::XPathNavigator>>
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Clone](./clone/)() | При переопределении в производном классе возвращает клон этого объекта [XPathNodeIterator](./). |
| virtual [get_Count](./get_count/)() | Возвращает индекс последнего узла в выбранном наборе узлов. |
| virtual [get_Current](./get_current/)() | При переопределении в производном классе получает объект [XPathNavigator](../xpathnavigator/) для этого [XPathNodeIterator](./), расположенный на текущем контекстном узле. |
| virtual [get_CurrentPosition](./get_currentposition/)() | При переопределении в производном классе получает индекс текущей позиции в выбранном наборе узлов. |
| [GetEnumerator](./getenumerator/)() override | Возвращает объект IEnumerator для перебора выбранного набора узлов. |
| virtual [MoveNext](./movenext/)() | При переопределении в производном классе перемещает объект [XPathNavigator](../xpathnavigator/), возвращаемый методом [XPathNodeIterator::get_Current](./get_current/), к следующему узлу в выбранном наборе узлов. |
| [XPathNodeIterator](./xpathnodeiterator/)() | Инициализирует новый экземпляр класса [XPathNodeIterator](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
