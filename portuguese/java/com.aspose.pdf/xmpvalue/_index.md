---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa valor XMP"
type: docs
weight: 5750
url: /pt/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

Representa valor XMP

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | Construtor para valor de data e hora. |
| [XmpValue](#XmpValue-double-) | Construtor para valor de ponto flutuante. |
| [XmpValue](#XmpValue-int-) | Construtor para valor inteiro. |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | Construtor para valor de string. |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | Inicializa novo valor XMP de string. |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | Construtor para valor de array. |

## Métodos

| Método | Descrição |
| --- | --- |
| [isArray](#isArray--) | Retorna verdadeiro se XmpValue for um array. |
| [isDateTime](#isDateTime--) | Retorna verdadeiro se o valor for DateTime. |
| [isDouble](#isDouble--) | Retorna verdadeiro se o valor for de ponto flutuante. |
| [isField](#isField--) | Retorna verdadeiro se XmpValue for um campo. |
| [isInteger](#isInteger--) | Retorna verdadeiro se o valor for inteiro. |
| [isNamedValue](#isNamedValue--) | Retorna verdadeiro se XmpValue for um valor nomeado. |
| [isNamedValues](#isNamedValues--) | Retorna verdadeiro se XmpValue representar valores nomeados. |
| [isRaw](#isRaw--) | Valor não suportado/desconhecido e código XML bruto é fornecido. |
| [isString](#isString--) | Retorna verdadeiro se o valor for string. |
| [isStructure](#isStructure--) | Retorna verdadeiro se XmpValue representar estrutura. |
| [to_](#to_-com.aspose.pdf.XmpValue-) | Converte XmpValue em array. |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | Converte XmpValue para array. |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | Obter array de KeyValuePair |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | Converte XmpValue para valor nomeado. |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | Converte XmpValue em string. |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | Converte DateTime em XmpValue. |
| [to_XmpValue](#to_XmpValue-double-) | Converte double em XmpValue. |
| [to_XmpValue](#to_XmpValue-int-) | Converte inteiro em XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | Converte array para XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | Converte string para XmpValue. |
| [toArray](#toArray--) | Retorna array. |
| [toDateTime](#toDateTime--) | Converte para data e hora. |
| [toDateTimeOffset](#toDateTimeOffset--) | Converte o valor XMP atual para uma representação {@link DateTimeOffset}. |
| [toDictionary](#toDictionary--) | Retorna um dicionário que contém valores nomeados. |
| [toDouble](#toDouble--) | Converte para double. |
| [toField](#toField--) | Retorna o valor XMP como campo XMP. |
| [toInteger](#toInteger--) | Converte para integer. |
| [toNamedValue](#toNamedValue--) | Retorna o valor XMP como valor nomeado. |
| [toNamedValueInternal](#toNamedValueInternal--) | Somente para uso interno |
| [toNamedValues](#toNamedValues--) | Retorna o valor XMP como coleção de valores nomeados. |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | Código XML bruto para valores desconhecidos/não suportados. |
| [toString](#toString--) | Retorna a representação em string de XmpValue. |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | Retorna a representação em string de XmpValue. |
| [toStringValue](#toStringValue--) | Converte para string. |
| [toStructure](#toStructure--) | Retorna o valor XMP como estrutura (conjunto de campos). |

### XmpValue {#XmpValue-java.util.Date-}
Construtor para valor de data e hora.

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

Construtor para valor de ponto flutuante.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor double. |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

Construtor para valor inteiro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor integer. |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
Construtor para valor de string.

### XmpValue {#XmpValue-java.lang.String-boolean-}
Inicializa novo valor XMP de string.

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
Construtor para valor de array.

### isArray {#isArray--}
```
public boolean isArray()
```

Retorna verdadeiro se XmpValue for um array.

**Returns:**
valor booleano

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

Retorna verdadeiro se o valor for DateTime.

**Returns:**
valor booleano

### isDouble {#isDouble--}
```
public boolean isDouble()
```

Retorna verdadeiro se o valor for de ponto flutuante.

**Returns:**
valor booleano

### isField {#isField--}
```
public boolean isField()
```

Retorna verdadeiro se XmpValue for um campo.

**Returns:**
valor booleano

### isInteger {#isInteger--}
```
public boolean isInteger()
```

Retorna verdadeiro se o valor for inteiro.

**Returns:**
valor booleano

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

Retorna verdadeiro se XmpValue for um valor nomeado.

**Returns:**
valor booleano

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

Retorna verdadeiro se XmpValue representar valores nomeados.

**Returns:**
valor booleano

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

Valor não suportado/desconhecido e código XML bruto é fornecido.

**Returns:**
True se o valor for retornado como dados brutos.

### isString {#isString--}
```
public boolean isString()
```

Retorna verdadeiro se o valor for string.

**Returns:**
valor booleano

### isStructure {#isStructure--}
```
public boolean isStructure()
```

Retorna verdadeiro se XmpValue representar estrutura.

**Returns:**
valor booleano

### to_ {#to_-com.aspose.pdf.XmpValue-}
Converte XmpValue em array.

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
Converte XmpValue para array.

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
Obter array de KeyValuePair

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
Converte XmpValue para valor nomeado.

### to_String {#to_String-com.aspose.pdf.XmpValue-}
Converte XmpValue em string.

### to_XmpValue {#to_XmpValue-java.util.Date-}
Converte DateTime em XmpValue.

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

Converte double em XmpValue.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double (Valor a converter) |

**Returns:**
Instância de XmpValue

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

Converte inteiro em XmpValue.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int (Valor a converter) |

**Returns:**
Instância de XmpValue

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
Converte array para XmpValue.

### to_XmpValue {#to_XmpValue-java.lang.String-}
Converte string para XmpValue.

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

Retorna array.

**Returns:**
Array de XmpValue

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

Converte para data e hora.

**Returns:**
Instância de Date

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

Converte o valor XMP atual para uma representação {@link DateTimeOffset}.

**Returns:**
Um {@link DateTimeOffset} que representa o valor XMP atual.

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

Retorna um dicionário que contém valores nomeados.

**Returns:**
Dicionário

### toDouble {#toDouble--}
```
public double toDouble()
```

Converte para double.

**Returns:**
valor double

### toField {#toField--}
```
public XmpField toField()
```

Retorna o valor XMP como campo XMP.

**Returns:**
Instância de XmpField

### toInteger {#toInteger--}
```
public int toInteger()
```

Converte para integer.

**Returns:**
valor int

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

Retorna o valor XMP como valor nomeado.

**Returns:**
(Valor nomeado) Instância de HashMap com chave String e valor XmpValue

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

Somente para uso interno

**Returns:**
Somente para uso interno

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

Retorna o valor XMP como coleção de valores nomeados.

**Returns:**
(Valor de coleção nomeada) Instância de HashMap com chave String e valor XmpValue

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

Código XML bruto para valores desconhecidos/não suportados.

**Returns:**
Nó XML para este valor.

### toString {#toString--}
```
public String toString()
```

Retorna a representação em string de XmpValue.

**Returns:**
Representação de string

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
Retorna a representação em string de XmpValue.

**Returns:**
Representação de string

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

Converte para string.

**Returns:**
valor String

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

Retorna o valor XMP como estrutura (conjunto de campos).

**Returns:**
Array de XmpField
