---
title: Aspose::Pdf::Forms::Signature::set_TimestampSettings method
linktitle: set_TimestampSettings
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Signature::set_TimestampSettings method. Gets/sets timestamp settings in C++.'
type: docs
weight: 2800
url: /cpp/aspose.pdf.forms/signature/set_timestampsettings/
---
## Signature::set_TimestampSettings method


Gets/sets timestamp settings.

```cpp
void Aspose::Pdf::Forms::Signature::set_TimestampSettings(const System::SharedPtr<Aspose::Pdf::TimestampSettings> &value)
```

## Remarks


If the property is set and a certificate is provided to the constructor of the [Signature](../) class, the digital signature will be timestamped with an embedded timestamp. If the property is set but no certificate is provided to the constructor of the [Signature](../) class, the timestamp will be added as a separate signature. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TimestampSettings](../../../aspose.pdf/timestampsettings/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
