---
title: "Document.Optimize"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Document. Linéariser le document afin d'ouvrir la première page le plus rapidement possible, d'afficher la page suivante ou de suivre le lien vers la page suivante le plus rapidement possible, d'afficher la page de façon incrémentielle à mesure qu'elle arrive lorsque les données d'une page sont livrées sur un canal lent, d'afficher d'abord les données les plus utiles, de permettre l'interaction de l'utilisateur, comme suivre un lien, même avant que la page entière n'ait été reçue et affichée. L'appel de cette méthode n'enregistre pas réellement le document. Au contraire, le document est seulement préparé avec une structure optimisée ; il faut ensuite appeler Save pour obtenir le document optimisé."
type: docs
weight: 770
url: /fr/net/aspose.pdf/document/optimize/
---
## Document.Optimize method

Linéariser le document afin de - ouvrir la première page le plus rapidement possible ; - afficher la page suivante ou suivre le lien vers la page suivante le plus rapidement possible ; - afficher la page de façon incrémentielle dès qu'elle arrive lorsque les données d'une page sont livrées sur un canal lent (afficher d'abord les données les plus utiles) ; - permettre l'interaction de l'utilisateur, comme le suivi d'un lien, d'être effectuée même avant que la page entière n'ait été reçue et affichée. L'appel de cette méthode ne sauvegarde pas réellement le document. Au contraire, le document n'est préparé qu'à avoir une structure optimisée, appelez ensuite Save pour obtenir le document optimisé.

```csharp
public void Optimize()
```

### Exemples

L'exemple suivant montre comment optimiser un document PDF pour le Web.

```csharp
[C#]
	// Le chemin vers votre fichier PDF.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Ouvrir le document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimiser pour le Web
	pdfDocument.Optimize();

	// Enregistrer le document de sortie
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

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


