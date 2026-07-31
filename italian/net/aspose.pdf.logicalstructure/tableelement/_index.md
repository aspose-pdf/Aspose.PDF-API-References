---
title: "Classe TableElement"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "classe Aspose.Pdf.LogicalStructure.TableElement. Rappresenta l'elemento di struttura Table nella struttura logica."
type: docs
weight: 6920
url: /it/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Rappresenta l'elemento di struttura Table nella struttura logica.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Ottiene o imposta il testo effettivo per l'elemento di struttura. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Ottiene o imposta l'allineamento della tabella. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Ottiene o imposta il testo alternativo per l'elemento di struttura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Ottiene l'oggetto StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Ottiene o imposta il colore di sfondo della tabella. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Ottiene o imposta il bordo della tabella. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Ottiene o imposta la rottura verticale della tabella; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ottiene la collezione di figli di oggetti Element. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Ottiene o imposta la regolazione della colonna della tabella. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Ottiene le larghezze delle colonne della tabella. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Ottiene o imposta gli stili degli angoli del bordo. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Ottiene l'oggetto AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Ottiene il bordo predefinito della cella. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Ottiene o imposta il padding predefinito della cella. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Ottiene o imposta lo stato di testo predefinito della cella. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Ottiene o imposta la larghezza predefinita della colonna. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Ottiene o imposta il testo di espansione per l'elemento di struttura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Ottiene l'ID per l'elemento di struttura. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Ottiene o imposta il bordo incluso nelle larghezze delle colonne. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Ottiene o imposta se la tabella è interrotta - verrà troncata per la pagina successiva. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Ottiene o imposta la lingua per l'elemento di struttura. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Ottiene o imposta la coordinata sinistra della tabella. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Ottiene la pagina su cui alcuni o tutti gli elementi figlio saranno renderizzati. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ottieni l'elemento genitore. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Ottiene o imposta il conteggio massimo di colonne per la tabella. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Ottiene il conteggio delle prime righe ripetute per più pagine. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Ottiene lo stile per le righe ripetute. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Ottiene il tipo dell'elemento di struttura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Ottiene o imposta il titolo per l'elemento di struttura. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Ottiene o imposta la coordinata superiore della tabella. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Aggiungi Element alla collezione di figli. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Cambia l'elemento genitore per l'elemento di struttura corrente |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Cancella tutti i figli. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Cancella l'ID per l'elemento di struttura. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Crea [`TableTHeadElement`](../tabletheadelement/) e lo aggiunge alla tabella corrente. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Crea [`TableTFootElement`](../tabletfootelement/) e lo aggiunge alla tabella corrente. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Crea [`TableTHeadElement`](../tabletheadelement/) e lo aggiunge alla tabella corrente. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trova Elementi di un determinato tipo |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Genera l'ID per l'elemento di struttura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserisci Element nella collezione di figli all'indice specificato. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Rimuove: un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figlio, l'oggetto corrispondente dal documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Rimuove un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figlio e l'oggetto corrispondente dal documento. Inserisce gli oggetti figlio dell'oggetto rimosso nella precedente collezione di oggetti figlio del padre a partire dall'indice dell'oggetto rimosso. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Rimuovi figlio a. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Imposta l'ID per l'elemento di struttura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Imposta il tag personalizzato per l'elemento di struttura. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Associa un elemento di struttura all'Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Associa un elemento di struttura all'Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Associa un elemento di struttura all'operatore BDC del flusso di contenuto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Associa un elemento di struttura al XForm del flusso di contenuto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Associa un elemento di struttura al XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Vedi anche

* class [BLSElement](../blselement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


