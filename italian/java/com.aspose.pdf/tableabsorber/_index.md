---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta un oggetto assorbitore di elementi tabella. Esegue la ricerca e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TableAbsorber.TableList}. </p> <hr> <pre> The."
type: docs
weight: 4800
url: /it/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> Rappresenta un oggetto assorbitore di elementi tabella. Esegue la ricerca e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TableAbsorber.TableList}. </p> <hr> <pre> L'esempio dimostra come trovare una tabella nella prima pagina del documento PDF e sostituire il testo in una cella della tabella. // Apri documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crea l'oggetto TableAbsorber per trovare le tabelle TableAbsorber absorber = new TableAbsorber(); // Visita la prima pagina con l'assorbitore absorber.visit(doc.getPages().get_Item(1)); // Ottieni l'accesso alla prima tabella nella pagina, alla sua prima cella e ai frammenti di testo al suo interno TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Modifica il testo del primo frammento di testo nella cella fragment.setText("hi world"); // Salva il documento doc.save("D:\\Tests\\output.pdf"); </pre>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> Inizializza una nuova istanza di {@code TableAbsorber}. </p> <hr> Esegue la ricerca delle tabelle e fornisce l'accesso alle tabelle tramite l'oggetto {@code TableList}. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Inizializza una nuova istanza di {@code TableAbsorber}. </p> <hr> Esegue la ricerca delle tabelle e fornisce l'accesso alle tabelle tramite l'oggetto {@code TableList}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTableList](#getTableList--) | <p> Restituisce un IList readonly contenente le tabelle trovate </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Ottiene le opzioni di ricerca del testo. </p> <hr> Consente di definire diverse opzioni che saranno utilizzate durante la ricerca di testo contenuto nelle tabelle. |
| [isUseFlowEngine](#isUseFlowEngine--) | Abilita un motore di riconoscimento tabelle alternativo, superiore in numerosi scenari e capace di riconoscere tabelle senza bordi. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> Rimuove un {@code AbsorbedTable} dalla pagina. </p> <hr> <p> Si prega di tenere presente che modifica la collezione TableList. Nel caso di rimozione/sostituzione di tabelle in un ciclo, utilizzare una copia della collezione TableList. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> Sostituisce un {@code AbsorbedTable} con {@code Table} nella pagina. </p> <hr> <p> Si prega di tenere presente che modifica la collezione TableList. Nel caso di rimozione/sostituzione di tabelle in un ciclo, utilizzare una copia della collezione TableList. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Ottiene o imposta le opzioni di ricerca del testo. </p> <hr> Consente di definire diverse opzioni che saranno utilizzate durante la ricerca di testo contenuto nelle tabelle. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | Abilita un motore di riconoscimento tabelle alternativo, superiore in numerosi scenari e capace di riconoscere tabelle senza bordi. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Estrae le tabelle dal documento specificato. </p> <hr> <pre> L'esempio dimostra come estrarre una tabella nella prima pagina del documento PDF. // Apri documento Document doc = new Document(@"D:\\Tests\\input.pdf"); // Crea l'oggetto TableAbsorber per trovare le tabelle TableAbsorber absorber = new TableAbsorber(); // Visita la prima pagina con l'assorbitore absorber.visit(pdfDocument); // Ottieni l'accesso alla prima tabella nella pagina, alla sua prima cella e ai frammenti di testo al suo interno TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Modifica il testo del primo frammento di testo nella cella fragment.setText ("hi world"); // Salva il documento doc.save(@"D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Estrae le tabelle nella pagina specificata </p> <hr> <pre> L'esempio dimostra come estrarre una tabella nella prima pagina del documento PDF. // Apri documento Document doc = new Document(@"D:\\Tests\\input.pdf"); // Crea l'oggetto TableAbsorber per trovare le tabelle TableAbsorber absorber = new TableAbsorber(); // Visita la prima pagina con l'assorbitore absorber.visit(doc.getPages.get_item(1)); // Ottieni l'accesso alla prima tabella nella pagina, alla sua prima cella e ai frammenti di testo al suo interno TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Modifica il testo del primo frammento di testo nella cella fragment.setText ("hi world"); // Salva il documento doc.save(@"D:\\Tests\\output.pdf"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> Inizializza una nuova istanza di {@code TableAbsorber}. </p> <hr> Esegue la ricerca delle tabelle e fornisce l'accesso alle tabelle tramite l'oggetto {@code TableList}.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Inizializza una nuova istanza di {@code TableAbsorber}. </p> <hr> Esegue la ricerca delle tabelle e fornisce l'accesso alle tabelle tramite l'oggetto {@code TableList}.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> Restituisce un IList readonly contenente le tabelle trovate </p>

**Returns:**
{@code IGenericList<AbsorbedTable> object}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Ottiene le opzioni di ricerca del testo. </p> <hr> Consente di definire diverse opzioni che saranno utilizzate durante la ricerca di testo contenuto nelle tabelle.

**Returns:**
oggetto TextSearchOptions

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

Abilita un motore di riconoscimento tabelle alternativo, superiore in numerosi scenari e capace di riconoscere tabelle senza bordi.

**Returns:**
valore booleano

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> Rimuove un {@code AbsorbedTable} dalla pagina. </p> <hr> <p> Si prega di tenere presente che modifica la collezione TableList. Nel caso di rimozione/sostituzione di tabelle in un ciclo, utilizzare una copia della collezione TableList. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> Sostituisce un {@code AbsorbedTable} con {@code Table} nella pagina. </p> <hr> <p> Si prega di tenere presente che modifica la collezione TableList. Nel caso di rimozione/sostituzione di tabelle in un ciclo, utilizzare una copia della collezione TableList. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Ottiene o imposta le opzioni di ricerca del testo. </p> <hr> Consente di definire diverse opzioni che saranno utilizzate durante la ricerca di testo contenuto nelle tabelle.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

Abilita un motore di riconoscimento tabelle alternativo, superiore in numerosi scenari e capace di riconoscere tabelle senza bordi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| useFlowEngine |  | valore booleano |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Estrae tabelle dal documento specificato. </p> <hr> <pre> L'esempio dimostra come estrarre una tabella nella prima pagina del documento PDF. // Apri documento Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Crea l'oggetto TableAbsorber per trovare le tabelle TableAbsorber absorber = new TableAbsorber(); // Visita la prima pagina con l'assorbitore absorber.visit(pdfDocument); // Ottieni l'accesso alla prima tabella nella pagina, alla sua prima cella e ai frammenti di testo al suo interno TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Modifica il testo del primo frammento di testo nella cella fragment.setText (\"hi world\"); // Salva il documento doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Estrae tabelle nella pagina specificata </p> <hr> <pre> L'esempio dimostra come estrarre una tabella nella prima pagina del documento PDF. // Apri documento Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Crea l'oggetto TableAbsorber per trovare le tabelle TableAbsorber absorber = new TableAbsorber(); // Visita la prima pagina con l'assorbitore absorber.visit(doc.getPages.get_item(1)); // Ottieni l'accesso alla prima tabella nella pagina, alla sua prima cella e ai frammenti di testo al suo interno TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Modifica il testo del primo frammento di testo nella cella fragment.setText (\"hi world\"); // Salva il documento doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
