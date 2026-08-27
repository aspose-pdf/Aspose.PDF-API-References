---
title: "Tampon"
linktitle: "Tampon"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant un tampon."
type: docs
weight: 700
url: /fr/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

Classe représentant un tampon.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Stamp](#Stamp--) | Constructeur pour l'objet Stamp. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | Définit l'image qui sera utilisée comme tampon. |
| [bindImage](#bindImage-java.lang.String-) | <p> Définit l'image comme un tampon. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Définit le texte comme un tampon. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | Définit l'état du texte du tampon. |
| [close](#close--) | Ferme cette instance. |
| [getBlendingSpace](#getBlendingSpace--) | Obtient une valeur BlendingColorSpace qui définit un espace colorimétrique utilisé pour effectuer des opérations de transparence et de fusion sur la page. |
| [getOpacity](#getOpacity--) | Obtient l'opacité du tampon. |
| [getPageNumber](#getPageNumber--) | Obtient le numéro de page. |
| [getPages](#getPages--) | Obtient un tableau avec les numéros de pages qui seront affectés par le tampon. |
| [getQuality](#getQuality--) | Obtient la qualité du tampon image en pourcentage. Valeurs valides 0..100%. |
| [getRotation](#getRotation--) | Obtient la rotation du tampon en degrés. |
| [getStampId](#getStampId--) | Obtient l'identifiant du tampon. |
| [isBackground](#isBackground--) | Obtient le statut d'arrière-plan. Si vrai, le tampon sera placé en arrière-plan de la page tamponnée. Par défaut, il est défini sur false. |
| [setBackground](#setBackground-boolean-) | Définit le statut d'arrière-plan. Si vrai, le tampon sera placé en arrière-plan de la page tamponnée. Par défaut, il est défini sur false. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | Définit une valeur BlendingColorSpace qui définit un espace colorimétrique utilisé pour effectuer des opérations de transparence et de fusion sur la page. |
| [setImageSize](#setImageSize-float-float-) | Définit la taille du tampon image. L'image sera redimensionnée selon les valeurs spécifiées. |
| [setOpacity](#setOpacity-float-) | Définit l'opacité du tampon. |
| [setOrigin](#setOrigin-float-float-) | Définit la position sur la page où le tampon sera placé. |
| [setPageNumber](#setPageNumber-int-) | Définit le numéro de page. |
| [setPages](#setPages-int:A-) | <p> Définit un tableau avec les numéros de pages qui seront affectés par le tampon. Si Pages = null, toutes les pages du document sont affectées. </p> |
| [setQuality](#setQuality-int-) | Définit la qualité du tampon image en pourcentage. Valeurs valides 0..100%. |
| [setRotation](#setRotation-float-) | <p> Obtient ou définit la rotation du tampon en degrés. </p> |
| [setStampId](#setStampId-int-) | Définit l'identifiant du tampon. |

### Stamp {#Stamp--}
```
public Stamp()
```

Constructeur pour l'objet Stamp.

### bindImage {#bindImage-java.io.InputStream-}
Définit l'image qui sera utilisée comme tampon.

### bindImage {#bindImage-java.lang.String-}
<p> Définit l'image comme un tampon. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
Définit le texte comme un tampon.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
Définit l'état du texte du tampon.

### close {#close--}
```
public void close()
```

Ferme cette instance.

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

Obtient une valeur BlendingColorSpace qui définit un espace colorimétrique utilisé pour effectuer des opérations de transparence et de fusion sur la page.

**Returns:**
valeur int @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

Obtient l'opacité du tampon.

**Returns:**
Valeur flottante

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Obtient le numéro de page.

**Returns:**
valeur int

### getPages {#getPages--}
```
public int[] getPages()
```

Obtient un tableau avec les numéros de pages qui seront affectés par le tampon.

**Returns:**
tableau d'int

### getQuality {#getQuality--}
```
public int getQuality()
```

Obtient la qualité du tampon image en pourcentage. Valeurs valides 0..100%.

**Returns:**
valeur int

### getRotation {#getRotation--}
```
public float getRotation()
```

Obtient la rotation du tampon en degrés.

**Returns:**
Valeur flottante

### getStampId {#getStampId--}
```
public int getStampId()
```

Obtient l'identifiant du tampon.

**Returns:**
valeur int

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Obtient le statut d'arrière-plan. Si vrai, le tampon sera placé en arrière-plan de la page tamponnée. Par défaut, il est défini sur false.

**Returns:**
valeur booléenne

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Définit le statut d'arrière-plan. Si vrai, le tampon sera placé en arrière-plan de la page tamponnée. Par défaut, il est défini sur false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
Définit une valeur BlendingColorSpace qui définit un espace colorimétrique utilisé pour effectuer des opérations de transparence et de fusion sur la page.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

Définit la taille du tampon image. L'image sera redimensionnée selon les valeurs spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de l'image. |
| hauteur |  | Hauteur de l'image. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

Définit l'opacité du tampon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

Définit la position sur la page où le tampon sera placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| originX |  | Coordonnée X du tampon. |
| originY |  | Coordonnée Y du tampon. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Définit le numéro de page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> Définit un tableau avec les numéros de pages qui seront affectés par le tampon. Si Pages = null, toutes les pages du document sont affectées. </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | tableau d'entiers <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Définit la qualité du tampon image en pourcentage. Valeurs valides 0..100%.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> Obtient ou définit la rotation du tampon en degrés. </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur flottante <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Définit l'identifiant du tampon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
