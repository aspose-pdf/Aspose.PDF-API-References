---
title: "Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength método"
linktitle: "set_AvoidEstimatingSignatureLength"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength método. Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.pdf.forms/signature/set_avoidestimatingsignaturelength/
---
## Signature::set_AvoidEstimatingSignatureLength method


Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma.

```cpp
void Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength(bool value)
```

## Observaciones


Evita estimar la longitud de la firma antes de firmar un documento. Se usa para firmar a través de [CustomSignHash](../) y mediante [ExternalSignature](../../externalsignature/). Si [CustomSignHash](../) devuelve una firma más larga que [DefaultSignatureLength](../), entonces se lanzará [Aspose::Pdf::Security::SignatureLengthMismatchException](../../../aspose.pdf.security/signaturelengthmismatchexception/). El valor predeterminado es **false**.
## Ver también

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
