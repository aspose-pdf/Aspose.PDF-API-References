---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: ComHelper-metod. Skapa och returnera bara Dokument med hjälp av filnamn. Samma som Dokument
type: docs
weight: 20
url: /sv/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

Skapa och returnera bara Dokument med hjälp av *filnamn*. Samma som [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | Sträng | Namnet på pdf-dokumentfilen. |

### Returvärde

Dokumentobjekt

### Se Även

* klass [Document](../../document/)
* klass [ComHelper](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Initiera och returnera en ny instans av klass [`Document`](../../document/) för att arbeta med krypterat dokument.

```csharp
public Document OpenFile(string filename, string password)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | Sträng | Dokumentfilnamn. |
| password | Sträng | Användar- eller ägarlösenord. |

### Returvärde

Dokumentobjekt

### Se Även

* klass [Document](../../document/)
* klass [ComHelper](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Initiera ny instans av klass [`Document`](../../document/) för att arbeta med krypterat dokument.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | Sträng | Dokumentfilnamn. |
| password | Sträng | Användar- eller ägarlösenord. |
| isManagedStream | Boolean | om det är inställt på `true` stängs inre ström innan utgång; annars görs det inte. |

### Returvärde

Dokumentobjekt

### Se Även

* klass [Document](../../document/)
* klass [ComHelper](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

Öppna ett befintligt dokument från en fil och tillhandahåll nödvändiga konverteringsalternativ för att få pdf-dokument.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | Sträng | Indatafil att konvertera till pdf-dokument. |
| options | LoadOptions | Representerar egenskaper för att konvertera *filnamn* till pdf-dokument. |

### Returvärde

Dokumentobjekt

### Se Även

* klass [Document](../../document/)
* klass [LoadOptions](../../loadoptions/)
* klass [ComHelper](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)