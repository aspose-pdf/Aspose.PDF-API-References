---
title: "Класс System::Xml::XmlImplementation"
linktitle: "XmlImplementation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlImplementation. Определяет контекст для набора объектов XmlDocument в C++."
type: docs
weight: 2000
url: /ru/cpp/system.xml/xmlimplementation/
---
## XmlImplementation class


Определяет контекст для набора объектов [XmlDocument](../xmldocument/).

```cpp
class XmlImplementation : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [CreateDocument](./createdocument/)() | Создает новый [XmlDocument](../xmldocument/). |
| [HasFeature](./hasfeature/)(const String\&, const String\&) | Проверяет, реализует ли реализация модели документа [Object](../../system/object/) (DOM) конкретную функцию. |
| [XmlImplementation](./xmlimplementation/)() | Инициализирует новый экземпляр класса [XmlImplementation](./). |
| [XmlImplementation](./xmlimplementation/)(const SharedPtr\<XmlNameTable\>\&) | Инициализирует новый экземпляр класса [XmlImplementation](./) с указанным [XmlNameTable](../xmlnametable/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
