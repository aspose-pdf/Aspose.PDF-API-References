---
title: "Classe Image"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Image classe. Rappresenta un'immagine."
type: docs
weight: 5990
url: /it/net/aspose.pdf/image/
---
## Image class

Rappresenta un'immagine.

```csharp
public sealed class Image : BaseParagraph
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Image](image/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Ottiene o imposta i byte dell'immagine non compressi. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Ottiene la dimensione del bitmap dell'immagine. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Ottiene o imposta il file dell'immagine. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Ottiene o imposta il tipo di file dell'immagine. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Ottiene o imposta l'altezza dell'immagine. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Ottiene o imposta la larghezza dell'immagine. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del paragrafo. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore PDF). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Ottiene o imposta la scala dell'immagine. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Ottiene o imposta lo stream dell'immagine. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'immagine utilizza la risoluzione durante la generazione. |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Ottiene o imposta un valore bool che indica se l'immagine è forzata a bianco e nero. Se viene utilizzata un'immagine TIFF del sottoformato CCITT, questa proprietà deve essere impostata su true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false. (per la generazione PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false. (per la generazione PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di PDF) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Ottiene o imposta un valore stringa che indica il titolo dell'immagine. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del paragrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Clona l'immagine. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Restituisce il tipo MIME per l'immagine. |

## Esempi

Il seguente esempio mostra come convertire le immagini (PNG, JPEG, GIF, BMP o altri formati immagine) in un file PDF.

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Il percorso della tua immagine (bmp, png, gif, jpeg, ecc.) File.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// Il percorso del file PDF di output.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Inizializza un documento PDF vuoto
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Carica il file immagine di esempio
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Salva il documento PDF di output
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

### Vedi anche

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


