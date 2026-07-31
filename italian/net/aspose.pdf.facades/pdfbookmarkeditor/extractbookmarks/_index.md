---
title: "PdfBookmarkEditor.ExtractBookmarks"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfBookmarkEditor. Estrae i segnalibri di tutti i livelli dal documento."
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Estrae i segnalibri di tutti i livelli dal Document.

```csharp
public Bookmarks ExtractBookmarks()
```

### Valore di ritorno

La collezione di segnalibri di tutti i segnalibri presenti nel documento.

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Vedi anche

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Estrae i segnalibri di tutti i livelli dal Document.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| upperLevel | Boolean | Se vero, estrae solo i segnalibri di livello superiore. Altrimenti, estrae tutti i segnalibri ricorsivamente. |

### Valore di ritorno

Elenco dei segnalibri estratti.

### Vedi anche

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
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

### Valore di ritorno

La collezione di segnalibri contiene elementi con lo stesso titolo.

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Vedi anche

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Estrae i figli di un segnalibro con un titolo simile a quello del segnalibro specificato.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bookmark | Bookmark | Il segnalibro specificato. |

### Valore di ritorno

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

### Vedi anche

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


