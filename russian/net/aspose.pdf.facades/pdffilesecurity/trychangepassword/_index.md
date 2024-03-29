---
title: TryChangePassword
second_title: Aspose.PDF для справочника API .NET
description: Изменяет пароль пользователя и пароль владельца на пароль владельца сохраняя исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен. Не генерирует исключение если процесс завершился неудачно. со случайной строкой если новый пароль владельца пустой или нулевой.
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Изменяет пароль пользователя и пароль владельца на пароль владельца, сохраняя исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен. Не генерирует исключение, если процесс завершился неудачно. со случайной строкой, если новый пароль владельца пустой или нулевой.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | String | Оригинальный пароль владельца. |
| newUserPassword | String | Новый пароль пользователя. |
| newOwnerPassword | String | Новый пароль владельца. |

### Возвращаемое значение

Верно для успеха или ложно.

### Примеры

```csharp
[C#]
 string inFile = "D:\\input.pdf"; // TestPath может быть переназначен.
 string outFile = "D:\\output.pdf";	// TestPath может быть переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Смотрите также

* class [PdfFileSecurity](../../pdffilesecurity)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesecurity)
* сборка [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен на случайной строкой, если новый пароль владельца недействителен или пуст.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | String | Оригинальный пароль владельца. |
| newUserPassword | String | Новый пароль пользователя. |
| newOwnerPassword | String | Новый пароль владельца. |
| privilege | DocumentPrivilege | Сбросить безопасность. |
| keySize | KeySize | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |

### Возвращаемое значение

Верно для успеха или ложно.

### Примеры

```csharp
[C#]
string inFile = ".D:\\input.pdf"; // TestPath может быть переназначен.
string outFile = "D:\\output.pdf";	// TestPath может быть переназначен.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Смотрите также

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesecurity)
* сборка [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен на случайной строкой, если новый пароль владельца недействителен или пуст. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) недействительны, и соответствующее исключение будет вызвано, если комплект встретит эту комбинацию.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | String | Оригинальный пароль владельца. |
| newUserPassword | String | Новый пароль пользователя. |
| newOwnerPassword | String | Новый пароль владельца. |
| privilege | DocumentPrivilege | Сбросить безопасность. |
| keySize | KeySize | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |
| cipher | Algorithm | Algorithm.AES для шифрования с использованием алгоритма AES или Algorithm.RC4 для шифрования RC4. |

### Возвращаемое значение

Верно для успеха или ложно.

### Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; // TestPath может быть переназначен.
string outFile = "D:\\output.pdf";	// TestPath может быть переназначен.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Смотрите также

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesecurity)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
