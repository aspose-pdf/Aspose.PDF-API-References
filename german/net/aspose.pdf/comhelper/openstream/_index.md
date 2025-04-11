---
title: ComHelper.OpenStream
second_title: Aspose.PDF for .NET API Reference
description: ComHelper-Methode. Initialisieren und neue Dokumentinstanz aus dem Eingabestrom zurückgeben
type: docs
weight: 30
url: /de/net/aspose.pdf/comhelper/openstream/
---
## OpenStream(Stream) {#openstream}

Initialisieren und eine neue Dokumentinstanz aus dem *Eingabe*stream zurückgeben.

```csharp
public Document OpenStream(Stream input)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Stream mit PDF-Dokument. |

### Rückgabewert

Dokumentenobjekt

### Siehe auch

* Klasse [Document](../../document/)
* Klasse [ComHelper](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string) {#openstream_3}

Initialisieren und eine neue Dokumentinstanz aus dem *Eingabe*stream zurückgeben.

```csharp
public Document OpenStream(Stream input, string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Eingabestreamobjekt, entsprechendes PDF ist passwortgeschützt. |
| password | String | Benutzer- oder Eigentümerpasswort. |

### Rückgabewert

Dokumentenobjekt

### Siehe auch

* Klasse [Document](../../document/)
* Klasse [ComHelper](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, bool) {#openstream_2}

Initialisieren und eine neue Dokumentinstanz aus dem *Eingabe*stream zurückgeben.

```csharp
public Document OpenStream(Stream input, bool isManagedStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Stream mit PDF-Dokument. |
| isManagedStream | Boolean | Wenn auf `true` gesetzt, wird der innere Stream vor dem Verlassen geschlossen; andernfalls nicht. |

### Rückgabewert

Dokumentenobjekt

### Siehe auch

* Klasse [Document](../../document/)
* Klasse [ComHelper](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string, bool) {#openstream_4}

Initialisieren und eine neue Dokumentinstanz aus dem *Eingabe*stream zurückgeben.

```csharp
public Document OpenStream(Stream input, string password, bool isManagedStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Stream mit PDF-Dokument. |
| password | String | Benutzer- oder Eigentümerpasswort. |
| isManagedStream | Boolean | Wenn auf `true` gesetzt, wird der innere Stream vor dem Verlassen geschlossen; andernfalls nicht. |

### Rückgabewert

Dokumentenobjekt

### Siehe auch

* Klasse [Document](../../document/)
* Klasse [ComHelper](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, LoadOptions) {#openstream_1}

Öffnen und ein vorhandenes Dokument aus einem Stream zurückgeben, das die notwendige Konvertierung bereitstellt, um ein PDF-Dokument zu erhalten.

```csharp
public Document OpenStream(Stream input, LoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Eingabestream zur Konvertierung in ein PDF-Dokument. |
| options | LoadOptions | Stellt Eigenschaften für die Konvertierung von *input* in ein PDF-Dokument dar. |

### Rückgabewert

Dokumentenobjekt

### Siehe auch

* Klasse [Document](../../document/)
* Klasse [LoadOptions](../../loadoptions/)
* Klasse [ComHelper](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)