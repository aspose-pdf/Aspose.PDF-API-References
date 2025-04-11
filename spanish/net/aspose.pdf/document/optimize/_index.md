---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Método de documento. Linealizar el documento para abrir la primera página lo más rápido posible, mostrar la siguiente página o seguir por enlace a la siguiente página lo más rápido posible, mostrar la página de manera incremental a medida que llega cuando los datos para una página se entregan a través de un canal lento, mostrar los datos más útiles primero, permitir la interacción del usuario, como seguir un enlace, que se realice incluso antes de que se haya recibido y mostrado toda la página. Invocar este método no guarda realmente el documento. Por el contrario, el documento solo está preparado para tener una estructura optimizada, llame luego a Guardar para obtener el documento optimizado.
type: docs
weight: 750
url: /es/net/aspose.pdf/document/optimize/
---
## Método Document.Optimize

Linealizar el documento para - abrir la primera página lo más rápido posible; - mostrar la siguiente página o seguir por enlace a la siguiente página lo más rápido posible; - mostrar la página de manera incremental a medida que llega cuando los datos para una página se entregan a través de un canal lento (mostrar los datos más útiles primero); - permitir la interacción del usuario, como seguir un enlace, que se realice incluso antes de que se haya recibido y mostrado toda la página. Invocar este método no guarda realmente el documento. Por el contrario, el documento solo está preparado para tener una estructura optimizada, llame luego a Guardar para obtener el documento optimizado.

```csharp
public void Optimize()
```

### Ejemplos

El siguiente ejemplo muestra cómo optimizar un documento PDF para la web.

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

### Ver También

* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)