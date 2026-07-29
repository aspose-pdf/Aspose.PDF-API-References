---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente un objet absorbeur de texte. Effectue l'extraction de texte et fournit l'accès au résultat via l'objet {@code TextAbsorber.Text}. </p> <hr> <pre> L'exemple."
type: docs
weight: 4900
url: /fr/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> Représente un objet absorbant de texte. Effectue l'extraction de texte et fournit l'accès au résultat via l'objet {@code TextAbsorber.Text}. </p> <hr> <pre> L'exemple montre comment extraire le texte de la première page du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> L'objet {@code TextAbsorber} est utilisé pour extraire le texte d'un document Pdf ou de la page du document. </p>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> Initialise une nouvelle instance de {@code TextAbsorber}. </p> <hr> <pre> L'exemple montre comment extraire le texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> Initialise une nouvelle instance de {@code TextAbsorber}. </p> <hr> <pre> L'exemple montre comment extraire le texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> Initialise une nouvelle instance de {@code TextAbsorber}. </p> <hr> <pre> L'exemple montre comment extraire le texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Initialise une nouvelle instance de {@code TextAbsorber}. </p> <hr> <pre> L'exemple montre comment extraire le texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet {@code TextAbsorber.Text}. </p> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getErrors](#getErrors--) | Liste d'objets {@code TextExtractionError}. Elle contient des informations sur les erreurs trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut réduire les performances. |
| [getExtractionOptions](#getExtractionOptions--) | <p> Obtient les options d'extraction de texte. </p> <hr> <pre> L'exemple montre comment définir le mode de formatage de texte Pur et effectuer l'extraction de texte. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permet de définir le mode de formatage du texte {@code TextExtractionOptions} pendant l'extraction. Le mode par défaut est {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [getText](#getText--) | <p> Obtient le texte extrait que {@code TextAbsorber} extrait du document PDF ou de la page. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | Obtient les options de recherche de texte. Permet de définir un rectangle qui délimite le texte extrait. Par défaut, le rectangle est vide. Cela signifie que seules les limites de la page définissent la région d'extraction du texte. |
| [hasErrors](#hasErrors--) | La valeur indique si des erreurs ont été trouvées lors de l'extraction du texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Définit les options d'extraction de texte. </p> <hr> <pre> L'exemple montre comment définir le mode de formatage de texte Pur et effectuer l'extraction de texte. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permet de définir le mode de formatage du texte {@code TextExtractionOptions} pendant l'extraction. Le mode par défaut est {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Définit les options de recherche de texte. Permet de définir un rectangle qui délimite le texte extrait. Par défaut, le rectangle est vide. Cela signifie que seules les limites de la page définissent la région d'extraction du texte. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extrait le texte du document spécifié </p> <hr> <pre> L'exemple montre comment extraire du texte d'un document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extrait le texte de la page spécifiée </p> <hr> <pre> L'exemple montre comment extraire du texte de la première page du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> Extrait le texte du XForm spécifié. </p> <hr> <pre> L'exemple montre comment extraire du texte de la première page du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> Initialise une nouvelle instance de {@code TextAbsorber}. </p> <hr> <pre> L'exemple montre comment extraire le texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> Initialise une nouvelle instance de {@code TextAbsorber}. </p> <hr> <pre> L'exemple montre comment extraire le texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> Initialise une nouvelle instance de {@code TextAbsorber}. </p> <hr> <pre> L'exemple montre comment extraire le texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Initialise une nouvelle instance de {@code TextAbsorber}. </p> <hr> <pre> L'exemple montre comment extraire le texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet {@code TextAbsorber.Text}. </p>

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Liste d'objets {@code TextExtractionError}. Elle contient des informations sur les erreurs trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut réduire les performances.

**Returns:**
Liste d'objets TextExtractionError

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Obtient les options d'extraction de texte. </p> <hr> <pre> L'exemple montre comment définir le mode de formatage de texte Pur et effectuer l'extraction de texte. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permet de définir le mode de formatage du texte {@code TextExtractionOptions} pendant l'extraction. Le mode par défaut est {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

**Returns:**
Valeur de TextExtractionOptions

### getText {#getText--}
```
public String getText()
```

<p> Obtient le texte extrait que {@code TextAbsorber} extrait du document PDF ou de la page. </p>

**Returns:**
Valeur String <hr> <pre> L'exemple montre comment extraire du texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Obtient les options de recherche de texte. Permet de définir un rectangle qui délimite le texte extrait. Par défaut, le rectangle est vide. Cela signifie que seules les limites de la page définissent la région d'extraction du texte.

**Returns:**
Valeur de TextSearchOptions

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

La valeur indique si des erreurs ont été trouvées lors de l'extraction du texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances.

**Returns:**
valeur booléenne

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Définit les options d'extraction de texte. </p> <hr> <pre> L'exemple montre comment définir le mode de formatage de texte Pur et effectuer l'extraction de texte. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permet de définir le mode de formatage du texte {@code TextExtractionOptions} pendant l'extraction. Le mode par défaut est {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Définit les options de recherche de texte. Permet de définir un rectangle qui délimite le texte extrait. Par défaut, le rectangle est vide. Cela signifie que seules les limites de la page définissent la région d'extraction du texte.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extrait le texte du document spécifié </p> <hr> <pre> L'exemple montre comment extraire du texte d'un document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extrait le texte de la page spécifiée </p> <hr> <pre> L'exemple montre comment extraire du texte de la première page du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> Extrait le texte du XForm spécifié. </p> <hr> <pre> L'exemple montre comment extraire du texte de la première page du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre>
