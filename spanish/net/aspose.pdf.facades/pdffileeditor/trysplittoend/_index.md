---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide desde la ubicación y guarda la parte trasera como un nuevo archivo
type: docs
weight: 470
url: /es/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Divide desde la ubicación y guarda la parte trasera como un nuevo archivo.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo Pdf de origen. |
| location | Int32 | La posición de división. |
| outputFile | String | Ruta del archivo Pdf de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Observaciones

El método TrySplitToEnd es como el método SplitToEnd, excepto que el método TrySplitToEnd no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Divide desde la ubicación especificada y guarda la parte trasera como un nuevo archivo Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Stream del archivo Pdf de origen. |
| location | Int32 | La posición de división. |
| outputStream | Stream | Stream del archivo Pdf de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Observaciones

Los streams NO se cierran después de esta operación a menos que se especifique CloseConcatedStreams. El método TrySplitToEnd es como el método SplitToEnd, excepto que el método TrySplitToEnd no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Divide desde la ubicación especificada y guarda la parte trasera en el objeto HttpResponse.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Stream del documento de origen. |
| location | Int32 | Punto de división. |
| response | HttpResponse | Objeto HttpResponse. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TrySplitToEnd es como el método SplitToEnd, excepto que el método TrySplitToEnd no lanza una excepción si la operación falla.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Divide desde la ubicación especificada y guarda la parte trasera en el objeto HttpResponse.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | nombre del archivo de origen. |
| location | Int32 | Punto de división. |
| response | HttpResponse | Objetos HttpResponse. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TrySplitToEnd es como el método SplitToEnd, excepto que el método TrySplitToEnd no lanza una excepción si la operación falla.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)