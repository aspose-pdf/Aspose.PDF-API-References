---
title: "Метод System::Xml::XmlReader::get_IsEmptyElement"
linktitle: "get_IsEmptyElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlReader::get_IsEmptyElement. При переопределении в производном классе возвращает значение, указывающее, является ли текущий узел пустым элементом (например, <MyElement/>) в C++."
type: docs
weight: 1300
url: /ru/cpp/system.xml/xmlreader/get_isemptyelement/
---
## XmlReader::get_IsEmptyElement method


При переопределении в производном классе возвращает значение, указывающее, является ли текущий узел пустым элементом (например, **<MyElement/>**).

```cpp
virtual bool System::Xml::XmlReader::get_IsEmptyElement()=0
```


### ReturnValue

**true** if the current node is an element ([XmlReader::get_NodeType](../get_nodetype/) equals [XmlNodeType::Element](../../xmlnodetype/)) that ends with **/>**; otherwise, **false**.

## См. также

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
