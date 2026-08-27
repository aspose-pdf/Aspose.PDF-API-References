---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente un objet absorbeur d'éléments de tableau. Effectue une recherche et fournit l'accès aux résultats de recherche via {@code TableAbsorber.TableList} collection. </p> <hr> <pre> The."
type: docs
weight: 4800
url: /fr/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> Représente un objet absorbeur d'éléments de tableau. Effectue une recherche et fournit l'accès aux résultats de recherche via {@code TableAbsorber.TableList} collection. </p> <hr> <pre> L'exemple montre comment trouver un tableau sur la première page du document PDF et remplacer le texte dans une cellule de tableau. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer un objet TableAbsorber pour trouver les tableaux TableAbsorber absorber = new TableAbsorber(); // Visiter la première page avec l'absorbeur absorber.visit(doc.getPages().get_Item(1)); // Accéder au premier tableau de la page, à sa première cellule et aux fragments de texte qu'elle contient TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Modifier le texte du premier fragment de texte dans la cellule fragment.setText("hi world"); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> Initialise une nouvelle instance de {@code TableAbsorber}. </p> <hr> Effectue la recherche de tableaux et fournit l'accès aux tableaux via {@code TableList} objet. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Initialise une nouvelle instance de {@code TableAbsorber}. </p> <hr> Effectue la recherche de tableaux et fournit l'accès aux tableaux via {@code TableList} objet. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getTableList](#getTableList--) | <p> Renvoie une IList en lecture seule contenant les tableaux qui ont été trouvés </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Obtient les options de recherche de texte. </p> <hr> Permet de définir plusieurs options qui seront utilisées lors de la recherche de texte contenue dans les tableaux. |
| [isUseFlowEngine](#isUseFlowEngine--) | Activez un moteur de reconnaissance de tableau alternatif qui est supérieur dans de nombreux scénarios et capable de reconnaître les tableaux sans bordures. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> Supprime un {@code AbsorbedTable} de la page. </p> <hr> <p> Veuillez noter que cela modifie la collection TableList. En cas de suppression/remplacement de tableaux dans une boucle, veuillez utiliser une copie de la collection TableList. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> Remplace un {@code AbsorbedTable} par {@code Table} sur la page. </p> <hr> <p> Veuillez noter que cela modifie la collection TableList. En cas de suppression/remplacement de tableaux dans une boucle, veuillez utiliser une copie de la collection TableList. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Obtient ou définit les options de recherche de texte. </p> <hr> Permet de définir plusieurs options qui seront utilisées lors de la recherche de texte contenue dans les tableaux. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | Activez un moteur de reconnaissance de tableau alternatif qui est supérieur dans de nombreux scénarios et capable de reconnaître les tableaux sans bordures. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extrait les tableaux du document spécifié. </p> <hr> <pre> L'exemple montre comment extraire un tableau sur la première page du document PDF. // Ouvrir le document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Créer un objet TableAbsorber pour trouver les tableaux TableAbsorber absorber = new TableAbsorber(); // Visiter la première page avec l'absorbeur absorber.visit(pdfDocument); // Accéder au premier tableau de la page, à sa première cellule et aux fragments de texte qu'elle contient TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Modifier le texte du premier fragment de texte dans la cellule fragment.setText ("hi world"); // Enregistrer le document doc.save(@"D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extrait les tableaux de la page spécifiée </p> <hr> <pre> L'exemple montre comment extraire un tableau sur la première page du document PDF. // Ouvrir le document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Créer un objet TableAbsorber pour trouver les tableaux TableAbsorber absorber = new TableAbsorber(); // Visiter la première page avec l'absorbeur absorber.visit(doc.getPages.get_item(1)); // Accéder au premier tableau de la page, à sa première cellule et aux fragments de texte qu'elle contient TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Modifier le texte du premier fragment de texte dans la cellule fragment.setText ("hi world"); // Enregistrer le document doc.save(@"D:\\Tests\\output.pdf"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> Initialise une nouvelle instance de {@code TableAbsorber}. </p> <hr> Effectue la recherche de tableaux et fournit l'accès aux tableaux via {@code TableList} objet.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Initialise une nouvelle instance de {@code TableAbsorber}. </p> <hr> Effectue la recherche de tableaux et fournit l'accès aux tableaux via {@code TableList} objet.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> Renvoie une IList en lecture seule contenant les tableaux qui ont été trouvés </p>

**Returns:**
{@code IGenericList<AbsorbedTable> objet}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Obtient les options de recherche de texte. </p> <hr> Permet de définir plusieurs options qui seront utilisées lors de la recherche de texte contenue dans les tableaux.

**Returns:**
TextSearchOptions objet

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

Activez un moteur de reconnaissance de tableau alternatif qui est supérieur dans de nombreux scénarios et capable de reconnaître les tableaux sans bordures.

**Returns:**
valeur booléenne

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> Supprime un {@code AbsorbedTable} de la page. </p> <hr> <p> Veuillez noter que cela modifie la collection TableList. En cas de suppression/remplacement de tableaux dans une boucle, veuillez utiliser une copie de la collection TableList. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> Remplace un {@code AbsorbedTable} par {@code Table} sur la page. </p> <hr> <p> Veuillez noter que cela modifie la collection TableList. En cas de suppression/remplacement de tableaux dans une boucle, veuillez utiliser une copie de la collection TableList. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Obtient ou définit les options de recherche de texte. </p> <hr> Permet de définir plusieurs options qui seront utilisées lors de la recherche de texte contenue dans les tableaux.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

Activez un moteur de reconnaissance de tableau alternatif qui est supérieur dans de nombreux scénarios et capable de reconnaître les tableaux sans bordures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| useFlowEngine |  | valeur booléenne |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extrait les tableaux du document spécifié. </p> <hr> <pre> L'exemple montre comment extraire un tableau sur la première page du document PDF. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extrait les tableaux de la page spécifiée </p> <hr> <pre> L'exemple montre comment extraire un tableau sur la première page du document PDF. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
