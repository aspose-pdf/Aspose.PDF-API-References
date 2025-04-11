---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Ajoute des pages choisies à partir d'un tableau de documents dans portStreams. Le document résultant comprend firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage
type: docs
weight: 380
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Ajoute des pages, qui sont choisies à partir d'un tableau de documents dans portStreams. Le document résultant comprend firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux Pdf d'entrée. |
| portStreams | Stream[] | Documents à partir desquels copier des pages. |
| startPage | Int32 | La page commence dans les documents portStreams. |
| endPage | Int32 | La page se termine dans les documents portStreams. |
| outputStream | Stream | Flux Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TryAppend est semblable à la méthode Append, sauf que la méthode TryAppend ne lance pas d'exception si l'opération échoue.

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

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Ajoute des pages, qui sont choisies à partir des documents portFiles. Le document résultant comprend firstInputFile et toutes les pages des documents portFiles dans la plage startPage à endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf d'entrée. |
| portFiles | String[] | Documents à partir desquels copier des pages. |
| startPage | Int32 | La page commence dans les documents portFiles. |
| endPage | Int32 | La page se termine dans les documents portFiles. |
| outputFile | String | Document Pdf de sortie. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TryAppend est semblable à la méthode Append, sauf que la méthode TryAppend ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Ajoute des documents au document source et enregistre le résultat dans l'objet de réponse.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux contenant le document source. |
| portStreams | Stream[] | Tableau de flux avec des documents à ajouter. |
| startPage | Int32 | Page de début de la page ajoutée. |
| endPage | Int32 | Page de fin des pages ajoutées. |
| response | HttpResponse | Objet de réponse où le document sera enregistré. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TryAppend est semblable à la méthode Append, sauf que la méthode TryAppend ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Ajoute des documents au document source et enregistre le résultat dans l'objet HttpResponse.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Nom du fichier contenant le document source. |
| portFiles | String[] | Tableau de noms de fichiers contenant les documents ajoutés. |
| startPage | Int32 | Page de début des pages ajoutées. |
| endPage | Int32 | Page de fin des pages ajoutées. |
| response | HttpResponse | Objet de réponse où le document sera enregistré. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TryAppend est semblable à la méthode Append, sauf que la méthode TryAppend ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)