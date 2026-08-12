---
title: "Класс System::Xml::XmlDocument"
linktitle: "XmlDocument"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlDocument. Представляет XML‑документ. Вы можете использовать этот класс для загрузки, проверки, редактирования, добавления и позиционирования XML в документе на C++."
type: docs
weight: 1400
url: /ru/cpp/system.xml/xmldocument/
---
## XmlDocument class


Представляет XML‑документ. Вы можете использовать этот класс для загрузки, проверки, редактирования, добавления и позиционирования XML в документе.

```cpp
class XmlDocument : public System::Xml::XmlNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. |
| [CreateAttribute](./createattribute/)(const String\&) | Создаёт [XmlAttribute](../xmlattribute/) с указанным именем. |
| [CreateAttribute](./createattribute/)(const String\&, const String\&) | Создаёт [XmlAttribute](../xmlattribute/) с указанным квалифицированным именем и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateAttribute](./createattribute/)(const String\&, const String\&, const String\&) | Создаёт [XmlAttribute](../xmlattribute/) с указанными [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/) и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateCDataSection](./createcdatasection/)(const String\&) | Создаёт [XmlCDataSection](../xmlcdatasection/) с указанными данными. |
| virtual [CreateComment](./createcomment/)(const String\&) | Создаёт [XmlComment](../xmlcomment/) с указанными данными. |
| virtual [CreateDocumentFragment](./createdocumentfragment/)() | Создаёт [XmlDocumentFragment](../xmldocumentfragment/). |
| virtual [CreateDocumentType](./createdocumenttype/)(const String\&, const String\&, const String\&, const String\&) | Возвращает новый объект [XmlDocumentType](../xmldocumenttype/). |
| [CreateElement](./createelement/)(const String\&) | Создаёт элемент с указанным именем. |
| [CreateElement](./createelement/)(const String\&, const String\&) | Создаёт [XmlElement](../xmlelement/) с квалифицированным именем и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateElement](./createelement/)(const String\&, const String\&, const String\&) | Создаёт элемент с указанными [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/) и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateEntityReference](./createentityreference/)(const String\&) | Создаёт [XmlEntityReference](../xmlentityreference/) с указанным именем. |
| [CreateNavigator](./createnavigator/)() override | Создаёт новый объект XPathNavigator для навигации по этому документу. |
| virtual [CreateNode](./createnode/)(XmlNodeType, const String\&, const String\&, const String\&) | Создаёт [XmlNode](../xmlnode/) с указанными [XmlNodeType](../xmlnodetype/), [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_Name](./get_name/) и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateNode](./createnode/)(const String\&, const String\&, const String\&) | Создаёт [XmlNode](../xmlnode/) с указанным типом узла, [XmlDocument::get_Name](./get_name/) и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateNode](./createnode/)(XmlNodeType, const String\&, const String\&) | Создаёт [XmlNode](../xmlnode/) с указанными [XmlNodeType](../xmlnodetype/), [XmlDocument::get_Name](./get_name/) и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateProcessingInstruction](./createprocessinginstruction/)(const String\&, const String\&) | Создаёт [XmlProcessingInstruction](../xmlprocessinginstruction/) с указанным именем и данными. |
| virtual [CreateSignificantWhitespace](./createsignificantwhitespace/)(const String\&) | Создаёт узел [XmlSignificantWhitespace](../xmlsignificantwhitespace/). |
| virtual [CreateTextNode](./createtextnode/)(const String\&) | Создаёт [XmlText](../xmltext/) с указанным текстом. |
| virtual [CreateWhitespace](./createwhitespace/)(const String\&) | Создаёт узел [XmlWhitespace](../xmlwhitespace/). |
| virtual [CreateXmlDeclaration](./createxmldeclaration/)(const String\&, const String\&, const String\&) | Создаёт узел [XmlDeclaration](../xmldeclaration/) с указанными значениями. |
| [get_BaseURI](./get_baseuri/)() override | Возвращает базовый URI текущего узла. |
| [get_DocumentElement](./get_documentelement/)() | Возвращает корневой [XmlElement](../xmlelement/) документа. |
| virtual [get_DocumentType](./get_documenttype/)() | Возвращает узел, содержащий объявление DOCTYPE. |
| [get_Implementation](./get_implementation/)() | Возвращает объект [XmlImplementation](../xmlimplementation/) текущего документа. |
| [get_InnerXml](./get_innerxml/)() override | Возвращает разметку, представляющую дочерние элементы текущего узла. |
| [get_IsReadOnly](./get_isreadonly/)() override | Возвращает значение, указывающее, является ли текущий узел только для чтения. |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя узла. |
| [get_NameTable](./get_nametable/)() | Возвращает [XmlNameTable](../xmlnametable/), связанный с этой реализацией. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Возвращает [XmlDocument](./), к которому принадлежит текущий узел. |
| [get_PreserveWhitespace](./get_preservewhitespace/)() | Возвращает значение, указывающее, сохранять ли пробелы в содержимом элемента. |
| [get_SchemaInfo](./get_schemainfo/)() override | Возвращает Post-Schema-Validation-Infoset (PSVI) узла. |
| [get_Schemas](./get_schemas/)() | Возвращает объект XmlSchemaSet, связанный с этим [XmlDocument](./). |
| virtual [GetElementById](./getelementbyid/)(String) | Возвращает [XmlElement](../xmlelement/) с указанным ID. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String) | Возвращает [XmlNodeList](../xmlnodelist/), содержащий список всех дочерних элементов, соответствующих указанному имени. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String, String) | Возвращает [XmlNodeList](../xmlnodelist/), содержащий список всех дочерних элементов, которые соответствуют указанным [XmlDocument::get_LocalName](./get_localname/) и [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [ImportNode](./importnode/)(SharedPtr\<XmlNode\>, bool) | Импортирует узел из другого документа в текущий документ. |
| virtual [Load](./load/)(String) | Загружает XML‑документ из указанного URL. |
| virtual [Load](./load/)(SharedPtr\<IO::Stream\>) | Загружает XML‑документ из указанного потока. |
| virtual [Load](./load/)(SharedPtr\<IO::TextReader\>) | Загружает XML‑документ из указанного TextReader. |
| virtual [Load](./load/)(SharedPtr\<XmlReader\>) | Загружает XML‑документ из указанного [XmlReader](../xmlreader/). |
| virtual [LoadXml](./loadxml/)(String) | Загружает XML‑документ из указанной строки. |
| virtual [ReadNode](./readnode/)(SharedPtr\<XmlReader\>) | Создаёт объект [XmlNode](../xmlnode/) на основе информации из [XmlReader](../xmlreader/). Читатель должен быть позиционирован на узле или атрибуте. |
| virtual [Save](./save/)(String) | Сохраняет XML‑документ в указанный файл. Если указанный файл существует, этот метод перезапишет его. |
| virtual [Save](./save/)(SharedPtr\<IO::Stream\>) | Сохраняет XML‑документ в указанный поток. |
| virtual [Save](./save/)(SharedPtr\<IO::TextWriter\>) | Сохраняет XML‑документ в указанный TextWriter. |
| virtual [Save](./save/)(SharedPtr\<XmlWriter\>) | Сохраняет XML‑документ в указанный [XmlWriter](../xmlwriter/). |
| [set_InnerText](./set_innertext/)(String) override | Всегда генерирует InvalidOperationException. |
| [set_InnerXml](./set_innerxml/)(String) override | Устанавливает разметку, представляющую дочерние элементы текущего узла. |
| [set_PreserveWhitespace](./set_preservewhitespace/)(bool) | Устанавливает значение, указывающее, сохранять ли пробелы в содержимом элемента. |
| [set_Schemas](./set_schemas/)(const SharedPtr\<Schema::XmlSchemaSet\>\&) | Устанавливает объект XmlSchemaSet, связанный с этим [XmlDocument](./). |
| virtual [set_XmlResolver](./set_xmlresolver/)(SharedPtr\<System::Xml::XmlResolver\>) | Устанавливает [XmlResolver](../xmlresolver/), используемый для разрешения внешних ресурсов. |
| [Validate](./validate/)(Schema::ValidationEventHandler) | Проверяет [XmlDocument](./) на соответствие схемам XML [Schema](../../system.xml.schema/) Definition Language (XSD), содержащимся в списке [XmlDocument::get_Schemas](./get_schemas/). |
| [Validate](./validate/)(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) | Проверяет указанный объект [XmlNode](../xmlnode/) на соответствие схемам XML [Schema](../../system.xml.schema/) Definition Language (XSD), находящимся в списке [XmlDocument::get_Schemas](./get_schemas/). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет всех дочерних узлов узла [XmlDocument](./) в указанный [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет узел [XmlDocument](./) в указанный [XmlWriter](../xmlwriter/). |
| [XmlDocument](./xmldocument/)() | Инициализирует новый экземпляр класса [XmlDocument](./). |
| [XmlDocument](./xmldocument/)(const SharedPtr\<XmlNameTable\>\&) | Инициализирует новый экземпляр класса [XmlDocument](./) с указанным [XmlNameTable](../xmlnametable/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
