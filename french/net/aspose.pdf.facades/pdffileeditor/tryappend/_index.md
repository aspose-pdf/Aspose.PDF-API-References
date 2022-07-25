---
title: TryAppend
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ajoute des pages qui sont choisies dans un tableau de documents dans portStreams. Le document de résultat inclut firstInputFile et toutes les pages de documents portStreams dans la plage startPage à endPage.
type: docs
weight: 410
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Ajoute des pages, qui sont choisies dans un tableau de documents dans portStreams. Le document de résultat inclut firstInputFile et toutes les pages de documents portStreams dans la plage startPage à endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée PDF. |
| portStreams | Stream[] | Documents à partir desquels copier des pages. |
| startPage | Int32 | La page commence dans les documents portStreams. |
| endPage | Int32 | La page se termine dans les documents portStreams . |
| outputStream | Stream | Flux de sortie PDF. |

### Return_Value

Vrai pour le succès, ou faux.

### Remarques

La méthode TryAppend est similaire à la méthode Append, sauf que la méthode TryAppend ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_2}

Ajoute des pages, qui sont choisies parmi les documents portFiles. Le document de résultat inclut firstInputFile et toutes les pages de documents portFiles dans la plage startPage to endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Saisir le fichier Pdf. |
| portFiles | String[] | Documents à partir desquels copier des pages. |
| startPage | Int32 | La page commence dans les documents portFiles. |
| endPage | Int32 | La page se termine dans les documents portFiles . |
| outputFile | String | Document PDF de sortie. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryAppend est similaire à la méthode Append, sauf que la méthode TryAppend ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Ajoute des documents au document source et enregistre le résultat dans l'objet de réponse.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux qui contient le document source. |
| portStreams | Stream[] | Tableau de flux avec des documents à annexer. |
| startPage | Int32 | Page de démarrage de la page jointe. |
| endPage | Int32 | Page de fin des pages jointes. |
| response | HttpResponse | Objet de réponse où le document sera enregistré. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryAppend est similaire à la méthode Append, sauf que la méthode TryAppend ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Ajoute des documents au document source et enregistre le résultat dans l'objet HttpResponse.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Nom du fichier contenant le document source. |
| portFiles | String[] | Tableau de noms de fichiers contenant des documents joints. |
| startPage | Int32 | Page de démarrage des pages jointes. |
| endPage | Int32 | Page de fin des pages jointes. |
| response | HttpResponse | Objet de réponse où le document sera enregistré. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryAppend est similaire à la méthode Append, sauf que la méthode TryAppend ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
