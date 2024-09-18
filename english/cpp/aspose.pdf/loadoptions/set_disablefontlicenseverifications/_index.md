---
title: Aspose::Pdf::LoadOptions::set_DisableFontLicenseVerifications method
linktitle: set_DisableFontLicenseVerifications
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LoadOptions::set_DisableFontLicenseVerifications method. Sets flag to disable any license restrictions for all fonts while loading the file. When true, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default false in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf/loadoptions/set_disablefontlicenseverifications/
---
## LoadOptions::set_DisableFontLicenseVerifications method


Sets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::LoadOptions::set_DisableFontLicenseVerifications(bool value)
```

## Remarks


Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So he takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. 
## See Also

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
