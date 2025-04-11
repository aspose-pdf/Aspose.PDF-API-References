---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmetod. Lagrar dokumentet i ström
type: docs
weight: 840
url: /sv/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Lagrar dokumentet i ström.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | Stream | Ström där dokumentet ska lagras. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Sparar dokumentet i den angivna filen.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | Sträng | Sökväg till filen där dokumentet kommer att lagras. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Sparar dokumentet inkrementellt (dvs. med hjälp av inkrementell uppdateringsteknik).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

## Kommentarer

För att spara dokumentet inkrementellt måste vi öppna dokumentfilen för skrivning. Därför måste Document initialiseras med en skrivbar ström som i följande kodsnutt: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // gör några ändringar och spara dokumentet inkrementellt doc.Save();

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Sparar dokumentet med spara alternativ.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | SaveOptions | Spara alternativ. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se Även

* klass [SaveOptions](../../saveoptions/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Sparar dokumentet med ett nytt namn tillsammans med ett filformat.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | Sträng | Sökväg till filen där dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se Även

* enum [SaveFormat](../../saveformat/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Sparar dokumentet med ett nytt namn tillsammans med ett filformat.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Undantag

| undantag | tillstånd |
| --- | --- |
| ArgumentException | ArgumentException när [`HtmlSaveOptions`](../../htmlsaveoptions/) skickas till en metod. Att spara ett dokument till htmlström stöds inte. Vänligen använd metoden för att spara till fil. |

### Se Även

* enum [SaveFormat](../../saveformat/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Sparar dokumentet med ett nytt namn och ställer in dess spara alternativ.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | Sträng | Sökväg till filen där dokumentet kommer att lagras. |
| options | SaveOptions | Spara alternativ. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se Även

* klass [SaveOptions](../../saveoptions/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Sparar dokumentet till en ström med spara alternativ.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där dokumentet kommer att lagras. |
| options | SaveOptions | Spara alternativ. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Undantag

| undantag | tillstånd |
| --- | --- |
| ArgumentException | ArgumentException när [`HtmlSaveOptions`](../../htmlsaveoptions/) skickas till en metod. Att spara ett dokument till htmlström stöds inte. Vänligen använd metoden för att spara till fil. |

### Se Även

* klass [SaveOptions](../../saveoptions/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)