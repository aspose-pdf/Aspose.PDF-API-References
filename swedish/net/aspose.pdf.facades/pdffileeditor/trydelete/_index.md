---
title: TryDelete
second_title: Aspose.PDF för .NET API Referens
description: Tar bort sidor specificerade av nummermatris från inmatningsfilen sparar som en ny pdf-fil.
type: docs
weight: 430
url: /sv/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_2}

Tar bort sidor specificerade av nummermatris från inmatningsfilen, sparar som en ny pdf-fil.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Indatafilsökväg. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputFile | String | Utdatafilens sökväg. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryDelete-metoden är som Delete-metoden, förutom att TryDelete -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Tar bort sidor specificerade av nummermatris från inmatningsfilen, sparar som en ny pdf-fil.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafil Stream. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputStream | Stream | Utdatafilström. |

### Returvärde

Sant för framgång, eller falskt.

### Anmärkningar

TryDelete-metoden är som Delete-metoden, förutom att TryDelete -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Tar bort specificerade sidor från dokument och lagrar resultatet till HttpResponse-objekt.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Sökväg till källfilen. |
| pageNumber | Int32[] | Uppsättning av sidnummer som måste raderas. |
| response | HttpResponse | Svarsobjekt där resultatdokumentet kommer att lagras. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryDelete-metoden är som Delete-metoden, förutom att TryDelete -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Tar bort angivna sidor från dokument och sparar resultatet i HttpResponse-objekt.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Källdokumentström. |
| pageNumber | Int32[] | Matris med sidnummer som kommer att raderas. |
| response | HttpResponse | HttpResponse-objekt |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryDelete-metoden är som Delete-metoden, förutom att TryDelete -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->