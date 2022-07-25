---
title: TableTRElement
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta lelemento della struttura TR nella struttura logica della tabella.
type: docs
weight: 4680
url: /it/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement class

Rappresenta l'elemento della struttura TR nella struttura logica della tabella.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Ottiene o imposta il testo effettivo per l'elemento della struttura. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Ottiene o imposta il testo alternativo per l'elemento struttura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | OttieneStructureAttributeCollection oggetto. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor) { get; set; } | Ottiene o imposta il colore di sfondo della riga. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border) { get; set; } | Ottiene o imposta il bordo della riga. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Ottiene la raccolta dei bambini diElement oggetti. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | OttieneAttributeOwnerStandard oggetto. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder) { get; set; } | Ottiene il bordo della cella predefinito. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding) { get; set; } | Ottiene o imposta il margine predefinito per le celle di riga. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate) { get; set; } | Ottiene o imposta lo stato del testo predefinito per le celle di riga |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Ottiene o imposta il testo di espansione per l'elemento struttura. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight) { get; set; } | Ottiene l'altezza della riga fissa - la riga potrebbe avere un'altezza fissa. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Ottiene l'ID per l'elemento struttura. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage) { get; set; } | Ottiene la riga fissa è in una nuova pagina - la pagina con questa proprietà dovrebbe essere stampata alla pagina successiva Predefinito false. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken) { get; set; } | Ottiene la riga può essere interrotta tra due pagine. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Ottiene o imposta la lingua per l'elemento struttura. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight) { get; set; } | Ottiene l'altezza per la riga. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Ottieni elemento padre. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Ottiene il tipo di elemento della struttura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Ottiene o imposta il titolo per l'elemento struttura. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment) { get; set; } | Ottiene o imposta l'allineamento verticale. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | AggiungiElement alla raccolta dei bambini. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Modifica elemento padre per elemento struttura corrente |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Cancella ID per elemento struttura. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd)() | Crea[`TableTHElement`](../tablethelement) e l'ho aggiunto alla tabella corrente. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth)() | Crea[`TableTHElement`](../tablethelement) e l'ho aggiunto alla tabella corrente. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Trova elementi di un determinato tipo |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Genera ID per elemento struttura. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Imposta l'ID per l'elemento della struttura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Imposta tag personalizzati per l'elemento struttura. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Guarda anche

* class [TableChildElement](../tablechildelement)
* spazio dei nomi [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
