---
title: "Classe OutlineItemCollection"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.OutlineItemCollection. Rappresenta una voce di indice nella gerarchia dell'indice di un documento PDF"
type: docs
weight: 8150
url: /it/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

Rappresenta una voce di outline nella gerarchia di outline del documento PDF.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Inizializza l'istanza della voce di indice utilizzando l'oggetto gerarchia radice. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Ottiene o imposta l'azione per questa voce di indice. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Ottiene o imposta il flag grassetto per il testo del titolo di questa voce di indice |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Ottiene o imposta il colore per il testo del titolo di questa voce di indice. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Conteggio degli elementi della raccolta. Per favore non confondere con VisibleCount: VisibleCount restituisce il numero di elementi della struttura visibili a tutti i livelli. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Ottiene o imposta la destinazione per questa voce di indice. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Ottiene la voce di indice che rappresenta il primo elemento di livello superiore nella gerarchia dell'indice. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Verifica se la voce di indice che rappresenta l'elemento successivo rispetto a questa voce nella gerarchia dell'indice. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Restituisce un valore che indica se la collezione è di sola lettura. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Ottiene il valore che indica se l'accesso a questa collezione è sincronizzato (thread safe). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Ottiene o imposta il flag corsivo per il testo del titolo di questa voce di indice |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Ottiene la voce di indice dalla collezione usando l'indice. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Ottiene la voce di indice che rappresenta l'ultimo elemento di livello superiore nella gerarchia dell'indice. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Ottiene il livello gerarchico della voce di indice. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Ottiene la voce di indice che rappresenta l'elemento successivo rispetto a questa voce nella gerarchia dell'indice. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Ottiene o imposta lo stato di apertura (true/false) per la voce di indice. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Ottiene l'oggetto padre di questa voce di indice nella gerarchia dell'indice. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Ottiene la voce di indice che rappresenta l'elemento precedente rispetto a questa voce nella gerarchia dell'indice. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Ottiene l'oggetto che può essere usato per sincronizzare l'accesso a questa raccolta. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Ottiene o imposta il titolo per questa voce di indice. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Ottiene il numero totale di voci di indice a tutti i livelli nella gerarchia dell'indice del documento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Aggiunge un elemento di contorno alla raccolta. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Cancella tutti gli elementi dalla raccolta. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Verifica se la raccolta contiene l'elemento specificato. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Copia le voci di indice in un System.Array, iniziando a un indice specifico di System.Array. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Elimina questa voce di indice dalla gerarchia dell'indice del documento. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Elimina la voce di indice con il nome specificato dalla gerarchia dell'indice del documento. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Restituisce un enumeratore che itera attraverso la collezione. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Inserisce la voce di indice nella raccolta nella posizione specificata. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Rimuove l'elemento per indice. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Rimuove l'elemento della raccolta di indice. |

### Vedi anche

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


