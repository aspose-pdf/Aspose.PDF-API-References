---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Extrae marcadores de todos los niveles del documento
type: docs
weight: 60
url: /es/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Extrae marcadores de todos los niveles del documento.

```csharp
public Bookmarks ExtractBookmarks()
```

### Valor de Retorno

La colección de marcadores de todos los marcadores que existen en el documento.

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Véase También

* clase [Bookmarks](../../bookmarks/)
* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Extrae marcadores de todos los niveles del documento.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| upperLevel | Booleano | Si es verdadero, extrae solo marcadores de nivel superior. De lo contrario, extrae todos los marcadores de forma recursiva. |

### Valor de Retorno

Lista de marcadores extraídos.

### Véase También

* clase [Bookmarks](../../bookmarks/)
* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

Extrae los marcadores con el título especificado.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| title | Cadena | Título del ítem extraído. |

### Valor de Retorno

La colección de marcadores tiene ítems con el mismo título.

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Véase También

* clase [Bookmarks](../../bookmarks/)
* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Extrae los hijos de un marcador con un título como en el marcador especificado.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bookmark | Marcador | El marcador especificado. |

### Valor de Retorno

Colección de marcadores con marcadores hijos.

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Véase También

* clase [Bookmarks](../../bookmarks/)
* clase [Bookmark](../../bookmark/)
* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)