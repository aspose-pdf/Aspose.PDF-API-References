---
title: "SvgExtractor.Extract"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode SvgExtractor. Extrait l'image svg en chaîne à partir des éléments graphiques représentés par l'absorbeur avec un filtre prédicat"
type: docs
weight: 20
url: /fr/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Extrait l'image svg vers une chaîne à partir des éléments graphiques représentés par !:absorber avec un filtre prédicat.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| absorbeur | GraphicsAbsorber | L'objet GraphicsAbsorber qui contient les éléments graphiques. |
| filtre | Predicate`1 | Une fonction prédicat utilisée pour filtrer les éléments graphiques. |
| page | Page | La page où l'absorbeur obtient les éléments graphiques. |

### Valeur de retour

La chaîne contenant le contenu SVG.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si une erreur s'est produite lors de la conversion en SVG. |

### Voir aussi

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Extrait l'image svg vers un fichier à partir des éléments graphiques représentés par !:absorber avec un filtre prédicat.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| absorbeur | GraphicsAbsorber | L'objet GraphicsAbsorber qui contient les éléments graphiques. |
| filtre | Predicate`1 | Une fonction prédicat utilisée pour filtrer les éléments graphiques. |
| page | Page | La page où l'absorbeur obtient les éléments graphiques. |
| svgFilePath | String | Le chemin du fichier SVG cible. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si une erreur s'est produite lors de la conversion en SVG. |

### Voir aussi

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Extrait les éléments graphiques dans une chaîne SVG. Options ignorées - regroupement, extraction depuis un rectangle.

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| éléments | IEnumerable`1 | Les éléments graphiques à convertir. |
| page | Page | La page où l'absorbeur obtient les éléments graphiques. |

### Valeur de retour

La chaîne contenant le contenu SVG.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si une erreur s'est produite lors de la conversion en SVG. |

### Voir aussi

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Extrait les éléments graphiques dans un seul fichier SVG. Options ignorées - regroupement, extraction depuis un rectangle.

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| éléments | IEnumerable`1 | Les éléments graphiques à convertir. |
| page | Page | La page où l'absorbeur obtient les éléments graphiques. |
| svgFilePath | String | Le chemin du fichier SVG cible. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si une erreur s'est produite lors de la conversion en SVG. |

### Voir aussi

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Extrait des images Svg d'une page vers des chaînes.

```csharp
public List<string> Extract(Page page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | La page à extraire. |

### Valeur de retour

La liste des chaînes de contenu SVG.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si une erreur s'est produite lors de la conversion en SVG. |

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Extrait des images Svg d'une page vers des fichiers.

```csharp
public void Extract(Page page, string directory)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | La page à extraire. |
| répertoire | String | Le répertoire cible où placer les images SVG. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si une erreur s'est produite lors de la conversion en SVG. |

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


