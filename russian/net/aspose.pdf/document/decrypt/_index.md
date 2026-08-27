---
title: "Document.Decrypt"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Document. Расшифровывает документ. Затем вызовите Save, чтобы получить расшифрованную версию документа"
type: docs
weight: 620
url: /ru/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

Расшифровывает документ. Затем вызовите Save, чтобы получить расшифрованную версию документа.

```csharp
public void Decrypt()
```

### Примеры

Следующий пример кода показывает, как расшифровать PDF‑файл.

```csharp
[C#]
	// Путь к вашему файлу PDF.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Открыть документ
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// Расшифровать PDF
		document.Decrypt();

		// Сохранить обновлённый PDF
		document.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"

    ' Open document
    Using document As Document = New Document(pdfFilePath, "YOUR_PASSWORD")

        ' Decrypt PDF
        document.Decrypt()

        ' Save updated PDF
        document.Save(pdfFilePath)
    End Using
```

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


