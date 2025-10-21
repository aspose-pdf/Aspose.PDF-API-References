---
title: Aspose::Pdf::LoadOptions::set_WarningHandler method
linktitle: set_WarningHandler
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LoadOptions::set_WarningHandler method. Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf/loadoptions/set_warninghandler/
---
## LoadOptions::set_WarningHandler method


Callback to handle any warnings generated. The WarningHandler returns [ReturnAction](../../returnaction/) enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

```cpp
void Aspose::Pdf::LoadOptions::set_WarningHandler(System::SharedPtr<IWarningCallback> value)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
