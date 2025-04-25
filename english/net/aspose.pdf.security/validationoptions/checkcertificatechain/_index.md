---
title: ValidationOptions.CheckCertificateChain
second_title: Aspose.PDF for .NET API Reference
description: ValidationOptions property. Gets or sets a value indicating whether the certificate chain should be checked during the validation process
type: docs
weight: 20
url: /net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

Gets or sets a value indicating whether the certificate chain should be checked during the validation process.

```csharp
public bool CheckCertificateChain { get; set; }
```

## Remarks

When the property is set, the existence of a chain of certificates will be checked, if it is absent, then the result of the verification will be Undefined, which corresponds to the behavior of Adobe Acrobat. If you just want to check the status of revocation online, then set the field in `false`. The default value is `false`.

### See Also

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


