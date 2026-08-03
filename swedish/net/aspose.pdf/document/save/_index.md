---
title: "Document.Save"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document-metod. Sparar dokumentet till en ström med sparaalternativ"
type: docs
weight: 850
url: /sv/net/aspose.pdf/document/save/
---
## Save(Stream, SaveOptions) {#save_4}

Sparar dokumentet till en ström med sparalternativ.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där dokumentet kommer att lagras. |
| options | SaveOptions | Sparaalternativ. |

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

## Save(Stream) {#save_2}

Lagrar document i en ström.

```csharp
public void Save(Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utdata | Stream | Ström där dokumentet ska lagras. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Sparar document i den angivna filen.

```csharp
public void Save(string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till filen där dokumentet kommer att lagras. |

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Spara document inkrementellt (dvs. med inkrementell uppdateringsteknik).

```csharp
public void Save()
```

## Anmärkningar

För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför måste Document initieras med en skrivbar ström som i följande kodsnutt: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // gör några ändringar och spara dokumentet inkrementellt doc.Save();

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Sparar document med sparalternativ.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | SaveOptions | Sparaalternativ. |

### Se även

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Sparar document med ett nytt namn samt ett filformat.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till filen där dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |

### Se även

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Sparar document med ett nytt namn samt ett filformat.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |

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

## Save(string, SaveOptions) {#save_7}

Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till filen där dokumentet kommer att lagras. |
| options | SaveOptions | Sparaalternativ. |

### Se även

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


