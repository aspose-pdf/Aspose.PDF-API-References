---
title: "Класс System::Xml::XPath::XPathDocument"
linktitle: "XPathDocument"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XPath::XPathDocument. Предоставляет быстрое, только для чтения, представление XML‑документа в памяти, используя модель данных XPath в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml.xpath/xpathdocument/
---
## XPathDocument class


Предоставляет быстрое, только для чтения, представление XML‑документа в памяти, используя модель данных [XPath](../).

```cpp
class XPathDocument : public System::Xml::XPath::IXPathNavigable
```

## Методы

| Метод | Описание |
| --- | --- |
| [CreateNavigator](./createnavigator/)() override | Инициализирует только для чтения объект [XPathNavigator](../xpathnavigator/) для навигации по узлам в этом [XPathDocument](./). |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&) | Инициализирует новый экземпляр класса [XPathDocument](./) из XML‑данных, содержащихся в указанном объекте [XmlReader](../../system.xml/xmlreader/). |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&, XmlSpace) | Инициализирует новый экземпляр класса [XPathDocument](./) из XML‑данных, содержащихся в указанном объекте [XmlReader](../../system.xml/xmlreader/), с указанной обработкой пробельных символов. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::TextReader\>\&) | Инициализирует новый экземпляр класса [XPathDocument](./) из XML‑данных, содержащихся в указанном объекте TextReader. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::Stream\>\&) | Инициализирует новый экземпляр класса [XPathDocument](./) из XML‑данных в указанном объекте Stream. |
| [XPathDocument](./xpathdocument/)(const String\&) | Инициализирует новый экземпляр класса [XPathDocument](./) из XML‑данных в указанном файле. |
| [XPathDocument](./xpathdocument/)(const String\&, XmlSpace) | Инициализирует новый экземпляр класса [XPathDocument](./) из XML‑данных в файле, указанном с заданной обработкой пробельных символов. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [IXPathNavigable](../ixpathnavigable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
