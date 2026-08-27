---
title: "PdfBookmarkEditor.ExtractBookmarks"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfBookmarkEditor méthode. Extrait les signets de tous les niveaux du document"
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Extrait les signets de tous les niveaux du document.

```csharp
public Bookmarks ExtractBookmarks()
```

### Valeur de retour

La collection de signets de tous les signets présents dans le document.

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Voir aussi

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Extrait les signets de tous les niveaux du document.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| upperLevel | Boolean | Si vrai, extrait uniquement les signets de niveau supérieur. Sinon, extrait tous les signets de manière récursive. |

### Valeur de retour

Liste des signets extraits.

### Voir aussi

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

Extrait les signets avec le titre spécifié.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| title | String | Titre de l'élément extrait. |

### Valeur de retour

La collection de signets contient des éléments avec le même titre.

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Voir aussi

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Extrait les enfants d'un signet dont le titre correspond à celui du signet spécifié.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signet | Signet | Le signet spécifié. |

### Valeur de retour

Collection de signets avec des signets enfants.

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Voir aussi

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


