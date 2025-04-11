---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: طريقة الوثيقة. قم بتسريع الوثيقة لفتح الصفحة الأولى بأسرع ما يمكن، عرض الصفحة التالية أو اتباع الرابط إلى الصفحة التالية بأسرع ما يمكن، عرض الصفحة بشكل تدريجي عند وصول البيانات لصفحة ما عبر قناة بطيئة، عرض البيانات الأكثر فائدة أولاً، السماح بتفاعل المستخدم مثل اتباع رابط ليتم تنفيذه حتى قبل استلام الصفحة بالكامل وعرضها. استدعاء هذه الطريقة لا يحفظ الوثيقة فعليًا. على العكس، الوثيقة فقط مُعدة لتكون لها هيكل مُحسن، اتصل بعد ذلك بـ Save للحصول على وثيقة مُحسنة.
type: docs
weight: 750
url: /ar/net/aspose.pdf/document/optimize/
---
## Document.Optimize method

قم بتسريع الوثيقة لفتح الصفحة الأولى بأسرع ما يمكن؛ - عرض الصفحة التالية أو اتباع الرابط إلى الصفحة التالية بأسرع ما يمكن؛ - عرض الصفحة بشكل تدريجي عند وصول البيانات لصفحة ما عبر قناة بطيئة (عرض البيانات الأكثر فائدة أولاً)؛ - السماح بتفاعل المستخدم، مثل اتباع رابط، ليتم تنفيذه حتى قبل استلام الصفحة بالكامل وعرضها. استدعاء هذه الطريقة لا يحفظ الوثيقة فعليًا. على العكس، الوثيقة فقط مُعدة لتكون لها هيكل مُحسن، اتصل بعد ذلك بـ Save للحصول على وثيقة مُحسنة.

```csharp
public void Optimize()
```

### Examples

المثال التالي يوضح كيفية تحسين وثيقة PDF للويب.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimize for web
	pdfDocument.Optimize();

	// Save output document
	pdfDocument.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
	
    ' Open document
    Using pdfDocument As Document = New Document(pdfFilePath)

        ' Optimize for web
        pdfDocument.Optimize()

        ' Save output document
        pdfDocument.Save(pdfFilePath)
    End Using
```

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)