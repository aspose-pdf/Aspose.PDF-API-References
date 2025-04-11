---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Define a segurança do arquivo Pdf com senhas de usuário/proprietário vazias. A senha do proprietário será adicionada por uma string aleatória. Lança uma exceção se o processo falhar.
type: docs
weight: 80
url: /pt/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Define a segurança do arquivo Pdf com senhas de usuário/proprietário vazias. A senha do proprietário será adicionada por uma string aleatória. Lança uma exceção se o processo falhar.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| privilege | DocumentPrivilege | Defina o privilégio. |

### Valor de Retorno

Verdadeiro para sucesso.

## Exemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### Veja Também

* classe [DocumentPrivilege](../../documentprivilege/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Define a segurança do arquivo Pdf com a senha original. Lança uma exceção se o processo falhar.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | Senha original do usuário. |
| ownerPassword | String | Senha original do proprietário. |
| privilege | DocumentPrivilege | Defina o privilégio. |

### Valor de Retorno

Verdadeiro para sucesso.

## Exemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Veja Também

* classe [DocumentPrivilege](../../documentprivilege/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)