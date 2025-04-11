---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Méthode Document. Linéariser le document afin d'ouvrir la première page aussi rapidement que possible, afficher la page suivante ou suivre un lien vers la page suivante aussi rapidement que possible, afficher la page de manière incrémentielle à mesure qu'elle arrive lorsque les données d'une page sont livrées sur un canal lent, afficher d'abord les données les plus utiles, permettre l'interaction de l'utilisateur, comme suivre un lien, même avant que la page entière ait été reçue et affichée. L'invocation de cette méthode ne sauvegarde pas réellement le document. Au contraire, le document est seulement préparé pour avoir une structure optimisée, appelez ensuite Save pour obtenir le document optimisé.
type: docs
weight: 750
url: /fr/net/aspose.pdf/document/optimize/
---
## Méthode Document.Optimize

Linéariser le document afin de - ouvrir la première page aussi rapidement que possible ; - afficher la page suivante ou suivre un lien vers la page suivante aussi rapidement que possible ; - afficher la page de manière incrémentielle à mesure qu'elle arrive lorsque les données d'une page sont livrées sur un canal lent (afficher d'abord les données les plus utiles) ; - permettre l'interaction de l'utilisateur, comme suivre un lien, même avant que la page entière ait été reçue et affichée. L'invocation de cette méthode ne sauvegarde pas réellement le document. Au contraire, le document est seulement préparé pour avoir une structure optimisée, appelez ensuite Save pour obtenir le document optimisé.

```csharp
public void Optimize()
```

### Exemples

L'exemple suivant montre comment optimiser un document PDF pour le web.

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

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)