---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Descriptografa um documento Pdf criptografado pela senha do proprietário. Se o documento não tiver senha de proprietário, é permitido usar a senha do usuário. Lança uma exceção se o processo falhar.
type: docs
weight: 60
url: /pt/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## Método PdfFileSecurity.DecryptFile

Descriptografa um documento Pdf criptografado pela senha do proprietário. Se o documento não tiver senha de proprietário, é permitido usar a senha do usuário. Lança uma exceção se o processo falhar.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ownerPassword | String | Senha do proprietário. |

### Valor de Retorno

Verdadeiro para sucesso.

## Exemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### Veja Também

* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)