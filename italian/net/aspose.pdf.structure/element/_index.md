---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Structure.Element class. Class representing base element of logical structure
type: docs
weight: 10140
url: /it/net/aspose.pdf.structure/element/
---
## Classe Elemento

Classe che rappresenta l'elemento base della struttura logica.

```csharp
public abstract class Element
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Facoltativo; PDF 1.4) Testo che è una sostituzione esatta per l'elemento di struttura e i suoi figli. Questo testo di sostituzione (che dovrebbe applicarsi a quanto più piccolo possibile contenuto) è utile quando si estraggono i contenuti del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Facoltativo) Una descrizione alternativa dell'elemento di struttura e dei suoi figli in forma leggibile dall'uomo, che è utile quando si estraggono i contenuti del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Ottiene la collezione di elementi figli. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Facoltativo; PDF 1.5) La forma espansa di un'abbreviazione. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Facoltativo; PDF 1.4) Una lingua che specifica la lingua naturale per tutto il testo nell'elemento di struttura, tranne dove sovrascritto da specifiche linguistiche per elementi di struttura annidati o contenuti contrassegnati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Rimuovi elemento. |

### Vedi Anche

* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)