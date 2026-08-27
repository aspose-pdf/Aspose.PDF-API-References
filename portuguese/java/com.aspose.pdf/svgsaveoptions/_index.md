---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Opções de salvamento para exportação para o formato SVG."
type: docs
weight: 4720
url: /pt/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

Opções de salvamento para exportação para o formato SVG.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para tratamento personalizado dos arquivos de imagens externas referenciadas criados (como BMP ou JPEG incorporados) incorporados ao SVG salvo. Essa estratégia deve processar os recursos e retornar uma string que representa a URI desejada do recurso salvo no SVG gerado. Se o processamento deste ou daquele arquivo, por algum motivo, precisar ser feito pelo próprio código do conversor, e não por código personalizado, defina no código personalizado a bandeira 'CustomProcessingCancelled' da variável do parâmetro 'imageSavingInfo'. Isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas pelo conversor como se não houvesse nenhum código externo personalizado. |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | Especifica se a saída será criada como um único arquivo zip. Consulte o comentário da opção 'TreatTargetFileNameAsDirectory' para ver as regras de nomenclatura dos arquivos svg das páginas para documento de origem multipáginas, que também são aplicadas ao conjunto zipado de arquivos de saída. |
| [isScaleToPixels](#isScaleToPixels--) | Especifica se deve escalar o documento de saída de pontos tipográficos para pixels. |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | Esta opção define se será criado um diretório de destino (se ainda não existir) com o mesmo nome do arquivo de saída solicitado, em vez do próprio arquivo de saída. Assim, esse diretório conterá todas as imagens SVG de saída das páginas (conforme descrito abaixo). Caso contrário, os arquivos de saída das páginas, exceto a primeira, serão criados exatamente no diretório solicitado como o arquivo de saída principal, mas terão no nome do arquivo o sufixo _[2...n], que é definido pelo número da página, por exemplo, se você definir o arquivo de saída "C:\\AsposeTests\\output.svg" e a saída contiver vários arquivos SVG das páginas, então os arquivos das páginas também serão criados no diretório "C:\\AsposeTests\\" e terão os nomes 'output.svg', 'output_2.svg', 'output_3.svg' etc. |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | Especifica se a saída será criada como um único arquivo zip. Consulte o comentário da opção 'TreatTargetFileNameAsDirectory' para ver as regras de nomenclatura dos arquivos svg das páginas para documento de origem multipáginas, que também são aplicadas ao conjunto zipado de arquivos de saída. |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para o tratamento personalizado dos arquivos de imagens externas referenciadas criados (como BMP ou JPEG incorporados) incorporados ao SVG salvo. |
| [setScaleToPixels](#setScaleToPixels-boolean-) | Especifica se deve escalar o documento de saída de pontos tipográficos para pixels. |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | Esta opção define se será criado um diretório de destino (se ainda não existir) com o mesmo nome do arquivo de saída solicitado, em vez do próprio arquivo de saída. Assim, esse diretório conterá todas as imagens SVG de saída das páginas (conforme descrito abaixo). Caso contrário, os arquivos de saída das páginas, exceto a primeira, serão criados exatamente no diretório solicitado como o arquivo de saída principal, mas terão no nome do arquivo o sufixo _[2...n], que é definido pelo número da página, por exemplo, se você definir o arquivo de saída "C:\\AsposeTests\\output.svg" e a saída contiver vários arquivos SVG das páginas, então os arquivos das páginas também serão criados no diretório "C:\\AsposeTests\\" e terão os nomes 'output.svg', 'output_2.svg', 'output_3.svg' etc. |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

Construtor

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para tratamento personalizado dos arquivos de imagens externas referenciadas criados (como BMP ou JPEG incorporados) incorporados ao SVG salvo. Essa estratégia deve processar os recursos e retornar uma string que representa a URI desejada do recurso salvo no SVG gerado. Se o processamento deste ou daquele arquivo, por algum motivo, precisar ser feito pelo próprio código do conversor, e não por código personalizado, defina no código personalizado a bandeira 'CustomProcessingCancelled' da variável do parâmetro 'imageSavingInfo'. Isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas pelo conversor como se não houvesse nenhum código externo personalizado.

**Returns:**
Instância de EmbeddedImagesSavingStrategy

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

Especifica se a saída será criada como um único arquivo zip. Consulte o comentário da opção 'TreatTargetFileNameAsDirectory' para ver as regras de nomenclatura dos arquivos svg das páginas para documento de origem multipáginas, que também são aplicadas ao conjunto zipado de arquivos de saída.

**Returns:**
valor booleano

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

Especifica se deve escalar o documento de saída de pontos tipográficos para pixels.

**Returns:**
valor booleano

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

Esta opção define se será criado um diretório de destino (se ainda não existir) com o mesmo nome do arquivo de saída solicitado, em vez do próprio arquivo de saída. Assim, esse diretório conterá todas as imagens SVG de saída das páginas (conforme descrito abaixo). Caso contrário, os arquivos de saída das páginas, exceto a primeira, serão criados exatamente no diretório solicitado como o arquivo de saída principal, mas terão no nome do arquivo o sufixo _[2...n], que é definido pelo número da página, por exemplo, se você definir o arquivo de saída "C:\AsposeTests\output.svg" e a saída contiver vários arquivos SVG das páginas, então os arquivos das páginas também serão criados no diretório "C:\AsposeTests\" e terão os nomes 'output.svg', 'output_2.svg', 'output_3.svg' etc.

**Returns:**
valor booleano

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

Especifica se a saída será criada como um único arquivo zip. Consulte o comentário da opção 'TreatTargetFileNameAsDirectory' para ver as regras de nomenclatura dos arquivos svg das páginas para documento de origem multipáginas, que também são aplicadas ao conjunto zipado de arquivos de saída.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| compressOutputToZipArchive |  | valor booleano |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para o tratamento personalizado dos arquivos de imagens externas referenciadas criados (como BMP ou JPEG incorporados) incorporados ao SVG salvo.

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

Especifica se deve escalar o documento de saída de pontos tipográficos para pixels.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scaleToPixels |  | valor booleano |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

Esta opção define se será criado um diretório de destino (se ainda não existir) com o mesmo nome do arquivo de saída solicitado, em vez do próprio arquivo de saída. Assim, esse diretório conterá todas as imagens SVG de saída das páginas (conforme descrito abaixo). Caso contrário, os arquivos de saída das páginas, exceto a primeira, serão criados exatamente no diretório solicitado como o arquivo de saída principal, mas terão no nome do arquivo o sufixo _[2...n], que é definido pelo número da página, por exemplo, se você definir o arquivo de saída "C:\AsposeTests\output.svg" e a saída contiver vários arquivos SVG das páginas, então os arquivos das páginas também serão criados no diretório "C:\AsposeTests\" e terão os nomes 'output.svg', 'output_2.svg', 'output_3.svg' etc.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | valor booleano |
