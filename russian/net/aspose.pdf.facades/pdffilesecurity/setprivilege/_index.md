---
title: "PdfFileSecurity.SetPrivilege"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileSecurity. Устанавливает безопасность PDF‑файла с пустыми паролями пользователя/владельца. Пароль владельца будет заменён случайной строкой. Выбрасывает исключение, если процесс завершился неудачно"
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Устанавливает безопасность PDF‑файла с пустыми паролями пользователя/владельца. Пароль владельца будет заменён случайной строкой. Выбрасывает исключение, если процесс завершился неудачей.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| привилегия | DocumentPrivilege | Установить привилегию. |

### Возвращаемое значение

True при успехе.

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

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Устанавливает безопасность PDF‑файла с оригинальным паролем. Выбрасывает исключение, если процесс завершился неудачей.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Исходный пароль пользователя. |
| ownerPassword | String | Исходный пароль владельца. |
| привилегия | DocumentPrivilege | Установить привилегию. |

### Возвращаемое значение

True при успехе.

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

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


