---
title: "System::Xml::XmlWriter::WriteProcessingInstruction метод"
linktitle: "WriteProcessingInstruction"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWriter::WriteProcessingInstruction метод. При переопределении в производном классе записывает инструкцию обработки с пробелом между именем и текстом следующим образом: <?name text?> в C++."
type: docs
weight: 2700
url: /ru/cpp/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction method


При переопределении в производном классе записывает инструкцию обработки с пробелом между именем и текстом следующим образом: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя инструкции обработки. |
| text | String | Текст, включаемый в инструкцию обработки. |
## Примечания



Этот метод используется для создания декларации XML после того, как уже был вызван [XmlWriter::WriteStartDocument](../writestartdocument/).
## См. также

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
