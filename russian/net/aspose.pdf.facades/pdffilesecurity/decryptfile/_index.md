---
title: "PdfFileSecurity.DecryptFile"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileSecurity. Расшифровывает зашифрованный PDF‑документ с помощью пароля владельца. Если у документа нет пароля владельца, допускается использование пароля пользователя. Выбрасывает исключение, если процесс завершился неудачей"
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile method

Расшифровывает зашифрованный PDF‑документ с помощью пароля владельца. Если у документа нет пароля владельца, допускается использование пароля пользователя. Выбрасывает исключение, если процесс завершился неудачей.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | String | Пароль владельца. |

### Возвращаемое значение

True при успехе.

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

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


