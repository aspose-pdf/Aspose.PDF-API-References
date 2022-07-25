---
title: Insert
second_title: Referencia de API de Aspose.PDF para .NET
description: Inserta páginas de otro archivo en el archivo PDF en una posición.
type: docs
weight: 320
url: /es/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_3}

Inserta páginas de otro archivo en el archivo PDF en una posición.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo PDF de entrada. |
| insertLocation | Int32 | Posición en el archivo de entrada. |
| portFile | String | El archivo Pdf de la portabilidad. |
| startPage | Int32 | Posición de inicio en portFile. |
| endPage | Int32 | Posición final en portFile. |
| outputFile | String | Archivo PDF de salida. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Inserta páginas de otro archivo en el archivo Pdf de entrada.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de entrada del archivo PDF. |
| insertLocation | Int32 | Insertar posición en el archivo de entrada. |
| portStream | Stream | Secuencia de archivo Pdf para páginas. |
| startPage | Int32 | Desde qué página empezar. |
| endPage | Int32 | A qué página terminar. |
| outputStream | Stream | Salida de corriente. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_4}

Inserta páginas de otro archivo en el archivo Pdf de entrada.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo PDF de entrada. |
| insertLocation | Int32 | Insertar posición en el archivo de entrada. |
| portFile | String | Páginas del archivo Pdf. |
| pageNumber | Int32[] | El número de página del archivo portado en portFile. |
| outputFile | String | Archivo PDF de salida. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Inserta páginas de otro archivo en el archivo Pdf de entrada.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de entrada del archivo PDF. |
| insertLocation | Int32 | Insertar posición en el archivo de entrada. |
| portStream | Stream | Secuencia de archivo Pdf para páginas. |
| pageNumber | Int32[] | El número de página del archivo portado en portFile. |
| outputStream | Stream | Salida de corriente. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], HttpResponse) {#insert_5}

Inserta el contenido del archivo en el archivo de origen y almacena el resultado en el objeto HttpResponse.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Nombre del archivo de origen. |
| insertLocation | Int32 | Número de página donde se insertará el segundo archivo. |
| portFile | String | Ruta al archivo que se insertará. |
| pageNumber | Int32[] | Matriz de números de página en el archivo de origen que se insertará. |
| response | HttpResponse | Objeto de respuesta donde se almacenará el resultado. |

### Valor_devuelto

verdadero de la inserción fue exitosa.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], HttpResponse) {#insert_2}

Inserta un documento en otro documento y almacena el resultado en el objeto de respuesta.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Transmisión con documento de origen |
| insertLocation | Int32 | Ubicación donde se insertará otro documento. |
| portStream | Stream | Documento a insertar. |
| pageNumber | Int32[] | Matriz de números de página en el segundo documento que se insertará. |
| response | HttpResponse | Objeto de respuesta donde se almacenará el resultado. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
