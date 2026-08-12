---
title: "System::Xml::XmlWriterSettings class"
linktitle: "XmlWriterSettings"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWriterSettings class. Указывает набор функций, поддерживаемых объектом XmlWriter, созданным методом XmlWriter::Create в C++."
type: docs
weight: 4500
url: /ru/cpp/system.xml/xmlwritersettings/
---
## XmlWriterSettings class


Указывает набор функций, поддерживаемых объектом [XmlWriter](../xmlwriter/), созданным методом [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() | Создаёт копию экземпляра [XmlWriterSettings](./). |
| [get_CheckCharacters](./get_checkcharacters/)() | Возвращает значение, указывающее, должен ли XML‑писатель проверять, что все символы в документе соответствуют разделу "2.2 Characters" W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| [get_CloseOutput](./get_closeoutput/)() | Возвращает значение, указывающее, должен ли [XmlWriter](../xmlwriter/) также закрывать базовый поток или TextWriter при вызове метода [XmlWriter::Close](../xmlwriter/close/). |
| [get_ConformanceLevel](./get_conformancelevel/)() | Возвращает уровень соответствия, который XML‑писатель проверяет в выводимом XML. |
| [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Возвращает значение, указывающее, не экранирует ли [XmlWriter](../xmlwriter/) атрибуты URI. |
| [get_Encoding](./get_encoding/)() | Возвращает тип используемой текстовой кодировки. |
| [get_Indent](./get_indent/)() | Возвращает значение, указывающее, следует ли делать отступы у элементов. |
| [get_IndentChars](./get_indentchars/)() | Возвращает строку символов, используемую для отступов. Этот параметр применяется, когда значение [XmlWriterSettings::set_Indent](./set_indent/) установлено в **true**. |
| [get_NamespaceHandling](./get_namespacehandling/)() | Возвращает значение, указывающее, должен ли [XmlWriter](../xmlwriter/) удалять дублирующие объявления пространств имён при записи XML‑содержимого. Поведение по умолчанию заключается в том, что писатель выводит все объявления пространств имён, присутствующие в его разрешателе пространств имён. |
| [get_NewLineChars](./get_newlinechars/)() | Возвращает строку символов, используемую для разрывов строк. |
| [get_NewLineHandling](./get_newlinehandling/)() | Возвращает значение, указывающее, следует ли нормализовать разрывы строк в выводе. |
| [get_NewLineOnAttributes](./get_newlineonattributes/)() | Возвращает значение, указывающее, следует ли записывать атрибуты на новой строке. |
| [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Возвращает значение, указывающее, следует ли опустить объявление XML. |
| [get_OutputMethod](./get_outputmethod/)() | Возвращает метод, используемый для сериализации вывода [XmlWriter](../xmlwriter/). |
| [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Возвращает значение, указывающее, будет ли [XmlWriter](../xmlwriter/) добавлять закрывающие теги ко всем незакрытым тегам элементов при вызове метода [XmlWriter::Close](../xmlwriter/close/). |
| [Reset](./reset/)() | Сбрасывает члены класса настроек к их значениям по умолчанию. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | Устанавливает значение, указывающее, должен ли XML‑writer проверять, что все символы в документе соответствуют разделу \"2.2 Characters\" рекомендации W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| [set_CloseOutput](./set_closeoutput/)(bool) | Устанавливает значение, указывающее, должен ли [XmlWriter](../xmlwriter/) также закрывать базовый поток или TextWriter при вызове метода [XmlWriter::Close](../xmlwriter/close/). |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | Устанавливает уровень соответствия, который XML‑writer проверяет в выводе XML. |
| [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(bool) | Устанавливает значение, указывающее, не экранирует ли [XmlWriter](../xmlwriter/) атрибуты URI. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<System::Text::Encoding\>\&) | Устанавливает тип используемой кодировки текста. |
| [set_Indent](./set_indent/)(bool) | Устанавливает значение, указывающее, следует ли делать отступы у элементов. |
| [set_IndentChars](./set_indentchars/)(const String\&) | Устанавливает строку символов, используемую при отступах. Этот параметр используется, когда значение [XmlWriterSettings::set_Indent](./set_indent/) установлено в **true**. |
| [set_NamespaceHandling](./set_namespacehandling/)(System::Xml::NamespaceHandling) | Устанавливает значение, указывающее, должен ли [XmlWriter](../xmlwriter/) удалять дублирующие объявления пространств имён при записи XML‑содержимого. Поведение по умолчанию заключается в том, что writer выводит все объявления пространств имён, присутствующие в разрешателе пространств имён writer'а. |
| [set_NewLineChars](./set_newlinechars/)(const String\&) | Устанавливает строку символов, используемую для разрывов строк. |
| [set_NewLineHandling](./set_newlinehandling/)(System::Xml::NewLineHandling) | Устанавливает значение, указывающее, следует ли нормализовать разрывы строк в выводе. |
| [set_NewLineOnAttributes](./set_newlineonattributes/)(bool) | Устанавливает значение, указывающее, следует ли записывать атрибуты на новой строке. |
| [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(bool) | Устанавливает значение, указывающее, следует ли опустить объявление XML. |
| [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(bool) | Устанавливает значение, указывающее, будет ли [XmlWriter](../xmlwriter/) добавлять закрывающие теги ко всем незакрытым тегам элементов при вызове метода [XmlWriter::Close](../xmlwriter/close/). |
| [XmlWriterSettings](./xmlwritersettings/)() | Инициализирует новый экземпляр класса [XmlWriterSettings](./). |
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
