---
title: "XFA"
linktitle: "XFA"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa formulário XML relativo à Arquitetura de Formulários XML (XFA)."
type: docs
weight: 5550
url: /pt/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

Representa formulário XML relativo à Arquitetura de Formulários XML (XFA).

## Métodos

| Método | Descrição |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | Anexe o valor XML ao nó do modelo que corresponde à expressão XPath |
| [beginCachedUpdates](#beginCachedUpdates--) | Inicie o modo de atualizações em cache. Todas as alterações feitas ao XFA serão armazenadas em cache e salvas na estrutura do documento na chamada EndCachedUpdates. Isso permite melhorar o desempenho ao evitar operações redundantes ao salvar pacotes XML no documento quando muitas alterações ao XFA são feitas. |
| [endCachedUpdates](#endCachedUpdates--) | Finaliza as atualizações em cache e salva todos os dados na estrutura do documento. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Aplainar o campo do formulário XFA. |
| [get_Item](#get_Item-java.lang.String-) | Obtém o valor do nó de dados de acordo com {@code path}. |
| [getConfig](#getConfig--) | Componente XFA Config de um formulário XFA. |
| [getDatasets](#getDatasets--) | Componente XFA Datasets de um formulário XFA. |
| [getFieldNames](#getFieldNames--) | Lista de nomes de campos no modelo de formulário. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> Retorna um mapa com o nome curto do campo e seu valor string para todos os campos. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | Retorna o nó XML do modelo de campo XFA. |
| [getFieldTemplates](#getFieldTemplates--) | Retorna a lista de todos os modelos de campo no formulário XFA. |
| [getForm](#getForm--) | Obtém o Componente de Formulário XFA de um formulário XFA. |
| [getNamespaceManager_](#getNamespaceManager_--) | Obtém o namespace para o formulário XFA. Os seguintes namespaces são definidos: "data" para dados do formulário e "tpl" para o modelo do formulário. |
| [getNamespaceManager](#getNamespaceManager--) | Retorna o gerenciador de namespaces com os namespaces usados para modelo e dados. |
| [getTemplate](#getTemplate--) | Componente XFA Template de um formulário XFA. |
| [getXDP](#getXDP--) | Pacote de Dados XML (todos os componentes do formulário XFA dentro de um contêiner XML circundante). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Obtém o valor do nó de dados de acordo com {@code path}. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | Define a imagem para o campo XFA. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | Tenta exportar o script de cálculo do formulário XFA. Caso contrário, retorna a string vazia; |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
Anexe o valor XML ao nó do modelo que corresponde à expressão XPath

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

Inicie o modo de atualizações em cache. Todas as alterações feitas ao XFA serão armazenadas em cache e salvas na estrutura do documento na chamada EndCachedUpdates. Isso permite melhorar o desempenho ao evitar operações redundantes ao salvar pacotes XML no documento quando muitas alterações ao XFA são feitas.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

Finaliza as atualizações em cache e salva todos os dados na estrutura do documento.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
Aplainar o campo do formulário XFA.

### get_Item {#get_Item-java.lang.String-}
Obtém o valor do nó de dados de acordo com {@code path}.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

Componente XFA Config de um formulário XFA.

**Returns:**
Objeto XmlNode

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

Componente XFA Datasets de um formulário XFA.

**Returns:**
Objeto XmlNode

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Lista de nomes de campos no modelo de formulário.

**Returns:**
array de valores String

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> Retorna um mapa com o nome curto do campo e seu valor string para todos os campos. </p>

**Returns:**
Objeto {@code HashMap<String, String>}

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
Retorna o nó XML do modelo de campo XFA.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

Retorna a lista de todos os modelos de campo no formulário XFA.

**Returns:**
Lista de modelos de campo.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

Obtém o Componente de Formulário XFA de um formulário XFA.

**Returns:**
Objeto XmlNode

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

Obtém o namespace para o formulário XFA. Os seguintes namespaces são definidos: "data" para dados do formulário e "tpl" para o modelo do formulário.

**Returns:**
Objeto XmlNamespaceManager

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

Retorna o gerenciador de namespaces com os namespaces usados para modelo e dados.

**Returns:**
Objeto XmlNamespaceManager

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

Componente XFA Template de um formulário XFA.

**Returns:**
Objeto XmlNode

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

Pacote de Dados XML (todos os componentes do formulário XFA dentro de um contêiner XML circundante).

**Returns:**
Objeto XmlDocument

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
Obtém o valor do nó de dados de acordo com {@code path}.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
Define a imagem para o campo XFA.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
Tenta exportar o script de cálculo do formulário XFA. Caso contrário, retorna a string vazia;
