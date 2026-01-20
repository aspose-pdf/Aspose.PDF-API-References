---
title: System::Diagnostics::Process class
linktitle: Process
second_title: Aspose.PDF for C++ API Reference
description: 'System::Diagnostics::Process class. Encapsulates process information and manipulation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.diagnostics/process/
---
## Process class


Encapsulates process information and manipulation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Process : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_EnableRaisingEvents](./get_enableraisingevents/)() const | Gets whether the event Exited should be raised when the process terminates. |
| [get_ExitCode](./get_exitcode/)() const | Gets process exit code. |
| [get_PrivateMemorySize64](./get_privatememorysize64/)() const | Gets process private memory set size. |
| [get_ProcessName](./get_processname/)() const | Gets process name. |
| [get_StandardError](./get_standarderror/)() const | Provides reader to read from process error output. Not implemented. |
| [get_StandardOutput](./get_standardoutput/)() const | Provides reader to read from process standard output. Not implemented. |
| [get_StartInfo](./get_startinfo/)() const | Gets process start information. |
| [get_WorkingSet64](./get_workingset64/)() const | Gets process memory working set size. |
| static [GetCurrentProcess](./getcurrentprocess/)() | Gets information on current process. [Windows](../../system.windows/) only. |
| [GetOutputText](./getoutputtext/)() const | Gets process output text. |
| [set_EnableRaisingEvents](./set_enableraisingevents/)(bool) | Sets whether the event Exited should be raised when the process terminates. |
| [Start](./start/)() | Starts process with pre-defined parameters. |
| static [Start](./start/)(const String\&, const String\&) | Starts process with specified path and arguments. |
| static [Start](./start/)(const SharedPtr\<ProcessStartInfo\>\&) | Starts process with specified path and arguments. |
| [WaitForExit](./waitforexit/)(int) | Waits for process to exit. Not implemented. |
| [WaitForExit](./waitforexit/)() | Waits for process to exit, doesn't return until it's over. |
| virtual [~Process](./~process/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
