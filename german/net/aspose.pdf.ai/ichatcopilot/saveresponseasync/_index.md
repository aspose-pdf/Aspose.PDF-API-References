---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot-Methode. Speichert die Antwort für die gegebene Nachricht asynchron in einer PDF-Datei
type: docs
weight: 40
url: /de/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Speichert die Antwort für die gegebene Nachricht asynchron in einer PDF-Datei.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | String | Die Eingabenachricht, für die die Antwort gespeichert wird. |
| outputFileName | String | Der Name der Ausgabedatei (PDF), in der die Antwort gespeichert wird. |
| cancellationToken | Nullable`1 | Das Abbruchtoken (optional). |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt.

### Siehe auch

* Schnittstelle [IChatCopilot](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Speichert die Antwort für die gegebene Nachricht asynchron in einer Datei mit dem angegebenen Format.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | String | Die Eingabenachricht, für die die Antwort gespeichert wird. |
| outputFileName | String | Der Name der Ausgabedatei, in der die Antwort gespeichert wird. |
| saveFormat | SaveFormat | Das Format, in dem die Antwort gespeichert werden soll (PDF, wenn nicht angegeben). |
| cancellationToken | Nullable`1 | Das Abbruchtoken (optional). |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt.

### Siehe auch

* Enum [SaveFormat](../../../aspose.pdf/saveformat/)
* Schnittstelle [IChatCopilot](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Speichert die Antworten für die gegebene Liste von Nachrichten asynchron in einer PDF-Datei.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | List`1 | Die Liste der Eingabenachrichten, für die die Antworten gespeichert werden. |
| outputFileName | String | Der Name der Ausgabedatei (PDF), in der die Antworten gespeichert werden. |
| cancellationToken | Nullable`1 | Das Abbruchtoken (optional). |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt.

### Siehe auch

* Schnittstelle [IChatCopilot](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Speichert die Antworten für die gegebene Liste von Nachrichten asynchron in einer Datei mit dem angegebenen Format.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | List`1 | Die Liste der Eingabenachrichten, für die die Antworten gespeichert werden. |
| outputFileName | String | Der Name der Ausgabedatei, in der die Antworten gespeichert werden. |
| saveFormat | SaveFormat | Das Format, in dem die Antworten gespeichert werden sollen (PDF, wenn nicht angegeben). |
| cancellationToken | Nullable`1 | Das Abbruchtoken (optional). |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt.

### Siehe auch

* Enum [SaveFormat](../../../aspose.pdf/saveformat/)
* Schnittstelle [IChatCopilot](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)