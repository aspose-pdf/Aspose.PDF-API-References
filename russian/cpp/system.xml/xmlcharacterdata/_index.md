---
title: "System::Xml::XmlCharacterData класс"
linktitle: "XmlCharacterData"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlCharacterData класс. Предоставляет методы манипуляции текстом, которые используются несколькими классами в C++."
type: docs
weight: 900
url: /ru/cpp/system.xml/xmlcharacterdata/
---
## XmlCharacterData class


Предоставляет методы манипуляции текстом, используемые несколькими классами.

```cpp
class XmlCharacterData : public System::Xml::XmlLinkedNode
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [AppendData](./appenddata/)(String) | Добавляет указанную строку в конец символьных данных узла. |
| virtual [DeleteData](./deletedata/)(int32_t, int32_t) | Удаляет диапазон символов из узла. |
| virtual [get_Data](./get_data/)() | Возвращает данные узла. |
| [get_InnerText](./get_innertext/)() override | Возвращает объединённые значения узла и всех его дочерних узлов. |
| virtual [get_Length](./get_length/)() | Возвращает длину данных в символах. |
| [get_Value](./get_value/)() override | Возвращает значение узла. |
| virtual [InsertData](./insertdata/)(int32_t, String) | Вставляет указанную строку в указанную позицию символов. |
| virtual [ReplaceData](./replacedata/)(int32_t, int32_t, String) | Заменяет указанное количество символов, начиная с указанного смещения, указанной строкой. |
| virtual [set_Data](./set_data/)(String) | Устанавливает данные узла. |
| [set_InnerText](./set_innertext/)(String) override | Устанавливает объединённые значения узла и всех его дочерних узлов. |
| [set_Value](./set_value/)(String) override | Устанавливает значение узла. |
| virtual [Substring](./substring/)(int32_t, int32_t) | Получает подстроку полного текста из указанного диапазона. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
