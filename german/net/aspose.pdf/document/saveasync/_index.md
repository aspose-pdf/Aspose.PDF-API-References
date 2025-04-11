---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Dokumentenmethode. Speichert das Dokument in einen Stream
type: docs
weight: 840
url: /de/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Speichert das Dokument in einen Stream.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| output | Stream | Stream, in dem das Dokument gespeichert werden soll. |
| cancellationToken | CancellationToken | Abbruch-Token. |

### Rückgabewert

Asynchrone Aufgabe.

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Speichert das Dokument in der angegebenen Datei.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFileName | String | Pfad zur Datei, in der das Dokument gespeichert wird. |
| cancellationToken | CancellationToken | Abbruch-Token. |

### Rückgabewert

Asynchrone Aufgabe.

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Speichert das Dokument inkrementell (d.h. unter Verwendung der inkrementellen Aktualisierungstechnik).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cancellationToken | CancellationToken | Abbruch-Token. |

### Rückgabewert

Asynchrone Aufgabe.

## Anmerkungen

Um das Dokument inkrementell zu speichern, müssen wir die Dokumentdatei zum Schreiben öffnen. Daher muss das Dokument mit einem beschreibbaren Stream initialisiert werden, wie im folgenden Code-Snippet: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // Änderungen vornehmen und das Dokument inkrementell speichern doc.Save();

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Speichert das Dokument mit Speicheroptionen.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | SaveOptions | Speicheroptionen. |
| cancellationToken | CancellationToken | Abbruch-Token. |

### Rückgabewert

Asynchrone Aufgabe.

### Siehe auch

* Klasse [SaveOptions](../../saveoptions/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Speichert das Dokument mit einem neuen Namen zusammen mit einem Dateiformat.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFileName | String | Pfad zur Datei, in der das Dokument gespeichert wird. |
| format | SaveFormat | Formatoptionen. |
| cancellationToken | CancellationToken | Abbruch-Token. |

### Rückgabewert

Asynchrone Aufgabe.

### Siehe auch

* Enum [SaveFormat](../../saveformat/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Speichert das Dokument mit einem neuen Namen zusammen mit einem Dateiformat.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Stream, in dem das Dokument gespeichert wird. |
| format | SaveFormat | Formatoptionen. |
| cancellationToken | CancellationToken | Abbruch-Token. |

### Rückgabewert

Asynchrone Aufgabe.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | ArgumentException, wenn [`HtmlSaveOptions`](../../htmlsaveoptions/) an eine Methode übergeben wird. Das Speichern eines Dokuments im HTML-Stream wird nicht unterstützt. Bitte verwenden Sie die Methode zum Speichern in die Datei. |

### Siehe auch

* Enum [SaveFormat](../../saveformat/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Speichert das Dokument mit einem neuen Namen und setzt seine Speicheroptionen.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFileName | String | Pfad zur Datei, in der das Dokument gespeichert wird. |
| options | SaveOptions | Speicheroptionen. |
| cancellationToken | CancellationToken | Abbruch-Token. |

### Rückgabewert

Asynchrone Aufgabe.

### Siehe auch

* Klasse [SaveOptions](../../saveoptions/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Speichert das Dokument in einen Stream mit Speicheroptionen.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Stream, in dem das Dokument gespeichert wird. |
| options | SaveOptions | Speicheroptionen. |
| cancellationToken | CancellationToken | Abbruch-Token. |

### Rückgabewert

Asynchrone Aufgabe.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | ArgumentException, wenn [`HtmlSaveOptions`](../../htmlsaveoptions/) an eine Methode übergeben wird. Das Speichern eines Dokuments im HTML-Stream wird nicht unterstützt. Bitte verwenden Sie die Methode zum Speichern in die Datei. |

### Siehe auch

* Klasse [SaveOptions](../../saveoptions/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)