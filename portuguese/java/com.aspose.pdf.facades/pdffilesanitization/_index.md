---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a API de sanitização e recuperação. Use-a se não for possível criar/abrir documentos de outra forma."
type: docs
weight: 510
url: /pt/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

Representa a API de sanitização e recuperação. Use-a se não for possível criar/abrir documentos de outra forma.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | Inicializa uma nova instância. |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Vincula um fluxo Pdf para Sanitizar. |
| [bindPdf](#bindPdf-java.lang.String-) | Vincula um arquivo Pdf para sanitização. |
| [close](#close--) | Fecha a fachada. |
| [getLog](#getLog--) | Depois que o arquivo foi salvo, você pode verificar o que foi feito com o arquivo. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | Permite gerar um novo xref e trailer para o documento. |
| [getUseTrimBottom](#getUseTrimBottom--) | Permite remover dados após os dados pdf |
| [getUseTrimTop](#getUseTrimTop--) | Permite remover dados antes dos dados pdf. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | Remove o xref antigo com trailer e cria um novo xref com trailer. |
| [recover](#recover--) | Recupera o documento. Use propriedades para personalizar. |
| [save](#save-java.io.OutputStream-) | Salva o PDF resultante em um stream. |
| [save](#save-java.lang.String-) | Salva o PDF resultante em um arquivo. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | Permite gerar um novo xref e trailer para o documento. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | Permite remover dados após os dados pdf |
| [setUseTrimTop](#setUseTrimTop-boolean-) | Permite remover dados antes dos dados pdf. |
| [trimBottom](#trimBottom--) | Remove dados após o último %%EOF. |
| [trimTop](#trimTop--) | Remove dados antes de %PDF. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

Inicializa uma nova instância.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.io.InputStream-}
Vincula um fluxo Pdf para Sanitizar.

### bindPdf {#bindPdf-java.lang.String-}
Vincula um arquivo Pdf para sanitização.

### close {#close--}
```
public void close()
```

Fecha a fachada.

### getLog {#getLog--}
```
public final List < String > getLog()
```

Depois que o arquivo foi salvo, você pode verificar o que foi feito com o arquivo.

**Returns:**
lista de elementos String

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

Permite gerar um novo xref e trailer para o documento.

**Returns:**
valor booleano

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

Permite remover dados após os dados pdf

**Returns:**
valor booleano

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

Permite remover dados antes dos dados pdf.

**Returns:**
valor booleano

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

Remove o xref antigo com trailer e cria um novo xref com trailer.

### recover {#recover--}
```
public final void recover()
```

Recupera o documento. Use propriedades para personalizar.

### save {#save-java.io.OutputStream-}
Salva o PDF resultante em um stream.

### save {#save-java.lang.String-}
Salva o PDF resultante em um arquivo.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

Permite gerar um novo xref e trailer para o documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

Permite remover dados após os dados pdf

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

Permite remover dados antes dos dados pdf.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

Remove dados após o último %%EOF.

### trimTop {#trimTop--}
```
public final void trimTop()
```

Remove dados antes de %PDF.
