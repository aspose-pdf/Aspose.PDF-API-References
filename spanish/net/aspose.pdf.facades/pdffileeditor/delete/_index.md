---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Elimina las páginas especificadas por el array de números del archivo de entrada y guarda como un nuevo archivo Pdf
type: docs
weight: 270
url: /es/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Elimina las páginas especificadas por el array de números del archivo de entrada, guarda como un nuevo archivo Pdf.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de entrada. |
| pageNumber | Int32[] | Índice de la página del archivo de entrada. |
| outputFile | String | Ruta del archivo de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Elimina las páginas especificadas por el array de números del archivo de entrada, guarda como un nuevo archivo Pdf.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del archivo de entrada. |
| pageNumber | Int32[] | Índice de la página del archivo de entrada. |
| outputStream | Stream | Flujo del archivo de salida. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)