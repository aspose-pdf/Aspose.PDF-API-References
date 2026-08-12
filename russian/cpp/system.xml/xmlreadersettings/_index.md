---
title: "System::Xml::XmlReaderSettings класс"
linktitle: "XmlReaderSettings"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReaderSettings класс. Указывает набор функций, поддерживаемых объектом XmlReader, созданным методом XmlReader::Create в C++."
type: docs
weight: 3400
url: /ru/cpp/system.xml/xmlreadersettings/
---
## XmlReaderSettings class


Указывает набор функций, поддерживаемых объектом [XmlReader](../xmlreader/), созданным методом [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [CheckReadOnly](./checkreadonly/)(const String\&) |  |
| [Clone](./clone/)() | Создает копию экземпляра [XmlReaderSettings](./). |
| [get_CheckCharacters](./get_checkcharacters/)() | Возвращает значение, указывающее, выполнять ли проверку символов. |
| [get_CloseInput](./get_closeinput/)() | Возвращает значение, указывающее, следует ли закрывать базовый поток или TextReader при закрытии считывателя. |
| [get_ConformanceLevel](./get_conformancelevel/)() | Возвращает уровень соответствия, которому будет соответствовать [XmlReader](../xmlreader/). |
| [get_DtdProcessing](./get_dtdprocessing/)() | Возвращает значение, определяющее обработку DTD. |
| [get_IgnoreComments](./get_ignorecomments/)() | Возвращает значение, указывающее, игнорировать ли комментарии. |
| [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Возвращает значение, указывающее, игнорировать ли инструкции обработки. |
| [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Возвращает значение, указывающее, игнорировать ли незначительные пробелы. |
| [get_LineNumberOffset](./get_linenumberoffset/)() | Возвращает смещение номера строки объекта [XmlReader](../xmlreader/). |
| [get_LinePositionOffset](./get_linepositionoffset/)() | Возвращает смещение позиции строки объекта [XmlReader](../xmlreader/). |
| [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Возвращает значение, указывающее максимальное допустимое количество символов в документе, получаемое в результате расширения сущностей. |
| [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Возвращает значение, указывающее максимальное допустимое количество символов в XML‑документе. Нулевое (0) значение означает отсутствие ограничений размера XML‑документа. Ненулевое значение задаёт максимальный размер в символах. |
| [get_NameTable](./get_nametable/)() | Возвращает [XmlNameTable](../xmlnametable/), используемый для атомизированных сравнений строк. |
| [get_ProhibitDtd](./get_prohibitdtd/)() | Возвращает значение, указывающее, запрещать ли обработку определений типа документа (DTD). |
| [get_Schemas](./get_schemas/)() | Возвращает XmlSchemaSet, используемый при выполнении проверки схемы. |
| [get_ValidationFlags](./get_validationflags/)() | Возвращает значение, указывающее настройки проверки схемы. Этот параметр применяется к объектам [XmlReader](../xmlreader/), которые проверяют схемы (значение [XmlReaderSettings::get_ValidationType](./get_validationtype/) равно [ValidationType::Schema](../validationtype/)). |
| [get_ValidationType](./get_validationtype/)() | Возвращает значение, указывающее, будет ли [XmlReader](../xmlreader/) выполнять проверку или назначение типа при чтении. |
| [Reset](./reset/)() | Сбрасывает члены класса настроек к их значениям по умолчанию. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | Устанавливает значение, указывающее, выполнять ли проверку символов. |
| [set_CloseInput](./set_closeinput/)(bool) | Устанавливает значение, указывающее, следует ли закрывать базовый поток или TextReader при закрытии считывателя. |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | Устанавливает уровень соответствия, которому будет соответствовать [XmlReader](../xmlreader/). |
| [set_DtdProcessing](./set_dtdprocessing/)(System::Xml::DtdProcessing) | Устанавливает значение, определяющее обработку DTD. |
| [set_IgnoreComments](./set_ignorecomments/)(bool) | Устанавливает значение, указывающее, игнорировать ли комментарии. |
| [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(bool) | Устанавливает значение, указывающее, игнорировать ли инструкции обработки. |
| [set_IgnoreWhitespace](./set_ignorewhitespace/)(bool) | Устанавливает значение, указывающее, игнорировать ли незначительные пробелы. |
| [set_LineNumberOffset](./set_linenumberoffset/)(int32_t) | Устанавливает смещение номера строки объекта [XmlReader](../xmlreader/). |
| [set_LinePositionOffset](./set_linepositionoffset/)(int32_t) | Устанавливает смещение позиции строки объекта [XmlReader](../xmlreader/). |
| [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(int64_t) | Устанавливает значение, указывающее максимальное допустимое количество символов в документе, получаемое при раскрытии сущностей. |
| [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(int64_t) | Устанавливает значение, указывающее максимальное допустимое количество символов в XML‑документе. Нулевое (0) значение означает отсутствие ограничений размера XML‑документа. Ненулевое значение задаёт максимальный размер в символах. |
| [set_NameTable](./set_nametable/)(const SharedPtr\<XmlNameTable\>\&) | Устанавливает [XmlNameTable](../xmlnametable/), используемый для атомарных сравнений строк. |
| [set_ProhibitDtd](./set_prohibitdtd/)(bool) | Устанавливает значение, указывающее, следует ли запрещать обработку определений типов документов (DTD). |
| [set_Schemas](./set_schemas/)(const SharedPtr\<Schema::XmlSchemaSet\>\&) | Устанавливает XmlSchemaSet, используемый при выполнении проверки схемы. |
| [set_ValidationFlags](./set_validationflags/)(Schema::XmlSchemaValidationFlags) | Устанавливает значение, указывающее параметры проверки схемы. Этот параметр применяется к объектам [XmlReader](../xmlreader/), которые проверяют схемы (значение [XmlReaderSettings::get_ValidationType](./get_validationtype/) равно [ValidationType::Schema](../validationtype/)). |
| [set_ValidationType](./set_validationtype/)(System::Xml::ValidationType) | Устанавливает значение, указывающее, будет ли [XmlReader](../xmlreader/) выполнять проверку или назначение типа при чтении. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Устанавливает [XmlResolver](../xmlresolver/), используемый для доступа к внешним документам. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Добавляет обработчик события, возникающего, когда считыватель обнаруживает ошибки проверки. |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Удаляет обработчик события, возникающего, когда считыватель обнаруживает ошибки проверки. |
| [XmlReaderSettings](./xmlreadersettings/)() | Инициализирует новый экземпляр класса [XmlReaderSettings](./). |
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
