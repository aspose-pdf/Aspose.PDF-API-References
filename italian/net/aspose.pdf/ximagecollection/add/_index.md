---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: Metodo XImageCollection. Aggiunge una nuova immagine alla lista delle immagini. Questo metodo aggiunge l'immagine come riferimento allo stesso PdfObject, il che consente di ridurre la dimensione del file
type: docs
weight: 70
url: /it/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

Aggiunge una nuova immagine alla lista delle immagini. Questo metodo aggiunge l'immagine come riferimento allo stesso PdfObject (il che consente di ridurre la dimensione del file)

```csharp
public string Add(XImage image)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | XImage | XImage da aggiungere. |

### Valore di ritorno

Nome dell'immagine aggiunta.

### Vedi anche

* classe [XImage](../../ximage/)
* classe [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Aggiunge un'entità alla fine della collezione, in modo che l'entità possa essere accessibile dall'ultimo indice.

```csharp
public string Add(Stream image)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Stream | Stream contenente i dati dell'immagine (in formato JPEG). |

### Valore di ritorno

Nome dell'immagine aggiunta.

### Vedi anche

* classe [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Aggiunge un'entità alla fine della collezione, in modo che l'entità possa essere accessibile dall'ultimo indice.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Oggetto contenente un array di pixel e informazioni sul bitmap (Larghezza, Altezza, FormatoPixel). |

### Valore di ritorno

Nome dell'immagine aggiunta.

### Vedi anche

* classe [BitmapInfo](../../bitmapinfo/)
* classe [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Aggiunge un'entità alla fine della collezione, in modo che l'entità possa essere accessibile dall'ultimo indice.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Stream | Stream contenente i dati dell'immagine. |
| filterType | ImageFilterType | Il tipo di filtro dell'immagine. |

### Valore di ritorno

Nome dell'immagine aggiunta.

### Vedi anche

* enum [ImageFilterType](../../imagefiltertype/)
* classe [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Aggiunge un'entità alla fine della collezione, in modo che l'entità possa essere accessibile dall'ultimo indice.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Oggetto contenente un array di pixel e informazioni sul bitmap (Larghezza, Altezza, FormatoPixel). |
| filterType | ImageFilterType | Il tipo di filtro dell'immagine. |

### Valore di ritorno

Nome dell'immagine aggiunta.

### Vedi anche

* classe [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* classe [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Aggiunge un'entità alla fine della collezione, in modo che l'entità possa essere accessibile dall'ultimo indice.

```csharp
public void Add(Stream image, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Stream | Stream contenente i dati dell'immagine (in formato JPEG). |
| quality | Int32 | Qualità JPEG. |

### Vedi anche

* classe [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)