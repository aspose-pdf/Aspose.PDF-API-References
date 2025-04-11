---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: Metodo OptimizedMemoryStream. Quando sovrascritto in una classe derivata, legge una sequenza di byte dallo stream corrente e avanza la posizione all'interno dello stream in base al numero di byte letti
type: docs
weight: 100
url: /it/net/aspose.pdf/optimizedmemorystream/read/
---
## Metodo OptimizedMemoryStream.Read

Quando sovrascritto in una classe derivata, legge una sequenza di byte dallo stream corrente e avanza la posizione all'interno dello stream in base al numero di byte letti.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | Byte[] | Un array di byte. Quando questo metodo restituisce, il buffer contiene l'array di byte specificato con i valori |
| offset | Int32 | L'offset in byte basato su zero in cui iniziare a memorizzare i dati letti dallo stream corrente. |
| count | Int32 | Il numero massimo di byte da leggere dallo stream corrente. |

### Valore di Ritorno

Il numero totale di byte letti nel buffer. Questo può essere inferiore al numero di byte richiesti se non ci sono attualmente così tanti byte disponibili, o zero (0) se è stata raggiunta la fine dello stream.

### Vedi Anche

* classe [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)