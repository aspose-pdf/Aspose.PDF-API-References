---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Establece la seguridad del archivo Pdf con la contraseña original. No lanza una excepción si el proceso falla.
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## Método PdfFileSecurity.TrySetPrivilege

Establece la seguridad del archivo Pdf con la contraseña original. No lanza una excepción si el proceso falla.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña de usuario original. |
| ownerPassword | String | Contraseña de propietario original. |
| privilege | DocumentPrivilege | Establecer privilegio. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Ver También

* clase [DocumentPrivilege](../../documentprivilege/)
* clase [PdfFileSecurity](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)