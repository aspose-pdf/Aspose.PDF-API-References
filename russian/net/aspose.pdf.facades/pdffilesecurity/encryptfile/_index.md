---
title: "PdfFileSecurity.EncryptFile"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileSecurity. Шифрует PDF‑файл с паролем пользователя и паролем владельца и задаёт привилегии доступа к документу. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца равен null или пустой. Выбрасывает исключение, если процесс завершился неудачно"
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Шифрует PDF‑файл с паролем пользователя и паролем владельца и устанавливает привилегии доступа документа. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца равен null или пустой. Выбрасывает исключение, если процесс завершился неудачей.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| привилегия | DocumentPrivilege | Установить привилегию. |
| keySize | KeySize | KeySize.x40 для шифрования 40‑бит, KeySize.x128 для шифрования 128‑бит и KeySize.x256 для шифрования 256‑бит. |

### Возвращаемое значение

True при успехе.

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

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Шифрует PDF‑файл с паролем пользователя и паролем владельца и устанавливает привилегии доступа документа. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) являются недействительными, и соответствующее исключение будет вызвано, если набор столкнётся с этой комбинацией. Выбрасывает исключение, если процесс завершился неудачей.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| привилегия | DocumentPrivilege | Установить привилегию. |
| keySize | KeySize | KeySize.x40 для шифрования 40‑бит, KeySize.x128 для шифрования 128‑бит и KeySize.x256 для шифрования 256‑бит. |
| cipher | Algorithm | Algorithm.AES для шифрования с использованием алгоритма AES или Algorithm.RC4 для шифрования RC4. |

### Возвращаемое значение

True при успехе.

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

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


