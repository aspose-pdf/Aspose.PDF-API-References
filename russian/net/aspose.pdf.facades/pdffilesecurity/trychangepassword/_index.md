---
title: PdfFileSecurity.TryChangePassword
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSecurity. Изменяет пароль пользователя и пароль владельца, при этом пароль владельца сохраняет оригинальные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен на случайную строку, если новый пароль владельца равен null или пустой. Не вызывает исключение, если процесс завершился неудачно.
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Изменяет пароль пользователя и пароль владельца по паролю владельца, сохраняет оригинальные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен на случайную строку, если новый пароль владельца равен null или пустой. Не вызывает исключение, если процесс завершился неудачно.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | String | Оригинальный пароль владельца. |
| newUserPassword | String | Новый пароль пользователя. |
| newOwnerPassword | String | Новый пароль владельца. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### См. также

* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Изменяет пароль пользователя и пароль по паролю владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен на случайную строку, если новый пароль владельца равен null или пустой. Не вызывает исключение, если процесс завершился неудачно.

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
| keySize | KeySize | KeySize.x40 для 40 битного шифрования, KeySize.x128 для 128 битного шифрования и KeySize.x256 для 256 битного шифрования. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### См. также

* класс [DocumentPrivilege](../../documentprivilege/)
* перечисление [KeySize](../../keysize/)
* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Изменяет пароль пользователя и пароль по паролю владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен на случайную строку, если новый пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) являются недопустимыми, и соответствующее исключение будет вызвано, если комплект столкнется с этой комбинацией. Не вызывает исключение, если процесс завершился неудачно.

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
| keySize | KeySize | KeySize.x40 для 40 битного шифрования, KeySize.x128 для 128 битного шифрования и KeySize.x256 для 256 битного шифрования. |
| cipher | Algorithm | Algorithm.AES для шифрования с использованием алгоритма AES или Algorithm.RC4 для шифрования RC4. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### См. также

* класс [DocumentPrivilege](../../documentprivilege/)
* перечисление [KeySize](../../keysize/)
* перечисление [Algorithm](../../algorithm/)
* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)