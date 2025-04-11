---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSecurity. Расшифровывает зашифрованный Pdf документ с помощью пароля владельца. Если у документа нет пароля владельца, разрешается использовать пароль пользователя. Вызывает исключение, если процесс завершился неудачно.
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## Метод PdfFileSecurity.DecryptFile

Расшифровывает зашифрованный Pdf документ с помощью пароля владельца. Если у документа нет пароля владельца, разрешается использовать пароль пользователя. Вызывает исключение, если процесс завершился неудачно.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | String | Пароль владельца. |

### Возвращаемое значение

True для успеха.

## Примеры

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### См. также

* класс [PdfFileSecurity](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)