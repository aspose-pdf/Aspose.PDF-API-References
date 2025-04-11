---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo Document. Memorizza il documento nello stream
type: docs
weight: 840
url: /it/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Memorizza il documento nello stream.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | Stream | Stream dove il documento sarà memorizzato. |
| cancellationToken | CancellationToken | Token di cancellazione. |

### Valore di ritorno

Compito asincrono.

### Vedi anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Salva il documento nel file specificato.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file dove il documento sarà memorizzato. |
| cancellationToken | CancellationToken | Token di cancellazione. |

### Valore di ritorno

Compito asincrono.

### Vedi anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Salva il documento in modo incrementale (cioè utilizzando la tecnica di aggiornamento incrementale).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cancellationToken | CancellationToken | Token di cancellazione. |

### Valore di ritorno

Compito asincrono.

## Osservazioni

Per salvare il documento in modo incrementale, dobbiamo aprire il file del documento per la scrittura. Pertanto, il Document deve essere inizializzato con uno stream scrivibile come nel seguente frammento di codice: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // apporta alcune modifiche e salva il documento in modo incrementale doc.Save();

### Vedi anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Salva il documento con opzioni di salvataggio.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | SaveOptions | Opzioni di salvataggio. |
| cancellationToken | CancellationToken | Token di cancellazione. |

### Valore di ritorno

Compito asincrono.

### Vedi anche

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Salva il documento con un nuovo nome insieme a un formato di file.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file dove il documento sarà memorizzato. |
| format | SaveFormat | Opzioni di formato. |
| cancellationToken | CancellationToken | Token di cancellazione. |

### Valore di ritorno

Compito asincrono.

### Vedi anche

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Salva il documento con un nuovo nome insieme a un formato di file.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream dove il documento sarà memorizzato. |
| format | SaveFormat | Opzioni di formato. |
| cancellationToken | CancellationToken | Token di cancellazione |

### Valore di ritorno

Compito asincrono.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | ArgumentException quando [`HtmlSaveOptions`](../../htmlsaveoptions/) viene passato a un metodo. Salvare un documento nello stream html non è supportato. Si prega di utilizzare il metodo salva nel file. |

### Vedi anche

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file dove il documento sarà memorizzato. |
| options | SaveOptions | Opzioni di salvataggio. |
| cancellationToken | CancellationToken | Token di cancellazione. |

### Valore di ritorno

Compito asincrono.

### Vedi anche

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Salva il documento in uno stream con opzioni di salvataggio.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream dove il documento sarà memorizzato. |
| options | SaveOptions | Opzioni di salvataggio. |
| cancellationToken | CancellationToken | Token di cancellazione. |

### Valore di ritorno

Compito asincrono.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | ArgumentException quando [`HtmlSaveOptions`](../../htmlsaveoptions/) viene passato a un metodo. Salvare un documento nello stream html non è supportato. Si prega di utilizzare il metodo salva nel file. |

### Vedi anche

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)