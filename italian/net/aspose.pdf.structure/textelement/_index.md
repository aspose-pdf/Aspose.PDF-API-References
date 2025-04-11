---
title: Class TextElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Structure.TextElement. Elemento di testo generale della struttura logica del documento
type: docs
weight: 10190
url: /it/net/aspose.pdf.structure/textelement/
---
## Classe TextElement

Elemento di testo generale della struttura logica del documento.

```csharp
public class TextElement : Element
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Facoltativo; PDF 1.4) Testo che è una sostituzione esatta per l'elemento di struttura e i suoi figli. Questo testo di sostituzione (che dovrebbe applicarsi a un pezzo di contenuto il più piccolo possibile) è utile quando si estraggono i contenuti del documento a supporto dell'accessibilità per utenti con disabilità o per altri scopi. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Facoltativo) Una descrizione alternativa dell'elemento di struttura e dei suoi figli in forma leggibile dall'uomo, che è utile quando si estraggono i contenuti del documento a supporto dell'accessibilità per utenti con disabilità o per altri scopi. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Ottiene la collezione di elementi figli. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Facoltativo; PDF 1.5) La forma espansa di un'abbreviazione. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Facoltativo; PDF 1.4) Una lingua che specifica la lingua naturale per tutto il testo nell'elemento di struttura, tranne dove sovrascritto da specifiche linguistiche per elementi di struttura annidati o contenuti contrassegnati. |
| [Text](../../aspose.pdf.structure/textelement/text/) { get; } | Ottiene il valore dell'elemento di struttura del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Rimuovi elemento. |

### Vedi Anche

* classe [Element](../element/)
* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)