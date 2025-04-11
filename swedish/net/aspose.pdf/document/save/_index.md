---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmetod. Lagrar dokument i ström
type: docs
weight: 830
url: /sv/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

Lagrar dokument i ström.

```csharp
public void Save(Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | Stream | Ström där dokumentet ska lagras. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Sparar dokumentet i den angivna filen.

```csharp
public void Save(string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till filen där dokumentet kommer att lagras. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Spara dokumentet inkrementellt (dvs. med hjälp av inkrementell uppdateringsteknik).

```csharp
public void Save()
```

## Kommentarer

För att spara dokumentet inkrementellt måste vi öppna dokumentfilen för skrivning. Därför måste Document initialiseras med en skrivbar ström som i nästa kodsnutt: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // gör några ändringar och spara dokumentet inkrementellt doc.Save();

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Sparar dokumentet med spara alternativ.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | SaveOptions | Spara alternativ. |

### Se Även

* klass [SaveOptions](../../saveoptions/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Sparar dokumentet med ett nytt namn tillsammans med ett filformat.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till filen där dokumentet kommer att lagras. |
| format | SaveFormat | Format alternativ. |

### Se Även

* enum [SaveFormat](../../saveformat/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Sparar dokumentet med ett nytt namn tillsammans med ett filformat.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där dokumentet kommer att lagras. |
| format | SaveFormat | Format alternativ. |

### Undantag

| undantag | tillstånd |
| --- | --- |
| ArgumentException | ArgumentException när [`HtmlSaveOptions`](../../htmlsaveoptions/) skickas till en metod. Att spara ett dokument till html-ström stöds inte. Vänligen använd metoden spara till filen. |

### Se Även

* enum [SaveFormat](../../saveformat/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Sparar dokumentet med ett nytt namn och ställer in dess spara alternativ.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till filen där dokumentet kommer att lagras. |
| options | SaveOptions | Spara alternativ. |

### Se Även

* klass [SaveOptions](../../saveoptions/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Sparar dokumentet till en ström med spara alternativ.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där dokumentet kommer att lagras. |
| options | SaveOptions | Spara alternativ. |

### Undantag

| undantag | tillstånd |
| --- | --- |
| ArgumentException | ArgumentException när [`HtmlSaveOptions`](../../htmlsaveoptions/) skickas till en metod. Att spara ett dokument till html-ström stöds inte. Vänligen använd metoden spara till filen. |

### Se Även

* klass [SaveOptions](../../saveoptions/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)