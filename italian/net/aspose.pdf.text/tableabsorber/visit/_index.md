---
title: "TableAbsorber.Visit"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo TableAbsorber. Estrae le tabelle nella pagina specificata"
type: docs
weight: 70
url: /it/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Estrae le tabelle nella pagina specificata

```csharp
public virtual void Visit(Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Page | Oggetto pagina PDF. |

## Esempi

L'esempio dimostra come estrarre una tabella nella prima pagina del documento PDF.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TableAbsorber per trovare le tabelle
TableAbsorber absorber = new TableAbsorber();

// Visita la prima pagina con l'assorbitore
absorber.Visit(doc.Pages[1]);

// Ottieni l'accesso alla prima tabella nella pagina, alla sua prima cella e ai frammenti di testo al suo interno
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Modifica il testo del primo frammento di testo nella cella
fragment.Text = "hi world";

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Estrae le tabelle nel documento specificato.

```csharp
public void Visit(Document pdf)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdf | Document | Oggetto Pdf pocument. |

## Esempi

L'esempio dimostra come estrarre una tabella nella prima pagina del documento PDF.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TableAbsorber per trovare le tabelle
TableAbsorber absorber = new TableAbsorber();

// Visita la prima pagina con l'assorbitore
absorber.Visit(doc);

// Ottieni l'accesso alla prima tabella nella pagina, alla sua prima cella e ai frammenti di testo al suo interno
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Modifica il testo del primo frammento di testo nella cella
fragment.Text = "hi world";

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


