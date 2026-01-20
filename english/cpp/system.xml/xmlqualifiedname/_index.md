---
title: System::Xml::XmlQualifiedName class
linktitle: XmlQualifiedName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlQualifiedName class. Represents an XML qualified name in C++.'
type: docs
weight: 3200
url: /cpp/system.xml/xmlqualifiedname/
---
## XmlQualifiedName class


Represents an XML qualified name.

```cpp
class XmlQualifiedName : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Determines whether the specified [XmlQualifiedName](./) object is equal to the current [XmlQualifiedName](./) object. |
| [get_IsEmpty](./get_isempty/)() const | Returns a value indicating whether the [XmlQualifiedName](./) is empty. |
| [get_Name](./get_name/)() const | Returns a string representation of the qualified name of the [XmlQualifiedName](./). |
| [get_Namespace](./get_namespace/)() const | Returns a string representation of the namespace of the [XmlQualifiedName](./). |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for the [XmlQualifiedName](./). |
| static [ToString](./tostring/)(const String\&, const String\&) | Returns the string value of the [XmlQualifiedName](./). |
| [ToString](./tostring/)() const override | Returns the string value of the [XmlQualifiedName](./). |
| [XmlQualifiedName](./xmlqualifiedname/)() | Initializes a new instance of the [XmlQualifiedName](./) class. |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&) | Initializes a new instance of the [XmlQualifiedName](./) class with the specified name. |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&, const String\&) | Initializes a new instance of the [XmlQualifiedName](./) class with the specified name and namespace. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Provides an empty [XmlQualifiedName](./). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
