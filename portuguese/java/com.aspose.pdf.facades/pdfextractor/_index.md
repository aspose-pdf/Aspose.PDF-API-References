---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe para extrair imagens e texto de documentos PDF."
type: docs
weight: 400
url: /pt/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

Classe para extrair imagens e texto de documentos PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Vincula um documento Pdf para edição. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Vincula um documento Pdf para edição. / * / * / * |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> Vincula o documento PDF a partir de um fluxo. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> Vincula o arquivo PDF de entrada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre> |
| [extractAttachment](#extractAttachment--) | Extrai anexos de um documento Pdf. |
| [extractAttachment](#extractAttachment-java.lang.String-) | Extrai anexos de um documento Pdf. |
| [extractImage](#extractImage--) | <p> Extrai imagens de um arquivo PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> Obtém todos os contêineres de Conteúdo Marcado como imagens separadas. </p> <p> Cada Conteúdo Marcado será salvo como imagem no formato png nomeada com {@code MCID_<ID number of block for the page>.png}</p> |
| [extractText](#extractText--) | <p> Extrai texto de um documento Pdf. </p> <hr> <pre> O primeiro exemplo demonstra como extrair todo o texto de um arquivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> O segundo exemplo demonstra como extrair o texto de cada página em um único arquivo txt. </p> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Extrai texto de um documento Pdf. </p> <hr> <pre> O primeiro exemplo demonstra como extrair todo o texto de um arquivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> O segundo exemplo demonstra como extrair o texto de cada página em um único arquivo txt. </p> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | Somente para uso interno |
| [getAttachment](#getAttachment--) | <p> Salva todos os arquivos de anexo em streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> Salva todos os arquivos de anexo em streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | Obtém a lista de anexos. |
| [getAttachNames](#getAttachNames--) | <p> Retorna a lista de anexos no arquivo PDF. Observação: ExtractAttachments deve ser chamado antes de usar este método. </p> <hr> <pre> O exemplo demonstra como extrair os nomes dos anexos de um arquivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> Obtém a página final no intervalo de páginas onde a operação de extração será realizada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> Define o modo para o processo de extração de imagens. </p> <hr> O valor padrão é ExtractImageMode.DefinedInResources, que extrai todas as imagens definidas nos recursos. Para extrair as imagens realmente exibidas, deve ser usado o modo ExtractImageMode.ActuallyUsed. |
| [getExtractTextMode](#getExtractTextMode--) | <p> Obtém o modo para o resultado da extração de texto. </p> <hr> <pre> O exemplo demonstra o uso da propriedade {@code ExtractTextMode} no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> Valor: 0 é modo de texto puro e 1 é modo de ordenação bruta. O padrão é 0.</p> |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Recupera a próxima imagem do arquivo PDF e a armazena em um fluxo. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Recupera a próxima imagem do arquivo PDF e a armazena em um fluxo com o formato de imagem especificado. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> Recupera a próxima imagem do documento PDF. Nota: ExtractImage deve ser chamado antes do uso deste método. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Recupera a próxima imagem do documento PDF com o formato de imagem especificado. Nota: ExtractImage deve ser chamado antes do uso deste método. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> Salva o texto de uma página em um fluxo. </p> <hr> <pre> O exemplo demonstra o uso do método {@code GetNextPageText} no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> Salva o texto de uma página em um arquivo. </p> <hr> <pre> O exemplo demonstra o uso do método GetNextPageText no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | Obtém a senha do arquivo de entrada. |
| [getResolution](#getResolution--) | Obtém a resolução das imagens extraídas. O valor padrão é 150. Imagens que têm um valor de resolução maior são mais nítidas. Contudo, aumentar o valor da resolução resulta em maior tempo e memória necessários para extrair as imagens. Normalmente, para obter uma imagem nítida, basta definir a resolução para 150 ou 300. |
| [getStartPage](#getStartPage--) | Objeto Pdf.Engine que representa o documento PDF. |
| [getText](#getText-java.io.OutputStream-) | Salva o texto em um fluxo. veja também:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | Salva o texto em um fluxo. veja também:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | Salva o texto em um arquivo. veja também:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | Obtém opções de pesquisa de texto. |
| [hasNextImage](#hasNextImage--) | <p> Verifica se há mais imagens acessíveis no documento PDF. Nota: ExtractImage deve ser chamado antes do uso deste método. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> Indica se é possível obter mais textos ou não. </p> <hr> <pre> O exemplo demonstra o uso da propriedade {@code HasNextPageText} no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | É verdadeiro quando o texto contém símbolos hebraicos ou árabes. Esse caso deve ser considerado especialmente porque as funções de string alteram seu comportamento e iniciam o processamento do texto da direita para a esquerda (exceto números e outros caracteres não textuais). |
| [setEndPage](#setEndPage-int-) | <p> Define a página final no intervalo de páginas onde a operação de extração será realizada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> Define o modo para o processo de extração de imagens. </p> <hr> O valor padrão é ExtractImageMode.DefinedInResources, que extrai todas as imagens definidas nos recursos. Para extrair as imagens realmente exibidas, deve ser usado o modo ExtractImageMode.ActuallyUsed. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> Define o modo para o resultado da extração de texto. </p> <hr> <pre> O exemplo demonstra o uso da propriedade {@code ExtractTextMode} no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> Valor: 0 é modo de texto puro e 1 é modo de ordenação bruta. O padrão é 0. |
| [setPassword](#setPassword-java.lang.String-) | Define a senha do arquivo de entrada. |
| [setResolution](#setResolution-int-) | Defina a resolução para imagens extraídas. O valor padrão é 150. Imagens que têm um valor de resolução maior são mais nítidas. No entanto, aumentar o valor da resolução resulta em maior tempo e memória necessários para extrair imagens. Normalmente, para obter uma imagem nítida, basta definir a resolução para 150 ou 300. |
| [setStartPage](#setStartPage-int-) | <p> Define a página inicial no intervalo de páginas onde a operação de extração será realizada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Define opções de pesquisa de texto. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Vincula um documento Pdf para edição. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Vincula um documento Pdf para edição. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> Vincula o documento PDF a partir de um fluxo. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> Vincula o arquivo PDF de entrada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Extrai anexos de um documento Pdf.

### extractAttachment {#extractAttachment-java.lang.String-}
Extrai anexos de um documento Pdf.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> Extrai imagens de um arquivo PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> Obtém todos os contêineres de Conteúdo Marcado como imagens separadas. </p> <p> Cada Conteúdo Marcado será salvo como imagem no formato png nomeada com {@code MCID_<ID number of block for the page>.png}</p>

### extractText {#extractText--}
```
public void extractText()
```

<p> Extrai texto de um documento PDF. </p> <hr> <pre> O primeiro exemplo demonstra como extrair todo o texto de um arquivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> O segundo exemplo demonstra como extrair o texto de cada página em um único arquivo txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> Extrai texto de um documento PDF. </p> <hr> <pre> O primeiro exemplo demonstra como extrair todo o texto de um arquivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> O segundo exemplo demonstra como extrair o texto de cada página em um único arquivo txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
Somente para uso interno

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> Salva todos os arquivos de anexo em streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
O array de fluxo do arquivo de anexo no documento PDF.

### getAttachment {#getAttachment-java.lang.String-}
<p> Salva todos os arquivos de anexo em streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
O array de fluxo do arquivo de anexo no documento PDF.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

Obtém a lista de anexos.

**Returns:**
Retorna uma List<FileSpecificatio>.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> Retorna a lista de anexos no arquivo PDF. Observação: ExtractAttachments deve ser chamado antes de usar este método. </p> <hr> <pre> O exemplo demonstra como extrair os nomes dos anexos de um arquivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
Lista de anexos

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> Obtém a página final no intervalo de páginas onde a operação de extração será realizada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
página final.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> Define o modo para o processo de extração de imagens. </p> <hr> O valor padrão é ExtractImageMode.DefinedInResources, que extrai todas as imagens definidas nos recursos. Para extrair as imagens realmente exibidas, deve ser usado o modo ExtractImageMode.ActuallyUsed.

**Returns:**
Valor ExtractImageMode @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> Obtém o modo para o resultado da extração de texto. </p> <hr> <pre> O exemplo demonstra o uso da propriedade {@code ExtractTextMode} no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> Valor: 0 é modo de texto puro e 1 é modo de ordenação bruta. O padrão é 0.

**Returns:**
resultado da extração de texto.

### getNextImage {#getNextImage-java.io.OutputStream-}
Recupera a próxima imagem do arquivo PDF e a armazena em um fluxo.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Recupera a próxima imagem do arquivo PDF e a armazena em um fluxo com o formato de imagem especificado.

### getNextImage {#getNextImage-java.lang.String-}
<p> Recupera a próxima imagem do documento PDF. Nota: ExtractImage deve ser chamado antes do uso deste método. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
Recupera a próxima imagem do documento PDF com o formato de imagem especificado. Nota: ExtractImage deve ser chamado antes do uso deste método.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> Salva o texto de uma página em um fluxo. </p> <hr> <pre> O exemplo demonstra o uso do método {@code GetNextPageText} no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> Salva o texto de uma página em um arquivo. </p> <hr> <pre> O exemplo demonstra o uso do método GetNextPageText no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

Obtém a senha do arquivo de entrada.

**Returns:**
valor String

### getResolution {#getResolution--}
```
public int getResolution()
```

Obtém a resolução das imagens extraídas. O valor padrão é 150. Imagens que têm um valor de resolução maior são mais nítidas. Contudo, aumentar o valor da resolução resulta em maior tempo e memória necessários para extrair as imagens. Normalmente, para obter uma imagem nítida, basta definir a resolução para 150 ou 300.

**Returns:**
valor int

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Objeto Pdf.Engine que representa o documento PDF.

**Returns:**
página inicial no intervalo de páginas.

### getText {#getText-java.io.OutputStream-}
Salva o texto em um fluxo. veja também:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
Salva o texto em um fluxo. veja também:{@code ExtractText}

### getText {#getText-java.lang.String-}
Salva o texto em um arquivo. veja também:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Obtém opções de pesquisa de texto.

**Returns:**
opções de pesquisa de texto.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> Verifica se há mais imagens acessíveis no documento PDF. Nota: ExtractImage deve ser chamado antes do uso deste método. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

**Returns:**
Verdadeiro se mais imagens estiverem acessíveis.

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> Indica se é possível obter mais textos ou não. </p> <hr> <pre> O exemplo demonstra o uso da propriedade {@code HasNextPageText} no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
Pode obter mais textos ou não, verdadeiro indica que pode, falso indica que não.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

É verdadeiro quando o texto contém símbolos hebraicos ou árabes. Esse caso deve ser considerado especialmente porque as funções de string alteram seu comportamento e iniciam o processamento do texto da direita para a esquerda (exceto números e outros caracteres não textuais).

**Returns:**
valor booleano

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> Define a página final no intervalo de páginas onde a operação de extração será realizada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | página final. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> Define o modo para o processo de extração de imagens. </p> <hr> O valor padrão é ExtractImageMode.DefinedInResources, que extrai todas as imagens definidas nos recursos. Para extrair as imagens realmente exibidas, deve ser usado o modo ExtractImageMode.ActuallyUsed.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> Define o modo para o resultado da extração de texto. </p> <hr> <pre> O exemplo demonstra o uso da propriedade {@code ExtractTextMode} no cenário de extração de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> Valor: 0 é modo de texto puro e 1 é modo de ordenação bruta. O padrão é 0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | resultado da extração de texto. |

### setPassword {#setPassword-java.lang.String-}
Define a senha do arquivo de entrada.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Defina a resolução para imagens extraídas. O valor padrão é 150. Imagens que têm um valor de resolução maior são mais nítidas. No entanto, aumentar o valor da resolução resulta em maior tempo e memória necessários para extrair imagens. Normalmente, para obter uma imagem nítida, basta definir a resolução para 150 ou 300.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> Define a página inicial no intervalo de páginas onde a operação de extração será realizada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | página inicial no intervalo de páginas. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Define opções de pesquisa de texto.
