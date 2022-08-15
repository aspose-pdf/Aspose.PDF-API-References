---
title: Append
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ajoute des pages qui sont choisies dans un tableau de documents dans portStreams. Le document de résultat inclut firstInputFile et toutes les pages de documents portStreams dans la plage startPage à endPage.
type: docs
weight: 280
url: /fr/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Ajoute des pages, qui sont choisies dans un tableau de documents dans portStreams. Le document de résultat inclut firstInputFile et toutes les pages de documents portStreams dans la plage startPage à endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_4}

Ajoute des pages, qui sont choisies parmi les documents portFiles. Le document de résultat inclut firstInputFile et toutes les pages de documents portFiles dans la plage startPage to endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
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

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_3}

Ajoute les pages, qui sont choisies dans portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Saisir le fichier Pdf. |
| portFile | String | Pages du fichier Pdf. |
| startPage | Int32 | La page commence dans portFile. |
| endPage | Int32 | La page se termine par portFile. |
| outputFile | String | Document PDF de sortie. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Ajoute des pages, qui sont choisies dans portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Fichier d'entrée Flux. |
| portStream | Stream | Pages du fichier Pdf Stream. |
| startPage | Int32 | La page commence dans portFile Stream. |
| endPage | Int32 | La page se termine par portFile Stream. |
| outputStream | Stream | Flux de fichiers Pdf de sortie. |

### Return_Value

Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Append(Stream, Stream[], int, int, HttpResponse) {#append_2}

Ajoute des documents au document source et enregistre le résultat dans l'objet de réponse.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

true si l'opération a réussi.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, HttpResponse) {#append_5}

Ajoute des documents au document source et enregistre le résultat dans l'objet HttpResponse.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
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

true si l'opération a réussi.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
