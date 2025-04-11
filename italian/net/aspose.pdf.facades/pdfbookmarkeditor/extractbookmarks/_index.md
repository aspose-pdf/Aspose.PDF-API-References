---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfBookmarkEditor. Estrae i segnalibri di tutti i livelli dal documento
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Estrae i segnalibri di tutti i livelli dal documento.

```csharp
public Bookmarks ExtractBookmarks()
```

### Valore di Ritorno

La collezione di segnalibri di tutti i segnalibri che esistono nel documento.

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Vedi Anche

* classe [Bookmarks](../../bookmarks/)
* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Estrae i segnalibri di tutti i livelli dal documento.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| upperLevel | Boolean | Se vero, estrae solo i segnalibri di livello superiore. Altrimenti, estrae tutti i segnalibri ricorsivamente. |

### Valore di Ritorno

Elenco dei segnalibri estratti.

### Vedi Anche

* classe [Bookmarks](../../bookmarks/)
* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

Estrae i segnalibri con il titolo specificato.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| title | String | Titolo dell'elemento estratto. |

### Valore di Ritorno

La collezione di segnalibri ha elementi con lo stesso titolo.

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Vedi Anche

* classe [Bookmarks](../../bookmarks/)
* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Estrae i figli di un segnalibro con un titolo simile al segnalibro specificato.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bookmark | Bookmark | Il segnalibro specificato. |

### Valore di Ritorno

Collezione di segnalibri con segnalibri figli.

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Vedi Anche

* classe [Bookmarks](../../bookmarks/)
* classe [Bookmark](../../bookmark/)
* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)