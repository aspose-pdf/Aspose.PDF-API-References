---
title: System::Drawing::Printing::PrintEventArgs class
linktitle: PrintEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Printing::PrintEventArgs class. Provides data for the BeginPrint and EndPrint events. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.drawing.printing/printeventargs/
---
## PrintEventArgs class


Provides data for the BeginPrint and EndPrint events. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PrintEventArgs : public System::ComponentModel::CancelEventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [get_PrintAction](./get_printaction/)() | Returns a value that specify a print action represented by the current objet. |
| [PrintEventArgs](./printeventargs/)() | Constructs a new instance of [PrintEventArgs](./) object. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## See Also

* Class [CancelEventArgs](../../system.componentmodel/canceleventargs/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.PDF for C++](../../)
