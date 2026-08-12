---
title: "Класс System::Xml::XmlNodeReader"
linktitle: "XmlNodeReader"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlNodeReader. Представляет читатель, обеспечивающий быстрый, некешированный доступ только в прямом направлении к XML-данным в XmlNode на C++."
type: docs
weight: 2800
url: /ru/cpp/system.xml/xmlnodereader/
---
## XmlNodeReader class


Представляет читатель, обеспечивающий быстрый, некешированный доступ только в прямом направлении к XML-данным в [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() override | Изменяет [XmlNodeReader::get_ReadState](./get_readstate/) на [ReadState::Closed](../readstate/). |
| [get_AttributeCount](./get_attributecount/)() override | Возвращает количество атрибутов текущего узла. |
| [get_BaseURI](./get_baseuri/)() override | Возвращает базовый URI текущего узла. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Возвращает значение, указывающее, реализует ли [XmlNodeReader](./) методы чтения двоичного содержимого. |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Возвращает значение, указывающее, может ли этот читатель разбирать и разрешать сущности. |
| [get_Depth](./get_depth/)() override | Возвращает глубину текущего узла в XML-документе. |
| [get_EOF](./get_eof/)() override | Возвращает значение, указывающее, находится ли читатель в конце потока. |
| [get_HasAttributes](./get_hasattributes/)() override | Возвращает значение, указывающее, имеет ли текущий узел какие-либо атрибуты. |
| [get_HasValue](./get_hasvalue/)() override | Возвращает значение, указывающее, может ли текущий узел иметь значение [XmlNodeReader::get_Value](./get_value/). |
| [get_IsDefault](./get_isdefault/)() override | Возвращает значение, указывающее, является ли текущий узел атрибутом, сгенерированным из значения по умолчанию, определённого в DTD или схеме. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Возвращает значение, указывающее, является ли текущий узел пустым элементом (например, **<MyElement/>**). |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя текущего узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя текущего узла. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Возвращает URI пространства имён (как определено в спецификации W3C Namespace) узла, на котором находится читатель. |
| [get_NameTable](./get_nametable/)() override | Возвращает [XmlNameTable](../xmlnametable/), связанный с этой реализацией. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_Prefix](./get_prefix/)() override | Возвращает префикс пространства имён, связанный с текущим узлом. |
| [get_ReadState](./get_readstate/)() override | Возвращает состояние читателя. |
| [get_SchemaInfo](./get_schemainfo/)() override | Возвращает информацию схемы, назначенную текущему узлу. |
| [get_Value](./get_value/)() override | Возвращает текстовое значение текущего узла. |
| [get_XmlLang](./get_xmllang/)() override | Возвращает текущую область **xml:lang**. |
| [get_XmlSpace](./get_xmlspace/)() override | Возвращает текущую область действия **xml:space**. |
| [GetAttribute](./getattribute/)(String) override | Возвращает значение атрибута с указанным именем. |
| [GetAttribute](./getattribute/)(String, String) override | Возвращает значение атрибута с указанным локальным именем и URI пространства имён. |
| [GetAttribute](./getattribute/)(int32_t) override | Возвращает значение атрибута с указанным индексом. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Разрешает префикс пространства имён в области действия текущего элемента. |
| [MoveToAttribute](./movetoattribute/)(String) override | Переходит к атрибуту с указанным именем. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Переходит к атрибуту с указанным локальным именем и URI пространства имён. |
| [MoveToAttribute](./movetoattribute/)(int32_t) override | Переходит к атрибуту с указанным индексом. |
| [MoveToElement](./movetoelement/)() override | Переходит к элементу, содержащему текущий узел атрибута. |
| [MoveToFirstAttribute](./movetofirstattribute/)() override | Переходит к первому атрибуту. |
| [MoveToNextAttribute](./movetonextattribute/)() override | Переходит к следующему атрибуту. |
| [Read](./read/)() override | Читает следующий узел из потока. |
| [ReadAttributeValue](./readattributevalue/)() override | Разбирает значение атрибута в один или несколько узлов **[Text](../../system.text/)**, **EntityReference** или **EndEntity**. |
| [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Читает содержимое и возвращает двоичные байты, декодированные из Base64. |
| [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Читает содержимое и возвращает двоичные байты, декодированные из BinHex. |
| [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Читает элемент и декодирует содержимое Base64. |
| [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Читает элемент и декодирует содержимое BinHex. |
| [ReadString](./readstring/)() override | Читает содержимое элемента или текстового узла как строку. |
| [ResolveEntity](./resolveentity/)() override | Разрешает ссылку на сущность для узлов **EntityReference**. |
| [Skip](./skip/)() override | Пропускает дочерние узлы текущего узла. |
| [XmlNodeReader](./xmlnodereader/)(const SharedPtr\<XmlNode\>\&) | Создаёт экземпляр класса [XmlNodeReader](./), используя указанный [XmlNode](../xmlnode/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlReader](../xmlreader/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
