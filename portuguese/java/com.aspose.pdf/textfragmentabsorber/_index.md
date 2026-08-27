---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa um objeto absorvedor de fragmentos de texto. Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p>."
type: docs
weight: 5120
url: /pt/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> Representa um objeto absorvedor de fragmentos de texto. Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto e sua fonte.
// Abrir documento Document doc = new Document("D:\\Tests\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento com.aspose.pdf.Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto e a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).setText ( "hi world");
absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
// Salvar documento doc.save("D:\\Tests\\output.pdf");
</pre> <hr> <p> O objeto {@code TextFragmentAbsorber} é basicamente usado em cenários de pesquisa de texto. Quando a pesquisa é concluída, as ocorrências são representadas por objetos {@code TextFragment} que a coleção {@code TextFragmentAbsorber.TextFragments} contém. O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de pesquisa, às propriedades do texto e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc). </p>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a pesquisa de todos os segmentos de texto do documento ou página. </p> <hr> <pre>
O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.
// Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf");
// Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont("Arial");
// Criar objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber();
// Configurar o absorvedor para pesquisar todas as ocorrências de texto "hello world" absorber.setPhrase ( "hello world");
// Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber);
// Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world");
// Salvar documento doc.save("D:\\\\Tests\\\\output.pdf");
</pre> <hr> <p> Executa a pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> |

## Métodos

| Método | Descrição |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | Aplica o tamanho da fonte para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido que percorrer os fragmentos se todos os fragmentos nas página(s) foram absorvidos. Caso contrário funciona de forma semelhante ao percorrer. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | Aplica a fonte para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido que percorrer os fragmentos se todos os fragmentos nas página(s) foram absorvidos. Caso contrário funciona de forma semelhante ao percorrer. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | Aplica a fonte e o tamanho para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido que percorrer os fragmentos se todos os fragmentos nas página(s) foram absorvidos. Caso contrário funciona de forma semelhante ao percorrer. |
| [getErrors](#getErrors--) | Lista de objetos {@code TextExtractionError}. Contém informações sobre erros encontrados durante a extração de texto. A busca por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho. |
| [getExtractionOptions](#getExtractionOptions--) | Obtém opções de extração de texto. |
| [getPhrase](#getPhrase--) | <p> Obtém a frase que o {@code TextFragmentAbsorber} pesquisa no documento PDF ou página. </p> |
| [getRegexResults](#getRegexResults--) | Obtém dicionário de ocorrências de pesquisa que são apresentadas com a classe System.Text.RegularExpressions.Regex como chave e {@link TextFragment} como valor. O exemplo demonstra como encontrar texto com um array de expressões regulares na primeira página do documento PDF. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | Obtém o texto extraído que o {@code TextAbsorber} extrai no documento PDF ou na página. |
| [getTextEditOptions](#getTextEditOptions--) | Obtém opções de edição de texto. As opções definem comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [getTextFragments](#getTextFragments--) | <p> Obtém coleção de ocorrências de pesquisa que são apresentadas com objetos {@code TextFragment}. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Obtém as opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto ou mais longo. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Obtém opções de pesquisa. As opções permitem pesquisa usando expressões regulares. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | O valor indica se erros foram encontrados durante a extração de texto. A pesquisa por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | Remove todo o texto do documento. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | Remove todo o texto da página especificada. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Remove texto dentro do retângulo especificado da página especificada. |
| [reset](#reset--) | Limpa a coleção TextFragments deste objeto {@code TextFragmentAbsorber}. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Define opções de extração de texto. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> Define a frase que o {@code TextFragmentAbsorber} procura no documento PDF ou na página. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Define opções de edição de texto. As opções definem comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> Define a coleção de ocorrências de pesquisa que são apresentadas com objetos {@code TextFragment}. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Define opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto/mais longo. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Define opções de pesquisa. As opções permitem pesquisa usando expressões regulares. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Executa pesquisa no documento especificado. </p> <hr> <pre> O exemplo demonstra como encontrar texto em um documento PDF e substituir o texto de todas as ocorrências de pesquisa. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar fonte que será usada para mudar a fonte do texto do documento Font font = FontRepository.findFont("Arial"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página absorber.visit(doc); // Alterar o texto da primeira ocorrência absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Salvar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Executa pesquisa na página especificada. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar fonte que será usada para mudar a fonte do texto do documento Font font = FontRepository.findFont("Arial"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página absorber.visit(doc.getPages().get(1)); // Alterar texto de todas as ocorrências de pesquisa for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Salvar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | Executa pesquisa no objeto de formulário especificado. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> Inicializa uma nova instância do {@code TextFragmentAbsorber} que realiza a busca de todos os segmentos de texto do documento ou da página. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza a busca de texto e fornece acesso aos resultados da busca via coleção {@code TextFragmentAbsorber.TextFragments}. </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

Aplica o tamanho da fonte para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido que percorrer os fragmentos se todos os fragmentos nas página(s) foram absorvidos. Caso contrário funciona de forma semelhante ao percorrer.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontSize |  | Tamanho da fonte do texto. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
Aplica a fonte para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido que percorrer os fragmentos se todos os fragmentos nas página(s) foram absorvidos. Caso contrário funciona de forma semelhante ao percorrer.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
Aplica a fonte e o tamanho para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido que percorrer os fragmentos se todos os fragmentos nas página(s) foram absorvidos. Caso contrário funciona de forma semelhante ao percorrer.

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Lista de objetos {@code TextExtractionError}. Contém informações sobre erros encontrados durante a extração de texto. A busca por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho.

**Returns:**
Lista de objetos TextExtractionError

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

Obtém opções de extração de texto.

**Returns:**
Objeto TextExtractionOptions

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> Obtém a frase que o {@code TextFragmentAbsorber} pesquisa no documento PDF ou página. </p>

**Returns:**
Valor de string <hr> <pre> O exemplo demonstra como executar a busca de texto várias vezes e realizar substituições de texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // search another word and replace it absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

Obtém dicionário de ocorrências de pesquisa que são apresentadas com a classe System.Text.RegularExpressions.Regex como chave e {@link TextFragment} como valor. O exemplo demonstra como encontrar texto com um array de expressões regulares na primeira página do documento PDF. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults();

**Returns:**
Instância de Dictionary

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

Obtém o texto extraído que o {@code TextAbsorber} extrai no documento PDF ou na página.

**Returns:**
Valor de string O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // abre o documento Document doc = new Document(inFile); // cria objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceita o absorvedor para todas as páginas do documento doc.getPages().accept(absorber); // obtém o texto extraído String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Obtém opções de edição de texto. As opções definem comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte.

**Returns:**
Objeto TextEditOptions

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> Obtém coleção de ocorrências de pesquisa que são apresentadas com objetos {@code TextFragment}. </p>

**Returns:**
Objeto TextFragmentCollection <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir todas as ocorrências encontradas por um novo texto. // abre o documento Document doc = new Document("D:\\Tests\\input.pdf"); // encontra a fonte que será usada para mudar a fonte do texto do documento Font font = FontRepository.findFont("Arial"); // cria objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // aceita o absorvedor para a primeira página doc.getPages().get(1).accept(absorber); // altera o texto de todas as ocorrências encontradas for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // salva o documento doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Obtém as opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto ou mais longo.

**Returns:**
Valor TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Obtém opções de pesquisa. As opções permitem pesquisa usando expressões regulares. </p>

**Returns:**
Objeto TextSearchOptions <hr> <pre> O exemplo demonstra como executar a busca de texto usando expressão regular. // abre o documento Document doc = new Document("D:\\Tests\\input.pdf"); // cria objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // faz o absorvedor buscar todas as palavras que começam com 'h' e terminam com 'o' usando expressão regular. absorber.setPhrase ( "h\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // devemos encontrar a palavra "hello" e substituí-la por "Hi" doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // salva o documento doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

O valor indica se erros foram encontrados durante a extração de texto. A pesquisa por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho.

**Returns:**
valor booleano

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
Remove todo o texto do documento.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
Remove todo o texto da página especificada.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Remove texto dentro do retângulo especificado da página especificada.

### reset {#reset--}
```
public void reset()
```

Limpa a coleção TextFragments deste objeto {@code TextFragmentAbsorber}.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
Define opções de extração de texto.

### setPhrase {#setPhrase-java.lang.String-}
<p> Define a frase que o {@code TextFragmentAbsorber} procura no documento PDF ou na página. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Define opções de edição de texto. As opções definem comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> Define a coleção de ocorrências de pesquisa que são apresentadas com objetos {@code TextFragment}. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Define opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto/mais longo.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Define opções de pesquisa. As opções permitem pesquisa usando expressões regulares. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Realiza pesquisa no documento especificado. </p> <hr> <pre> O exemplo demonstra como encontrar texto em um documento PDF e substituir o texto de todas as ocorrências encontradas. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Realiza pesquisa na página especificada. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( \"hi world\"); } // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
Executa pesquisa no objeto de formulário especificado.
