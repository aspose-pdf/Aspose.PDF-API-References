---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSecurity. Устанавливает безопасность Pdf файла с оригинальным паролем. Не вызывает исключение, если процесс завершился неудачно
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## Метод PdfFileSecurity.TrySetPrivilege

Устанавливает безопасность Pdf файла с оригинальным паролем. Не вызывает исключение, если процесс завершился неудачно.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Оригинальный пароль пользователя. |
| ownerPassword | String | Оригинальный пароль владельца. |
| privilege | DocumentPrivilege | Установить привилегию. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### См. также

* класс [DocumentPrivilege](../../documentprivilege/)
* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)