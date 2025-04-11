---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Metodo Document. Memorizza il documento nello stream
type: docs
weight: 830
url: /it/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

Memorizza il documento nello stream.

```csharp
public void Save(Stream output)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | Stream | Stream dove il documento sarà memorizzato. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Salva il documento nel file specificato.

```csharp
public void Save(string outputFileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file dove il documento sarà memorizzato. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Salva il documento in modo incrementale (cioè utilizzando la tecnica di aggiornamento incrementale).

```csharp
public void Save()
```

## Osservazioni

Per salvare il documento in modo incrementale, dobbiamo aprire il file del documento per la scrittura. Pertanto, il Document deve essere inizializzato con uno stream scrivibile come nel seguente frammento di codice: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // apporta alcune modifiche e salva il documento in modo incrementale doc.Save();

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Salva il documento con opzioni di salvataggio.

```csharp
public void Save(SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | SaveOptions | Opzioni di salvataggio. |

### Vedi Anche

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Salva il documento con un nuovo nome insieme a un formato di file.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file dove il documento sarà memorizzato. |
| format | SaveFormat | Opzioni di formato. |

### Vedi Anche

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Salva il documento con un nuovo nome insieme a un formato di file.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream dove il documento sarà memorizzato. |
| format | SaveFormat | Opzioni di formato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | ArgumentException quando [`HtmlSaveOptions`](../../htmlsaveoptions/) è passato a un metodo. Salvare un documento nello stream html non è supportato. Si prega di utilizzare il metodo salva nel file. |

### Vedi Anche

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file dove il documento sarà memorizzato. |
| options | SaveOptions | Opzioni di salvataggio. |

### Vedi Anche

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Salva il documento in uno stream con opzioni di salvataggio.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream dove il documento sarà memorizzato. |
| options | SaveOptions | Opzioni di salvataggio. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | ArgumentException quando [`HtmlSaveOptions`](../../htmlsaveoptions/) è passato a un metodo. Salvare un documento nello stream html non è supportato. Si prega di utilizzare il metodo salva nel file. |

### Vedi Anche

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)