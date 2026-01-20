---
title: System::Xml::XmlNodeChangedEventArgs class
linktitle: XmlNodeChangedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeChangedEventArgs class. Provides data for the XmlDocument::NodeChanged, XmlDocument::NodeChanging, XmlDocument::NodeInserted, XmlDocument::NodeInserting, XmlDocument::NodeRemoved and XmlDocument::NodeRemoving events in C++.'
type: docs
weight: 2600
url: /cpp/system.xml/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs class


Provides data for the **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** and **XmlDocument::NodeRemoving** events.

```cpp
class XmlNodeChangedEventArgs : public System::EventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [get_Action](./get_action/)() | Returns a value indicating what type of node change event is occurring. |
| [get_NewParent](./get_newparent/)() | Returns the value of the [XmlNode::get_ParentNode](../xmlnode/get_parentnode/) after the operation completes. |
| [get_NewValue](./get_newvalue/)() | Returns the new value of the node. |
| [get_Node](./get_node/)() | Returns the [XmlNode](../xmlnode/) that is being added, removed or changed. |
| [get_OldParent](./get_oldparent/)() | Returns the value of the [XmlNode::get_ParentNode](../xmlnode/get_parentnode/) before the operation began. |
| [get_OldValue](./get_oldvalue/)() | Returns the original value of the node. |
| [XmlNodeChangedEventArgs](./xmlnodechangedeventargs/)(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) | Initializes a new instance of the [XmlNodeChangedEventArgs](./) class. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
