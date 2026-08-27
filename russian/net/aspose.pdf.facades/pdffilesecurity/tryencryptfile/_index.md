---
title: "PdfFileSecurity.TryEncryptFile"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileSecurity. Шифрует PDF‑файл с паролем пользователя и паролем владельца и задаёт привилегии доступа к документу. Пароль пользователя и пароль владельца могут быть null или пустыми. Если входной пароль владельца null или пустой, пароль владельца будет заменён случайной строкой. Не выбрасывает исключение, если процесс завершился неудачей"
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

Шифрует PDF‑файл с пользовательским паролем и паролем владельца и задаёт привилегии доступа документа. Пользовательский пароль и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца null или пустой. Не бросает исключение при неудаче процесса.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| привилегия | DocumentPrivilege | Установить привилегию. |
| keySize | KeySize | KeySize.x40 для шифрования 40‑бит, KeySize.x128 для шифрования 128‑бит и KeySize.x256 для шифрования 256‑бит. |

### Возвращаемое значение

True при успехе, иначе false.

## Примеры

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

### См. также

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


