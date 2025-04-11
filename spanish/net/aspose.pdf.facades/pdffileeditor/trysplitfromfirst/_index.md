---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide el archivo Pdf desde la primera página hasta la ubicación especificada y guarda la parte frontal como un nuevo archivo
type: docs
weight: 460
url: /es/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Divide el archivo Pdf desde la primera página hasta la ubicación especificada y guarda la parte frontal como un nuevo archivo.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo Pdf de origen. |
| location | Int32 | El punto de división. |
| outputFile | String | Archivo Pdf de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Observaciones

El método TrySplitFromFirst es como el método SplitFromFirst, excepto que el método TrySplitFromFirst no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Stream del archivo Pdf de origen. |
| location | Int32 | El punto de división. |
| outputStream | Stream | Stream del archivo de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Observaciones

Los streams NO se cierran después de esta operación. El método TrySplitFromFirst es como el método SplitFromFirst, excepto que el método TrySplitFromFirst no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Divide el documento desde la primera página hasta la ubicación y guarda el resultado en objetos HttpResponse.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Nombre del archivo de origen. |
| location | Int32 | Punto de división. |
| response | HttpResponse | Objetos HttpResponse. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TrySplitFromFirst es como el método SplitFromFirst, excepto que el método TrySplitFromFirst no lanza una excepción si la operación falla.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Divide el documento desde el inicio hasta la ubicación especificada y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Stream del documento de origen. |
| location | Int32 | El punto de división. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TrySplitFromFirst es como el método SplitFromFirst, excepto que el método TrySplitFromFirst no lanza una excepción si la operación falla.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)