---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Extrai marcadores de todos os níveis do documento
type: docs
weight: 60
url: /pt/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Extrai marcadores de todos os níveis do documento.

```csharp
public Bookmarks ExtractBookmarks()
```

### Return Value

A coleção de marcadores de todos os marcadores que existem no documento.

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### See Also

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Extrai marcadores de todos os níveis do documento.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| upperLevel | Boolean | Se verdadeiro, extrai apenas marcadores de nível superior. Caso contrário, extrai todos os marcadores recursivamente. |

### Return Value

Lista de marcadores extraídos.

### See Also

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

Extrai os marcadores com o título especificado.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parameter | Type | Description |
| --- | --- | --- |
| title | String | Título do item extraído. |

### Return Value

A coleção de marcadores contém itens com o mesmo título.

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### See Also

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Extrai os filhos de um marcador com um título como no marcador especificado.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | Bookmark | O marcador especificado. |

### Return Value

Coleção de marcadores com marcadores filhos.

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### See Also

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)