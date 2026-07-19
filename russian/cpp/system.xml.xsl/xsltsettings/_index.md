---
title: "System::Xml::Xsl::XsltSettings класс"
linktitle: "XsltSettings"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Xsl::XsltSettings класс. Указывает функции XSLT, которые поддерживаются во время выполнения XSLT‑таблицы стилей в C++."
type: docs
weight: 800
url: /ru/cpp/system.xml.xsl/xsltsettings/
---
## XsltSettings class


Указывает функции XSLT, которые следует поддерживать во время выполнения XSLT‑таблицы стилей.

```cpp
class XsltSettings : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [get_Default](./get_default/)() | Возвращает объект [XsltSettings](./) с настройками по умолчанию. Поддержка функции XSLT **document()** и встроенных блоков скриптов отключена. |
| [get_EnableDocumentFunction](./get_enabledocumentfunction/)() | Возвращает значение, указывающее, следует ли включить поддержку функции XSLT **document()**. |
| [get_EnableScript](./get_enablescript/)() | Возвращает значение, указывающее, следует ли включить поддержку встроенных блоков скриптов. |
| static [get_TrustedXslt](./get_trustedxslt/)() | Возвращает объект [XsltSettings](./), который включает поддержку функции XSLT **document()** и встроенных блоков скриптов. |
| [set_EnableDocumentFunction](./set_enabledocumentfunction/)(bool) | Устанавливает значение, указывающее, следует ли включить поддержку функции XSLT **document()**. |
| [set_EnableScript](./set_enablescript/)(bool) | Устанавливает значение, указывающее, следует ли включить поддержку встроенных блоков скриптов. |
| [XsltSettings](./xsltsettings/)() | Инициализирует новый экземпляр класса [XsltSettings](./) с настройками по умолчанию. |
| [XsltSettings](./xsltsettings/)(bool, bool) | Инициализирует новый экземпляр класса [XsltSettings](./) с указанными настройками. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
