---
title: "ComHelper.OpenFile"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ComHelper‑metod. Skapa och returnera helt enkelt Document med filnamn. Samma som Document"
type: docs
weight: 20
url: /sv/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

Skapa och returnera helt enkelt Document med *filename*. Samma som [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Namnet på pdf-dokumentfilen. |

### Returvärde

Document-objekt

### Se även

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Initiera och returnera en ny instans av klassen [`Document`](../../document/) för att arbeta med krypterat dokument.

```csharp
public Document OpenFile(string filename, string password)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Document‑filnamn. |
| lösenord | String | Användar- eller ägarlösenord. |

### Returvärde

Document-objekt

### Se även

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Initiera en ny instans av klassen [`Document`](../../document/) för att arbeta med krypterat dokument.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Document‑filnamn. |
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

## OpenFile(string, LoadOptions) {#openfile_1}

Öppna ett befintligt dokument från en fil och ange nödvändiga konverteringsalternativ för att få ett pdf-dokument.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | String | Indatafil för att konvertera till pdf-dokument. |
| options | LoadOptions | Representerar egenskaper för att konvertera *filename* till pdf-dokument. |

### Returvärde

Document-objekt

### Se även

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


