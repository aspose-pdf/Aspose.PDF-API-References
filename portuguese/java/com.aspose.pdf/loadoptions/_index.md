---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "O tipo LoadOptions contém nível de abstração nas opções de carregamento individuais."
type: docs
weight: 2790
url: /pt/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

O tipo LoadOptions contém nível de abstração nas opções de carregamento individuais.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | Representa o formato de arquivo que {@code LoadOptions} descreve. |
| [getWarningHandler](#getWarningHandler--) | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação Load continua, porém o usuário também pode retornar Abort, caso em que a operação Load deve ser interrompida. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Obtém ou define a flag para desativar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando {@code }, permite executar operações com fontes que são proibidas pela licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desativem a incorporação dessa fonte. Por padrão {@code }. Tenha cuidado ao usar esta flag. Quando ela está definida, significa que a pessoa que a define assume toda a responsabilidade por possíveis violações de licença/lei. Portanto, ele assume o risco por conta própria. Recomenda‑se fortemente usar esta flag somente quando você estiver totalmente confiante de que não está violando a lei de direitos autorais. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Obtém ou define a flag para desativar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando {@code }, permite executar operações com fontes que são proibidas pela licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desativem a incorporação dessa fonte. Por padrão {@code }. Tenha cuidado ao usar esta flag. Quando ela está definida, significa que a pessoa que a define assume toda a responsabilidade por possíveis violações de licença/lei. Portanto, ele assume o risco por conta própria. Recomenda‑se fortemente usar esta flag somente quando você estiver totalmente confiante de que não está violando a lei de direitos autorais. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação Load continua, porém o usuário também pode retornar Abort, caso em que a operação Load deve ser interrompida. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

Representa o formato de arquivo que {@code LoadOptions} descreve.

**Returns:**
Elemento LoadFormat @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação Load continua, porém o usuário também pode retornar Abort, caso em que a operação Load deve ser interrompida.

**Returns:**
Valor IWarningCallback

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Obtém ou define a flag para desativar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando {@code }, permite executar operações com fontes que são proibidas pela licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desativem a incorporação dessa fonte. Por padrão {@code }. Tenha cuidado ao usar esta flag. Quando ela está definida, significa que a pessoa que a define assume toda a responsabilidade por possíveis violações de licença/lei. Portanto, ele assume o risco por conta própria. Recomenda‑se fortemente usar esta flag somente quando você estiver totalmente confiante de que não está violando a lei de direitos autorais.

**Returns:**
valor booleano

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Obtém ou define a flag para desativar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando {@code }, permite executar operações com fontes que são proibidas pela licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desativem a incorporação dessa fonte. Por padrão {@code }. Tenha cuidado ao usar esta flag. Quando ela está definida, significa que a pessoa que a define assume toda a responsabilidade por possíveis violações de licença/lei. Portanto, ele assume o risco por conta própria. Recomenda‑se fortemente usar esta flag somente quando você estiver totalmente confiante de que não está violando a lei de direitos autorais.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação Load continua, porém o usuário também pode retornar Abort, caso em que a operação Load deve ser interrompida.
