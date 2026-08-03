---
title: "ComHelper.OpenStream"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ComHelper-metoden. Initierar och returnerar en ny Document-instans från inmatningsströmmen"
type: docs
weight: 30
url: /sv/net/aspose.pdf/comhelper/openstream/
---
## OpenStream(Stream) {#openstream}

Initiera och returnera en ny Document-instans från *input*-strömmen.

```csharp
public Document OpenStream(Stream input)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Ström med pdf-dokument. |

### Returvärde

Document-objekt

### Se även

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string) {#openstream_3}

Initiera och returnera en ny Document-instans från *input*-strömmen.

```csharp
public Document OpenStream(Stream input, string password)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Inmatningsströmobjekt, motsvarande pdf är lösenordsskyddad. |
| lösenord | String | Användar- eller ägarlösenord. |

### Returvärde

Document-objekt

### Se även

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, bool) {#openstream_2}

Initiera och returnera en ny Document-instans från *input*-strömmen.

```csharp
public Document OpenStream(Stream input, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Ström med pdf-dokument. |
| isManagedStream | Boolean | om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |

### Returvärde

Document-objekt

### Se även

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string, bool) {#openstream_4}

Initiera och returnera en ny Document-instans från *input*-strömmen.

```csharp
public Document OpenStream(Stream input, string password, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Ström med pdf-dokument. |
| lösenord | String | Användar- eller ägarlösenord. |
| isManagedStream | Boolean | om den är satt till `true` stängs den inre strömmen innan avslut; annars gör den det inte. |

### Returvärde

Document-objekt

### Se även

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, LoadOptions) {#openstream_1}

Öppna och returnera ett befintligt dokument från en ström och ange nödvändig konvertering för att få ett pdf-dokument.

```csharp
public Document OpenStream(Stream input, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | Stream | Indataström för att konvertera till pdf-dokument. |
| options | LoadOptions | Representerar egenskaper för att konvertera *input* till pdf-dokument. |

### Returvärde

Document-objekt

### Se även

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


