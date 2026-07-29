---
title: "ComHelper"
linktitle: "ComHelper"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Fornece métodos para clientes COM carregarem um documento no Aspose.PDF. </p> <hr> <p> Use a classe ComHelper para carregar um documento de um arquivo ou stream em um objeto Document."
type: docs
weight: 760
url: /pt/java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> Fornece métodos para clientes COM carregarem um documento no Aspose.PDF. </p> <hr> <p> Use a classe ComHelper para carregar um documento de um arquivo ou fluxo em um objeto Document em uma aplicação COM. A classe Document fornece um construtor padrão para criar um novo documento e também fornece construtores sobrecarregados para carregar um documento de um arquivo ou fluxo. Se você estiver usando Aspose.Words a partir de uma aplicação .NET, pode usar todos os construtores de Document diretamente, mas se estiver usando Aspose.PDF a partir de uma aplicação COM, apenas o construtor padrão de Document está disponível. </p>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | Basta criar e retornar Document usando {@code filename}. O mesmo que {@code Document(Stream)}. |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Abra um documento existente a partir de um arquivo fornecendo as opções de conversão necessárias para obter o documento PDF. |
| [openFile](#openFile-java.lang.String-java.lang.String-) | Inicialize e retorne uma nova instância da classe {@code Document} para trabalhar com documento criptografado. |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | Inicialize uma nova instância da classe {@code Document} para trabalhar com documento criptografado. |
| [openStream](#openStream-java.io.InputStream-) | Inicialize e retorne uma nova instância de Document a partir do stream {@code input}. |
| [openStream](#openStream-java.io.InputStream-boolean-) | Inicialize e retorne uma nova instância de Document a partir do stream {@code input}. |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Abra e retorne um documento existente a partir de um stream fornecendo a conversão necessária para obter o documento PDF. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | Inicialize e retorne uma nova instância de Document a partir do stream {@code input}. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | Inicialize e retorne uma nova instância de Document a partir do stream {@code input}. |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
Basta criar e retornar Document usando {@code filename}. O mesmo que {@code Document(Stream)}.

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
Abra um documento existente a partir de um arquivo fornecendo as opções de conversão necessárias para obter o documento PDF.

### openFile {#openFile-java.lang.String-java.lang.String-}
Inicialize e retorne uma nova instância da classe {@code Document} para trabalhar com documento criptografado.

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
Inicialize uma nova instância da classe {@code Document} para trabalhar com documento criptografado.

### openStream {#openStream-java.io.InputStream-}
Inicialize e retorne uma nova instância de Document a partir do stream {@code input}.

### openStream {#openStream-java.io.InputStream-boolean-}
Inicialize e retorne uma nova instância de Document a partir do stream {@code input}.

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Abra e retorne um documento existente a partir de um stream fornecendo a conversão necessária para obter o documento PDF.

### openStream {#openStream-java.io.InputStream-java.lang.String-}
Inicialize e retorne uma nova instância de Document a partir do stream {@code input}.

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
Inicialize e retorne uma nova instância de Document a partir do stream {@code input}.
