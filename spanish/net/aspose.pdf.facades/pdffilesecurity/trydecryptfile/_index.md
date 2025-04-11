---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Desencripta un documento Pdf encriptado por contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar la contraseña de usuario. No lanza una excepción si el proceso falla.
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## Método PdfFileSecurity.TryDecryptFile

Desencripta un documento Pdf encriptado por contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar la contraseña de usuario. No lanza una excepción si el proceso falla.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ownerPassword | String | Contraseña de propietario. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### Ver También

* clase [PdfFileSecurity](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)