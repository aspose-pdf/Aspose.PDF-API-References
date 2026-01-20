---
title: System::Xml::XmlCharacterData class
linktitle: XmlCharacterData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlCharacterData class. Provides text manipulation methods that are used by several classes in C++.'
type: docs
weight: 900
url: /cpp/system.xml/xmlcharacterdata/
---
## XmlCharacterData class


Provides text manipulation methods that are used by several classes.

```cpp
class XmlCharacterData : public System::Xml::XmlLinkedNode
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AppendData](./appenddata/)(String) | Appends the specified string to the end of the character data of the node. |
| virtual [DeleteData](./deletedata/)(int32_t, int32_t) | Removes a range of characters from the node. |
| virtual [get_Data](./get_data/)() | Returns the data of the node. |
| [get_InnerText](./get_innertext/)() override | Returns the concatenated values of the node and all the children of the node. |
| virtual [get_Length](./get_length/)() | Returns the length of the data, in characters. |
| [get_Value](./get_value/)() override | Returns the value of the node. |
| virtual [InsertData](./insertdata/)(int32_t, String) | Inserts the specified string at the specified character offset. |
| virtual [ReplaceData](./replacedata/)(int32_t, int32_t, String) | Replaces the specified number of characters starting at the specified offset with the specified string. |
| virtual [set_Data](./set_data/)(String) | Sets the data of the node. |
| [set_InnerText](./set_innertext/)(String) override | Sets the concatenated values of the node and all the children of the node. |
| [set_Value](./set_value/)(String) override | Sets the value of the node. |
| virtual [Substring](./substring/)(int32_t, int32_t) | Retrieves a substring of the full string from the specified range. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
