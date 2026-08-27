---
title: "FileParams"
linktitle: "FileParams"
second_title: "Referência da API Aspose.PDF para Java"
description: "Define um dicionário de parâmetros de arquivo incorporado que deve conter informações adicionais específicas do arquivo."
type: docs
weight: 1490
url: /pt/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

Define um dicionário de parâmetros de arquivo incorporado que deve conter informações adicionais específicas do arquivo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | Construtor da classe FileParams. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCheckSum](#getCheckSum--) | Uma string de 16 bytes que é a soma de verificação dos bytes do arquivo incorporado descompactado. A soma de verificação é calculada aplicando o algoritmo padrão de digestão de mensagem MD5 aos bytes do fluxo do arquivo incorporado. |
| [getCreationDate](#getCreationDate--) | Obtém a data e hora em que o arquivo incorporado foi criado. |
| [getModDate](#getModDate--) | Obtém a data e hora em que o arquivo incorporado foi modificado pela última vez. |
| [getSize](#getSize--) | O tamanho do arquivo incorporado descompactado, em bytes. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Define a data e hora em que o arquivo incorporado foi criado. |
| [setModDate](#setModDate-java.util.Date-) | Define a data e hora em que o arquivo incorporado foi modificado pela última vez. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
Construtor da classe FileParams.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

Uma string de 16 bytes que é a soma de verificação dos bytes do arquivo incorporado descompactado. A soma de verificação é calculada aplicando o algoritmo padrão de digestão de mensagem MD5 aos bytes do fluxo do arquivo incorporado.

**Returns:**
valor String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Obtém a data e hora em que o arquivo incorporado foi criado.

**Returns:**
Objeto Date

### getModDate {#getModDate--}
```
public Date getModDate()
```

Obtém a data e hora em que o arquivo incorporado foi modificado pela última vez.

**Returns:**
Objeto Date

### getSize {#getSize--}
```
public int getSize()
```

O tamanho do arquivo incorporado descompactado, em bytes.

**Returns:**
valor int

### setCreationDate {#setCreationDate-java.util.Date-}
Define a data e hora em que o arquivo incorporado foi criado.

### setModDate {#setModDate-java.util.Date-}
Define a data e hora em que o arquivo incorporado foi modificado pela última vez.
