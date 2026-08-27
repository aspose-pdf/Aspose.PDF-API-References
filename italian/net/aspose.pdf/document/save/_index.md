---
title: "Document.Save"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Document. Salva il documento in un flusso con opzioni di salvataggio"
type: docs
weight: 850
url: /it/net/aspose.pdf/document/save/
---
## Save(Stream, SaveOptions) {#save_4}

Salva il documento in uno stream con le opzioni di salvataggio.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream in cui il documento sarà memorizzato. |
| options | SaveOptions | Opzioni di salvataggio. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | ArgumentException quando [`HtmlSaveOptions`](../../htmlsaveoptions/) viene passato a un metodo. Il salvataggio di un documento nello stream html non è supportato. Si prega di utilizzare il metodo di salvataggio su file. |

### Vedi anche

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Memorizza il documento in uno stream.

```csharp
public void Save(Stream output)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | Stream | Flusso in cui il documento dovrebbe essere memorizzato. |

### Vedi anche

* class [Document](../)
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
| outputFileName | String | Percorso del file in cui il documento sarà memorizzato. |

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Salva il documento in modo incrementale (cioè utilizzando la tecnica di aggiornamento incrementale).

```csharp
public void Save()
```

## Osservazioni

Per salvare il documento in modo incrementale dovremmo aprire il file del documento in scrittura. Pertanto Document deve essere inizializzato con uno stream scrivibile come nel seguente frammento di codice: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // apportare alcune modifiche e salvare il documento in modo incrementale doc.Save();

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Salva il documento con le opzioni di salvataggio.

```csharp
public void Save(SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | SaveOptions | Opzioni di salvataggio. |

### Vedi anche

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Salva il documento con un nuovo nome insieme a un formato file.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file in cui il documento sarà memorizzato. |
| format | SaveFormat | Opzioni di formato. |

### Vedi anche

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Salva il documento con un nuovo nome insieme a un formato file.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream in cui il documento sarà memorizzato. |
| format | SaveFormat | Opzioni di formato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | ArgumentException quando [`HtmlSaveOptions`](../../htmlsaveoptions/) viene passato a un metodo. Il salvataggio di un documento nello stream html non è supportato. Si prega di utilizzare il metodo di salvataggio su file. |

### Vedi anche

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
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
| outputFileName | String | Percorso del file in cui il documento sarà memorizzato. |
| options | SaveOptions | Opzioni di salvataggio. |

### Vedi anche

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


