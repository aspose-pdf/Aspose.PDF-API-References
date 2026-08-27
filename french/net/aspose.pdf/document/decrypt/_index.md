---
title: "Document.Decrypt"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Document. Déchiffre le document. Appelez ensuite Save pour obtenir la version déchiffrée du document"
type: docs
weight: 620
url: /fr/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

Déchiffre le document. Appelez ensuite Save pour obtenir la version déchiffrée du document.

```csharp
public void Decrypt()
```

### Exemples

Le code d'exemple suivant montre comment déchiffrer un fichier PDF.

```csharp
[C#]
	// Le chemin vers votre fichier PDF.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Ouvrir le document
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// Décrypter le PDF
		document.Decrypt();

		// Enregistrer le PDF mis à jour
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

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


