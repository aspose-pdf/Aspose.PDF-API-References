---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Criptografa arquivo Pdf com userpassword e ownerpassword e define os privilégios de acesso do documento. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Lança uma exceção se o processo falhar
type: docs
weight: 70
url: /pt/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Criptografa arquivo Pdf com userpassword e ownerpassword e define os privilégios de acesso do documento. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Lança uma exceção se o processo falhar.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | Senha do usuário. |
| ownerPassword | String | Senha do proprietário. |
| privilege | DocumentPrivilege | Definir privilégio. |
| keySize | KeySize | KeySize.x40 para criptografia de 40 bits, KeySize.x128 para criptografia de 128 bits e KeySize.x256 para criptografia de 256 bits. |

### Valor de Retorno

Verdadeiro para sucesso.

## Exemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Veja Também

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Criptografa arquivo Pdf com userpassword e ownerpassword e define os privilégios de acesso do documento. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e uma exceção correspondente será levantada se o kit encontrar essa combinação. Lança uma exceção se o processo falhar.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | Senha do usuário. |
| ownerPassword | String | Senha do proprietário. |
| privilege | DocumentPrivilege | Definir privilégio. |
| keySize | KeySize | KeySize.x40 para criptografia de 40 bits, KeySize.x128 para criptografia de 128 bits e KeySize.x256 para criptografia de 256 bits. |
| cipher | Algorithm | Algorithm.AES para criptografar usando o algoritmo AES ou Algorithm.RC4 para criptografia RC4. |

### Valor de Retorno

Verdadeiro para sucesso.

## Exemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Veja Também

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)