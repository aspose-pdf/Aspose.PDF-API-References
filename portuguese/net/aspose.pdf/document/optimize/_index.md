---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Método Document. Linearize o documento para abrir a primeira página o mais rápido possível, exibir a próxima página ou seguir por link para a próxima página o mais rápido possível, exibir a página incrementalmente à medida que chega quando os dados de uma página são entregues por um canal lento, exibir os dados mais úteis primeiro, permitir interação do usuário, como seguir um link, a ser realizada mesmo antes que a página inteira tenha sido recebida e exibida. Invocar este método não salva realmente o documento. Pelo contrário, o documento é apenas preparado para ter uma estrutura otimizada, chame então Salvar para obter o documento otimizado.
type: docs
weight: 750
url: /pt/net/aspose.pdf/document/optimize/
---
## Método Document.Optimize

Linearize o documento para - abrir a primeira página o mais rápido possível; - exibir a próxima página ou seguir por link para a próxima página o mais rápido possível; - exibir a página incrementalmente à medida que chega quando os dados de uma página são entregues por um canal lento (exibir os dados mais úteis primeiro); - permitir interação do usuário, como seguir um link, a ser realizada mesmo antes que a página inteira tenha sido recebida e exibida. Invocar este método não salva realmente o documento. Pelo contrário, o documento é apenas preparado para ter uma estrutura otimizada, chame então Salvar para obter o documento otimizado.

```csharp
public void Optimize()
```

### Exemplos

O seguinte exemplo mostra como otimizar um documento PDF para a web.

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

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)