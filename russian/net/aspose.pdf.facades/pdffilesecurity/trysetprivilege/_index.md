---
title: "PdfFileSecurity.TrySetPrivilege"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileSecurity. Устанавливает безопасность PDF‑файла с оригинальным паролем. Не выбрасывает исключение, если процесс завершился неудачей"
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege method

Устанавливает безопасность PDF‑файла с оригинальным паролем. Не бросает исключение при неудаче процесса.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Исходный пароль пользователя. |
| ownerPassword | String | Исходный пароль владельца. |
| привилегия | DocumentPrivilege | Установить привилегию. |

### Возвращаемое значение

True при успехе, иначе false.

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

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


