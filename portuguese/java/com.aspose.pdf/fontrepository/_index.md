---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Executa a pesquisa de fontes. Procura nas fontes instaladas no sistema e nas fontes padrão do Pdf. Também fornece funcionalidade para abrir fontes personalizadas. </p> <hr> <pre> O exemplo demonstra."
type: docs
weight: 1690
url: /pt/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> Executa a pesquisa de fontes. Procura nas fontes instaladas no sistema e nas fontes padrão do Pdf. Também fornece funcionalidade para abrir fontes personalizadas. </p> <hr> <pre> O exemplo demonstra como encontrar uma fonte e substituir a fonte do texto da primeira página. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | Adicione mais um caminho para fontes. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> Adicione fonte do sistema com a fonte especificada. </p> <hr> <pre> O exemplo demonstra como adicionar fonte do sistema. InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> Procura e retorna a fonte com o nome de fonte especificado. </p> <hr> <pre> O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> Procura e retorna a fonte com o nome de fonte especificado, ignorando ou respeitando a sensibilidade a maiúsculas/minúsculas. </p> <hr> <pre> O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> Procura e retorna a fonte com o nome de fonte e estilo de fonte especificados. </p> <hr> <pre> O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> Procura e retorna a fonte com o nome de fonte e estilo de fonte especificados, ignorando ou respeitando a sensibilidade a maiúsculas/minúsculas. </p> <hr> <pre> O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | Cópia da lista com os diretórios de fontes atuais. |
| [getSources](#getSources--) | Obtém a coleção de fontes de origem. |
| [getSubstitutions](#getSubstitutions--) | Obtém a coleção de estratégias de substituição de fontes. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | Fontes não encontradas serão substituídas pela fonte padrão. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Retorna o status da configuração de armazenamento de Font Sources. <br> Se verdadeiro, usa ThreadStatic e cada thread tem suas próprias Font Sources. <br> Se falso, usa configuração estática global para todas as threads. </p> <hr> Valor padrão é True. |
| [loadFonts](#loadFonts--) | Carrega fontes instaladas no sistema e fontes PDF padrão. Este método foi projetado para acelerar o processo de carregamento de fontes. Por padrão, as fontes são carregadas na primeira solicitação de qualquer fonte. O uso deste método carrega as fontes do sistema e as fontes PDF padrão imediatamente antes de abrir qualquer documento PDF. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> Abre fonte com o fluxo de fonte especificado. </p> <hr> <pre> O exemplo demonstra como abrir a fonte e substituir a fonte do texto da primeira página. // Abrir fonte InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salvar documento doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> Abre fonte com o caminho de arquivo de fonte especificado. </p> <hr> <pre> O exemplo demonstra como abrir a fonte e substituir a fonte do texto da primeira página. // Abrir fonte Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salvar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> Abre fonte com o caminho de arquivo de fonte especificado e caminho de arquivo de métricas. </p> <hr> <pre> O exemplo demonstra como abrir a fonte Type1 com métricas e substituir a fonte do texto da primeira página. // Abrir fonte Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Salvar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | Recarrega todas as fontes especificadas pela propriedade {@code Sources}({@link #getSources}) |
| [restoreLocalFontPath](#restoreLocalFontPath--) | Restaura a lista dos diretórios padrão de fontes por padrão. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | Define a lista do usuário com caminhos de fontes |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | Defina TRUE se precisar substituir fontes não encontradas pela fonte padrão. O valor padrão é false. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Opção para definir a configuração de armazenamento de Font Sources. Se true, usa ThreadStatic e cada thread tem seus próprios Font Sources. Se false, usa configuração estática global para todas as threads. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
Adicione mais um caminho para fontes.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> Adicionar fonte do sistema com a fonte especificada. </p> <hr> <pre> O exemplo demonstra como adicionar fonte do sistema. InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> Procura e retorna a fonte com o nome de fonte especificado. </p> <hr> <pre> O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página. // Encontrar fonte Font font = FontRepository.findFont("Arial"); // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salvar documento doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> Pesquisa e retorna a fonte com o nome de fonte especificado, ignorando ou respeitando a diferenciação entre maiúsculas e minúsculas. </p> <hr> <pre> O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página. // Encontrar fonte Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Abrir documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Salvar documento doc.save(\"D:\\Tests\\output.pdf\"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> Pesquisa e retorna a fonte com o nome de fonte e estilo de fonte especificados. </p> <hr> <pre> O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página. // Encontrar fonte Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Abrir documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Salvar documento doc.save(\"D:\\Tests\\output.pdf\"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> Pesquisa e retorna a fonte com o nome de fonte e estilo de fonte especificados, ignorando ou respeitando a diferenciação entre maiúsculas e minúsculas. </p> <hr> <pre> O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página. // Encontrar fonte Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic, true); // Abrir documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Salvar documento doc.save(\"D:\\Tests\\output.pdf\"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

Cópia da lista com os diretórios de fontes atuais.

**Returns:**
lista de String

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

Obtém a coleção de fontes de origem.

**Returns:**
objeto FontSourceCollection

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

Obtém a coleção de estratégias de substituição de fontes.

**Returns:**
objeto FontSubstitutionCollection

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

Fontes não encontradas serão substituídas pela fonte padrão.

**Returns:**
valor booleano

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Retorna o status da configuração de armazenamento de Font Sources. <br> Se verdadeiro, usa ThreadStatic e cada thread tem suas próprias Font Sources. <br> Se falso, usa configuração estática global para todas as threads. </p> <hr> Valor padrão é True.

**Returns:**
valor booleano

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

Carrega fontes instaladas no sistema e fontes PDF padrão. Este método foi projetado para acelerar o processo de carregamento de fontes. Por padrão, as fontes são carregadas na primeira solicitação de qualquer fonte. O uso deste método carrega as fontes do sistema e as fontes PDF padrão imediatamente antes de abrir qualquer documento PDF.

### openFont {#openFont-java.io.InputStream-int-}
<p> Abre a fonte com o fluxo de fonte especificado. </p> <hr> <pre> O exemplo demonstra como abrir a fonte e substituir a fonte do texto da primeira página. // Abrir fonte InputStream fontStream = new FileInputStream(\"C:\\WINDOWS\\Fonts\\arial.ttf\")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Abrir documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salvar documento doc.save(\"D:\\Tests\\output.pdf\"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> Abre a fonte com o caminho de arquivo de fonte especificado. </p> <hr> <pre> O exemplo demonstra como abrir a fonte e substituir a fonte do texto da primeira página. // Abrir fonte Font font = FontRepository.openFont(\"C:\\WINDOWS\\Fonts\\arial.ttf\"); // Abrir documento Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salvar documento doc.save(\"D:\\Tests\\output.pdf\"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> Abre a fonte com o caminho especificado do arquivo de fonte e do arquivo de métricas. </p> <hr> <pre> O exemplo demonstra como abrir uma fonte Type1 com métricas e substituir a fonte do texto da primeira página. // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

Recarrega todas as fontes especificadas pela propriedade {@code Sources}({@link #getSources})

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

Restaura a lista dos diretórios padrão de fontes por padrão.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
Define a lista do usuário com caminhos de fontes

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

Defina TRUE se precisar substituir fontes não encontradas pela fonte padrão. O valor padrão é false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Opção para definir a configuração de armazenamento de Font Sources. Se true, usa ThreadStatic e cada thread tem seus próprios Font Sources. Se false, usa configuração estática global para todas as threads.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isTheadLocal |  | valor booleano |
