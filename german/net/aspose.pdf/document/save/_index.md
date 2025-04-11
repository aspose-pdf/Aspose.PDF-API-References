---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmethode. Speichert das Dokument in einen Stream
type: docs
weight: 830
url: /de/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

Speichert das Dokument in einen Stream.

```csharp
public void Save(Stream output)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| output | Stream | Stream, in dem das Dokument gespeichert werden soll. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Speichert das Dokument in der angegebenen Datei.

```csharp
public void Save(string outputFileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFileName | String | Pfad zur Datei, in der das Dokument gespeichert wird. |

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Speichert das Dokument inkrementell (d.h. unter Verwendung der inkrementellen Aktualisierungstechnik).

```csharp
public void Save()
```

## Anmerkungen

Um das Dokument inkrementell zu speichern, müssen wir die Dokumentdatei zum Schreiben öffnen. Daher muss das Dokument mit einem beschreibbaren Stream initialisiert werden, wie im folgenden Code-Snippet: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // Änderungen vornehmen und das Dokument inkrementell speichern doc.Save();

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Speichert das Dokument mit Speicheroptionen.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | SaveOptions | Speicheroptionen. |

### Siehe auch

* Klasse [SaveOptions](../../saveoptions/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Speichert das Dokument mit einem neuen Namen zusammen mit einem Dateiformat.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFileName | String | Pfad zur Datei, in der das Dokument gespeichert wird. |
| format | SaveFormat | Formatoptionen. |

### Siehe auch

* Enum [SaveFormat](../../saveformat/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Speichert das Dokument mit einem neuen Namen zusammen mit einem Dateiformat.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Stream, in dem das Dokument gespeichert wird. |
| format | SaveFormat | Formatoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | ArgumentException, wenn [`HtmlSaveOptions`](../../htmlsaveoptions/) an eine Methode übergeben wird. Das Speichern eines Dokuments im HTML-Stream wird nicht unterstützt. Bitte verwenden Sie die Methode, um in die Datei zu speichern. |

### Siehe auch

* Enum [SaveFormat](../../saveformat/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Speichert das Dokument mit einem neuen Namen und legt seine Speicheroptionen fest.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFileName | String | Pfad zur Datei, in der das Dokument gespeichert wird. |
| options | SaveOptions | Speicheroptionen. |

### Siehe auch

* Klasse [SaveOptions](../../saveoptions/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Speichert das Dokument in einem Stream mit Speicheroptionen.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Stream, in dem das Dokument gespeichert wird. |
| options | SaveOptions | Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | ArgumentException, wenn [`HtmlSaveOptions`](../../htmlsaveoptions/) an eine Methode übergeben wird. Das Speichern eines Dokuments im HTML-Stream wird nicht unterstützt. Bitte verwenden Sie die Methode, um in die Datei zu speichern. |

### Siehe auch

* Klasse [SaveOptions](../../saveoptions/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)