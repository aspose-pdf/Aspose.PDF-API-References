---
title: "MemoryFontSource"
linktitle: "MemoryFontSource"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a fonte de arquivo de fonte única."
type: docs
weight: 3040
url: /pt/java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

Representa a fonte de arquivo de fonte única.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | Inicializa uma nova instância da classe {@code MemoryFontSource}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [close](#close--) | Fecha todos os recursos usados por este documento. |
| [dispose](#dispose--) | Libera recursos internos. Este método está obsoleto, use close() em vez disso. |
| [equals](#equals-java.lang.Object-) | Verifique se os objetos de origem de arquivo de fonte são iguais. |
| [getFontBytes](#getFontBytes--) | Array de bytes do arquivo de fonte. |
| [hashCode](#hashCode--) | Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.) |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

Inicializa uma nova instância da classe {@code MemoryFontSource}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontBytes |  | Array de bytes do arquivo de fonte. |

### close {#close--}
```
public void close()
```

Fecha todos os recursos usados por este documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libera recursos internos. Este método está obsoleto, use close() em vez disso.

### equals {#equals-java.lang.Object-}
Verifique se os objetos de origem de arquivo de fonte são iguais.

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

Array de bytes do arquivo de fonte.

**Returns:**
array byte[]

### hashCode {#hashCode--}
```
public int hashCode()
```

Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
um valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
