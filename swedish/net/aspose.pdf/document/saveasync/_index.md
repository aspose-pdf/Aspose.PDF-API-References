---
title: "Document.SaveAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document-metod. Sparar dokumentet till en ström med sparaalternativ"
type: docs
weight: 860
url: /sv/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Sparar dokumentet till en ström med sparalternativ.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där dokumentet kommer att lagras. |
| options | SaveOptions | Sparaalternativ. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | ArgumentException när [`HtmlSaveOptions`](../../htmlsaveoptions/) skickas till en metod. Att spara ett dokument till html-strömmen stöds inte. Använd metoden spara till filen. |

### Se även

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Lagrar document i en ström.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utdata | Stream | Ström där dokumentet ska lagras. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Sparar document i den angivna filen.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till filen där dokumentet kommer att lagras. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Spara document inkrementellt (dvs. med inkrementell uppdateringsteknik).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

## Anmärkningar

För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför måste Document initieras med en skrivbar ström som i följande kodsnutt: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // gör några ändringar och spara dokumentet inkrementellt doc.Save();

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Sparar document med sparalternativ.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | SaveOptions | Sparaalternativ. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se även

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Sparar document med ett nytt namn samt ett filformat.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till filen där dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se även

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Sparar document med ett nytt namn samt ett filformat.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |
| cancellationToken | CancellationToken | Avbrytningstoken |

### Returvärde

Asynkron uppgift.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | ArgumentException när [`HtmlSaveOptions`](../../htmlsaveoptions/) skickas till en metod. Att spara ett dokument till html-strömmen stöds inte. Använd metoden spara till filen. |

### Se även

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till filen där dokumentet kommer att lagras. |
| options | SaveOptions | Sparaalternativ. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Asynkron uppgift.

### Se även

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


