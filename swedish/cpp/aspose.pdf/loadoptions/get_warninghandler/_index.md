---
title: "Aspose::Pdf::LoadOptions::get_WarningHandler method"
linktitle: "get_WarningHandler"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LoadOptions::get_WarningHandler method. Callback för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, vilket innebär att Load‑operationen ska avbrytas i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf/loadoptions/get_warninghandler/
---
## LoadOptions::get_WarningHandler method


Callback för att hantera eventuella varningar som genereras. WarningHandler returnerar [ReturnAction](../../returnaction/) enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, vilket innebär att Load‑operationen ska avbrytas.

```cpp
System::SharedPtr<IWarningCallback> Aspose::Pdf::LoadOptions::get_WarningHandler() const
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
