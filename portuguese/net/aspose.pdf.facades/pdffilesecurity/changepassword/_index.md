---
title: PdfFileSecurity.ChangePassword
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Altera a senha do usuário e a senha do proprietário, mantendo as configurações de segurança originais. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Lança uma exceção se o processo falhar.
type: docs
weight: 40
url: /pt/net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## ChangePassword(string, string, string) {#changepassword}

Altera a senha do usuário e a senha do proprietário, mantendo as configurações de segurança originais. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Lança uma exceção se o processo falhar.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ownerPassword | String | Senha original do proprietário. |
| newUserPassword | String | Nova senha do usuário. |
| newOwnerPassword | String | Nova senha do proprietário. |

### Valor de Retorno

Verdadeiro para sucesso.

## Exemplos

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 fileSecurity.ChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.ChangePassword("owner","newuser","newowner")	
```

### Veja Também

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

Altera a senha do usuário e a senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Lança uma exceção se o processo falhar.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ownerPassword | String | Senha original do proprietário. |
| newUserPassword | String | Nova senha do usuário. |
| newOwnerPassword | String | Nova senha do proprietário. |
| privilege | DocumentPrivilege | Redefinir segurança. |
| keySize | KeySize | KeySize.x40 para criptografia de 40 bits, KeySize.x128 para criptografia de 128 bits e KeySize.x256 para criptografia de 256 bits. |

### Valor de Retorno

Verdadeiro para sucesso.

## Exemplos

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Veja Também

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

Altera a senha do usuário e a senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e uma exceção correspondente será levantada se o kit encontrar essa combinação. Lança uma exceção se o processo falhar.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ownerPassword | String | Senha original do proprietário. |
| newUserPassword | String | Nova senha do usuário. |
| newOwnerPassword | String | Nova senha do proprietário. |
| privilege | DocumentPrivilege | Redefinir segurança. |
| keySize | KeySize | KeySize.x40 para criptografia de 40 bits, KeySize.x128 para criptografia de 128 bits e KeySize.x256 para criptografia de 256 bits. |
| cipher | Algorithm | Algorithm.AES para criptografar usando o algoritmo AES ou Algorithm.RC4 para criptografia RC4. |

### Valor de Retorno

Verdadeiro para sucesso.

## Exemplos

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Veja Também

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)