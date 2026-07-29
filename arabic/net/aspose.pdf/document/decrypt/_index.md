---
title: "Document.Decrypt"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Document. تقوم بفك تشفير المستند. استدعِ ثم احفظ للحصول على نسخة غير مشفرة من المستند"
type: docs
weight: 620
url: /ar/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

يفك تشفير المستند. استدعِ ثم احفظ للحصول على نسخة غير مشفرة من المستند.

```csharp
public void Decrypt()
```

### أمثلة

يوضح الكود النموذجي التالي كيفية فك تشفير ملف PDF.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// فتح المستند
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// فك تشفير PDF
		document.Decrypt();

		// احفظ ملف PDF المحدث
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

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


