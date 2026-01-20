---
title: System::Xml::XmlNamespaceManager class
linktitle: XmlNamespaceManager
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamespaceManager class. Resolves, adds, and removes namespaces to a collection and provides scope management for these namespaces in C++.'
type: docs
weight: 2300
url: /cpp/system.xml/xmlnamespacemanager/
---
## XmlNamespaceManager class


Resolves, adds, and removes namespaces to a collection and provides scope management for these namespaces.

```cpp
class XmlNamespaceManager : public System::Xml::IXmlNamespaceResolver,
                            public System::Collections::Generic::IEnumerable<String>
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AddNamespace](./addnamespace/)(String, String) | Adds the given namespace to the collection. |
| virtual [get_DefaultNamespace](./get_defaultnamespace/)() | Returns the namespace URI for the default namespace. |
| virtual [get_NameTable](./get_nametable/)() | Returns the [XmlNameTable](../xmlnametable/) associated with this object. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator to use to iterate through the namespaces in the [XmlNamespaceManager](./). |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Returns a collection of namespace names keyed by prefix which can be used to enumerate the namespaces currently in scope. |
| virtual [HasNamespace](./hasnamespace/)(String) | Returns a value indicating whether the supplied prefix has a namespace defined for the current pushed scope. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Returns the namespace URI for the specified prefix. |
| [LookupPrefix](./lookupprefix/)(const String\&) override | Finds the prefix declared for the given namespace URI. |
| virtual [PopScope](./popscope/)() | Pops a namespace scope off the stack. |
| virtual [PushScope](./pushscope/)() | Pushes a namespace scope onto the stack. |
| virtual [RemoveNamespace](./removenamespace/)(String, String) | Removes the given namespace for the given prefix. |
| [XmlNamespaceManager](./xmlnamespacemanager/)(const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlNamespaceManager](./) class with the specified [XmlNameTable](../xmlnametable/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
