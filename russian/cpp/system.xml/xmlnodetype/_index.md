---
title: "System::Xml::XmlNodeType перечисление"
linktitle: "XmlNodeType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeType перечисление. Указывает тип узла в C++."
type: docs
weight: 6200
url: /ru/cpp/system.xml/xmlnodetype/
---
## XmlNodeType enum


Указывает тип узла.

```cpp
enum class XmlNodeType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Это возвращается [XmlReader](../xmlreader/), если метод **Read** не был вызван. |
| Элемент | 1 | Элемент (например, **<item>**). |
| Атрибут | 2 | Атрибут (например, **id='123'**). |
| Text | 3 | Текстовое содержимое узла. Узел [XmlNodeType::Text](./) не может иметь дочерних узлов. Он может появляться как дочерний узел узлов [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) и [XmlNodeType::EntityReference](./). |
| CDATA | 4 | Раздел CDATA (например, **my escaped text**). |
| EntityReference | 5 | Ссылка на сущность (например, **&num;**). |
| Entity | 6 | Объявление сущности (например, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Инструкция обработки (например, **<?pi test?>**). |
| Comment | 8 | Комментарий (например, ****). |
| Document | 9 | Объект документа, который, будучи корнем дерева документа, предоставляет доступ ко всему XML‑документу. |
| DocumentType | 10 | Объявление типа документа, обозначаемое следующим тегом (например, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Фрагмент документа. |
| Notation | 12 | Нотация в объявлении типа документа (например, **<!NOTATION...>**). |
| Whitespace | 13 | Пробелы между разметкой. |
| SignificantWhitespace | 14 | Пробелы между разметкой в модели смешанного содержимого или пробелы в пределах области **xml:space=\"preserve\"**. |
| EndElement | 15 | Тег закрывающего элемента (например, ****). |
| EndEntity | 16 | Возвращается, когда [XmlReader](../xmlreader/) доходит до конца замены сущности в результате вызова [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | Объявление XML (например, **<?xml version='1.0'?>**). Узел [XmlNodeType::XmlDeclaration](./) должен быть первым узлом в документе. Он не может иметь дочерних элементов. Он является дочерним узлом узла [XmlNodeType::Document](./). Он может иметь атрибуты, предоставляющие информацию о версии и кодировке. |

## См. также

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
