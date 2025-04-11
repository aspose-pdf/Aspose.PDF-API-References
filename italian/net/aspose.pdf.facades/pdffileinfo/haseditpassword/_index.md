---
title: PdfFileInfo.HasEditPassword
second_title: Aspose.PDF for .NET API Reference
description: Proprietà PdfFileInfo. Restituisce true se è necessaria una password per modificare le autorizzazioni o la proprietà di sicurezza del documento. Fai attenzione che questa proprietà può essere letta solo se è stata fornita una password valida nel costruttore di PdfFileInfo. Nel caso in cui PasswordType sia Inaccessible significa che è stata fornita una password non valida, la lettura di questa proprietà fallirà con InvalidPasswordException
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/pdffileinfo/haseditpassword/
---
## Proprietà PdfFileInfo.HasEditPassword

Restituisce true se è necessaria una password per modificare le autorizzazioni o la proprietà di sicurezza del documento. Fai attenzione che questa proprietà può essere letta solo se è stata fornita una password valida nel [`PdfFileInfo`](../) costruttore. Nel caso in cui PasswordType sia Inaccessible (significa che è stata fornita una password non valida) la lettura di questa proprietà fallirà con [`InvalidPasswordException`](../../../aspose.pdf/invalidpasswordexception/).

```csharp
public bool HasEditPassword { get; }
```

### Vedi Anche

* classe [PdfFileInfo](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)