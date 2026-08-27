---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Referência da API Aspose.PDF para Java"
description: "Formato numérico para medida."
type: docs
weight: 2940
url: /pt/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Formato numérico para medida.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | Construtor da classe NumberFormat. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAfterText](#getAfterText--) | Texto que deve ser concatenado após o rótulo |
| [getBeforeText](#getBeforeText--) | Texto que deve ser concatenado à esquerda do rótulo. |
| [getConvresionFactor](#getConvresionFactor--) | O fator de conversão usado para multiplicar um valor em unidades parciais do elemento anterior da matriz de formatos numéricos para obter um valor nas unidades deste formato numérico. |
| [getDenominator](#getDenominator--) | Se FractionDisplayment for ShowAsFraction, este valor é o denominador da fração. O valor padrão é 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | De que forma os valores fracionários são exibidos. |
| [getFractionSeparator](#getFractionSeparator--) | Texto que deve ser usado como posição decimal ao exibir valores numéricos. Uma string vazia indica que o padrão deve ser usado. O padrão é o caractere ponto. |
| [getPrecision](#getPrecision--) | Se FractionDisplayment for ShowAsDecimal, este valor é a precisão do valor fracionário; deve ser múltiplo de 10. O padrão é 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | Texto que deve ser usado entre ordens de milhar na exibição de valores numéricos. Uma string vazia indica que nenhum texto será adicionado. O padrão é a vírgula. |
| [getUnitLabel](#getUnitLabel--) | Uma string de texto que especifica um rótulo para exibir as unidades. |
| [isForceDenominator](#isForceDenominator--) | Se FractionDisplayment for ShowAsFraction, este valor determina se a fração deve ser reduzida ou não. Se o valor for true, a fração pode não ser reduzida. |
| [setAfterText](#setAfterText-java.lang.String-) | Texto que deve ser concatenado após o rótulo |
| [setBeforeText](#setBeforeText-java.lang.String-) | Texto que deve ser concatenado à esquerda do rótulo. |
| [setConvresionFactor](#setConvresionFactor-double-) | O fator de conversão usado para multiplicar um valor em unidades parciais do elemento anterior da matriz de formatos numéricos para obter um valor nas unidades deste formato numérico. |
| [setDenominator](#setDenominator-int-) | Se FractionDisplayment for ShowAsFraction, este valor é o denominador da fração. O valor padrão é 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | Se FractionDisplayment for ShowAsFraction, este valor determina se a fração deve ser reduzida ou não. Se o valor for true, a fração pode não ser reduzida. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | De que forma os valores fracionários são exibidos. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Texto que deve ser usado como posição decimal ao exibir valores numéricos. Uma string vazia indica que o padrão deve ser usado. O padrão é o caractere ponto. |
| [setPrecision](#setPrecision-int-) | Se FractionDisplayment for ShowAsDecimal, este valor é a precisão do valor fracionário; deve ser múltiplo de 10. O padrão é 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Texto que deve ser usado entre ordens de milhar na exibição de valores numéricos. Uma string vazia indica que nenhum texto será adicionado. O padrão é a vírgula. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
Construtor da classe NumberFormat.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Texto que deve ser concatenado após o rótulo

**Returns:**
Objeto String

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Texto que deve ser concatenado à esquerda do rótulo.

**Returns:**
Objeto String

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

O fator de conversão usado para multiplicar um valor em unidades parciais do elemento anterior da matriz de formatos numéricos para obter um valor nas unidades deste formato numérico.

**Returns:**
valor double

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

Se FractionDisplayment for ShowAsFraction, este valor é o denominador da fração. O valor padrão é 16.

**Returns:**
valor int

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

De que forma os valores fracionários são exibidos.

**Returns:**
Valor FractionStyle @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Texto que deve ser usado como posição decimal ao exibir valores numéricos. Uma string vazia indica que o padrão deve ser usado. O padrão é o caractere ponto.

**Returns:**
valor String

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

Se FractionDisplayment for ShowAsDecimal, este valor é a precisão do valor fracionário; deve ser múltiplo de 10. O padrão é 100.

**Returns:**
valor int

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Texto que deve ser usado entre ordens de milhar na exibição de valores numéricos. Uma string vazia indica que nenhum texto será adicionado. O padrão é a vírgula.

**Returns:**
valor String

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

Uma string de texto que especifica um rótulo para exibir as unidades.

**Returns:**
Objeto String

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

Se FractionDisplayment for ShowAsFraction, este valor determina se a fração deve ser reduzida ou não. Se o valor for true, a fração pode não ser reduzida.

**Returns:**
valor booleano

### setAfterText {#setAfterText-java.lang.String-}
Texto que deve ser concatenado após o rótulo

### setBeforeText {#setBeforeText-java.lang.String-}
Texto que deve ser concatenado à esquerda do rótulo.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

O fator de conversão usado para multiplicar um valor em unidades parciais do elemento anterior da matriz de formatos numéricos para obter um valor nas unidades deste formato numérico.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

Se FractionDisplayment for ShowAsFraction, este valor é o denominador da fração. O valor padrão é 16.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

Se FractionDisplayment for ShowAsFraction, este valor determina se a fração deve ser reduzida ou não. Se o valor for true, a fração pode não ser reduzida.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
De que forma os valores fracionários são exibidos.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Texto que deve ser usado como posição decimal ao exibir valores numéricos. Uma string vazia indica que o padrão deve ser usado. O padrão é o caractere ponto.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

Se FractionDisplayment for ShowAsDecimal, este valor é a precisão do valor fracionário; deve ser múltiplo de 10. O padrão é 100.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Texto que deve ser usado entre ordens de milhar na exibição de valores numéricos. Uma string vazia indica que nenhum texto será adicionado. O padrão é a vírgula.

### setUnitLabel {#setUnitLabel-java.lang.String-}
