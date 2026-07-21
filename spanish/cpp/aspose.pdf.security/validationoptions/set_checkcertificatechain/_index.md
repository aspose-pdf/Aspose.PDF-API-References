---
title: "Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain método"
linktitle: "set_CheckCertificateChain"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain método. Establece un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.security/validationoptions/set_checkcertificatechain/
---
## ValidationOptions::set_CheckCertificateChain method


Establece un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación.

```cpp
void Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain(bool value)
```

## Observaciones


Cuando se establece la propiedad, se comprobará la existencia de una cadena de certificados; si está ausente, el resultado de la verificación será [ValidationStatus::Undefined](../../validationstatus/), lo que corresponde al comportamiento de Adobe Acrobat. Si solo desea comprobar el estado de revocación en línea, establezca el campo en **false**. El valor predeterminado es **false**.
## Ver también

* Class [ValidationOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
