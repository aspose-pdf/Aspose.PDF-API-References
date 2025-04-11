---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Descriptografa um documento Pdf criptografado pela senha do proprietário. Se o documento não tiver senha de proprietário, é permitido usar a senha do usuário. Não lança uma exceção se o processo falhar.
type: docs
weight: 100
url: /pt/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## Método PdfFileSecurity.TryDecryptFile

Descriptografa um documento Pdf criptografado pela senha do proprietário. Se o documento não tiver senha de proprietário, é permitido usar a senha do usuário. Não lança uma exceção se o processo falhar.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ownerPassword | String | Senha do proprietário. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

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

### Veja Também

* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)