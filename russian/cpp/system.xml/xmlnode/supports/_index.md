---
title: "System::Xml::XmlNode::Supports метод"
linktitle: "Supports"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNode::Supports метод. Проверяет, реализует ли DOM‑реализация конкретную возможность в C++."
type: docs
weight: 4400
url: /ru/cpp/system.xml/xmlnode/supports/
---
## XmlNode::Supports method


Проверяет, реализует ли реализация DOM конкретную возможность.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| функция | String | Имя пакета функции для тестирования. Это имя не чувствительно к регистру. |
| версия | String | Номер версии имени пакета для проверки. Если версия не указана (null), поддержка любой версии функции приводит к тому, что метод возвращает true. |

### ReturnValue

**true** if the feature is implemented in the specified version; otherwise, **false**.
## Примечания



В следующей таблице описаны комбинации, которые возвращают **true**. |||
|-|-|
| Функция | Версия |
| XML | 1.0 |
| XML | 2.0 |

## См. также

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
