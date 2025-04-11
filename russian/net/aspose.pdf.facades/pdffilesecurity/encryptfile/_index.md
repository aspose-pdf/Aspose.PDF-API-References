---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSecurity. Шифрует Pdf файл с помощью userpassword и ownerpassword и устанавливает привилегии доступа к документам. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если входной пароль владельца нулевой или пустой. Вызывает исключение, если процесс завершился неудачно
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Шифрует Pdf файл с помощью userpassword и ownerpassword и устанавливает привилегии доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если входной пароль владельца нулевой или пустой. Вызывает исключение, если процесс завершился неудачно.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| privilege | DocumentPrivilege | Установить привилегию. |
| keySize | KeySize | KeySize.x40 для шифрования на 40 бит, KeySize.x128 для шифрования на 128 бит и KeySize.x256 для шифрования на 256 бит. |

### Возвращаемое значение

True для успешного выполнения.

## Примеры

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

### См. также

* класс [DocumentPrivilege](../../documentprivilege/)
* перечисление [KeySize](../../keysize/)
* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Шифрует Pdf файл с помощью userpassword и ownerpassword и устанавливает привилегии доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если входной пароль владельца нулевой или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) являются недопустимыми, и соответствующее исключение будет вызвано, если комплект столкнется с этой комбинацией. Вызывает исключение, если процесс завершился неудачно.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| privilege | DocumentPrivilege | Установить привилегию. |
| keySize | KeySize | KeySize.x40 для шифрования на 40 бит, KeySize.x128 для шифрования на 128 бит и KeySize.x256 для шифрования на 256 бит. |
| cipher | Algorithm | Algorithm.AES для шифрования с использованием алгоритма AES или Algorithm.RC4 для шифрования RC4. |

### Возвращаемое значение

True для успешного выполнения.

## Примеры

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

### См. также

* класс [DocumentPrivilege](../../documentprivilege/)
* перечисление [KeySize](../../keysize/)
* перечисление [Algorithm](../../algorithm/)
* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)