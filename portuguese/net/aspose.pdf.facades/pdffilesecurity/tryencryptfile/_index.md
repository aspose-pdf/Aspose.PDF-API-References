---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Criptografa o arquivo Pdf com a senha do usuário e a senha do proprietário e define os privilégios de acesso do documento. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Não lança uma exceção se o processo falhar.
type: docs
weight: 110
url: /pt/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## Método PdfFileSecurity.TryEncryptFile

Criptografa o arquivo Pdf com a senha do usuário e a senha do proprietário e define os privilégios de acesso do documento. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Não lança uma exceção se o processo falhar.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | Senha do usuário. |
| ownerPassword | String | Senha do proprietário. |
| privilege | DocumentPrivilege | Definir privilégio. |
| keySize | KeySize | KeySize.x40 para criptografia de 40 bits, KeySize.x128 para criptografia de 128 bits e KeySize.x256 para criptografia de 256 bits. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Exemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Veja Também

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)