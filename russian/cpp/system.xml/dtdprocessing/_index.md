---
title: "Перечисление System::Xml::DtdProcessing"
linktitle: "DtdProcessing"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление System::Xml::DtdProcessing. Указывает варианты обработки DTD. Перечисление DtdProcessing используется классом XmlReaderSettings в C++."
type: docs
weight: 4700
url: /ru/cpp/system.xml/dtdprocessing/
---
## DtdProcessing enum


Указывает варианты обработки DTD. Перечисление [DtdProcessing](./) используется классом [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Prohibit | 0 | Указывает, что при встрече DTD генерируется [XmlException](../xmlexception/) с сообщением, что DTD запрещены. Это поведение по умолчанию. |
| Игнорировать | 1 | Вызывает игнорирование элемента DOCTYPE. Обработка DTD не происходит, и DTD/DOCTYPE теряется при выводе. |
| Разобрать | 2 | Используется для разбора DTD. |

## См. также

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
