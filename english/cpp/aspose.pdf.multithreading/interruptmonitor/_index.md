---
title: Aspose::Pdf::Multithreading::InterruptMonitor class
linktitle: InterruptMonitor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Multithreading::InterruptMonitor class. Represents information about interruption in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class


Represents information about interruption.

```cpp
class InterruptMonitor : public Aspose::Pdf::Multithreading::IInterruptMonitor
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Disposes used resources. |
| [get_CancellationToken](./get_cancellationtoken/)() override | Monitor's cancellation token used for process interruption. By default each [IInterruptMonitor](../iinterruptmonitor/) generates its own cancellationSource. |
| static [get_ThreadLocalInstance](./get_threadlocalinstance/)() | Gets the [IInterruptMonitor](../iinterruptmonitor/) instance which is unique for each thread. |
| [Interrupt](./interrupt/)() override | Sends a request to interrupt operations. |
| [InterruptMonitor](./interruptmonitor/)() | Initializes a new instance of the [InterruptMonitor](./) class. |
| static [set_ThreadLocalInstance](./set_threadlocalinstance/)(System::SharedPtr\<IInterruptMonitor\>) | Sets the [IInterruptMonitor](../iinterruptmonitor/) instance which is unique for each thread. |
## See Also

* Class [IInterruptMonitor](../iinterruptmonitor/)
* Namespace [Aspose::Pdf::Multithreading](../)
* Library [Aspose.PDF for C++](../../)
