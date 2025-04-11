---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSecurity. Устанавливает безопасность Pdf файла с пустыми паролями пользователя/владельца. Пароль владельца будет добавлен случайной строкой. Вызывает исключение, если процесс завершился неудачно
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Устанавливает безопасность Pdf файла с пустыми паролями пользователя/владельца. Пароль владельца будет добавлен случайной строкой. Вызывает исключение, если процесс завершился неудачно.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| privilege | DocumentPrivilege | Установить привилегию. |

### Возвращаемое значение

True для успеха.

## Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### См. также

* класс [DocumentPrivilege](../../documentprivilege/)
* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Устанавливает безопасность Pdf файла с оригинальным паролем. Вызывает исключение, если процесс завершился неудачно.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Оригинальный пароль пользователя. |
| ownerPassword | String | Оригинальный пароль владельца. |
| privilege | DocumentPrivilege | Установить привилегию. |

### Возвращаемое значение

True для успеха.

## Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### См. также

* класс [DocumentPrivilege](../../documentprivilege/)
* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)