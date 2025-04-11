---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Inserta páginas de otro archivo en el archivo Pdf en una posición
type: docs
weight: 290
url: /es/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

Inserta páginas de otro archivo en el archivo Pdf en una posición.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo Pdf de entrada. |
| insertLocation | Int32 | Posición en el archivo de entrada. |
| portFile | String | El archivo Pdf de portación. |
| startPage | Int32 | Posición de inicio en portFile. |
| endPage | Int32 | Posición final en portFile. |
| outputFile | String | Archivo Pdf de salida. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Ver También

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Inserta páginas de otro archivo en el archivo Pdf de entrada.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de entrada del archivo Pdf. |
| insertLocation | Int32 | Posición de inserción en el archivo de entrada. |
| portStream | Stream | Flujo del archivo Pdf para páginas. |
| startPage | Int32 | Desde qué página comenzar. |
| endPage | Int32 | Hasta qué página terminar. |
| outputStream | Stream | Flujo de salida. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Ver También

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

Inserta páginas de otro archivo en el archivo Pdf de entrada.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo Pdf de entrada. |
| insertLocation | Int32 | Posición de inserción en el archivo de entrada. |
| portFile | String | Páginas del archivo Pdf. |
| pageNumber | Int32[] | El número de página de la portación en portFile. |
| outputFile | String | Archivo Pdf de salida. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Ver También

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Inserta páginas de otro archivo en el archivo Pdf de entrada.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de entrada del archivo Pdf. |
| insertLocation | Int32 | Posición de inserción en el archivo de entrada. |
| portStream | Stream | Flujo del archivo Pdf para páginas. |
| pageNumber | Int32[] | El número de página de la portación en portFile. |
| outputStream | Stream | Flujo de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Ver También

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)