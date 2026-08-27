---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Opções de salvamento para exportação para o formato Pdf."
type: docs
weight: 3790
url: /pt/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

Opções de salvamento para exportação para o formato Pdf.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | Nome da fonte usado por padrão para fontes que estão ausentes no computador. Quando o documento PDF que é salvo em PDF contém fontes que não estão disponíveis no próprio documento e no dispositivo, a API substitui essas fontes pela fonte padrão (se a fonte com {@code DefaultFontName} for encontrada no dispositivo) |
| [getTempPath](#getTempPath--) | Caminho para arquivos temporários. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Nome da fonte usado por padrão para fontes que estão ausentes no computador. Quando o documento PDF que é salvo em PDF contém fontes que não estão disponíveis no próprio documento e no dispositivo, a API substitui essas fontes pela fonte padrão (se a fonte com {@code DefaultFontName} for encontrada no dispositivo) |
| [setTempPath](#setTempPath-java.lang.String-) | Caminho para arquivos temporários. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

Construtor

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Nome da fonte usado por padrão para fontes que estão ausentes no computador. Quando o documento PDF que é salvo em PDF contém fontes que não estão disponíveis no próprio documento e no dispositivo, a API substitui essas fontes pela fonte padrão (se a fonte com {@code DefaultFontName} for encontrada no dispositivo)

**Returns:**
valor String

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

Caminho para arquivos temporários.

**Returns:**
valor String

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Nome da fonte usado por padrão para fontes que estão ausentes no computador. Quando o documento PDF que é salvo em PDF contém fontes que não estão disponíveis no próprio documento e no dispositivo, a API substitui essas fontes pela fonte padrão (se a fonte com {@code DefaultFontName} for encontrada no dispositivo)

### setTempPath {#setTempPath-java.lang.String-}
Caminho para arquivos temporários.
