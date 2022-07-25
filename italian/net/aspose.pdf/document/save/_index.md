---
title: Save
second_title: Aspose.PDF per .NET API Reference
description: Salva il documento in modo incrementale ovvero utilizzando la tecnica di aggiornamento incrementale.
type: docs
weight: 720
url: /it/net/aspose.pdf/document/save/
---
## Save() {#save}

Salva il documento in modo incrementale (ovvero utilizzando la tecnica di aggiornamento incrementale).

```csharp
public void Save()
```

### Osservazioni

Per salvare il documento in modo incrementale dovremmo aprire il file del documento per la scrittura. Pertanto il documento deve essere inizializzato con stream scrivibile come nel prossimo frammento di codice: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // apporta alcune modifiche e salva il documento in modo incrementale doc.Save();

### Guarda anche

* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Salva il documento con le opzioni di salvataggio.

```csharp
public void Save(SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | SaveOptions | Salva opzioni. |

### Guarda anche

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Salva il documento con un nuovo nome insieme a un formato file.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file in cui verrà archiviato il documento. |
| format | SaveFormat | Opzioni di formato. |

### Guarda anche

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Salva il documento con un nuovo nome insieme a un formato file.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream in cui verrà archiviato il documento. |
| format | SaveFormat | Opzioni di formato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | ArgumentException quando[`HtmlSaveOptions`](../../htmlsaveoptions) viene passato a un metodo. Il salvataggio di un documento nel flusso html non è supportato. Si prega di utilizzare il metodo di salvataggio nel file. |

### Guarda anche

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Salva il documento con un nuovo nome impostandone le opzioni di salvataggio.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file in cui verrà archiviato il documento. |
| options | SaveOptions | Salva opzioni. |

### Guarda anche

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Salva il documento in uno stream con opzioni di salvataggio.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream in cui verrà archiviato il documento. |
| options | SaveOptions | Salva opzioni. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | ArgumentException quando[`HtmlSaveOptions`](../../htmlsaveoptions) viene passato a un metodo. Il salvataggio di un documento nel flusso html non è supportato. Si prega di utilizzare il metodo di salvataggio nel file. |

### Guarda anche

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Save(HttpResponse, string, ContentDisposition, SaveOptions) {#save_8}

Salva il documento in un flusso di risposta con opzioni di salvataggio.

```csharp
public void Save(HttpResponse response, string outputFileName, ContentDisposition disposition, 
    SaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| response | HttpResponse | Incapsula le informazioni sulla risposta HTTP. |
| outputFileName | String | Nome file semplice, cioè senza percorso. |
| disposition | ContentDisposition | Rappresenta un'intestazione Content-Disposition del protocollo MIME. |
| options | SaveOptions | Salva opzioni. |

### Guarda anche

* enum [ContentDisposition](../../contentdisposition)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Memorizza il documento nello stream.

```csharp
public void Save(Stream output)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | Stream | Stream in cui archiviare la shell del documento. |

### Guarda anche

* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Salva il documento nel file specificato.

```csharp
public void Save(string outputFileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFileName | String | Percorso del file in cui verrà archiviato il documento. |

### Guarda anche

* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
