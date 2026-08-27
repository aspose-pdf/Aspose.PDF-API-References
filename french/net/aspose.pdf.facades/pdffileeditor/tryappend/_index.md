---
title: "PdfFileEditor.TryAppend"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Ajoute des pages qui sont choisies à partir d'un tableau de documents dans portStreams. Le document résultant comprend firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage."
type: docs
weight: 380
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Ajoute les pages, choisies dans un tableau de documents dans portStreams. Le document résultant comprend firstInputFile et toutes les pages des documents portStreams dans la plage de startPage à endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux Pdf d'entrée. |
| portStreams | Stream[] | Documents dont les pages seront copiées. |
| startPage | Int32 | La page commence dans les documents portStreams. |
| endPage | Int32 | La page se termine dans les documents portStreams . |
| outputStream | Stream | Flux Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TryAppend est similaire à la méthode Append, sauf que la méthode TryAppend ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Ajoute les pages, choisies dans les documents portFiles. Le document résultant comprend firstInputFile et toutes les pages des documents portFiles dans la plage de startPage à endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf d'entrée. |
| portFiles | String[] | Documents dont les pages seront copiées. |
| startPage | Int32 | La page commence dans les documents portFiles. |
| endPage | Int32 | La page se termine dans les documents portFiles . |
| outputFile | String | Document Pdf de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryAppend est similaire à la méthode Append, sauf que la méthode TryAppend ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


