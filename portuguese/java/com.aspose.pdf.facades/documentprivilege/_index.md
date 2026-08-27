---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa os privilégios para acessar o arquivo Pdf. Consulte {@code PdfFileSecurity}. Existem 4 maneiras de usar esta classe: 1.Usando privilégio predefinido diretamente. 2.Baseado em um."
type: docs
weight: 110
url: /pt/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Representa os privilégios para acessar arquivos Pdf. Consulte {@code PdfFileSecurity}. Existem 4 maneiras de usar esta classe: 1.Usando privilégio predefinido diretamente. 2.Baseado em um privilégio predefinido e alterando algumas permissões específicas. 3.Baseado em um privilégio predefinido e alterando uma combinação específica de permissões do Adobe Professional. 4.Mistura as maneiras 2 e 3. //Way1: Usando privilégio predefinido diretamente. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Baseado em um privilégio predefinido e alterando algumas permissões específicas. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Baseado em um privilégio predefinido e alterando uma combinação específica de permissões do Adobe Professional. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mistura as maneiras 2 e 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## Métodos

| Método | Descrição |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | Compara dois objetos {@code DocumentPrivilege}. |
| [equals](#equals-java.lang.Object-) | Indica se algum outro objeto é "igual a" este. <p> O método <code>equals</code> implementa uma relação de equivalência em referências de objetos não nulas: <ul> <li>É <i>reflexivo</i>: para qualquer valor de referência não nulo <code>x</code>, <code>x.equals(x)</code> deve retornar <code>true</code>. <li>É <i>simétrico</i>: para quaisquer valores de referência não nulos <code>x</code> e <code>y</code>, <code>x.equals(y)</code> deve retornar <code>true</code> se e somente se <code>y.equals(x)</code> retornar <code>true</code>. <li>É <i>transitivo</i>: para quaisquer valores de referência não nulos <code>x</code>, <code>y</code> e <code>z</code>, se <code>x.equals(y)</code> retornar <code>true</code> e <code>y.equals(z)</code> retornar <code>true</code>, então <code>x.equals(z)</code> deve retornar <code>true</code>. <li>É <i>consistente</i>: para quaisquer valores de referência não nulos <code>x</code> e <code>y</code>, múltiplas invocações de <tt>x.equals(y)</tt> retornam consistentemente <code>true</code> ou consistentemente <code>false</code>, desde que nenhuma informação usada nas comparações <code>equals</code> dos objetos seja modificada. <li>Para qualquer valor de referência não nulo <code>x</code>, <code>x.equals(null)</code> deve retornar <code>false</code>. </ul> <p> O método <tt>equals</tt> da classe <code>Object</code> implementa a relação de equivalência mais discriminatória possível entre objetos; isto é, para quaisquer valores de referência não nulos <code>x</code> e <code>y</code>, este método retorna <code>true</code> se e somente se <code>x</code> e <code>y</code> referirem-se ao mesmo objeto (<code>x == y</code> tem o valor <code>true</code>). <p> Observe que geralmente é necessário sobrescrever o método <tt>hashCode</tt> sempre que este método for sobrescrito, a fim de manter o contrato geral para o método <tt>hashCode</tt>, que afirma que objetos iguais devem ter códigos de hash iguais. |
| [getAllowAll](#getAllowAll--) | Tudo permitido. |
| [getAssembly](#getAssembly--) | Permite montar o arquivo. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | Obtém e define o nível de alteração do privilégio do documento. Assim como as configurações Changes Allowed do Adobe Professional. 0: Nenhum. 1: Inserção, exclusão e rotação de páginas. 2: Preenchimento de campos de formulário e assinatura de campos de assinatura existentes. 3: Comentários, preenchimento de campos de formulário e assinatura de campos de assinatura existentes. 4: Qualquer, exceto extração de páginas. Se a propriedade tiver o valor -1, o nível é indefinido. |
| [getCopy](#getCopy--) | Permite copiar o arquivo. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | Obtém e define o nível de cópia do privilégio do documento. Assim como as configurações de permissão do Adobe Professional. 0: Nenhum. 1: Habilita acesso a texto para dispositivos de leitura de tela para deficientes visuais. 2: Habilita a cópia de texto, imagens e outros conteúdos. Se a propriedade tiver o valor -1, o nível é indefinido. |
| [getDegradedPrinting](#getDegradedPrinting--) | Permite impressão degradada. |
| [getFillIn](#getFillIn--) | Permite preencher formulários no arquivo. |
| [getForbidAll](#getForbidAll--) | Tudo proibido. |
| [getModifyAnnotations](#getModifyAnnotations--) | Permite modificar anotações do arquivo. |
| [getModifyContents](#getModifyContents--) | Permite modificar o arquivo. |
| [getPrint](#getPrint--) | Permite imprimir o arquivo. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | Obtém e define o nível de impressão do privilégio do documento. Assim como as configurações Printing Allowed do Adobe Professional. 0: Nenhum. 1: Baixa resolução (150 dpi). 2: Alta resolução. Se a propriedade tiver o valor -1, o nível é indefinido. |
| [getScreenReaders](#getScreenReaders--) | Permite leitura apenas na tela. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por <code>java.util.Hashtable</code>. <p> O contrato geral de <code>hashCode</code> é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método <tt>hashCode</tt> deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações <tt>equals</tt> no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método <tt>equals(Object)</tt>, então chamar o método <code>hashCode</code> em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método <tt>hashCode</tt> em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe <tt>Object</tt> retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [isAllowAssembly](#isAllowAssembly--) | Define a permissão que permite montagem ou não. true permite e false é proibido. |
| [isAllowCopy](#isAllowCopy--) | Define a permissão que permite cópia ou não. true permite e false é proibido. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | Define a permissão que permite impressão degradada ou não. true permite e false é proibido. Quando definido, a impressão será limitada a uma representação de baixo nível da aparência, possivelmente de qualidade degradada. |
| [isAllowFillIn](#isAllowFillIn--) | Define a permissão que permite preenchimento de formulários ou não. true permite e false é proibido. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | Define a permissão que permite modificar anotações ou não. true permite e false é proibido. |
| [isAllowModifyContents](#isAllowModifyContents--) | Define a permissão que permite modificar o conteúdo ou não. true permite e false é proibido. |
| [isAllowPrint](#isAllowPrint--) | Define a permissão que permite impressão ou não. true permite e false é proibido. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | Define a permissão que permite leitores de tela ou não. true permite e false é proibido. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | Define a permissão que permite montagem ou não. true permite e false é proibido. |
| [setAllowCopy](#setAllowCopy-boolean-) | Define a permissão que permite cópia ou não. true permite e false é proibido. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | Define a permissão que permite impressão degradada ou não. true permite e false é proibido. Quando definido, a impressão será limitada a uma representação de baixo nível da aparência, possivelmente de qualidade degradada. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | Define a permissão que permite preenchimento de formulários ou não. true permite e false é proibido. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | Define a permissão que permite modificar anotações ou não. true permite e false é proibido. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | Define a permissão que permite modificar o conteúdo ou não. true permite e false é proibido. |
| [setAllowPrint](#setAllowPrint-boolean-) | Define a permissão que permite impressão ou não. true permite e false é proibido. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | Define a permissão que permite leitores de tela ou não. true permite e false é proibido. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | Obtém e define o nível de alteração do privilégio do documento. Assim como as configurações Changes Allowed do Adobe Professional. 0: Nenhum. 1: Inserção, exclusão e rotação de páginas. 2: Preenchimento de campos de formulário e assinatura de campos de assinatura existentes. 3: Comentários, preenchimento de campos de formulário e assinatura de campos de assinatura existentes. 4: Qualquer, exceto extração de páginas. Se a propriedade tiver o valor -1, o nível é indefinido. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | Obtém e define o nível de cópia do privilégio do documento. Assim como as configurações de permissão do Adobe Professional. 0: Nenhum. 1: Habilita acesso a texto para dispositivos de leitura de tela para deficientes visuais. 2: Habilita a cópia de texto, imagens e outros conteúdos. Se a propriedade tiver o valor -1, o nível é indefinido. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | Obtém e define o nível de impressão do privilégio do documento. Assim como as configurações Printing Allowed do Adobe Professional. 0: Nenhum. 1: Baixa resolução (150 dpi). 2: Alta resolução. Se a propriedade tiver o valor -1, o nível é indefinido. |

### compareTo {#compareTo-java.lang.Object-}
Compara dois objetos {@code DocumentPrivilege}.

### equals {#equals-java.lang.Object-}
Indica se algum outro objeto é "igual a" este. <p> O método <code>equals</code> implementa uma relação de equivalência em referências de objetos não nulas: <ul> <li>É <i>reflexivo</i>: para qualquer valor de referência não nulo <code>x</code>, <code>x.equals(x)</code> deve retornar <code>true</code>. <li>É <i>simétrico</i>: para quaisquer valores de referência não nulos <code>x</code> e <code>y</code>, <code>x.equals(y)</code> deve retornar <code>true</code> se e somente se <code>y.equals(x)</code> retornar <code>true</code>. <li>É <i>transitivo</i>: para quaisquer valores de referência não nulos <code>x</code>, <code>y</code> e <code>z</code>, se <code>x.equals(y)</code> retornar <code>true</code> e <code>y.equals(z)</code> retornar <code>true</code>, então <code>x.equals(z)</code> deve retornar <code>true</code>. <li>É <i>consistente</i>: para quaisquer valores de referência não nulos <code>x</code> e <code>y</code>, múltiplas invocações de <tt>x.equals(y)</tt> retornam consistentemente <code>true</code> ou consistentemente <code>false</code>, desde que nenhuma informação usada nas comparações <code>equals</code> dos objetos seja modificada. <li>Para qualquer valor de referência não nulo <code>x</code>, <code>x.equals(null)</code> deve retornar <code>false</code>. </ul> <p> O método <tt>equals</tt> da classe <code>Object</code> implementa a relação de equivalência mais discriminatória possível entre objetos; isto é, para quaisquer valores de referência não nulos <code>x</code> e <code>y</code>, este método retorna <code>true</code> se e somente se <code>x</code> e <code>y</code> referirem-se ao mesmo objeto (<code>x == y</code> tem o valor <code>true</code>). <p> Observe que geralmente é necessário sobrescrever o método <tt>hashCode</tt> sempre que este método for sobrescrito, a fim de manter o contrato geral para o método <tt>hashCode</tt>, que afirma que objetos iguais devem ter códigos de hash iguais.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

Tudo permitido.

**Returns:**
Elemento DocumentPrivilege

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

Permite montar o arquivo.

**Returns:**
Elemento DocumentPrivilege

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

Obtém e define o nível de alteração do privilégio do documento. Assim como as configurações Changes Allowed do Adobe Professional. 0: Nenhum. 1: Inserção, exclusão e rotação de páginas. 2: Preenchimento de campos de formulário e assinatura de campos de assinatura existentes. 3: Comentários, preenchimento de campos de formulário e assinatura de campos de assinatura existentes. 4: Qualquer, exceto extração de páginas. Se a propriedade tiver o valor -1, o nível é indefinido.

**Returns:**
valor int

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

Permite copiar o arquivo.

**Returns:**
Elemento DocumentPrivilege

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

Obtém e define o nível de cópia do privilégio do documento. Assim como as configurações de permissão do Adobe Professional. 0: Nenhum. 1: Habilita acesso a texto para dispositivos de leitura de tela para deficientes visuais. 2: Habilita a cópia de texto, imagens e outros conteúdos. Se a propriedade tiver o valor -1, o nível é indefinido.

**Returns:**
valor int

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

Permite impressão degradada.

**Returns:**
Elemento DocumentPrivilege

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

Permite preencher formulários no arquivo.

**Returns:**
Elemento DocumentPrivilege

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

Tudo proibido.

**Returns:**
Elemento DocumentPrivilege

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

Permite modificar anotações do arquivo.

**Returns:**
Elemento DocumentPrivilege

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

Permite modificar o arquivo.

**Returns:**
Elemento DocumentPrivilege

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

Permite imprimir o arquivo.

**Returns:**
Elemento DocumentPrivilege

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

Obtém e define o nível de impressão do privilégio do documento. Assim como as configurações Printing Allowed do Adobe Professional. 0: Nenhum. 1: Baixa resolução (150 dpi). 2: Alta resolução. Se a propriedade tiver o valor -1, o nível é indefinido.

**Returns:**
valor int

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

Permite leitura apenas na tela.

**Returns:**
Elemento DocumentPrivilege

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por <code>java.util.Hashtable</code>. <p> O contrato geral de <code>hashCode</code> é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método <tt>hashCode</tt> deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações <tt>equals</tt> no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método <tt>equals(Object)</tt>, então chamar o método <code>hashCode</code> em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método <tt>hashCode</tt> em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe <tt>Object</tt> retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
um valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

Define a permissão que permite montagem ou não. true permite e false é proibido.

**Returns:**
valor booleano

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

Define a permissão que permite cópia ou não. true permite e false é proibido.

**Returns:**
valor booleano

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

Define a permissão que permite impressão degradada ou não. true permite e false é proibido. Quando definido, a impressão será limitada a uma representação de baixo nível da aparência, possivelmente de qualidade degradada.

**Returns:**
valor booleano

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

Define a permissão que permite preenchimento de formulários ou não. true permite e false é proibido.

**Returns:**
valor booleano

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

Define a permissão que permite modificar anotações ou não. true permite e false é proibido.

**Returns:**
valor booleano

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

Define a permissão que permite modificar o conteúdo ou não. true permite e false é proibido.

**Returns:**
valor booleano

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

Define a permissão que permite impressão ou não. true permite e false é proibido.

**Returns:**
valor booleano

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

Define a permissão que permite leitores de tela ou não. true permite e false é proibido.

**Returns:**
valor booleano

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

Define a permissão que permite montagem ou não. true permite e false é proibido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

Define a permissão que permite cópia ou não. true permite e false é proibido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

Define a permissão que permite impressão degradada ou não. true permite e false é proibido. Quando definido, a impressão será limitada a uma representação de baixo nível da aparência, possivelmente de qualidade degradada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

Define a permissão que permite preenchimento de formulários ou não. true permite e false é proibido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

Define a permissão que permite modificar anotações ou não. true permite e false é proibido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

Define a permissão que permite modificar o conteúdo ou não. true permite e false é proibido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

Define a permissão que permite impressão ou não. true permite e false é proibido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

Define a permissão que permite leitores de tela ou não. true permite e false é proibido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

Obtém e define o nível de alteração do privilégio do documento. Assim como as configurações Changes Allowed do Adobe Professional. 0: Nenhum. 1: Inserção, exclusão e rotação de páginas. 2: Preenchimento de campos de formulário e assinatura de campos de assinatura existentes. 3: Comentários, preenchimento de campos de formulário e assinatura de campos de assinatura existentes. 4: Qualquer, exceto extração de páginas. Se a propriedade tiver o valor -1, o nível é indefinido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

Obtém e define o nível de cópia do privilégio do documento. Assim como as configurações de permissão do Adobe Professional. 0: Nenhum. 1: Habilita acesso a texto para dispositivos de leitura de tela para deficientes visuais. 2: Habilita a cópia de texto, imagens e outros conteúdos. Se a propriedade tiver o valor -1, o nível é indefinido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

Obtém e define o nível de impressão do privilégio do documento. Assim como as configurações Printing Allowed do Adobe Professional. 0: Nenhum. 1: Baixa resolução (150 dpi). 2: Alta resolução. Se a propriedade tiver o valor -1, o nível é indefinido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
