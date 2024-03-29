---
title: TryDecryptFile
second_title: Referencia de API de Aspose.PDF para .NET
description: Descifra un documento PDF cifrado por contraseña de propietario. Si el documento no tiene contraseña de propietario se permite usar contraseña de usuario. No lanza una excepción si el proceso falla.
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile method

Descifra un documento PDF cifrado por contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar contraseña de usuario. No lanza una excepción si el proceso falla.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| ownerPassword | String | Contraseña de propietario. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //El TestPath puede reasignarse.
string outFile = "D:\\output.pdf"; //El TestPath puede reasignarse.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### Ver también

* class [PdfFileSecurity](../../pdffilesecurity)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesecurity)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
