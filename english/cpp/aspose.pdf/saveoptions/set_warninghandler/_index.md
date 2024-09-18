---
title: Aspose::Pdf::SaveOptions::set_WarningHandler method
linktitle: set_WarningHandler
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SaveOptions::set_WarningHandler method. Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/saveoptions/set_warninghandler/
---
## SaveOptions::set_WarningHandler method


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::SaveOptions::set_WarningHandler(System::SharedPtr<IWarningCallback> value)
```

## See Also

* Class [IWarningCallback](../../iwarningcallback/)
* Class [SaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
