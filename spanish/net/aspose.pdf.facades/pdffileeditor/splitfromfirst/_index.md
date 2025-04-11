---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide el archivo Pdf desde la primera página hasta la ubicación especificada y guarda la parte frontal como un nuevo archivo
type: docs
weight: 340
url: /es/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Divide el archivo Pdf desde la primera página hasta la ubicación especificada y guarda la parte frontal como un nuevo archivo.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo Pdf de origen. |
| location | Int32 | El punto de división. |
| outputFile | String | Archivo Pdf de salida. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Stream del archivo Pdf de origen. |
| location | Int32 | El punto de división. |
| outputStream | Stream | Stream del archivo de salida. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Observaciones

Los streams NO se cierran después de esta operación.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)