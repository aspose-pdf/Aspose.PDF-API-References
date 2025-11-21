---
title: Aspose::Pdf::Multithreading::IInterruptMonitor class
linktitle: IInterruptMonitor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Multithreading::IInterruptMonitor class. Represents information about interruption in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor class


Represents information about interruption.

```cpp
class IInterruptMonitor : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_CancellationToken](./get_cancellationtoken/)() | Monitor's cancellation token used for process interruption. By default each [IInterruptMonitor](./) generates its own cancellationSource. |
| virtual [Interrupt](./interrupt/)() | Sends a request to interrupt operations. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Multithreading](../)
* Library [Aspose.PDF for C++](../../)
