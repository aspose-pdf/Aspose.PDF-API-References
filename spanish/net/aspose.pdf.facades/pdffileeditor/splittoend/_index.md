---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide desde la ubicación y guarda la parte trasera como un nuevo archivo
type: docs
weight: 360
url: /es/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Divide desde la ubicación especificada y guarda la parte trasera como un nuevo archivo Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Stream del archivo Pdf fuente. |
| location | Int32 | La posición de división. |
| outputStream | Stream | Stream del archivo Pdf de salida. |

### Valor de Retorno

True para éxito, o false.

## Observaciones

Los streams NO se cierran después de esta operación a menos que se especifique CloseConcatedStreams.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Divide desde la ubicación y guarda la parte trasera como un nuevo archivo.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo Pdf fuente. |
| location | Int32 | La posición de división. |
| outputFile | String | Ruta del archivo Pdf de salida. |

### Valor de Retorno

True para éxito, o false.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Divide desde la ubicación especificada y guarda la parte trasera como un nuevo archivo Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Stream del archivo Pdf fuente. |
| location | Int32 | La posición de división. |
| outputStream | Stream | Stream del archivo Pdf de salida. |

### Valor de Retorno

True para éxito, o false.

## Observaciones

Los streams NO se cierran después de esta operación a menos que se especifique CloseConcatedStreams.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)