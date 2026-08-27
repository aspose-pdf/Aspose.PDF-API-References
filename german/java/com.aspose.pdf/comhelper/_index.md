---
title: "ComHelper"
linktitle: "ComHelper"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt Methoden für COM-Clients bereit, um ein Dokument in Aspose.PDF zu laden. </p> <hr> <p> Verwenden Sie die ComHelper-Klasse, um ein Dokument aus einer Datei oder einem Stream in ein Document-Objekt zu laden. </p>"
type: docs
weight: 760
url: /de/java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> Stellt Methoden für COM‑Clients bereit, um ein Dokument in Aspose.PDF zu laden. </p> <hr> <p> Verwenden Sie die ComHelper‑Klasse, um ein Dokument aus einer Datei oder einem Stream in ein Document‑Objekt in einer COM‑Anwendung zu laden. Die Document‑Klasse bietet einen Standardkonstruktor zum Erstellen eines neuen Dokuments und ebenfalls überladene Konstruktoren zum Laden eines Dokuments aus einer Datei oder einem Stream. Wenn Sie Aspose.Words aus einer .NET‑Anwendung verwenden, können Sie alle Document‑Konstruktoren direkt nutzen, aber wenn Sie Aspose.PDF aus einer COM‑Anwendung verwenden, ist nur der Standard‑Document‑Konstruktor verfügbar. </p>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | Erstellen Sie einfach ein Document und geben Sie es zurück, indem Sie {@code filename} verwenden. Das gleiche wie {@code Document(Stream)}. |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Öffnen Sie ein vorhandenes Dokument aus einer Datei und geben Sie die erforderlichen Konvertierungsoptionen an, um ein PDF-Dokument zu erhalten. |
| [openFile](#openFile-java.lang.String-java.lang.String-) | Initialisieren und geben Sie eine neue Instanz der {@code Document}-Klasse zurück, um mit einem verschlüsselten Dokument zu arbeiten. |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | Initialisieren Sie eine neue Instanz der {@code Document}-Klasse, um mit einem verschlüsselten Dokument zu arbeiten. |
| [openStream](#openStream-java.io.InputStream-) | Initialisieren und geben Sie eine neue Document-Instanz aus dem {@code input}-Stream zurück. |
| [openStream](#openStream-java.io.InputStream-boolean-) | Initialisieren und geben Sie eine neue Document-Instanz aus dem {@code input}-Stream zurück. |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Öffnen und geben Sie ein vorhandenes Dokument aus einem Stream zurück, wobei die notwendigen Konvertierungen zum Erhalten eines PDF-Dokuments angegeben werden. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | Initialisieren und geben Sie eine neue Document-Instanz aus dem {@code input}-Stream zurück. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | Initialisieren und geben Sie eine neue Document-Instanz aus dem {@code input}-Stream zurück. |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
Erstellen Sie einfach ein Document und geben Sie es zurück, indem Sie {@code filename} verwenden. Das gleiche wie {@code Document(Stream)}.

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
Öffnen Sie ein vorhandenes Dokument aus einer Datei und geben Sie die erforderlichen Konvertierungsoptionen an, um ein PDF-Dokument zu erhalten.

### openFile {#openFile-java.lang.String-java.lang.String-}
Initialisieren und geben Sie eine neue Instanz der {@code Document}-Klasse zurück, um mit einem verschlüsselten Dokument zu arbeiten.

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
Initialisieren Sie eine neue Instanz der {@code Document}-Klasse, um mit einem verschlüsselten Dokument zu arbeiten.

### openStream {#openStream-java.io.InputStream-}
Initialisieren und geben Sie eine neue Document-Instanz aus dem {@code input}-Stream zurück.

### openStream {#openStream-java.io.InputStream-boolean-}
Initialisieren und geben Sie eine neue Document-Instanz aus dem {@code input}-Stream zurück.

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Öffnen und geben Sie ein vorhandenes Dokument aus einem Stream zurück, wobei die notwendigen Konvertierungen zum Erhalten eines PDF-Dokuments angegeben werden.

### openStream {#openStream-java.io.InputStream-java.lang.String-}
Initialisieren und geben Sie eine neue Document-Instanz aus dem {@code input}-Stream zurück.

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
Initialisieren und geben Sie eine neue Document-Instanz aus dem {@code input}-Stream zurück.
