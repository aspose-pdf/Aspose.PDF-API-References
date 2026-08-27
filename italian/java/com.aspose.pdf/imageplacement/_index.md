---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta le caratteristiche di un'immagine posizionata nella pagina di un documento Pdf. </p> <hr> <pre> L'esempio dimostra come trovare le immagini nella prima pagina del documento PDF e ottenere le immagini.</pre>"
type: docs
weight: 2330
url: /it/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> Rappresenta le caratteristiche di un'immagine posizionata nella pagina di un documento Pdf. </p> <hr> <pre> L'esempio dimostra come trovare le immagini nella prima pagina del documento PDF e ottenere le immagini come bitmap con dimensioni visibili. // Apri il documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crea l'oggetto ImagePlacementAbsorber per eseguire la ricerca del posizionamento dell'immagine ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(abs); // Recupera le immagini con dimensioni visibili for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Recupera l'immagine dalle risorse imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Crea un nuovo bitmap con le dimensioni effettive scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Quando un'immagine è posizionata su una pagina, può avere dimensioni diverse da quelle fisiche definite in {@code Resources}. L'oggetto {@code ImagePlacement} è destinato a fornire tali informazioni come dimensioni, risoluzione e così via. </p>

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | Ottiene i parametri di composizione dello stato grafico attivo per l'immagine posizionata nella pagina. |
| [getImage](#getImage--) | Ottiene l'oggetto risorsa XImage correlato. |
| [getMatrix](#getMatrix--) | Matrice di trasformazione corrente per questa immagine. |
| [getOperator](#getOperator--) | Operatore usato per visualizzare l'immagine. |
| [getPage](#getPage--) | Ottiene la pagina che contiene l'immagine. |
| [getRectangle](#getRectangle--) | Ottiene il rettangolo dell'Immagine. |
| [getResolution](#getResolution--) | Ottiene la risoluzione dell'Immagine. |
| [getRotation](#getRotation--) | Ottiene l'angolo di rotazione dell'Immagine. |
| [hide](#hide--) | Elimina l'immagine dalla pagina. |
| [replace](#replace-java.io.InputStream-) | Sostituisci l'immagine nella collezione con un'altra immagine. |
| [save](#save-java.io.OutputStream-) | Salva l'immagine con le trasformazioni corrispondenti: ridimensionamento, rotazione e risoluzione. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Salva l'immagine con le trasformazioni corrispondenti: ridimensionamento, rotazione e risoluzione. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

Ottiene i parametri di composizione dello stato grafico attivo per l'immagine posizionata nella pagina.

**Returns:**
Oggetto CompositingParameters

### getImage {#getImage--}
```
public XImage getImage()
```

Ottiene l'oggetto risorsa XImage correlato.

**Returns:**
oggetto XImage

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Matrice di trasformazione corrente per questa immagine.

**Returns:**
Oggetto Matrix

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

Operatore usato per visualizzare l'immagine.

**Returns:**
Istanza Operator

### getPage {#getPage--}
```
public Page getPage()
```

Ottiene la pagina che contiene l'immagine.

**Returns:**
oggetto Page

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ottiene il rettangolo dell'Immagine.

**Returns:**
oggetto Rectangle

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Ottiene la risoluzione dell'Immagine.

**Returns:**
Oggetto Resolution

### getRotation {#getRotation--}
```
public float getRotation()
```

Ottiene l'angolo di rotazione dell'Immagine.

**Returns:**
valore int

### hide {#hide--}
```
public final void hide()
```

Elimina l'immagine dalla pagina.

### replace {#replace-java.io.InputStream-}
Sostituisci l'immagine nella collezione con un'altra immagine.

### save {#save-java.io.OutputStream-}
Salva l'immagine con le trasformazioni corrispondenti: ridimensionamento, rotazione e risoluzione.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Salva l'immagine con le trasformazioni corrispondenti: ridimensionamento, rotazione e risoluzione.
