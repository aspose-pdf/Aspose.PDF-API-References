---
title: PdfFileInfo.HasEditPassword
second_title: Aspose.PDF for .NET API Reference
description: Propiedad PdfFileInfo. Devuelve verdadero si se necesita una contraseña para modificar los permisos o la propiedad de seguridad del documento. Preste atención a que esta propiedad solo se puede leer si se proporcionó una contraseña válida en el constructor de PdfFileInfo. En caso de que PasswordType sea Inaccessible, significa que se proporcionó una contraseña inválida y la lectura de esta propiedad fallará con InvalidPasswordException.
type: docs
weight: 60
url: /es/net/aspose.pdf.facades/pdffileinfo/haseditpassword/
---
## Propiedad PdfFileInfo.HasEditPassword

Devuelve verdadero si se necesita una contraseña para modificar los permisos o la propiedad de seguridad del documento. Preste atención a que esta propiedad solo se puede leer si se proporcionó una contraseña válida en [`PdfFileInfo`](../) constructor. En caso de que PasswordType sea Inaccessible (significa que se proporcionó una contraseña inválida) la lectura de esta propiedad fallará con [`InvalidPasswordException`](../../../aspose.pdf/invalidpasswordexception/).

```csharp
public bool HasEditPassword { get; }
```

### Véase también

* clase [PdfFileInfo](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)