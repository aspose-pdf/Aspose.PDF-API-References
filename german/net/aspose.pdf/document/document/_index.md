---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Dokumentenkonstruktor. Initialisieren Sie eine neue Dokumentinstanz aus dem Eingabestrom
type: docs
weight: 10
url: /de/net/aspose.pdf/document/document/
---
## Dokument(Stream) {#constructor_2}

Initialisieren Sie eine neue Dokumentinstanz aus dem *Eingabe*strom.

```csharp
public Document(Stream input)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Stream mit PDF-Dokument. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(Stream, bool) {#constructor_4}

Initialisieren Sie eine neue Dokumentinstanz aus dem *Eingabe*strom.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Stream mit PDF-Dokument. |
| isManagedStream | Boolean | Wenn auf `true` gesetzt, wird der innere Stream vor dem Verlassen geschlossen; andernfalls nicht. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(Stream, string) {#constructor_5}

Initialisieren Sie eine neue Dokumentinstanz aus dem *Eingabe*strom.

```csharp
public Document(Stream input, string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Eingabestreamobjekt, das entsprechende PDF ist passwortgeschützt. |
| password | String | Benutzer- oder Eigentümerpasswort. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(Stream, string, bool) {#constructor_6}

Initialisieren Sie eine neue Dokumentinstanz aus dem *Eingabe*strom.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Stream mit PDF-Dokument. |
| password | String | Benutzer- oder Eigentümerpasswort. |
| isManagedStream | Boolean | Wenn auf `true` gesetzt, wird der innere Stream vor dem Verlassen geschlossen; andernfalls nicht. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(string) {#constructor_7}

Initialisieren Sie einfach das Dokument mit *Dateiname*. Dasselbe wie `Document`.

```csharp
public Document(string filename)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Der Name der PDF-Dokumentdatei. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(string, bool) {#constructor_9}

Initialisieren Sie einfach das Dokument mit *Dateiname*. Dasselbe wie `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Der Name der PDF-Dokumentdatei. |
| isManagedStream | Boolean | Wenn auf `true` gesetzt, wird der innere Stream vor dem Verlassen geschlossen; andernfalls nicht. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(string, string) {#constructor_10}

Initialisiert eine neue Instanz der [`Document`](../) Klasse zum Arbeiten mit verschlüsseltem Dokument.

```csharp
public Document(string filename, string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Dokumentdateiname. |
| password | String | Benutzer- oder Eigentümerpasswort. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(string, string, bool) {#constructor_11}

Initialisiert eine neue Instanz der [`Document`](../) Klasse zum Arbeiten mit verschlüsseltem Dokument.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Dokumentdateiname. |
| password | String | Benutzer- oder Eigentümerpasswort. |
| isManagedStream | Boolean | Wenn auf `true` gesetzt, wird der innere Stream vor dem Verlassen geschlossen; andernfalls nicht. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument() {#constructor}

Initialisiert ein leeres Dokument.

```csharp
public Document()
```

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(PdfVersion) {#constructor_1}

Initialisiert ein leeres Dokument nach Version.

```csharp
public Document(PdfVersion version)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| version | PdfVersion | Die PDF-Version. |

### Siehe auch

* Enum [PdfVersion](../../pdfversion/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(string, LoadOptions) {#constructor_8}

Öffnet ein vorhandenes Dokument aus einer Datei und bietet die erforderlichen Konvertierungsoptionen, um ein PDF-Dokument zu erhalten.

```csharp
public Document(string filename, LoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Eingabedatei, die in ein PDF-Dokument konvertiert werden soll. |
| options | LoadOptions | Stellt Eigenschaften für die Konvertierung von *filename* in ein PDF-Dokument dar. |

### Siehe auch

* Klasse [LoadOptions](../../loadoptions/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Dokument(Stream, LoadOptions) {#constructor_3}

Öffnet ein vorhandenes Dokument aus einem Stream und bietet die erforderliche Konvertierung, um ein PDF-Dokument zu erhalten.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | Stream | Eingabestream, der in ein PDF-Dokument konvertiert werden soll. |
| options | LoadOptions | Stellt Eigenschaften für die Konvertierung von *input* in ein PDF-Dokument dar. |

### Siehe auch

* Klasse [LoadOptions](../../loadoptions/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)