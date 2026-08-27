---
title: "Classe Image"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Image classe. Représente une image."
type: docs
weight: 5990
url: /fr/net/aspose.pdf/image/
---
## Image class

Représente une image.

```csharp
public sealed class Image : BaseParagraph
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Image](image/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Obtient ou définit les octets d'image non compressés. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Obtient la taille du bitmap de l'image. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Obtient ou définit le fichier image. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Obtient ou définit le type de fichier image. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Obtient ou définit la hauteur de l'image. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Obtient ou définit la largeur de l'image. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du paragraphe |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur PDF). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Obtient ou définit l'échelle de l'image. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Obtient ou définit le flux de l'image. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'image utilise la résolution lors de la génération. |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'image est forcée à être en noir et blanc. Si une image TIFF du sous‑format CCITT est utilisée, cette propriété doit être définie sur true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Obtient ou définit une valeur chaîne qui indique le titre de l'image. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Clone l'image. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Renvoie le type MIME de l'image. |

## Exemples

L'exemple suivant montre comment convertir des images (PNG, JPEG, GIF, BMP ou d'autres formats d'image) en fichier PDF.

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre image (bmp, png, gif, jpeg, etc.) fichier.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// Le chemin du fichier PDF de sortie.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Initialiser un PDF Document vide
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Charger le fichier image d'exemple
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Enregistrer le PDF Document de sortie
	  pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir = "YOUR_DATA_DIRECTORY"

    ' The path to your image (bmp, png, gif, jpeg, etc.) File.
    Dim imageFile = Path.Combine(dataDir, "Image-to-PDF.png")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf")
 
    'Initialize empty PDF document
    Using pdfDocument As Document = New Document()
        pdfDocument.Pages.Add()
        Dim image As Image = New Image()
 
        ' Load sample image file
        image.File = imageFile
        pdfDocument.Pages(1).Paragraphs.Add(image)
 
        ' Save output PDF document
        pdfDocument.Save(pdfFile)
    End Using
```

### Voir aussi

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


