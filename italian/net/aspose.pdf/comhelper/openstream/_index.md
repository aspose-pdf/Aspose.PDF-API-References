---
title: ComHelper.OpenStream
second_title: Aspose.PDF for .NET API Reference
description: Metodo ComHelper. Inizializza e restituisce una nuova istanza di Document dall'input stream
type: docs
weight: 30
url: /it/net/aspose.pdf/comhelper/openstream/
---
## OpenStream(Stream) {#openstream}

Inizializza e restituisce una nuova istanza di Document dall'*input* stream.

```csharp
public Document OpenStream(Stream input)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Stream con documento pdf. |

### Valore di Ritorno

Oggetto Document

### Vedi Anche

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string) {#openstream_3}

Inizializza e restituisce una nuova istanza di Document dall'*input* stream.

```csharp
public Document OpenStream(Stream input, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Oggetto stream di input, il pdf corrispondente è protetto da password. |
| password | String | Password utente o proprietario. |

### Valore di Ritorno

Oggetto Document

### Vedi Anche

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, bool) {#openstream_2}

Inizializza e restituisce una nuova istanza di Document dall'*input* stream.

```csharp
public Document OpenStream(Stream input, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Stream con documento pdf. |
| isManagedStream | Boolean | se impostato su `true` lo stream interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Valore di Ritorno

Oggetto Document

### Vedi Anche

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string, bool) {#openstream_4}

Inizializza e restituisce una nuova istanza di Document dall'*input* stream.

```csharp
public Document OpenStream(Stream input, string password, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Stream con documento pdf. |
| password | String | Password utente o proprietario. |
| isManagedStream | Boolean | se impostato su `true` lo stream interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Valore di Ritorno

Oggetto Document

### Vedi Anche

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, LoadOptions) {#openstream_1}

Apre e restituisce un documento esistente da uno stream fornendo la necessaria conversione per ottenere un documento pdf.

```csharp
public Document OpenStream(Stream input, LoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Stream di input da convertire in documento pdf. |
| options | LoadOptions | Rappresenta le proprietà per convertire l'*input* in documento pdf. |

### Valore di Ritorno

Oggetto Document

### Vedi Anche

* classe [Document](../../document/)
* classe [LoadOptions](../../loadoptions/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)