---
title: System::Diagnostics::ProcessStartInfo class
linktitle: ProcessStartInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Diagnostics::ProcessStartInfo class. Describes process start parameters. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.diagnostics/processstartinfo/
---
## ProcessStartInfo class


Describes process start parameters. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ProcessStartInfo : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Arguments](./get_arguments/)() const | Gets process arguments. |
| [get_CreateNoWindow](./get_createnowindow/)() const | Gets NoWindow property. |
| [get_EnvironmentVariables](./get_environmentvariables/)() const | Gets process environment variables. |
| [get_FileName](./get_filename/)() const | Gets process file name. |
| [get_RedirectStandardError](./get_redirectstandarderror/)() const | Gets RedirectStandardError property. |
| [get_RedirectStandardInput](./get_redirectstandardinput/)() const | Gets RedirectStandardInput property. |
| [get_RedirectStandardOutput](./get_redirectstandardoutput/)() const | Gets RedirectStandardOutput property. |
| [get_UseShellExecute](./get_useshellexecute/)() const | Gets UseShellExecute property. |
| [get_WindowStyle](./get_windowstyle/)() const | Gets window style. |
| [get_WorkingDirectory](./get_workingdirectory/)() const | Gets working directory of the process. |
| [ProcessStartInfo](./processstartinfo/)() | Creates empty start info object. |
| [ProcessStartInfo](./processstartinfo/)(const String\&) | Creates start info object. |
| [ProcessStartInfo](./processstartinfo/)(const String\&, const String\&) | Creates start info object. |
| [set_Arguments](./set_arguments/)(const String\&) | Sets process arguments. |
| [set_CreateNoWindow](./set_createnowindow/)(bool) | Sets NoWindow property. |
| [set_FileName](./set_filename/)(const String\&) | Sets process file name. |
| [set_RedirectStandardError](./set_redirectstandarderror/)(bool) | Sets RedirectStandardError property. |
| [set_RedirectStandardInput](./set_redirectstandardinput/)(bool) | Sets RedirectStandardInput property. |
| [set_RedirectStandardOutput](./set_redirectstandardoutput/)(bool) | Sets RedirectStandardOutput property. |
| [set_UseShellExecute](./set_useshellexecute/)(bool) | Sets UseShellExecute property. |
| [set_WindowStyle](./set_windowstyle/)(ProcessWindowStyle) | Sets window style. |
| [set_WorkingDirectory](./set_workingdirectory/)(const String\&) | Sets working directory of the process. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
