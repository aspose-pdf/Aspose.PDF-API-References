---
title: "SystemFontSource"
linktitle: "SystemFontSource"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa todas as fontes instaladas no sistema."
type: docs
weight: 4770
url: /pt/java/com.aspose.pdf/systemfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.SystemFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.SystemFontSource

```
public final class SystemFontSource extends FontSource
```

Representa todas as fontes instaladas no sistema.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SystemFontSource](#SystemFontSource--) | Inicializa uma nova instância da classe. |

## Métodos

| Método | Descrição |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Verifica se os objetos de fonte do sistema são iguais. |
| [getFontDefinitions](#getFontDefinitions--) | Somente para uso interno |
| [hashCode](#hashCode--) | Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.) |

### SystemFontSource {#SystemFontSource--}
```
public SystemFontSource()
```

Inicializa uma nova instância da classe.

### equals {#equals-java.lang.Object-}
Verifica se os objetos de fonte do sistema são iguais.

### getFontDefinitions {#getFontDefinitions--}
```
public com.aspose.font.FontDefinition[] getFontDefinitions()
```

Somente para uso interno

**Returns:**
Objeto FontDefinition[]

### hashCode {#hashCode--}
```
public int hashCode()
```

Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
um valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
