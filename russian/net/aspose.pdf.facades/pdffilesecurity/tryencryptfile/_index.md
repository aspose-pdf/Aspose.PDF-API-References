---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSecurity. Шифрует Pdf файл с помощью userpassword и ownerpassword и устанавливает привилегии доступа к документу. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если входной пароль владельца равен null или пустой. Не вызывает исключение, если процесс завершился неудачно.
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## Метод PdfFileSecurity.TryEncryptFile

Шифрует Pdf файл с помощью userpassword и ownerpassword и устанавливает привилегии доступа к документу. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если входной пароль владельца равен null или пустой. Не вызывает исключение, если процесс завершился неудачно.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| privilege | DocumentPrivilege | Установить привилегию. |
| keySize | KeySize | KeySize.x40 для шифрования на 40 бит, KeySize.x128 для шифрования на 128 бит и KeySize.x256 для шифрования на 256 бит. |

### Возвращаемое значение

True для успеха, или false.

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

* класс [DocumentPrivilege](../../documentprivilege/)
* перечисление [KeySize](../../keysize/)
* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)