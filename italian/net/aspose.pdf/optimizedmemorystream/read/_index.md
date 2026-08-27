---
title: "OptimizedMemoryStream.Read"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OptimizedMemoryStream. Quando viene sovrascritto in una classe derivata legge una sequenza di byte dallo stream corrente e avanza la posizione all'interno dello stream del numero di byte letti"
type: docs
weight: 100
url: /it/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

Quando sovrascritto in una classe derivata, legge una sequenza di byte dallo stream corrente e avanza la posizione nello stream del numero di byte letti.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | Byte[] | Un array di byte. Quando questo metodo restituisce, il buffer contiene l'array di byte specificato con i valori |
| offset | Int32 | L'offset di byte basato su zero in a cui iniziare a memorizzare i dati letti dallo stream corrente. |
| conteggio | Int32 | Il numero massimo di byte da leggere dallo stream corrente. |

### Valore di ritorno

Il numero totale di byte letti nel buffer. Questo può essere inferiore al numero di byte richiesti se tale quantità di byte non è attualmente disponibile, o zero (0) se è stato raggiunto la fine dello stream.

### Vedi anche

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


