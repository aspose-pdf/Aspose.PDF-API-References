---
title: "Document.Optimize"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Document. Linearize المستند من أجل فتح الصفحة الأولى بأسرع ما يمكن، عرض الصفحة التالية أو اتباع الرابط إلى الصفحة التالية بأسرع ما يمكن، عرض الصفحة تدريجياً عند وصولها عندما يتم تسليم بيانات الصفحة عبر قناة بطيئة، عرض أكثر البيانات فائدة أولاً، السماح بتفاعل المستخدم مثل اتباع رابط يتم قبل استلام وعرض الصفحة بالكامل. استدعاء هذه الطريقة لا يحفظ المستند فعلياً. على العكس، يتم فقط إعداد المستند لهيكلة محسّنة؛ ثم استدعِ Save للحصول على المستند المحسّن."
type: docs
weight: 770
url: /ar/net/aspose.pdf/document/optimize/
---
## Document.Optimize method

قم بترتيب المستند لتتمكن من - فتح الصفحة الأولى بأسرع ما يمكن؛ - عرض الصفحة التالية أو الانتقال عبر رابط إلى الصفحة التالية بأسرع ما يمكن؛ - عرض الصفحة بشكل تدريجي عند وصولها عندما يتم تسليم بيانات الصفحة عبر قناة بطيئة (عرض أكثر البيانات فائدة أولاً)؛ - السماح بتفاعل المستخدم، مثل اتباع رابط، أن يتم حتى قبل استلام وعرض الصفحة بالكامل. استدعاء هذه الطريقة لا يحفظ المستند فعليًا. على العكس، يتم إعداد المستند فقط للحصول على بنية محسّنة، ثم استدعِ Save للحصول على المستند المحسّن.

```csharp
public void Optimize()
```

### أمثلة

المثال التالي يوضح كيفية تحسين مستند PDF للويب.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// فتح المستند
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// تحسين للويب
	pdfDocument.Optimize();

	// حفظ مستند الإخراج
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

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


