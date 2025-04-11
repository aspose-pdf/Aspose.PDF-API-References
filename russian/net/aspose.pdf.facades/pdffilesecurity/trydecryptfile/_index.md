---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSecurity. Расшифровывает зашифрованный Pdf документ с помощью пароля владельца. Если у документа нет пароля владельца, разрешается использовать пароль пользователя. Не вызывает исключение, если процесс завершился неудачей.
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## Метод PdfFileSecurity.TryDecryptFile

Расшифровывает зашифрованный Pdf документ с помощью пароля владельца. Если у документа нет пароля владельца, разрешается использовать пароль пользователя. Не вызывает исключение, если процесс завершился неудачей.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | String | Пароль владельца. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### См. также

* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)