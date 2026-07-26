---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Implementiert das Abrufen eines Ausgabestreams aus dem Speicher. Sie können ihn beispielsweise verwenden, wenn Sie die begleitende Ausgabe (wie eine Protokolldatei) nicht auf die Festplatte schreiben möchten, aber Sie möchten es trotzdem."
type: docs
weight: 4880
url: /de/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

Implementiert das Abrufen eines Ausgabestreams aus dem Speicher. Sie können es beispielsweise verwenden, wenn Sie die begleitende Ausgabe (wie eine Protokolldatei) nicht auf die Festplatte schreiben möchten, sondern sie anschließend aus dem Speicher lesen wollen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | Erstellt eine neue Instanz. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close](#close--) | Gibt die Instanz frei. @throws IOException IOException‑Ausnahme kann ausgelöst werden, wenn ein I/O‑Fehler auftritt |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | Gibt den Stream zum Lesen zurück. Ohne in Unterverzeichnissen nach einer Datei zu suchen. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | Gibt den Stream zum Lesen zurück. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | Gibt den Stream zum Schreiben zurück. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

Erstellt eine neue Instanz.

### close {#close--}
```
public void close() throws IOException
```

Gibt die Instanz frei. @throws IOException IOException‑Ausnahme kann ausgelöst werden, wenn ein I/O‑Fehler auftritt

### getFile {#getFile-java.lang.String-java.lang.String:A-}
Gibt den Stream zum Lesen zurück. Ohne in Unterverzeichnissen nach einer Datei zu suchen.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
Gibt den Stream zum Lesen zurück.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
Gibt den Stream zum Schreiben zurück.
