---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Costruttore di documento. Inizializzare una nuova istanza di Document dal flusso di input.
type: docs
weight: 10
url: /it/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Inizializza una nuova istanza di Document dal *flusso* di input.

```csharp
public Document(Stream input)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso con documento pdf. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

Inizializza una nuova istanza di Document dal *flusso* di input.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso con documento pdf. |
| isManagedStream | Boolean | Se impostato su `true`, il flusso interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

Inizializza una nuova istanza di Document dal *flusso* di input.

```csharp
public Document(Stream input, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Oggetto flusso di input, il corrispondente pdf è protetto da password. |
| password | String | Password utente o proprietario. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_6}

Inizializza una nuova istanza di Document dal *flusso* di input.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso con documento pdf. |
| password | String | Password utente o proprietario. |
| isManagedStream | Boolean | Se impostato su `true`, il flusso interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_7}

Inizializza semplicemente Document utilizzando *filename*. È lo stesso di `Document`.

```csharp
public Document(string filename)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Il nome del file del documento pdf. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_9}

Inizializza semplicemente Document utilizzando *filename*. È lo stesso di `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Il nome del file del documento pdf. |
| isManagedStream | Boolean | Se impostato su `true`, il flusso interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_10}

Inizializza una nuova istanza della classe [`Document`](../) per lavorare con documenti crittografati.

```csharp
public Document(string filename, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome del file del documento. |
| password | String | Password utente o proprietario. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_11}

Inizializza una nuova istanza della classe [`Document`](../) per lavorare con documenti crittografati.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome del file del documento. |
| password | String | Password utente o proprietario. |
| isManagedStream | Boolean | Se impostato su `true`, il flusso interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Inizializza un documento vuoto.

```csharp
public Document()
```

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

Inizializza un documento vuoto per versione.

```csharp
public Document(PdfVersion version)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| version | PdfVersion | La versione PDF. |

### Vedi Anche

* enum [PdfVersion](../../pdfversion/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_8}

Apre un documento esistente da un file fornendo le opzioni di conversione necessarie per ottenere un documento pdf.

```csharp
public Document(string filename, LoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | File di input da convertire in documento pdf. |
| options | LoadOptions | Rappresenta le proprietà per convertire *filename* in documento pdf. |

### Vedi Anche

* classe [LoadOptions](../../loadoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Apre un documento esistente da un flusso fornendo la conversione necessaria per ottenere un documento pdf.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso di input da convertire in documento pdf. |
| options | LoadOptions | Rappresenta le proprietà per convertire *input* in documento pdf. |

### Vedi Anche

* classe [LoadOptions](../../loadoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)