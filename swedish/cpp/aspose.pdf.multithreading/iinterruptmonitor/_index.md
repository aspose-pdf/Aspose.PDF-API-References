---
title: "Aspose::Pdf::Multithreading::IInterruptMonitor klass"
linktitle: "IInterruptMonitor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Multithreading::IInterruptMonitor klass. Representerar information om avbrott i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor class


Representerar information om avbrott.

```cpp
class IInterruptMonitor : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_CancellationToken](./get_cancellationtoken/)() | Monitorns avbokningstoken används för processavbrott. Som standard genererar varje [IInterruptMonitor](./) sin egen cancellationSource. |
| virtual [Interrupt](./interrupt/)() | Skickar en begäran om att avbryta operationer. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Multithreading](../)
* Library [Aspose.PDF for C++](../../)
