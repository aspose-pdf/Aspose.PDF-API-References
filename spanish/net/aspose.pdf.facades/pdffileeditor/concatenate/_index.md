---
title: Concatenate
second_title: Referencia de API de Aspose.PDF para .NET
description: Concatena dos archivos.
type: docs
weight: 290
url: /es/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_5}

Concatena dos archivos.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| firstInputFile | String | Primer archivo a concatenar. |
| secInputFile | String | Segundo archivo a concatenar. |
| outputFile | String | Archivo de salida. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Concatena dos archivos.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| firstInputStream | Stream | Transmisión del primer archivo. |
| secInputStream | Stream | Transmisión del segundo archivo. |
| outputStream | Stream | Secuencia donde se almacenará el archivo de resultados. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Concatena documentos.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| src | Document[] | Matriz de documentos fuente. |
| dest | Document | Documento de destino. |

### Valor_devuelto

True si la concatenación se realiza correctamente.

### Ver también

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_7}

Concatena archivos en un solo archivo.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFiles | String[] | Matriz de archivos para concatenar. |
| outputFile | String | Nombre del archivo de salida. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Concatena archivos

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream[] | Matriz de secuencias que se van a concatenar. |
| outputStream | Stream | Secuencia donde se almacenará el archivo de resultados. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_6}

Combina dos documentos PDF en un nuevo documento PDF con páginas de forma alternativa y llena los espacios en blanco con páginas en blanco. p. ej.: el documento 1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. La fusión de los dos documentos PDF producirá el documento de resultado con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco .

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| firstInputFile | String | Primer archivo. |
| secInputFile | String | Segundo archivo. |
| blankPageFile | String | Archivo PDF con página en blanco. |
| outputFile | String | Archivo de resultados. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Combina dos documentos PDF en un nuevo documento PDF con páginas de forma alternativa y llena los espacios en blanco con páginas en blanco. p. ej.: el documento 1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. La fusión de los dos documentos PDF producirá el documento de resultado con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco .

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| firstInputStream | Stream | La primera secuencia de PDF. |
| secInputStream | Stream | La segunda secuencia de PDF. |
| blankPageStream | Stream | El Pdf Stream con página en blanco. |
| outputStream | Stream | Flujo de PDF de salida. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Concatenate(string[], HttpResponse) {#concatenate_8}

Concatena archivos y guarda el resultado en el objeto HttpResposnse.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFiles | String[] | Matriz de archivos para concatenar. |
| response | HttpResponse | Objeto de respuesta. |

### Valor_devuelto

true si la concatenación fue exitosa.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Concatena archivos y almacena el resultado en el objeto HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream[] | Matriz de flujos que contienen archivos para concatenar. |
| response | HttpResponse | Objeto de respuesta/ |

### Valor_devuelto

verdadero si la operación se realizó correctamente.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
