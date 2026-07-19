---
title: "Класс System::Xml::XmlSignificantWhitespace"
linktitle: "XmlSignificantWhitespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlSignificantWhitespace. Представляет пробелы между разметкой в узле смешанного содержимого или пробелы внутри области xml:space=''preserve''. Это также называется значимыми пробелами в C++."
type: docs
weight: 3700
url: /ru/cpp/system.xml/xmlsignificantwhitespace/
---
## XmlSignificantWhitespace class


Представляет пробельные символы между разметкой в узле смешанного содержимого или пробелы внутри области **xml:space='preserve'**. Это также называется значимыми пробельными символами.

```cpp
class XmlSignificantWhitespace : public System::Xml::XmlCharacterData
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_PreviousText](./get_previoustext/)() override | Возвращает текстовый узел, который непосредственно предшествует этому узлу. |
| [get_Value](./get_value/)() override | Возвращает значение узла. |
| [set_Value](./set_value/)(String) override | Устанавливает значение узла. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет всех дочерних узлов узла в указанный [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет узел в указанный [XmlWriter](../xmlwriter/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlCharacterData](../xmlcharacterdata/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
