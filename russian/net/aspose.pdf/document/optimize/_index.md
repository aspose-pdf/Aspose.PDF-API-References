---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Метод Document. Линеаризуйте документ, чтобы как можно быстрее открыть первую страницу, отобразить следующую страницу или перейти по ссылке на следующую страницу как можно быстрее, отображать страницу по мере её поступления, когда данные для страницы передаются по медленному каналу, отображать наиболее полезные данные в первую очередь, разрешить взаимодействие с пользователем, такое как переход по ссылке, даже до того, как вся страница будет получена и отображена. Вызов этого метода на самом деле не сохраняет документ. Напротив, документ только подготавливается к оптимизированной структуре, затем вызовите Save, чтобы получить оптимизированный документ.
type: docs
weight: 750
url: /ru/net/aspose.pdf/document/optimize/
---
## Метод Document.Optimize

Линеаризуйте документ, чтобы - как можно быстрее открыть первую страницу; - отобразить следующую страницу или перейти по ссылке на следующую страницу как можно быстрее; - отображать страницу по мере её поступления, когда данные для страницы передаются по медленному каналу (отображать наиболее полезные данные в первую очередь); - разрешить взаимодействие с пользователем, такое как переход по ссылке, даже до того, как вся страница будет получена и отображена. Вызов этого метода на самом деле не сохраняет документ. Напротив, документ только подготавливается к оптимизированной структуре, затем вызовите Save, чтобы получить оптимизированный документ.

```csharp
public void Optimize()
```

### Примеры

Следующий пример показывает, как оптимизировать PDF-документ для веба.

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

### См. также

* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)