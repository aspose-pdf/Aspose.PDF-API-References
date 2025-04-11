---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OutlineItemCollection. Rappresenta un'entrata dell'outline nella gerarchia dell'outline del documento PDF
type: docs
weight: 8010
url: /it/net/aspose.pdf/outlineitemcollection/
---
## Classe OutlineItemCollection

Rappresenta un'entrata dell'outline nella gerarchia dell'outline del documento PDF.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Inizializza l'istanza dell'elemento dell'outline utilizzando l'oggetto della gerarchia radice. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Ottiene o imposta l'azione per questo elemento dell'outline. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Ottiene o imposta il flag bold per il testo del titolo di questo elemento dell'outline |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Ottiene o imposta il colore per il testo del titolo di questo elemento dell'outline. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Conteggio degli elementi della collezione. Si prega di non confondere con VisibleCount: VisibleCount ottiene il numero di elementi dell'outline visibili a tutti i livelli. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Ottiene o imposta la destinazione per questo elemento dell'outline. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Ottiene l'elemento dell'outline che rappresenta il primo elemento di livello superiore nella gerarchia dell'outline. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Controlla se l'elemento dell'outline rappresenta il prossimo elemento relativamente a questo elemento nella gerarchia dell'outline. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Ottiene un valore che indica se la collezione è di sola lettura. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Ottiene il valore che indica se l'accesso a questa collezione è sincronizzato (thread safe). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Ottiene o imposta il flag italic per il testo del titolo di questo elemento dell'outline |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Ottiene l'elemento dell'outline dalla collezione utilizzando l'indice. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Ottiene l'elemento dell'outline che rappresenta l'ultimo elemento di livello superiore nella gerarchia dell'outline. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Ottiene il livello gerarchico dell'elemento dell'outline. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Ottiene l'elemento dell'outline che rappresenta il prossimo elemento relativamente a questo elemento nella gerarchia dell'outline. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Ottiene o imposta lo stato di apertura (true/false) per l'elemento dell'outline. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Ottiene l'oggetto padre di questo elemento dell'outline nella gerarchia dell'outline. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Ottiene l'elemento dell'outline che rappresenta l'elemento precedente relativamente a questo elemento nella gerarchia dell'outline. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Ottiene l'oggetto che può essere utilizzato per sincronizzare l'accesso a questa collezione. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Ottiene o imposta il titolo per questo elemento dell'outline. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Ottiene il numero totale di elementi dell'outline a tutti i livelli nella gerarchia dell'outline del documento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Aggiunge un elemento dell'outline alla collezione. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Pulisce tutti gli elementi dalla collezione. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Controlla se la collezione contiene l'elemento dato. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Copia le voci dell'outline in un System.Array, a partire da un particolare indice di System.Array. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Elimina questo elemento dell'outline dalla gerarchia dell'outline del documento. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Elimina l'entrata dell'outline con il nome specificato dalla gerarchia dell'outline del documento. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Restituisce un enumeratore che itera attraverso la collezione. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Inserisce l'elemento dell'outline nella collezione nel luogo specificato. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Rimuove l'elemento per indice. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Rimuove l'elemento della collezione dell'outline. |

### Vedi Anche

* classe [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)