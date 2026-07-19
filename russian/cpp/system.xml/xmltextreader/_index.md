---
title: "Класс System::Xml::XmlTextReader"
linktitle: "XmlTextReader"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlTextReader. Представляет читатель, обеспечивающий быстрый, некешированный, только прямой доступ к XML‑данным в C++."
type: docs
weight: 3900
url: /ru/cpp/system.xml/xmltextreader/
---
## XmlTextReader class


Представляет читатель, обеспечивающий быстрый, некешированный последовательный доступ к XML‑данным.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() override | Изменяет [XmlReader::get_ReadState](../xmlreader/get_readstate/) на **Closed**. |
| [get_AttributeCount](./get_attributecount/)() override | Возвращает количество атрибутов текущего узла. |
| [get_BaseURI](./get_baseuri/)() override | Возвращает базовый URI текущего узла. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Возвращает значение, указывающее, реализует ли [XmlTextReader](./) методы чтения бинарного содержимого. |
| [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Возвращает значение, указывающее, реализует ли [XmlTextReader](./) метод [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Возвращает значение, указывающее, может ли этот читатель разбирать и разрешать сущности. |
| [get_Depth](./get_depth/)() override | Возвращает глубину текущего узла в XML-документе. |
| [get_DtdProcessing](./get_dtdprocessing/)() | Возвращает перечисление [DtdProcessing](../dtdprocessing/). |
| [get_Encoding](./get_encoding/)() | Возвращает кодировку документа. |
| [get_EntityHandling](./get_entityhandling/)() | Возвращает значение, определяющее, как читатель обрабатывает сущности. |
| [get_EOF](./get_eof/)() override | Возвращает значение, указывающее, находится ли читатель в конце потока. |
| [get_HasValue](./get_hasvalue/)() override | Возвращает значение, указывающее, может ли текущий узел иметь [XmlTextReader::get_Value](./get_value/) отличное от [String::Empty](../../system/string/empty/). |
| [get_IsDefault](./get_isdefault/)() override | Возвращает значение, указывающее, является ли текущий узел атрибутом, сгенерированным из значения по умолчанию, определённого в DTD или схеме. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Возвращает значение, указывающее, является ли текущий узел пустым элементом (например, **<MyElement/>**). |
| [get_LineNumber](./get_linenumber/)() override | Возвращает текущий номер строки. |
| [get_LinePosition](./get_lineposition/)() override | Возвращает текущую позицию в строке. |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя текущего узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя текущего узла. |
| [get_Namespaces](./get_namespaces/)() | Возвращает значение, указывающее, следует ли поддерживать пространства имён. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Возвращает URI пространства имён (как определено в спецификации W3C Namespace) узла, на котором находится читатель. |
| [get_NameTable](./get_nametable/)() override | Возвращает [XmlNameTable](../xmlnametable/), связанный с этой реализацией. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_Normalization](./get_normalization/)() | Возвращает значение, указывающее, следует ли нормализовать пробельные символы и значения атрибутов. |
| [get_Prefix](./get_prefix/)() override | Возвращает префикс пространства имён, связанный с текущим узлом. |
| [get_ProhibitDtd](./get_prohibitdtd/)() | Возвращает значение, указывающее, разрешать ли обработку DTD. |
| [get_QuoteChar](./get_quotechar/)() override | Возвращает символ кавычки, используемый для заключения значения узла атрибута. |
| [get_ReadState](./get_readstate/)() override | Возвращает состояние читателя. |
| [get_Value](./get_value/)() override | Возвращает текстовое значение текущего узла. |
| [get_WhitespaceHandling](./get_whitespacehandling/)() | Возвращает значение, указывающее, как обрабатываются пробелы. |
| [get_XmlLang](./get_xmllang/)() override | Возвращает текущую область **xml:lang**. |
| [get_XmlSpace](./get_xmlspace/)() override | Возвращает текущую область действия **xml:space**. |
| [GetAttribute](./getattribute/)(String) override | Возвращает значение атрибута с указанным именем. |
| [GetAttribute](./getattribute/)(String, String) override | Возвращает значение атрибута с указанным локальным именем и URI пространства имён. |
| [GetAttribute](./getattribute/)(int32_t) override | Возвращает значение атрибута с указанным индексом. |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Возвращает коллекцию, содержащую все текущие области видимости пространств имён. |
| [GetRemainder](./getremainder/)() | Возвращает оставшуюся часть буферизованного XML. |
| [HasLineInfo](./haslineinfo/)() override | Возвращает значение, указывающее, может ли класс возвращать информацию о строках. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Разрешает префикс пространства имён в области действия текущего элемента. |
| [MoveToAttribute](./movetoattribute/)(String) override | Переходит к атрибуту с указанным именем. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Переходит к атрибуту с указанным локальным именем и URI пространства имён. |
| [MoveToAttribute](./movetoattribute/)(int32_t) override | Переходит к атрибуту с указанным индексом. |
| [MoveToElement](./movetoelement/)() override | Переходит к элементу, содержащему текущий узел атрибута. |
| [MoveToFirstAttribute](./movetofirstattribute/)() override | Переходит к первому атрибуту. |
| [MoveToNextAttribute](./movetonextattribute/)() override | Переходит к следующему атрибуту. |
| [Read](./read/)() override | Читает следующий узел из потока. |
| [ReadAttributeValue](./readattributevalue/)() override | Разбирает значение атрибута в один или несколько узлов **[Text](../../system.text/)**, **EntityReference** или **EndEntity**. |
| [ReadBase64](./readbase64/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Декодирует Base64 и возвращает декодированные двоичные байты. |
| [ReadBinHex](./readbinhex/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Декодирует **BinHex** и возвращает декодированные двоичные байты. |
| [ReadChars](./readchars/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) | Считывает текстовое содержимое элемента в буфер символов. Этот метод предназначен для последовательного чтения больших потоков встроенного текста. |
| [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Считывает содержимое и возвращает декодированные из **Base64** двоичные байты. |
| [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Считывает содержимое и возвращает декодированные из **BinHex** двоичные байты. |
| [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Читает элемент и декодирует содержимое Base64. |
| [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Считывает элемент и декодирует содержимое **BinHex**. |
| [ReadString](./readstring/)() override | Считывает содержимое элемента или текстового узла как строку. |
| [ResetState](./resetstate/)() | Сбрасывает состояние считывателя к [ReadState::Initial](../readstate/). |
| [ResolveEntity](./resolveentity/)() override | Разрешает ссылку на сущность для узлов **EntityReference**. |
| [set_DtdProcessing](./set_dtdprocessing/)(System::Xml::DtdProcessing) | Устанавливает перечисление [DtdProcessing](../dtdprocessing/). |
| [set_EntityHandling](./set_entityhandling/)(System::Xml::EntityHandling) | Устанавливает значение, определяющее, как считыватель обрабатывает сущности. |
| [set_Namespaces](./set_namespaces/)(bool) | Устанавливает значение, указывающее, следует ли поддерживать пространства имён. |
| [set_Normalization](./set_normalization/)(bool) | Устанавливает значение, указывающее, следует ли нормализовать пробелы и значения атрибутов. |
| [set_ProhibitDtd](./set_prohibitdtd/)(bool) | Устанавливает значение, указывающее, разрешать ли обработку DTD. |
| [set_WhitespaceHandling](./set_whitespacehandling/)(System::Xml::WhitespaceHandling) | Устанавливает значение, определяющее, как обрабатываются пробелы. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Устанавливает [XmlResolver](../xmlresolver/), используемый для разрешения ссылок DTD. |
| [Skip](./skip/)() override | Пропускает дочерние узлы текущего узла. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным потоком. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::Stream\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным URL и потоком. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным потоком и [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным URL, потоком и [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::TextReader\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным TextReader. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::TextReader\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным URL и TextReader. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным TextReader и [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным URL, TextReader и [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным потоком, [XmlNodeType](../xmlnodetype/) и [XmlParserContext](../xmlparsercontext/). |
| [XmlTextReader](./xmltextreader/)(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанной строкой, [XmlNodeType](../xmlnodetype/) и [XmlParserContext](../xmlparsercontext/). |
| [XmlTextReader](./xmltextreader/)(const String\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным файлом. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<XmlNameTable\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным файлом и [XmlNameTable](../xmlnametable/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Рекомендуется использовать класс [XmlReader](../xmlreader/) вместо этого.

Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlReader](../xmlreader/)
* Class [IXmlLineInfo](../ixmllineinfo/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
