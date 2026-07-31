---
title: "PdfFileEditor.TrySplitFromFirst"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Divide il file Pdf dalla prima pagina fino alla posizione specificata e salva la parte iniziale come un nuovo file"
type: docs
weight: 460
url: /it/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Divide il file Pdf dalla prima pagina fino alla posizione specificata e salva la parte anteriore come nuovo file.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File Pdf di origine. |
| location | Int32 | Il punto di divisione. |
| outputFile | String | File Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Il metodo TrySplitFromFirst è simile al metodo SplitFromFirst, tranne che il metodo TrySplitFromFirst non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Divide dall'inizio fino alla posizione specificata e salva la parte anteriore nello Stream di output.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del file Pdf di origine. |
| location | Int32 | Il punto di divisione. |
| outputStream | Stream | Stream del file di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Gli stream NON vengono chiusi dopo questa operazione. Il metodo TrySplitFromFirst è simile al metodo SplitFromFirst, tranne che il metodo TrySplitFromFirst non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


