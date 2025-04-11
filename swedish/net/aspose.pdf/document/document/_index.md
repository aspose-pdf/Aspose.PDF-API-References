---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Dokumentkonstruktör. Initiera en ny Document-instans från inmatningsströmmen
type: docs
weight: 10
url: /sv/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Initiera en ny Document-instans från *inmatnings*strömmen.

```csharp
public Document(Stream input)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | Stream | Ström med pdf-dokument. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

Initiera en ny Document-instans från *inmatnings*strömmen.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | Stream | Ström med pdf-dokument. |
| isManagedStream | Boolean | om inställt på `true` stängs inre ström innan utgång; annars görs det inte. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

Initiera en ny Document-instans från *inmatnings*strömmen.

```csharp
public Document(Stream input, string password)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | Stream | Inmatningsströmobjekt, motsvarande pdf är lösenordsskyddad. |
| password | String | Användar- eller ägarlösenord. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_6}

Initiera en ny Document-instans från *inmatnings*strömmen.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | Stream | Ström med pdf-dokument. |
| password | String | Användar- eller ägarlösenord. |
| isManagedStream | Boolean | Om inställt på `true` stängs inre ström innan utgång; annars görs det inte. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_7}

Initiera bara Document med *filnamn*. Samma som `Document`.

```csharp
public Document(string filename)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | Namnet på pdf-dokumentfilen. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_9}

Initiera bara Document med *filnamn*. Samma som `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | Namnet på pdf-dokumentfilen. |
| isManagedStream | Boolean | Om inställt på `true` stängs inre ström innan utgång; annars görs det inte. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_10}

Initierar en ny instans av [`Document`](../) klassen för att arbeta med krypterat dokument.

```csharp
public Document(string filename, string password)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | Dokumentfilnamn. |
| password | String | Användar- eller ägarlösenord. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_11}

Initierar en ny instans av [`Document`](../) klassen för att arbeta med krypterat dokument.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | Dokumentfilnamn. |
| password | String | Användar- eller ägarlösenord. |
| isManagedStream | Boolean | om inställt på `true` stängs inre ström innan utgång; annars görs det inte. |

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Initierar ett tomt dokument.

```csharp
public Document()
```

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

Initierar ett tomt dokument efter version.

```csharp
public Document(PdfVersion version)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| version | PdfVersion | PDF-versionen. |

### Se Även

* enum [PdfVersion](../../pdfversion/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_8}

Öppnar ett befintligt dokument från en fil och tillhandahåller nödvändiga konverteringsalternativ för att få pdf-dokument.

```csharp
public Document(string filename, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | Inmatningsfil för att konvertera till pdf-dokument. |
| options | LoadOptions | Representerar egenskaper för att konvertera *filnamn* till pdf-dokument. |

### Se Även

* klass [LoadOptions](../../loadoptions/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Öppnar ett befintligt dokument från en ström och tillhandahåller nödvändiga konverteringsalternativ för att få pdf-dokument.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | Stream | Inmatningsström för att konvertera till pdf-dokument. |
| options | LoadOptions | Representerar egenskaper för att konvertera *inmatning* till pdf-dokument. |

### Se Även

* klass [LoadOptions](../../loadoptions/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)