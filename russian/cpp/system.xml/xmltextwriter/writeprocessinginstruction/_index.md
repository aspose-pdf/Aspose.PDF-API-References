---
title: "System::Xml::XmlTextWriter::WriteProcessingInstruction метод"
linktitle: "WriteProcessingInstruction"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextWriter::WriteProcessingInstruction метод. Записывает инструкцию обработки с пробелом между именем и текстом в следующем виде: <?name text?> в C++."
type: docs
weight: 3300
url: /ru/cpp/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction method


Записывает инструкцию обработки с пробелом между именем и текстом следующим образом: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя инструкции обработки. |
| text | String | [Text](../../../system.text/) для включения в инструкцию обработки. |
## Примечания



Этот метод используется для создания объявления XML после того, как уже был вызван [XmlTextWriter::WriteStartDocument](../writestartdocument/).
## См. также

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
