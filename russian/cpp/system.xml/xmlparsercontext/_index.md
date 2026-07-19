---
title: "Класс System::Xml::XmlParserContext"
linktitle: "XmlParserContext"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlParserContext. Предоставляет всю контекстную информацию, необходимую XmlReader для разбора XML‑фрагмента в C++."
type: docs
weight: 3000
url: /ru/cpp/system.xml/xmlparsercontext/
---
## XmlParserContext class


Предоставляет всю контекстную информацию, необходимую [XmlReader](../xmlreader/) для разбора XML‑фрагмента.

```cpp
class XmlParserContext : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BaseURI](./get_baseuri/)() | Возвращает базовый URI. |
| [get_DocTypeName](./get_doctypename/)() | Возвращает имя объявления типа документа. |
| [get_Encoding](./get_encoding/)() | Возвращает тип кодировки. |
| [get_InternalSubset](./get_internalsubset/)() | Возвращает внутренний набор DTD. |
| [get_NamespaceManager](./get_namespacemanager/)() | Возвращает [XmlNamespaceManager](../xmlnamespacemanager/). |
| [get_NameTable](./get_nametable/)() | Возвращает [XmlNameTable](../xmlnametable/), используемый для атомизации строк. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../xmlnametable/). |
| [get_PublicId](./get_publicid/)() | Возвращает публичный идентификатор. |
| [get_SystemId](./get_systemid/)() | Возвращает системный идентификатор. |
| [get_XmlLang](./get_xmllang/)() | Возвращает текущую область **xml:lang**. |
| [get_XmlSpace](./get_xmlspace/)() | Возвращает текущую область действия **xml:space**. |
| [set_BaseURI](./set_baseuri/)(const String\&) | Устанавливает базовый URI. |
| [set_DocTypeName](./set_doctypename/)(const String\&) | Устанавливает имя объявления типа документа. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<System::Text::Encoding\>\&) | Устанавливает тип кодировки. |
| [set_InternalSubset](./set_internalsubset/)(const String\&) | Устанавливает внутренний набор DTD. |
| [set_NamespaceManager](./set_namespacemanager/)(const SharedPtr\<XmlNamespaceManager\>\&) | Устанавливает [XmlNamespaceManager](../xmlnamespacemanager/). |
| [set_NameTable](./set_nametable/)(const SharedPtr\<XmlNameTable\>\&) | Устанавливает [XmlNameTable](../xmlnametable/), используемый для атомизации строк. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../xmlnametable/). |
| [set_PublicId](./set_publicid/)(const String\&) | Устанавливает публичный идентификатор. |
| [set_SystemId](./set_systemid/)(const String\&) | Устанавливает системный идентификатор. |
| [set_XmlLang](./set_xmllang/)(const String\&) | Устанавливает текущую область действия **xml:lang**. |
| [set_XmlSpace](./set_xmlspace/)(System::Xml::XmlSpace) | Устанавливает текущую область действия **xml:space**. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) | Инициализирует новый экземпляр класса [XmlParserContext](./) с указанными [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), значениями **xml:lang** и **xml:space**. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) | Инициализирует новый экземпляр класса [XmlParserContext](./) с указанными [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, **xml:space** и кодировкой. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) | Инициализирует новый экземпляр класса [XmlParserContext](./) с указанными [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), базовым URI, значениями **xml:lang**, **xml:space** и типом документа. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) | Инициализирует новый экземпляр класса [XmlParserContext](./) с указанными [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), базовым URI, **xml:lang**, **xml:space**, кодировкой и типом документа. |
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
