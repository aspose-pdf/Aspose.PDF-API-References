---
title: Save
second_title: Aspose.PDF für .NET-API-Referenz
description: Dokument inkrementell speichern dh mit inkrementeller Aktualisierungstechnik.
type: docs
weight: 720
url: /de/net/aspose.pdf/document/save/
---
## Save() {#save}

Dokument inkrementell speichern (dh mit inkrementeller Aktualisierungstechnik).

```csharp
public void Save()
```

### Bemerkungen

Um das Dokument schrittweise zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher muss das Dokument wie im nächsten Code-Snippet mit einem beschreibbaren Stream initialisiert werden: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // einige Änderungen vornehmen und speichern das Dokument inkrementell doc.Save();

### Siehe auch

* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Speichert das Dokument mit Speicheroptionen.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | SaveOptions | Optionen speichern. |

### Siehe auch

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFileName | String | Pfad zur Datei, in der das Dokument gespeichert wird. |
| format | SaveFormat | Formatoptionen. |

### Siehe auch

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Streamen Sie, wo das Dokument gespeichert wird. |
| format | SaveFormat | Formatoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | ArgumentException Wenn[`HtmlSaveOptions`](../../htmlsaveoptions) wird an eine Methode übergeben. Das Speichern eines Dokuments im HTML-Stream wird nicht unterstützt. Bitte verwenden Sie die Methode zum Speichern in der Datei. |

### Siehe auch

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Speichert das Dokument unter einem neuen Namen und setzt seine Speicheroptionen.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFileName | String | Pfad zur Datei, in der das Dokument gespeichert wird. |
| options | SaveOptions | Optionen speichern. |

### Siehe auch

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Speichert das Dokument in einem Stream mit Speicheroptionen.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Streamen Sie, wo das Dokument gespeichert wird. |
| options | SaveOptions | Optionen speichern. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | ArgumentException Wenn[`HtmlSaveOptions`](../../htmlsaveoptions) wird an eine Methode übergeben. Das Speichern eines Dokuments im HTML-Stream wird nicht unterstützt. Bitte verwenden Sie die Methode zum Speichern in der Datei. |

### Siehe auch

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Save(HttpResponse, string, ContentDisposition, SaveOptions) {#save_8}

Speichert das Dokument in einem Antwortstrom mit Speicheroptionen.

```csharp
public void Save(HttpResponse response, string outputFileName, ContentDisposition disposition, 
    SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| response | HttpResponse | Kapselt HTTP-Antwortinformationen. |
| outputFileName | String | Einfacher Dateiname, dh ohne Pfad. |
| disposition | ContentDisposition | Stellt einen Content-Disposition-Header des MIME-Protokolls dar. |
| options | SaveOptions | Optionen speichern. |

### Siehe auch

* enum [ContentDisposition](../../contentdisposition)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Speichert das Dokument im Stream.

```csharp
public void Save(Stream output)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| output | Stream | Streamen Sie, wo das Dokument gespeichert werden soll. |

### Siehe auch

* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

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

* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
