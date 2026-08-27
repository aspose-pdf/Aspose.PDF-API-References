---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Propiedad ValidationOptions. Obtiene o establece un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación."
type: docs
weight: 20
url: /es/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

Obtiene o establece un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación.

```csharp
public bool CheckCertificateChain { get; set; }
```

## Observaciones

Cuando la propiedad está establecida, se comprobará la existencia de una cadena de certificados; si está ausente, el resultado de la verificación será Undefined, lo que corresponde al comportamiento de Adobe Acrobat. Si solo desea comprobar el estado de revocación en línea, establezca el campo en `false`. El valor predeterminado es `false`.

### Ver también

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


