---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Define a segurança do arquivo Pdf com a senha original. Não lança uma exceção se o processo falhar
type: docs
weight: 120
url: /pt/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## Método PdfFileSecurity.TrySetPrivilege

Define a segurança do arquivo Pdf com a senha original. Não lança uma exceção se o processo falhar.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | Senha original do usuário. |
| ownerPassword | String | Senha original do proprietário. |
| privilege | DocumentPrivilege | Definir privilégio. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

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

### Veja Também

* classe [DocumentPrivilege](../../documentprivilege/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)