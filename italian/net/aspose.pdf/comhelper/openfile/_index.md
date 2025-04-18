---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: Metodo ComHelper. Crea e restituisce un Documento utilizzando il nome file. Lo stesso di Document
type: docs
weight: 20
url: /it/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

Crea e restituisce un Documento utilizzando il *nome file*. Lo stesso di [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Il nome del file del documento pdf. |

### Valore di Ritorno

Oggetto Documento

### Vedi Anche

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Inizializza e restituisce una nuova istanza della classe [`Document`](../../document/) per lavorare con documenti crittografati.

```csharp
public Document OpenFile(string filename, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome del file del documento. |
| password | String | Password dell'utente o del proprietario. |

### Valore di Ritorno

Oggetto Documento

### Vedi Anche

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Inizializza una nuova istanza della classe [`Document`](../../document/) per lavorare con documenti crittografati.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome del file del documento. |
| password | String | Password dell'utente o del proprietario. |
| isManagedStream | Boolean | se impostato su `true`, lo stream interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Valore di Ritorno

Oggetto Documento

### Vedi Anche

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

Apri un documento esistente da un file fornendo le necessarie opzioni di conversione per ottenere un documento pdf.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | File di input da convertire in documento pdf. |
| options | LoadOptions | Rappresenta le proprietà per convertire il *nome file* in documento pdf. |

### Valore di Ritorno

Oggetto Documento

### Vedi Anche

* classe [Document](../../document/)
* classe [LoadOptions](../../loadoptions/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)