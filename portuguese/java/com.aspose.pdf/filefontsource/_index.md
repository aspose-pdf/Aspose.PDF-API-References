---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a fonte de arquivo de fonte única."
type: docs
weight: 1450
url: /pt/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

Representa a fonte de arquivo de fonte única.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | Inicializa uma nova instância da classe {@code FileFontSource}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Verifique se os objetos de origem de arquivo de fonte são iguais. |
| [getFilePath](#getFilePath--) | Caminho para o arquivo de fonte. |
| [hashCode](#hashCode--) | Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} do objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos forem diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho das tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} realmente retorna inteiros distintos para objetos distintos. (Isso geralmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java <span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [setFilePath](#setFilePath-java.lang.String-) | Caminho para o arquivo de fonte. |

### FileFontSource {#FileFontSource-java.lang.String-}
Inicializa uma nova instância da classe {@code FileFontSource}.

### equals {#equals-java.lang.Object-}
Verifique se os objetos de origem de arquivo de fonte são iguais.

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

Caminho para o arquivo de fonte.

**Returns:**
valor String

### hashCode {#hashCode--}
```
public int hashCode()
```

Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} do objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos forem diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho das tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} realmente retorna inteiros distintos para objetos distintos. (Isso geralmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java <span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
um valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
Caminho para o arquivo de fonte.
