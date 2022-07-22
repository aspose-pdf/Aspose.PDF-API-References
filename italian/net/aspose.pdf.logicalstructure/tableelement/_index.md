---
title: TableElement
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta lelemento della struttura della tabella nella struttura logica.
type: docs
weight: 4610
url: /it/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Rappresenta l'elemento della struttura della tabella nella struttura logica.

```csharp
public sealed class TableElement : BLSElement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Ottiene o imposta il testo effettivo per l'elemento della struttura. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment) { get; set; } | Ottiene o imposta l'allineamento della tabella. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Ottiene o imposta il testo alternativo per l'elemento struttura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | OttieneStructureAttributeCollection oggetto. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor) { get; set; } | Ottiene o imposta il colore di sfondo della tabella. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border) { get; set; } | Ottiene o imposta il bordo della tabella. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken) { get; set; } | Ottiene o imposta la verticale della tabella interrotta; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Ottiene la raccolta dei bambini diElement oggetti. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment) { get; set; } | Ottiene o imposta la regolazione della colonna della tabella. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths) { get; set; } | Ottiene le larghezze delle colonne della tabella. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle) { get; set; } | Ottiene o imposta gli stili degli angoli del bordo |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | OttieneAttributeOwnerStandard oggetto. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder) { get; set; } | Ottiene il bordo della cella predefinito. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding) { get; set; } | Ottiene o imposta il riempimento predefinito della cella. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate) { get; set; } | Ottiene o imposta lo stato predefinito del testo della cella. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth) { get; set; } | Ottiene o imposta la larghezza della colonna predefinita. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Ottiene o imposta il testo di espansione per l'elemento struttura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Ottiene l'ID per l'elemento struttura. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded) { get; set; } | Ottiene o imposta il bordo incluso nelle larghezze di colonna. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken) { get; set; } | Ottiene o imposta la tabella è interrotta - verrà troncata per la pagina successiva. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Ottiene o imposta la lingua per l'elemento struttura. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left) { get; set; } | Ottiene o imposta la coordinata sinistra della tabella. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Ottieni elemento padre. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount) { get; set; } | Ottiene o imposta il numero massimo di colonne per la tabella. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount) { get; set; } | Ottiene il conteggio delle prime righe ripetuto per più pagine. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle) { get; set; } | Ottiene lo stile per la ripetizione delle righe. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Ottiene il tipo di elemento della struttura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Ottiene o imposta il titolo per l'elemento struttura. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top) { get; set; } | Ottiene o imposta la coordinata superiore del tavolo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | AggiungiElement alla raccolta dei bambini. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Modifica elemento padre per elemento struttura corrente |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Cancella ID per elemento struttura. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody)() | Crea[`TableTHeadElement`](../tabletheadelement) e l'ho aggiunto alla tabella corrente. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot)() | Crea[`TableTFootElement`](../tabletfootelement) e l'ho aggiunto alla tabella corrente. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead)() | Crea[`TableTHeadElement`](../tabletheadelement) e l'ho aggiunto alla tabella corrente. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Trova elementi di un determinato tipo |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Genera ID per elemento struttura. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Imposta l'ID per l'elemento della struttura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Imposta tag personalizzati per l'elemento struttura. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Guarda anche

* class [BLSElement](../blselement)
* spazio dei nomi [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
