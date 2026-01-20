---
title: System::Drawing::Printing::PrintPageEventArgs class
linktitle: PrintPageEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Printing::PrintPageEventArgs class. Provides data for PrintPage event. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.drawing.printing/printpageeventargs/
---
## PrintPageEventArgs class


Provides data for PrintPage event. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PrintPageEventArgs : public System::EventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [get_Graphics](./get_graphics/)() | NOT IMPLEMENTED. |
| [get_HasMorePages](./get_hasmorepages/)() | NOT IMPLEMENTED. |
| [get_PageSettings](./get_pagesettings/)() | NOT IMPLEMENTED. |
| [PrintPageEventArgs](./printpageeventargs/)(const SharedPtr\<Graphics\>\&, const SharedPtr\<Rectangle\>\&, const SharedPtr\<Rectangle\>\&, const SharedPtr\<PageSettings\>\&) | Constructs a new instance of [PrintPageEventArgs](./) class. |
| [set_HasMorePages](./set_hasmorepages/)(bool) | NOT IMPLEMENTED. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ptr](./ptr/) | An alias for a shared pointer to an instance of this class. |
## See Also

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.PDF for C++](../../)
