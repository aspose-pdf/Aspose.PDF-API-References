---
title: SetPrivilege
second_title: Aspose.PDF для справочника API .NET
description: Устанавливает безопасность файла Pdf с пустыми паролями пользователя/владельца. Пароль владельца будет добавлен случайной строкой. Выдает исключение если процесс завершился неудачно.
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Устанавливает безопасность файла Pdf с пустыми паролями пользователя/владельца. Пароль владельца будет добавлен случайной строкой. Выдает исключение, если процесс завершился неудачно.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| privilege | DocumentPrivilege | Установить привилегию. |

### Возвращаемое значение

Верно для успеха.

### Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; // TestPath может быть переназначен.
string outFile = "D:\\output.pdf"; // TestPath может быть переназначен.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### Смотрите также

* class [DocumentPrivilege](../../documentprivilege)
* class [PdfFileSecurity](../../pdffilesecurity)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesecurity)
* сборка [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Устанавливает безопасность файла Pdf с исходным паролем. Выдает исключение, если процесс завершился неудачно.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Оригинальный пароль пользователя. |
| ownerPassword | String | Оригинальный пароль владельца. |
| privilege | DocumentPrivilege | Установить привилегию. |

### Возвращаемое значение

Верно для успеха.

### Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; // TestPath может быть переназначен.
string outFile = "D:\\output.pdf"; // TestPath может быть переназначен.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Смотрите также

* class [DocumentPrivilege](../../documentprivilege)
* class [PdfFileSecurity](../../pdffilesecurity)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesecurity)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->