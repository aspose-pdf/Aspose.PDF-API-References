---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue Pdf-Datei
type: docs
weight: 400
url: /de/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue Pdf-Datei.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Eingabedatei. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputFile | String | Pfad zur Ausgabedatei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die TryDelete-Methode ist wie die Delete-Methode, mit dem Unterschied, dass die TryDelete-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue Pdf-Datei.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedatei-Stream. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputStream | Stream | Ausgabedatei-Stream. |

### Rückgabewert

True für Erfolg oder false.

## Anmerkungen

Die TryDelete-Methode ist wie die Delete-Methode, mit dem Unterschied, dass die TryDelete-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Löscht die angegebenen Seiten aus dem Dokument und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Quelldatei. |
| pageNumber | Int32[] | Array von Seitennummern, die gelöscht werden müssen. |
| response | HttpResponse | Antwortobjekt, in dem das Ergebnisdokument gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die TryDelete-Methode ist wie die Delete-Methode, mit dem Unterschied, dass die TryDelete-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Löscht die angegebenen Seiten aus dem Dokument und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Quelldokuments. |
| pageNumber | Int32[] | Array von Seitennummern, die gelöscht werden. |
| response | HttpResponse | HttpResponse-Objekt |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die TryDelete-Methode ist wie die Delete-Methode, mit dem Unterschied, dass die TryDelete-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)