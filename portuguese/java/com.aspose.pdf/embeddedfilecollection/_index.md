---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa a coleção de arquivos incorporados."
type: docs
weight: 1200
url: /pt/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

Classe que representa a coleção de arquivos incorporados.

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | Adiciona a especificação de arquivo incorporado à coleção. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Adiciona o arquivo aos arquivos incorporados com a chave especificada. |
| [clear](#clear--) | Remova todos os arquivos incorporados do documento. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | Determina se a coleção contém a FileSpecification especificada. Não suportado. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | Copia a matriz de objetos FileSpecification para a coleção. |
| [delete](#delete--) | Remova todos os arquivos incorporados do documento. |
| [delete](#delete-java.lang.String-) | Remova todos os arquivos incorporados do documento. |
| [deleteByKey](#deleteByKey-java.lang.String-) | Exclui o arquivo da coleção pela sua chave na coleção. |
| [findByName](#findByName-java.lang.String-) | Retorna o arquivo incorporado pelo seu nome. |
| [get_Item](#get_Item-int-) | Obtém o arquivo incorporado pelo seu índice. |
| [get_Item](#get_Item-java.lang.String-) | Obtém o arquivo incorporado pelo seu nome. |
| [getKeys](#getKeys--) | Retorna a lista de chaves de anexos de arquivos. |
| [getSyncRoot](#getSyncRoot--) | Obtém um objeto que pode ser usado para sincronizar o acesso a esta coleção. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | Verifique se a estrutura Embedded Files existe. Retorne VERDADEIRO se a estrutura existir e FALSO caso contrário. Se o documento nunca contiver arquivos incorporados, essa estrutura não foi criada e está ausente. |
| [isReadOnly](#isReadOnly--) | Determina se a coleção é somente leitura. Sempre retorna falso. |
| [isSynchronized](#isSynchronized--) | Obtém um valor que indica se o acesso a esta coleção está sincronizado (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Retorna o enumerador da coleção. |
| [iterator](#iterator--) | Retorna o enumerador da coleção. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | Remove a FileSpecification especificada da coleção. Não suportado. |
| [size](#size--) | Obtém o número de arquivos incorporados na coleção. |

### add {#add-com.aspose.pdf.FileSpecification-}
Adiciona a especificação de arquivo incorporado à coleção.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
Adiciona o arquivo aos arquivos incorporados com a chave especificada.

### clear {#clear--}
```
public void clear()
```

Remova todos os arquivos incorporados do documento.

### contains {#contains-com.aspose.pdf.FileSpecification-}
Determina se a coleção contém a FileSpecification especificada. Não suportado.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
Copia a matriz de objetos FileSpecification para a coleção.

### delete {#delete--}
```
public void delete()
```

Remova todos os arquivos incorporados do documento.

### delete {#delete-java.lang.String-}
Remova todos os arquivos incorporados do documento.

### deleteByKey {#deleteByKey-java.lang.String-}
Exclui o arquivo da coleção pela sua chave na coleção.

### findByName {#findByName-java.lang.String-}
Retorna o arquivo incorporado pelo seu nome.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

Obtém o arquivo incorporado pelo seu índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do arquivo incorporado. A numeração começa em 1. |

**Returns:**
Especificação do arquivo incorporado recuperado

### get_Item {#get_Item-java.lang.String-}
Obtém o arquivo incorporado pelo seu nome.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

Retorna a lista de chaves de anexos de arquivos.

**Returns:**
Lista de valores String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém um objeto que pode ser usado para sincronizar o acesso a esta coleção.

**Returns:**
Objeto para sincronização

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

Verifique se a estrutura Embedded Files existe. Retorne VERDADEIRO se a estrutura existir e FALSO caso contrário. Se o documento nunca contiver arquivos incorporados, essa estrutura não foi criada e está ausente.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Determina se a coleção é somente leitura. Sempre retorna falso.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtém um valor que indica se o acesso a esta coleção está sincronizado (thread safe).

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

Retorna o enumerador da coleção.

**Returns:**
Enumerador da coleção.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

Retorna o enumerador da coleção.

**Returns:**
Enumerador da coleção.

### remove {#remove-com.aspose.pdf.FileSpecification-}
Remove a FileSpecification especificada da coleção. Não suportado.

### size {#size--}
```
public int size()
```

Obtém o número de arquivos incorporados na coleção.

**Returns:**
valor int
