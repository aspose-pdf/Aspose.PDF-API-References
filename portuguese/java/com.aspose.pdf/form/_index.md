---
title: "Formulário"
linktitle: "Formulário"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o objeto de formulário."
type: docs
weight: 1740
url: /pt/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

Classe que representa o objeto de formulário.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | Adiciona campo no formulário. |
| [add](#add-com.aspose.pdf.Field-int-) | Adiciona campo no formulário. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | Adiciona um novo campo ao formulário; se este campo já estiver colocado em outro ou neste formulário, uma cópia do campo é criada. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | Adiciona campo no formulário. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Adiciona aparência adicional do campo à página especificada do documento na localização especificada. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | Adiciona aparência adicional do campo à página especificada do documento. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Define XFA do formulário para o valor especificado. |
| [clear](#clear--) | Exclui todos os campos do formulário. Não suportado. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | Determina se o campo está presente no formulário.. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copia campos colocados no formulário para um array. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | Copia os campos do formulário para um array. |
| [delete](#delete-com.aspose.pdf.Field-) | Exclui campo do formulário. |
| [delete](#delete-java.lang.String-) | Exclui campo do formulário pelo seu nome. |
| [flatten](#flatten--) | Remove todos os campos estáticos do formulário e coloca seus valores diretamente na página. |
| [get_Item](#get_Item-int-) | Obtém campo do formulário pelo índice do campo. |
| [get_Item](#get_Item-java.lang.String-) | Obtém campo do formulário pelo nome do campo. Lança exceção se o campo não for encontrado. |
| [get_xfa](#get_xfa--) | Somente para uso interno |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | Procura campo pelo nome do campo. Retorna null se o campo não for encontrado. |
| [getAutoRecalculate](#getAutoRecalculate--) | Se definido, todos os campos do formulário serão recalculados quando qualquer campo for alterado. O valor padrão é true. Defina como false para aumentar o desempenho ao preencher o formulário com grande quantidade de campos calculados. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | Se definido, campos ausentes do formulário serão criados automaticamente se estiverem presentes nas anotações. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtém a aparência padrão do formulário (objeto que descreve a fonte padrão, tamanho do texto e cor para os campos no formulário). |
| [getDefaultResources](#getDefaultResources--) | Obtém recursos padrão colocados neste formulário. |
| [getDocument](#getDocument--) | Somente para uso interno |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Se esta propriedade for verdadeira, retângulos vermelhos adicionais serão desenhados para os contêineres de elementos exigidos Xfa exclGroup. Esta propriedade foi introduzida porque há ausência de analogias para o exclGroup durante a conversão da representação Xfa dos formulários para o padrão. O valor padrão é falso. |
| [getFields](#getFields--) | Obtém a lista de todos os campos no nível mais baixo do formulário hierárquico. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Retorna os campos dentro do retângulo especificado. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | Se esta propriedade for verdadeira, o valor da chave NeedsRendering será ignorado durante a conversão do formulário XFA para o formulário padrão. O padrão é falso. |
| [getNeedsRendering](#getNeedsRendering--) | Obtém um valor que indica se o documento requer a remoção do formulário XFA dinâmico. Esta propriedade foi introduzida para determinar se {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) deve ser usado para remover o formulário XFA nos casos em que o formulário XFA está presente e {@code NeedsRendering}({@link #getNeedsRendering}) é falso. |
| [getRemovePermission](#getRemovePermission--) | Se esta propriedade for verdadeira, o dicionário \"Perms\" será removido do documento PDF após a conversão de documentos dinâmicos para o padrão. O dicionário \"Perms\" pode conter regras que atrapalham a exibição e seleção de campos obrigatórios no Adobe Acrobat Reader. O padrão é falso. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | Se definido, o documento contém assinaturas que podem ser invalidadas se o arquivo for salvo (gravado) de maneira que altere seu conteúdo anterior, ao contrário de uma atualização incremental. |
| [getSignaturesExist](#getSignaturesExist--) | Se definido, o documento contém pelo menos um campo de assinatura. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | Os formulários podem conter informações de assinatura, ou seja, podem estar assinados ou não assinados. E a visualização do formulário às vezes deve depender de o formulário estar assinado ou não. Esta propriedade informa ao conversor de formulários (por exemplo, durante a conversão de formulário XFA para formulário padrão) se o formulário resultante deve ser renderizado como assinado ou como não assinado. |
| [getSyncRoot](#getSyncRoot--) | Retorna o objeto de sincronização. |
| [getType](#getType--) | Obtém o tipo do formulário. Valores possíveis são: Standard, Static, Dynamic. |
| [getXFA](#getXFA--) | Obtém os dados XFA do formulário (se presentes). |
| [hasField](#hasField-com.aspose.pdf.Field-) | Verifica se o formulário já possui o campo especificado. |
| [hasField](#hasField-java.lang.String-) | Determina se o campo com o nome especificado já foi adicionado ao Formulário. |
| [hasField](#hasField-java.lang.String-boolean-) | Determina se o campo com o nome especificado já foi adicionado ao Formulário, com a capacidade de examinar a hierarquia de campos filhos. |
| [hasXfa](#hasXfa--) | Obtém um valor que indica se o documento contém formulário XFA. Esta propriedade foi introduzida para determinar se {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) deve ser usado para remover o formulário XFA nos casos em que o formulário XFA está presente e {@code NeedsRendering}({@link #getNeedsRendering}) é falso. |
| [isReadOnly](#isReadOnly--) | Determina se a coleção é somente leitura. Sempre retorna falso. |
| [isSynchronized](#isSynchronized--) | Retorna verdadeiro se o objeto for thread-safe. |
| [iterator](#iterator--) | Obtém a enumeração dos campos do formulário. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * Exporta os campos de formulário PDF para o formato JSON e grava o resultado no fluxo fornecido. / * / * Document document = new Document(\"PdfDoc.pdf\"); / * FileStream fs = new FileStream(\"export.json\", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | Exclui o campo do formulário. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | Remove a aparência do campo no índice especificado. Se restar apenas uma aparência filha, o método a incorpora ao campo. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | Se definido, todos os campos do formulário serão recalculados quando qualquer campo for alterado. O valor padrão é true. Defina como false para aumentar o desempenho ao preencher o formulário com grande quantidade de campos calculados. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | Se definido, campos ausentes do formulário serão criados automaticamente se estiverem presentes nas anotações. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | Permite definir a ordem de cálculo dos campos. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Define a aparência padrão do formulário (objeto que descreve a fonte padrão, tamanho do texto e cor para os campos no formulário). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Se esta propriedade for verdadeira, retângulos vermelhos adicionais serão desenhados para os contêineres de elementos exigidos Xfa exclGroup. Esta propriedade foi introduzida porque há ausência de analogias para o exclGroup durante a conversão da representação Xfa dos formulários para o padrão. O valor padrão é falso. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | Se esta propriedade for verdadeira, o valor da chave NeedsRendering será ignorado durante a conversão do formulário XFA para o formulário padrão. O padrão é falso. |
| [setRemovePermission](#setRemovePermission-boolean-) | Se esta propriedade for verdadeira, o dicionário \"Perms\" será removido do documento PDF após a conversão de documentos dinâmicos para o padrão. O dicionário \"Perms\" pode conter regras que atrapalham a exibição e seleção de campos obrigatórios no Adobe Acrobat Reader. O padrão é falso. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | Se definido, o documento contém assinaturas que podem ser invalidadas se o arquivo for salvo (gravado) de maneira que altere seu conteúdo anterior, ao contrário de uma atualização incremental. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | Se definido, o documento contém pelo menos um campo de assinatura. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | Os formulários podem conter informações de assinatura, ou seja, podem estar assinados ou não assinados. E a visualização do formulário às vezes deve depender de o formulário estar assinado ou não. Esta propriedade informa ao conversor de formulários (por exemplo, durante a conversão de formulário XFA para formulário padrão) se o formulário resultante deve ser renderizado como assinado ou como não assinado. |
| [setType](#setType-com.aspose.pdf.FormType-) | Obtém o tipo do formulário. Valores possíveis são: Standard, Static, Dynamic. |
| [size](#size--) | Obtém o número de campos neste formulário. |

### Form {#Form-com.aspose.pdf.IDocument-}
Construtor

### add {#add-com.aspose.pdf.Field-}
Adiciona campo no formulário.

### add {#add-com.aspose.pdf.Field-int-}
Adiciona campo no formulário.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
Adiciona um novo campo ao formulário; se este campo já estiver colocado em outro ou neste formulário, uma cópia do campo é criada.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
Adiciona campo no formulário.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
Adiciona aparência adicional do campo à página especificada do documento na localização especificada.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
Adiciona aparência adicional do campo à página especificada do documento.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
Define XFA do formulário para o valor especificado.

### clear {#clear--}
```
public void clear()
```

Exclui todos os campos do formulário. Não suportado.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
Determina se o campo está presente no formulário..

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copia campos colocados no formulário para um array.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
Copia os campos do formulário para um array.

### delete {#delete-com.aspose.pdf.Field-}
Exclui campo do formulário.

### delete {#delete-java.lang.String-}
Exclui campo do formulário pelo seu nome.

### flatten {#flatten--}
```
public void flatten()
```

Remove todos os campos estáticos do formulário e coloca seus valores diretamente na página.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Obtém campo do formulário pelo índice do campo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do campo. |

**Returns:**
Campo recuperado.

### get_Item {#get_Item-java.lang.String-}
Obtém campo do formulário pelo nome do campo. Lança exceção se o campo não for encontrado.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

Somente para uso interno

**Returns:**
objeto XFA

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  |  |

### get {#get-java.lang.String-}
Procura campo pelo nome do campo. Retorna null se o campo não for encontrado.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

Se definido, todos os campos do formulário serão recalculados quando qualquer campo for alterado. O valor padrão é true. Defina como false para aumentar o desempenho ao preencher o formulário com grande quantidade de campos calculados.

**Returns:**
valor booleano

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

Se definido, campos ausentes do formulário serão criados automaticamente se estiverem presentes nas anotações.

**Returns:**
valor booleano

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Obtém a aparência padrão do formulário (objeto que descreve a fonte padrão, tamanho do texto e cor para os campos no formulário).

**Returns:**
objeto DefaultAppearance

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

Obtém recursos padrão colocados neste formulário.

**Returns:**
valor de Resources

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Somente para uso interno

**Returns:**
objeto IDocument

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Se esta propriedade for verdadeira, retângulos vermelhos adicionais serão desenhados para os contêineres de elementos exigidos Xfa exclGroup. Esta propriedade foi introduzida porque há ausência de analogias para o exclGroup durante a conversão da representação Xfa dos formulários para o padrão. O valor padrão é falso.

**Returns:**
valor booleano

### getFields {#getFields--}
```
public Field [] getFields()
```

Obtém a lista de todos os campos no nível mais baixo do formulário hierárquico.

**Returns:**
Array com campos encontrados.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
Retorna os campos dentro do retângulo especificado.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

Se esta propriedade for verdadeira, o valor da chave NeedsRendering será ignorado durante a conversão do formulário XFA para o formulário padrão. O padrão é falso.

**Returns:**
valor booleano

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

Obtém um valor que indica se o documento requer a remoção do formulário XFA dinâmico. Esta propriedade foi introduzida para determinar se {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) deve ser usado para remover o formulário XFA nos casos em que o formulário XFA está presente e {@code NeedsRendering}({@link #getNeedsRendering}) é falso.

**Returns:**
valor booleano

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

Se esta propriedade for verdadeira, o dicionário \"Perms\" será removido do documento PDF após a conversão de documentos dinâmicos para o padrão. O dicionário \"Perms\" pode conter regras que atrapalham a exibição e seleção de campos obrigatórios no Adobe Acrobat Reader. O padrão é falso.

**Returns:**
valor booleano

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

Se definido, o documento contém assinaturas que podem ser invalidadas se o arquivo for salvo (gravado) de maneira que altere seu conteúdo anterior, ao contrário de uma atualização incremental.

**Returns:**
valor booleano

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

Se definido, o documento contém pelo menos um campo de assinatura.

**Returns:**
valor booleano

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

Os formulários podem conter informações de assinatura, ou seja, podem estar assinados ou não assinados. E a visualização do formulário às vezes deve depender de o formulário estar assinado ou não. Esta propriedade informa ao conversor de formulários (por exemplo, durante a conversão de formulário XFA para formulário padrão) se o formulário resultante deve ser renderizado como assinado ou como não assinado.

**Returns:**
elemento SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Retorna o objeto de sincronização.

**Returns:**
Objeto para sincronização

### getType {#getType--}
```
public FormType getType()
```

Obtém o tipo do formulário. Valores possíveis são: Standard, Static, Dynamic.

**Returns:**
valor FormType @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

Obtém os dados XFA do formulário (se presentes).

**Returns:**
valor XFA

### hasField {#hasField-com.aspose.pdf.Field-}
Verifica se o formulário já possui o campo especificado.

### hasField {#hasField-java.lang.String-}
Determina se o campo com o nome especificado já foi adicionado ao Formulário.

### hasField {#hasField-java.lang.String-boolean-}
Determina se o campo com o nome especificado já foi adicionado ao Formulário, com a capacidade de examinar a hierarquia de campos filhos.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

Obtém um valor que indica se o documento contém formulário XFA. Esta propriedade foi introduzida para determinar se {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) deve ser usado para remover o formulário XFA nos casos em que o formulário XFA está presente e {@code NeedsRendering}({@link #getNeedsRendering}) é falso.

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

Retorna verdadeiro se o objeto for thread-safe.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Obtém a enumeração dos campos do formulário.

**Returns:**
Enumerador de campo.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * Exporta os campos de formulário PDF para o formato JSON e grava o resultado no fluxo fornecido. / * / * Document document = new Document(\"PdfDoc.pdf\"); / * FileStream fs = new FileStream(\"export.json\", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
Exclui o campo do formulário.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
Remove a aparência do campo no índice especificado. Se restar apenas uma aparência filha, o método a incorpora ao campo.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

Se definido, todos os campos do formulário serão recalculados quando qualquer campo for alterado. O valor padrão é true. Defina como false para aumentar o desempenho ao preencher o formulário com grande quantidade de campos calculados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

Se definido, campos ausentes do formulário serão criados automaticamente se estiverem presentes nas anotações.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
Permite definir a ordem de cálculo dos campos.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Define a aparência padrão do formulário (objeto que descreve a fonte padrão, tamanho do texto e cor para os campos no formulário).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Se esta propriedade for verdadeira, retângulos vermelhos adicionais serão desenhados para os contêineres de elementos exigidos Xfa exclGroup. Esta propriedade foi introduzida porque há ausência de analogias para o exclGroup durante a conversão da representação Xfa dos formulários para o padrão. O valor padrão é falso.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

Se esta propriedade for verdadeira, o valor da chave NeedsRendering será ignorado durante a conversão do formulário XFA para o formulário padrão. O padrão é falso.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

Se esta propriedade for verdadeira, o dicionário \"Perms\" será removido do documento PDF após a conversão de documentos dinâmicos para o padrão. O dicionário \"Perms\" pode conter regras que atrapalham a exibição e seleção de campos obrigatórios no Adobe Acrobat Reader. O padrão é falso.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

Se definido, o documento contém assinaturas que podem ser invalidadas se o arquivo for salvo (gravado) de maneira que altere seu conteúdo anterior, ao contrário de uma atualização incremental.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

Se definido, o documento contém pelo menos um campo de assinatura.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

Os formulários podem conter informações de assinatura, ou seja, podem estar assinados ou não assinados. E a visualização do formulário às vezes deve depender de o formulário estar assinado ou não. Esta propriedade informa ao conversor de formulários (por exemplo, durante a conversão de formulário XFA para formulário padrão) se o formulário resultante deve ser renderizado como assinado ou como não assinado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | elemento SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
Obtém o tipo do formulário. Valores possíveis são: Standard, Static, Dynamic.

### size {#size--}
```
public final int size()
```

Obtém o número de campos neste formulário.

**Returns:**
valor int
