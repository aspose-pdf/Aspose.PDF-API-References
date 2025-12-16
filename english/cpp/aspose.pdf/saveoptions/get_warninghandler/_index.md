---
title: Aspose::Pdf::SaveOptions::get_WarningHandler method
linktitle: get_WarningHandler
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SaveOptions::get_WarningHandler method. Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf/saveoptions/get_warninghandler/
---
## SaveOptions::get_WarningHandler method


Callback to handle any warnings generated. The WarningHandler returns [ReturnAction](../../returnaction/) enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

```cpp
System::SharedPtr<IWarningCallback> Aspose::Pdf::SaveOptions::get_WarningHandler() const
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [SaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
