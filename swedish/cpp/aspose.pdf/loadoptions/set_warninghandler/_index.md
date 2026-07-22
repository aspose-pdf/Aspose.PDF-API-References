---
title: "Aspose::Pdf::LoadOptions::set_WarningHandler method"
linktitle: "set_WarningHandler"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LoadOptions::set_WarningHandler method. Callback för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, vilket innebär att Load‑operationen ska avbrytas i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf/loadoptions/set_warninghandler/
---
## LoadOptions::set_WarningHandler method


Callback för att hantera eventuella varningar som genereras. WarningHandler returnerar [ReturnAction](../../returnaction/) enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, vilket innebär att Load‑operationen ska avbrytas.

```cpp
void Aspose::Pdf::LoadOptions::set_WarningHandler(const System::SharedPtr<IWarningCallback> &value)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
