---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileSecurity. Representa a criptografia ou descriptografia de um arquivo Pdf com senha de proprietário ou usuário, alterando a configuração de segurança e a senha
type: docs
weight: 4550
url: /pt/net/aspose.pdf.facades/pdffilesecurity/
---
## Classe PdfFileSecurity

Representa a criptografia ou descriptografia de um arquivo Pdf com senha de proprietário ou usuário, alterando a configuração de segurança e a senha.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Inicializa o objeto PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Inicializa um novo objeto `PdfFileSecurity` com base no *documento*. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Retorna a exceção que foi lançada pela última operação. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Inicializa a fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Inicializa a fachada. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Altera a senha do usuário e a senha do proprietário pela senha do proprietário, mantendo as configurações de segurança originais. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Lança uma exceção se o processo falhar. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Altera a senha do usuário e a senha pela senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Lança uma exceção se o processo falhar. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Altera a senha do usuário e a senha pela senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e uma exceção correspondente será levantada se o kit encontrar essa combinação. Lança uma exceção se o processo falhar. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Fecha a fachada. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Descriptografa um documento Pdf criptografado pela senha do proprietário. Se o documento não tiver senha de proprietário, é permitido usar a senha do usuário. Lança uma exceção se o processo falhar. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Criptografa o arquivo Pdf com senha do usuário e senha do proprietário e define os privilégios de acesso do documento. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Lança uma exceção se o processo falhar. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Criptografa o arquivo Pdf com senha do usuário e senha do proprietário e define os privilégios de acesso do documento. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e uma exceção correspondente será levantada se o kit encontrar essa combinação. Lança uma exceção se o processo falhar. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva o documento PDF no fluxo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva o documento PDF no arquivo especificado. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Define a segurança do arquivo Pdf com senhas de usuário/proprietário vazias. A senha do proprietário será adicionada por uma string aleatória. Lança uma exceção se o processo falhar. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Define a segurança do arquivo Pdf com a senha original. Lança uma exceção se o processo falhar. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Altera a senha do usuário e a senha do proprietário pela senha do proprietário, mantendo as configurações de segurança originais. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Não lança uma exceção se o processo falhar. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Altera a senha do usuário e a senha pela senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Não lança uma exceção se o processo falhar. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Altera a senha do usuário e a senha pela senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e uma exceção correspondente será levantada se o kit encontrar essa combinação. Não lança uma exceção se o processo falhar. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Descriptografa um documento Pdf criptografado pela senha do proprietário. Se o documento não tiver senha de proprietário, é permitido usar a senha do usuário. Não lança uma exceção se o processo falhar. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Criptografa o arquivo Pdf com senha do usuário e senha do proprietário e define os privilégios de acesso do documento. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Não lança uma exceção se o processo falhar. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Define a segurança do arquivo Pdf com a senha original. Não lança uma exceção se o processo falhar. |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)