---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar ett absorberande objekt för textfragment. Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments} samling. </p>."
type: docs
weight: 5120
url: /sv/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> Representerar ett absorberande objekt för textfragment. Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments} samling. </p> <hr> <pre> Exemplet demonstrerar hur man hittar text på den första PDF-dokumentets sida och ersätter texten och dess teckensnitt. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra text och teckensnitt för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Objektet {@code TextFragmentAbsorber} används i huvudsak i textsökningsscenario. När sökningen är klar representeras förekomsterna av {@code TextFragment}-objekt som finns i {@code TextFragmentAbsorber.TextFragments}-samlingen. {@code TextFragment}-objektet ger åtkomst till sökförekomstens text, textegenskaper och möjliggör att redigera text och ändra texttillståndet (teckensnitt, teckenstorlek, färg osv). </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> Initierar en ny instans av {@code TextFragmentAbsorber} som söker igenom alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}-samlingen. </p> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | Tillämpar teckenstorlek för alla textfragment som absorberats. Det är snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det liknande som loopning. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | Tillämpar teckensnitt för alla textfragment som absorberats. Det är snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det på liknande sätt som loopning. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | Tillämpar teckensnitt och storlek för alla textfragment som absorberats. Det är snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det på liknande sätt som loopning. |
| [getErrors](#getErrors--) | Lista över {@code TextExtractionError}-objekt. Den innehåller information om fel som hittades under textutdragning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| [getExtractionOptions](#getExtractionOptions--) | Hämtar alternativ för textutdragning. |
| [getPhrase](#getPhrase--) | <p> Hämtar fras som {@code TextFragmentAbsorber} söker i PDF-dokumentet eller på sidan. </p> |
| [getRegexResults](#getRegexResults--) | Hämtar en ordbok med sökförekomster som presenteras med System.Text.RegularExpressions.Regex-klassen som nyckel och {@link TextFragment} som värde. Exemplet visar hur man hittar text med en array av reguljära uttryck på den första PDF-dokumentetsidan. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | Hämtar extraherad text som {@code TextAbsorber} extraherar i PDF-dokumentet eller på sidan. |
| [getTextEditOptions](#getTextEditOptions--) | Hämtar alternativ för textredigering. Alternativen definierar speciellt beteende när begärt tecken inte kan skrivas med teckensnittet. |
| [getTextFragments](#getTextFragments--) | <p> Hämtar en samling av sökförekomster som presenteras med {@code TextFragment}-objekt. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Hämtar alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts med kortare eller längre text. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Hämtar sökalternativ. Alternativen möjliggör sökning med reguljära uttryck. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | Värdet indikerar om fel hittades under textutvinning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestandan. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | Tar bort all text från dokumentet. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | Tar bort all text från den angivna sidan. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Tar bort text inom den angivna rektangeln från den angivna sidan. |
| [reset](#reset--) | Rensar TextFragments-samlingen för detta {@code TextFragmentAbsorber}-objekt. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Ställer in alternativ för textutvinning. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> Ställer in frasen som {@code TextFragmentAbsorber} söker i PDF-dokumentet eller på sidan. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Ställer in alternativ för textredigering. Alternativen definierar speciellt beteende när den begärda symbolen inte kan skrivas med teckensnittet. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> Ställer in samling av sökförekomster som presenteras med {@code TextFragment}-objekt. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Ställer in alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts till kortare eller längre. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Ställer in sökalternativ. Alternativen möjliggör sökning med reguljära uttryck. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Utför sökning i det angivna dokumentet. </p> <hr> <pre> Exemplet visar hur man hittar text i PDF-dokumentet och ersätter texten för alla sökförekomster. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Utför sökning på den angivna sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentetsida och ersätter texten. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | Utför sökning på det angivna formulärobjektet. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> Initierar en ny instans av {@code TextFragmentAbsorber} som utför sökning av alla textsegment i dokumentet eller sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Gör så att absorberaren söker alla "hello world"-textförekomster absorber.setPhrase ( "hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra texten för den första textförekomsten absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Utför textsökning och ger åtkomst till sökresultaten via {@code TextFragmentAbsorber.TextFragments}‑samlingen. </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

Tillämpar teckenstorlek för alla textfragment som absorberats. Det är snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det liknande som loopning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontSize |  | Teckenstorlek för texten. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
Tillämpar teckensnitt för alla textfragment som absorberats. Det är snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det på liknande sätt som loopning.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
Tillämpar teckensnitt och storlek för alla textfragment som absorberats. Det är snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det på liknande sätt som loopning.

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Lista över {@code TextExtractionError}-objekt. Den innehåller information om fel som hittades under textutdragning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda.

**Returns:**
Lista över TextExtractionError-objekt

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

Hämtar alternativ för textutdragning.

**Returns:**
TextExtractionOptions-objekt

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> Hämtar fras som {@code TextFragmentAbsorber} söker i PDF-dokumentet eller på sidan. </p>

**Returns:**
Strängvärde <hr> <pre> Exemplet visar hur man utför textsökning flera gånger och utför textersättningar. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // sök ett annat ord och ersätt det absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

Hämtar en ordbok med sökförekomster som presenteras med System.Text.RegularExpressions.Regex-klassen som nyckel och {@link TextFragment} som värde. Exemplet visar hur man hittar text med en array av reguljära uttryck på den första PDF-dokumentetsidan. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults();

**Returns:**
Dictionary-instans

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

Hämtar extraherad text som {@code TextAbsorber} extraherar i PDF-dokumentet eller på sidan.

**Returns:**
Strängvärde Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet. // öppna dokument Document doc = new Document(inFile); // skapa TextAbsorber-objekt för att extrahera text TextAbsorber absorber = new TextAbsorber(); // acceptera absorberaren för alla dokumentets sidor doc.getPages().accept(absorber); // hämta den extraherade texten String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Hämtar alternativ för textredigering. Alternativen definierar speciellt beteende när begärt tecken inte kan skrivas med teckensnittet.

**Returns:**
TextEditOptions-objekt

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> Hämtar en samling av sökförekomster som presenteras med {@code TextFragment}-objekt. </p>

**Returns:**
TextFragmentCollection-objekt <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter alla sökförekomster med ny text. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan doc.getPages().get(1).accept(absorber); // Ändra text för alla sökförekomster for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Hämtar alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts med kortare eller längre text.

**Returns:**
TextReplaceOptions-värde

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Hämtar sökalternativ. Alternativen möjliggör sökning med reguljära uttryck. </p>

**Returns:**
TextSearchOptions-objekt <hr> <pre> Exemplet visar hur man utför textsökning med reguljära uttryck. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Skapa TextFragmentAbsorber-objekt TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // gör så att absorberaren söker alla ord som börjar med 'h' och slutar med 'o' med reguljärt uttryck. absorber.setPhrase ( "h\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // vi bör hitta ordet "hello" och ersätta det med "Hi" doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

Värdet indikerar om fel hittades under textutvinning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestandan.

**Returns:**
booleskt värde

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
Tar bort all text från dokumentet.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
Tar bort all text från den angivna sidan.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Tar bort text inom den angivna rektangeln från den angivna sidan.

### reset {#reset--}
```
public void reset()
```

Rensar TextFragments-samlingen för detta {@code TextFragmentAbsorber}-objekt.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
Ställer in alternativ för textutvinning.

### setPhrase {#setPhrase-java.lang.String-}
<p> Ställer in frasen som {@code TextFragmentAbsorber} söker i PDF-dokumentet eller på sidan. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Ställer in alternativ för textredigering. Alternativen definierar speciellt beteende när den begärda symbolen inte kan skrivas med teckensnittet.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> Ställer in samling av sökförekomster som presenteras med {@code TextFragment}-objekt. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Ställer in alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts till kortare eller längre.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Ställer in sökalternativ. Alternativen möjliggör sökning med reguljära uttryck. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Utför sökning i det angivna dokumentet. </p> <hr> <pre> Exemplet visar hur man hittar text i ett PDF-dokument och ersätter texten för alla sökresultat. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textresultat TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan absorber.visit(doc); // Ändra texten för det första textresultatet absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Utför sökning på den angivna sidan. </p> <hr> <pre> Exemplet visar hur man hittar text på den första PDF-dokumentsidan och ersätter texten. // Öppna dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt Font font = FontRepository.findFont("Arial"); // Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textresultat TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Acceptera absorberaren för första sidan absorber.visit(doc.getPages().get(1)); // Ändra texten för alla sökresultat for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Spara dokument doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
Utför sökning på det angivna formulärobjektet.
