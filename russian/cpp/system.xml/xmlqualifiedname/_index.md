---
title: "Класс System::Xml::XmlQualifiedName"
linktitle: "XmlQualifiedName"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlQualifiedName. Представляет квалифицированное имя XML в C++."
type: docs
weight: 3200
url: /ru/cpp/system.xml/xmlqualifiedname/
---
## XmlQualifiedName class


Представляет квалифицированное имя XML.

```cpp
class XmlQualifiedName : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Определяет, равен ли указанный объект [XmlQualifiedName](./) текущему объекту [XmlQualifiedName](./). |
| [get_IsEmpty](./get_isempty/)() const | Возвращает значение, указывающее, пустой ли объект [XmlQualifiedName](./). |
| [get_Name](./get_name/)() const | Возвращает строковое представление квалифицированного имени объекта [XmlQualifiedName](./). |
| [get_Namespace](./get_namespace/)() const | Возвращает строковое представление пространства имён объекта [XmlQualifiedName](./). |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш‑код объекта [XmlQualifiedName](./). |
| static [ToString](./tostring/)(const String\&, const String\&) | Возвращает строковое значение [XmlQualifiedName](./). |
| [ToString](./tostring/)() const override | Возвращает строковое значение [XmlQualifiedName](./). |
| [XmlQualifiedName](./xmlqualifiedname/)() | Инициализирует новый экземпляр класса [XmlQualifiedName](./). |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&) | Инициализирует новый экземпляр класса [XmlQualifiedName](./) с указанным именем. |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&, const String\&) | Инициализирует новый экземпляр класса [XmlQualifiedName](./) с указанным именем и пространством имён. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](./empty/) | Предоставляет пустой [XmlQualifiedName](./). |
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
