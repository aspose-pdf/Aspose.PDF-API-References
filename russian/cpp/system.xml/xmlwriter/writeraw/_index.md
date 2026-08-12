---
title: "System::Xml::XmlWriter::WriteRaw метод"
linktitle: "WriteRaw"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWriter::WriteRaw метод. При переопределении в производном классе записывает необработанную разметку вручную из буфера символов в C++."
type: docs
weight: 2900
url: /ru/cpp/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) method


При переопределении в производном классе вручную записывает необработанную разметку из буфера символов.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | ArrayPtr\<char16_t\> | Массив символов, содержащий текст для записи. |
| индекс | int32_t | Позиция в буфере, указывающая начало текста для записи. |
| count | int32_t | Количество символов для записи. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteRaw(const String\&) method


При переопределении в производном классе вручную записывает необработанную разметку из строки.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const String\& | [String](../../../system/string/) содержащий текст для записи. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
