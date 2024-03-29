---
title: EncryptFile
second_title: Aspose.PDF для справочника API .NET
description: Шифрует файл Pdf с помощью пароля пользователя и пароля владельца и устанавливает права доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой если введенный пароль владельца недействителен или пуст. Выдает исключение если процесс не выполнен.
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Шифрует файл Pdf с помощью пароля пользователя и пароля владельца и устанавливает права доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если введенный пароль владельца недействителен или пуст. Выдает исключение, если процесс не выполнен.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пользовательский пароль. |
| ownerPassword | String | Пароль владельца. |
| privilege | DocumentPrivilege | Установить привилегию. |
| keySize | KeySize | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |

### Возвращаемое значение

Верно для успеха.

### Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; // TestPath может быть переназначен.
string outFile = "D:\\output.pdf"; // TestPath может быть переназначен.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Смотрите также

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesecurity)
* сборка [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Шифрует файл Pdf с помощью пароля пользователя и пароля владельца и устанавливает права доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если введенный пароль владельца пуст или пуст. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) недействительны, и соответствующее исключение будет вызвано, если комплект встретит эту комбинацию. Выдает исключение, если процесс завершился неудачно.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пользовательский пароль. |
| ownerPassword | String | Пароль владельца. |
| privilege | DocumentPrivilege | Установить привилегию. |
| keySize | KeySize | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |
| cipher | Algorithm | Algorithm.AES для шифрования с использованием алгоритма AES или Algorithm.RC4 для шифрования RC4. |

### Возвращаемое значение

Верно для успеха.

### Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; // TestPath может быть переназначен.
string outFile = "D:\\output.pdf"; // TestPath может быть переназначен.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Смотрите также

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesecurity)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
