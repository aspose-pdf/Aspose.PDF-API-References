---
title: "enum System::Xml::ConformanceLevel"
linktitle: "ConformanceLevel"
second_title: "Справочник API Aspose.PDF для C++"
description: "enum System::Xml::ConformanceLevel. Указывает степень проверки ввода или вывода, которую выполняют объекты XmlReader и XmlWriter в C++."
type: docs
weight: 4600
url: /ru/cpp/system.xml/conformancelevel/
---
## ConformanceLevel enum


Указывает степень проверки ввода или вывода, которую выполняют объекты [XmlReader](../xmlreader/) и [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | 0 | Объект [XmlReader](../xmlreader/) или [XmlWriter](../xmlwriter/) автоматически определяет, следует ли выполнять проверку на уровне документа или фрагмента, и выполняет соответствующую проверку. Если вы оборачиваете другой объект [XmlReader](../xmlreader/) или [XmlWriter](../xmlwriter/), внешний объект не выполняет дополнительную проверку соответствия. Проверка соответствия передаётся базовому объекту. |
| Fragment | 1 | Данные XML являются [правильно сформированным фрагментом XML](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), как определено W3C. Этот уровень соответствия представляет XML‑документ, который может не иметь корневого элемента, но в остальном правильно сформирован. Этот уровень проверки гарантирует, что поток, читаемый или записываемый, может быть обработан любым процессором как [внешняя разобранная сущность XML 1.0](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | Данные XML соответствуют правилам правильно сформированного [документа XML 1.0](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed), как определено W3C. Этот уровень проверки гарантирует, что поток, читаемый или записываемый, может быть обработан любым процессором как [документ XML 1.0](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## См. также

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
