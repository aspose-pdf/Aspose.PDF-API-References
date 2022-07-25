---
title: Save
second_title: Aspose.PDF för .NET API Referens
description: Spara dokument stegvis dvs. med inkrementell uppdateringsteknik.
type: docs
weight: 720
url: /sv/net/aspose.pdf/document/save/
---
## Save() {#save}

Spara dokument stegvis (dvs. med inkrementell uppdateringsteknik).

```csharp
public void Save()
```

### Anmärkningar

För att spara dokument stegvis bör vi öppna dokumentfilen för skrivning. Därför måste dokument initieras med skrivbar ström som i nästa kodavsnitt: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // gör några ändringar och spara dokumentet inkrementellt doc.Save();

### Se även

* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Sparar dokumentet med sparalternativ.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | SaveOptions | Spara alternativ. |

### Se även

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Sparar dokumentet med ett nytt namn tillsammans med ett filformat.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till fil där dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |

### Se även

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Sparar dokumentet med ett nytt namn tillsammans med ett filformat.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streama var dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | ArgumentException när[`HtmlSaveOptions`](../../htmlsaveoptions) överförs till en metod. Spara ett dokument till HTML-strömmen stöds inte. Använd metoden spara till filen. |

### Se även

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till fil där dokumentet kommer att lagras. |
| options | SaveOptions | Spara alternativ. |

### Se även

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Sparar dokumentet i en ström med ett sparalternativ.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streama var dokumentet kommer att lagras. |
| options | SaveOptions | Spara alternativ. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | ArgumentException när[`HtmlSaveOptions`](../../htmlsaveoptions) överförs till en metod. Spara ett dokument till HTML-strömmen stöds inte. Använd metoden spara till filen. |

### Se även

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Save(HttpResponse, string, ContentDisposition, SaveOptions) {#save_8}

Sparar dokumentet i en svarsström med ett sparalternativ.

```csharp
public void Save(HttpResponse response, string outputFileName, ContentDisposition disposition, 
    SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| response | HttpResponse | Kapslar in HTTP-svarsinformation. |
| outputFileName | String | Enkelt filnamn, dvs utan sökväg. |
| disposition | ContentDisposition | Representerar ett MIME-protokoll Content-Disposition-huvud. |
| options | SaveOptions | Spara alternativ. |

### Se även

* enum [ContentDisposition](../../contentdisposition)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Lagrar dokument i stream.

```csharp
public void Save(Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | Stream | Streama där dokumentskalet lagras. |

### Se även

* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Sparar dokument i den angivna filen.

```csharp
public void Save(string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | String | Sökväg till fil där dokumentet kommer att lagras. |

### Se även

* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
