---
title: TryInsert
second_title: Referencia de API de Aspose.PDF para .NET
description: Inserta páginas de otro archivo en el archivo Pdf de entrada.
type: docs
weight: 450
url: /es/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_2}

Inserta páginas de otro archivo en el archivo Pdf de entrada.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

### Observaciones

El método TryInsert es como el método Insert, excepto que el método TryInsert no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Inserta páginas de otro archivo en el archivo Pdf de entrada.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryInsert es como el método Insert, excepto que el método TryInsert no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Inserta el contenido del archivo en el archivo de origen y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryInsert es como el método Insert, excepto que el método TryInsert no genera una excepción si la operación falla.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Inserta un documento en otro documento y almacena el resultado en el objeto de respuesta.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryInsert es como el método Insert, excepto que el método TryInsert no genera una excepción si la operación falla.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
