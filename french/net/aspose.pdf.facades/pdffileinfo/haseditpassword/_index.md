---
title: PdfFileInfo.HasEditPassword
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfFileInfo. Renvoie vrai si un mot de passe est nécessaire pour modifier les autorisations ou la propriété de sécurité du document. Faites attention, cette propriété ne peut être lue que si un mot de passe valide a été fourni dans le constructeur de [`PdfFileInfo`](../). Dans le cas où le PasswordType est Inaccessible, la lecture de cette propriété échouera avec [`InvalidPasswordException`](../../../aspose.pdf/invalidpasswordexception/).
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/pdffileinfo/haseditpassword/
---
## Propriété PdfFileInfo.HasEditPassword

Renvoie vrai si un mot de passe est nécessaire pour modifier les autorisations ou la propriété de sécurité du document. Faites attention, cette propriété ne peut être lue que si un mot de passe valide a été fourni dans le constructeur de [`PdfFileInfo`](../). Dans le cas où le PasswordType est Inaccessible (ce qui signifie qu'un mot de passe invalide a été fourni), la lecture de cette propriété échouera avec [`InvalidPasswordException`](../../../aspose.pdf/invalidpasswordexception/).

```csharp
public bool HasEditPassword { get; }
```

### Voir aussi

* classe [PdfFileInfo](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)