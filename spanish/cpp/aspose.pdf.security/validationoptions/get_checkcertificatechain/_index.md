---
title: "Aspose::Pdf::Security::ValidationOptions::get_CheckCertificateChain método"
linktitle: "get_CheckCertificateChain"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ValidationOptions::get_CheckCertificateChain método. Obtiene un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.security/validationoptions/get_checkcertificatechain/
---
## ValidationOptions::get_CheckCertificateChain method


Obtiene un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación.

```cpp
bool Aspose::Pdf::Security::ValidationOptions::get_CheckCertificateChain() const
```

## Observaciones


Cuando se establece la propiedad, se comprobará la existencia de una cadena de certificados; si está ausente, el resultado de la verificación será [ValidationStatus::Undefined](../../validationstatus/), lo que corresponde al comportamiento de Adobe Acrobat. Si solo desea comprobar el estado de revocación en línea, establezca el campo en **false**. El valor predeterminado es **false**.
## Ver también

* Class [ValidationOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
