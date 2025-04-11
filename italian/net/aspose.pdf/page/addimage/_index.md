---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Metodo Page. Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine
type: docs
weight: 350
url: /it/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Il flusso dell'immagine. |
| imageRect | Rectangle | La posizione dell'immagine. |
| bbox | Rectangle | Bbox dell'immagine. |
| autoAdjustRectangle | Boolean | Regola l'immagine al centro del rettangolo di input. |

### Vedi Anche

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hocr | String | L'hocr dell'immagine. |
| imageStream | Stream | Il flusso dell'immagine. |
| imageRect | Rectangle | La posizione dell'immagine. |
| bbox | Rectangle | Il bbox dell'immagine. |

### Vedi Anche

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Aggiunge un'immagine alla pagina e la posiziona in base alla posizione del rettangolo dell'immagine.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | Stream | Il flusso dell'immagine. |
| imageRect | Rectangle | La posizione predefinita dell'immagine sulla pagina. |
| imageWidth | Int32 | La larghezza dell'immagine. |
| imageHeight | Int32 | L'altezza dell'immagine. |
| saveImageProportions | Boolean | Se il flag è impostato su true, l'immagine viene posizionata nella posizione del rettangolo; altrimenti, la dimensione del rettangolo diventa uguale alla dimensione dell'immagine. |
| bbox | Rectangle | Il bbox dell'immagine. |

### Vedi Anche

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imagePath | String | Il percorso dell'immagine. |
| rectangle | Rectangle | La posizione dell'immagine. |

### Vedi Anche

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)