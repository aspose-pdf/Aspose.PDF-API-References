---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Elimina le pagine specificate dall'array di numeri dal file di input e salva come un nuovo file Pdf
type: docs
weight: 270
url: /it/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Percorso del file di input. |
| pageNumber | Int32[] | Indice della pagina nel file di input. |
| outputFile | String | Percorso del file di output. |

### Return Value

True se l'operazione è riuscita.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream del file di input. |
| pageNumber | Int32[] | Indice della pagina nel file di input. |
| outputStream | Stream | Stream del file di output. |

### Return Value

True per successo, o false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)