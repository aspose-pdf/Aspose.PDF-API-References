---
title: "Метод System::Xml::XmlReaderSettings::get_NameTable"
linktitle: "get_NameTable"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlReaderSettings::get_NameTable. Возвращает XmlNameTable, используемый для атомизированных сравнений строк в C++."
type: docs
weight: 1500
url: /ru/cpp/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable method


Возвращает [XmlNameTable](../../xmlnametable/), используемый для атомизированных сравнений строк.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### ReturnValue

[XmlNameTable](../../xmlnametable/) который хранит все атомизированные строки, используемые всеми экземплярами [XmlReader](../../xmlreader/) , созданными с помощью этого объекта [XmlReaderSettings](../). По умолчанию это **nullptr**. Созданный экземпляр [XmlReader](../../xmlreader/) будет использовать новую пустую [NameTable](../../nametable/), если это значение равно **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
