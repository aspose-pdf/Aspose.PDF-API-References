---
title: System::Xml::Schema::ValidationEventArgs class
linktitle: ValidationEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::ValidationEventArgs class. Returns detailed information related to the ValidationEventHandler in C++.'
type: docs
weight: 200
url: /cpp/system.xml.schema/validationeventargs/
---
## ValidationEventArgs class


Returns detailed information related to the [ValidationEventHandler](../validationeventhandler/).

```cpp
class ValidationEventArgs : public System::EventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [get_Exception](./get_exception/)() | Returns the [XmlSchemaException](../xmlschemaexception/) associated with the validation event. |
| [get_Message](./get_message/)() | Returns the text description corresponding to the validation event. |
| [get_Severity](./get_severity/)() | Returns the severity of the validation event. |
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
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
