---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para acessar metainformações de documento PDF."
type: docs
weight: 490
url: /pt/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

Representa uma classe para acessar metainformações de documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão. |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inicializa a fachada. |
| [clearInfo](#clearInfo--) | Limpa todas as metainformações do documento PDF. |
| [close](#close--) | Fecha todos os recursos usados por este documento. |
| [dispose](#dispose--) | Fecha todos os recursos usados por esta instância. Este método está obsoleto, use close() em vez disso. |
| [getAuthor](#getAuthor--) | Obtém a informação do Autor do documento PDF. |
| [getCreationDate](#getCreationDate--) | Obtém a informação da CreationDate do documento PDF. |
| [getCreator](#getCreator--) | Obtém a informação do Creator do documento PDF. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | Obtém as configurações de privilégios do documento PDF. |
| [getHeader](#getHeader--) | <p> Obtém as informações personalizadas do documento PDF. </p> |
| [getInputFile](#getInputFile--) | Obtém o arquivo de entrada. |
| [getInputStream](#getInputStream--) | Obtém o fluxo de entrada. |
| [getKeywords](#getKeywords--) | Obtém as informações de Palavras‑chave do documento PDF. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | Obtém informações personalizadas do documento PDF com o nome da propriedade. Se não houver nenhuma propriedade que corresponda ao nome, retornará uma string vazia. |
| [getModDate](#getModDate--) | Obtém as informações de data ModDate do documento PDF. |
| [getNumberOfPages](#getNumberOfPages--) | Obtém o número de páginas do documento. |
| [getPageHeight](#getPageHeight-int-) | Obtém a altura da página especificada. |
| [getPageRotation](#getPageRotation-int-) | Obtém a rotação da página especificada. |
| [getPageWidth](#getPageWidth-int-) | Obtém a largura da página especificada. |
| [getPageXOffset](#getPageXOffset-int-) | Obtém o deslocamento horizontal da área de exibição da página especificada. |
| [getPageYOffset](#getPageYOffset-int-) | Obtém o deslocamento vertical da área de exibição da página especificada. |
| [getPasswordType](#getPasswordType--) | Retorna o tipo de senha que foi passado ao criar a instância PdfFileInfo. Veja os valores possíveis em {@code PasswordType}. Observe que o documento PDF pode ser aberto usando tanto a senha de usuário (ou abrir) quanto a senha de proprietário (ou permissões, edição). |
| [getPdfVersion](#getPdfVersion--) | Obtém as informações de versão do documento PDF. |
| [getProducer](#getProducer--) | Obtém as informações do Produtor do documento PDF. |
| [getSubject](#getSubject--) | Obtém as informações do Assunto do documento PDF. |
| [getTitle](#getTitle--) | Obtém as informações do Título do documento PDF. |
| [getUseStrictValidation](#getUseStrictValidation--) | Utiliza regras de validação estrita via a propriedade {@code IsPdfFile}({@link #isPdfFile}). |
| [hasCollection](#hasCollection--) | Retorna true se o arquivo de entrada atual for um arquivo 'Portfolio' que contém uma coleção de arquivos PDF. |
| [hasEditPassword](#hasEditPassword--) | Retorna true se for necessária uma senha para modificar permissões ou a propriedade de segurança do documento. Observe que esta propriedade só pode ser lida se uma senha válida for fornecida no construtor {@code PdfFileInfo}. Caso o PasswordType seja Inaccessible (significa que uma senha inválida foi fornecida), a leitura desta propriedade falhará com {@code InvalidPasswordException}. |
| [hasOpenPassword](#hasOpenPassword--) | Retorna true se for necessária uma senha para abrir o documento PDF protegido por senha. |
| [isEncrypted](#isEncrypted--) | Verifica se o documento PDF está criptografado. |
| [isPdfFile](#isPdfFile--) | Verifica se a entrada de origem é um arquivo PDF válido. |
| [save](#save-java.io.OutputStream-) | Salva o documento PDF no arquivo especificado. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | Salve o documento PDF atualizado no fluxo especificado. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | Salve o documento PDF atualizado no arquivo especificado. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | Altera as propriedades especificadas explicitamente definindo as informações do arquivo, as demais propriedades permanecem. |
| [setAuthor](#setAuthor-java.lang.String-) | Define as informações de Autor do documento PDF. |
| [setCreationDate](#setCreationDate-java.lang.String-) | Define as informações de CreationDate do documento PDF. |
| [setCreator](#setCreator-java.lang.String-) | Define as informações de Creator do documento PDF. |
| [setHeader](#setHeader-java.util.Map-) | Define as informações personalizadas do documento PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Define o arquivo de entrada. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Define o fluxo de entrada. |
| [setKeywords](#setKeywords-java.lang.String-) | Define as informações de Keywords do documento PDF. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | Define informações personalizadas do documento PDF. |
| [setModDate](#setModDate-java.lang.String-) | Define as informações de data ModDate do documento PDF. |
| [setSubject](#setSubject-java.lang.String-) | Define as informações de Subject do documento PDF. |
| [setTitle](#setTitle-java.lang.String-) | Define as informações de Title do documento PDF. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | Utiliza regras de validação estrita via a propriedade {@code IsPdfFile}({@link #isPdfFile}). |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa uma nova instância da classe com.aspose.pdf.facades.PdfFileInfo com valores padrão.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inicializa a fachada.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

Limpa todas as metainformações do documento PDF.

### close {#close--}
```
public void close()
```

Fecha todos os recursos usados por este documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Fecha todos os recursos usados por esta instância. Este método está obsoleto, use close() em vez disso.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Obtém a informação do Autor do documento PDF.

**Returns:**
valor String

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

Obtém a informação da CreationDate do documento PDF.

**Returns:**
valor String

### getCreator {#getCreator--}
```
public String getCreator()
```

Obtém a informação do Creator do documento PDF.

**Returns:**
valor String

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

Obtém as configurações de privilégios do documento PDF.

**Returns:**
As configurações de privilégios do documento PDF.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> Obtém as informações personalizadas do documento PDF. </p>

**Returns:**
{@code Map<String, String>} objeto

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Obtém o arquivo de entrada.

**Returns:**
valor String

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Obtém o fluxo de entrada.

**Returns:**
objeto InputStream

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Obtém as informações de Palavras‑chave do documento PDF.

**Returns:**
valor String

### getMetaInfo {#getMetaInfo-java.lang.String-}
Obtém informações personalizadas do documento PDF com o nome da propriedade. Se não houver nenhuma propriedade que corresponda ao nome, retornará uma string vazia.

### getModDate {#getModDate--}
```
public String getModDate()
```

Obtém as informações de data ModDate do documento PDF.

**Returns:**
valor String

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

Obtém o número de páginas do documento.

**Returns:**
valor int

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

Obtém a altura da página especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNum |  | Número da página. |

**Returns:**
A altura da página.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

Obtém a rotação da página especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNum |  | Número da página. |

**Returns:**
A rotação da página. O valor pode ser 0,90,180,270.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

Obtém a largura da página especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNum |  | Número da página. |

**Returns:**
A largura da página.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

Obtém o deslocamento horizontal da área de exibição da página especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNum |  | Número da página. |

**Returns:**
O deslocamento horizontal a partir do lado esquerdo da página.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

Obtém o deslocamento vertical da área de exibição da página especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNum |  | Número da página. |

**Returns:**
O deslocamento vertical da área de exibição da página.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

Retorna o tipo de senha que foi passado ao criar a instância PdfFileInfo. Veja os valores possíveis em {@code PasswordType}. Observe que o documento PDF pode ser aberto usando tanto a senha de usuário (ou abrir) quanto a senha de proprietário (ou permissões, edição).

**Returns:**
PasswordType elemento @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

Obtém as informações de versão do documento PDF.

**Returns:**
A string de versão.

### getProducer {#getProducer--}
```
public String getProducer()
```

Obtém as informações do Produtor do documento PDF.

**Returns:**
valor String

### getSubject {#getSubject--}
```
public String getSubject()
```

Obtém as informações do Assunto do documento PDF.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtém as informações do Título do documento PDF.

**Returns:**
valor String

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

Utiliza regras de validação estrita via a propriedade {@code IsPdfFile}({@link #isPdfFile}).

**Returns:**
valor booleano

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

Retorna true se o arquivo de entrada atual for um arquivo 'Portfolio' que contém uma coleção de arquivos PDF.

**Returns:**
valor booleano

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

Retorna true se for necessária uma senha para modificar permissões ou a propriedade de segurança do documento. Observe que esta propriedade só pode ser lida se uma senha válida for fornecida no construtor {@code PdfFileInfo}. Caso o PasswordType seja Inaccessible (significa que uma senha inválida foi fornecida), a leitura desta propriedade falhará com {@code InvalidPasswordException}.

**Returns:**
valor booleano

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

Retorna true se for necessária uma senha para abrir o documento PDF protegido por senha.

**Returns:**
valor booleano

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Verifica se o documento PDF está criptografado.

**Returns:**
valor booleano

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

Verifica se a entrada de origem é um arquivo PDF válido.

**Returns:**
valor booleano

### save {#save-java.io.OutputStream-}
Salva o documento PDF no arquivo especificado.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
Salve o documento PDF atualizado no fluxo especificado.

### saveNewInfo {#saveNewInfo-java.lang.String-}
Salve o documento PDF atualizado no arquivo especificado.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
Altera as propriedades especificadas explicitamente definindo as informações do arquivo, as demais propriedades permanecem.

### setAuthor {#setAuthor-java.lang.String-}
Define as informações de Autor do documento PDF.

### setCreationDate {#setCreationDate-java.lang.String-}
Define as informações de CreationDate do documento PDF.

### setCreator {#setCreator-java.lang.String-}
Define as informações de Creator do documento PDF.

### setHeader {#setHeader-java.util.Map-}
Define as informações personalizadas do documento PDF.

### setInputFile {#setInputFile-java.lang.String-}
Define o arquivo de entrada.

### setInputStream {#setInputStream-java.io.InputStream-}
Define o fluxo de entrada.

### setKeywords {#setKeywords-java.lang.String-}
Define as informações de Keywords do documento PDF.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
Define informações personalizadas do documento PDF.

### setModDate {#setModDate-java.lang.String-}
Define as informações de data ModDate do documento PDF.

### setSubject {#setSubject-java.lang.String-}
Define as informações de Subject do documento PDF.

### setTitle {#setTitle-java.lang.String-}
Define as informações de Title do documento PDF.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

Utiliza regras de validação estrita via a propriedade {@code IsPdfFile}({@link #isPdfFile}).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
