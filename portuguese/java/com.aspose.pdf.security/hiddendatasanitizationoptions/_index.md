---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa as opções de configuração para sanitizar dados ocultos dentro de um documento."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

Representa as opções de configuração para sanitizar dados ocultos dentro de um documento.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [all](#all--) | Cria uma nova instância da classe {@link HiddenDataSanitizationOptions} com todas as opções definidas para sanitização. Isso inclui habilitar a remoção de anotações, JavaScript, metadados, anexos, índice de pesquisa, informações privadas, achatamento de formulários e camadas, enquanto desabilita a opção de converter páginas em imagens. Configurações opcionais como {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) ou {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) podem ser modificadas manualmente após obter a instância, pois não estão ativas por padrão. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | Obtém a opção de converter páginas em imagens. Se esta opção estiver habilitada, a opção ImageCompressionOptions será ignorada. A opção deve ser habilitada manualmente ao usar o método {@code #All()} se for necessária. A conversão de páginas em imagens ocorrerá após a limpeza dos principais dados ocultos, que são controlados por outras opções. |
| [getFlattenForms](#getFlattenForms--) | Obtém um valor que indica se os formulários no documento devem ser achatados durante o processo de sanitização. O achatamento de formulários converte campos interativos em conteúdo estático, tornando-os não editáveis ou preenchíveis. |
| [getFlattenLayers](#getFlattenLayers--) | Obtém a opção de achatar as camadas no documento PDF. Quando habilitada, todas as camadas do documento são mescladas em uma única camada, removendo sua estrutura separada. Esta opção é útil para sanitizar documentos simplificando seu conteúdo e garantindo que nenhum dado oculto permaneça nas camadas. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Obtém a opção de conversão de imagens do documento. A opção deve ser habilitada manualmente ao usar o método {@code #All()} se for necessária. |
| [getImageDpi](#getImageDpi--) | Obtém a opção de resolver imagens de página durante a conversão. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | Obtém um valor que indica se as anotações devem ser removidas do documento. Quando habilitado, todas as anotações presentes no documento serão removidas durante o processo de sanitização. Anotações de redação serão aplicadas. |
| [getRemoveAttachments](#getRemoveAttachments--) | Obtém a opção de remover todos os arquivos anexados do documento. Quando habilitada, garante que quaisquer anexos dentro do PDF sejam eliminados durante o processo de sanitização. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | Obtém um valor que indica se o JavaScript e as ações associadas devem ser removidos do documento. Esta opção é útil para eliminar vulnerabilidades de segurança potenciais introduzidas por scripts incorporados. |
| [getRemoveMetadata](#getRemoveMetadata--) | Obtém uma opção para remover metadados do documento. Se definido como verdadeiro, metadados como propriedades do documento e informações adicionais de metadados incorporados serão removidos durante a sanitização. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | Obtém um valor que indica se o índice de pesquisa e as informações privadas devem ser removidos do documento. Habilita a remoção de índices de pesquisa incorporados e dados privados para melhorar a segurança e a privacidade do documento. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | Define a opção de converter páginas em imagens. Se esta opção estiver habilitada, a opção ImageCompressionOptions será ignorada. A opção deve ser habilitada manualmente ao usar o método {@code #All()} se for necessária. A conversão de páginas em imagens ocorrerá após a limpeza dos principais dados ocultos, que são controlados por outras opções. |
| [setFlattenForms](#setFlattenForms-boolean-) | Define um valor que indica se os formulários no documento devem ser achatados durante o processo de sanitização. O achatamento de formulários converte campos interativos em conteúdo estático, tornando-os não editáveis ou preenchíveis. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | Define a opção de achatar as camadas no documento PDF. Quando habilitada, todas as camadas do documento são mescladas em uma única camada, removendo sua estrutura separada. Esta opção é útil para sanitizar documentos simplificando seu conteúdo e garantindo que nenhum dado oculto permaneça nas camadas. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Define a opção de conversão de imagens do documento. A opção deve ser habilitada manualmente ao usar o método {@code #All()} se for necessária. |
| [setImageDpi](#setImageDpi-int-) | Define a opção de resolver imagens de página durante a conversão. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | Define um valor que indica se as anotações devem ser removidas do documento. Quando habilitado, todas as anotações presentes no documento serão removidas durante o processo de sanitização. Anotações de redação serão aplicadas. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | Define a opção de remover todos os arquivos anexados do documento. Quando habilitada, garante que quaisquer anexos dentro do PDF sejam eliminados durante o processo de sanitização. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | Define um valor que indica se o JavaScript e as ações associadas devem ser removidos do documento. Esta opção é útil para eliminar vulnerabilidades de segurança potenciais introduzidas por scripts incorporados. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | Define uma opção para remover metadados do documento. Se definido como verdadeiro, metadados como propriedades do documento e informações adicionais de metadados incorporados serão removidos durante a sanitização. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | Define um valor que indica se o índice de pesquisa e informações privadas devem ser removidos do documento. Permite a remoção de índices de pesquisa incorporados e dados privados para melhorar a segurança e a privacidade do documento. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

Cria uma nova instância da classe {@link HiddenDataSanitizationOptions} com todas as opções definidas para sanitização. Isso inclui habilitar a remoção de anotações, JavaScript, metadados, anexos, índice de pesquisa, informações privadas, achatamento de formulários e camadas, enquanto desabilita a opção de converter páginas em imagens. Configurações opcionais como {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) ou {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) podem ser modificadas manualmente após obter a instância, pois não estão ativas por padrão.

**Returns:**
Uma instância {@link HiddenDataSanitizationOptions} com todas as opções de sanitização pré-configuradas.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

Obtém a opção de converter páginas em imagens. Se esta opção estiver habilitada, a opção ImageCompressionOptions será ignorada. A opção deve ser habilitada manualmente ao usar o método {@code #All()} se for necessária. A conversão de páginas em imagens ocorrerá após a limpeza dos principais dados ocultos, que são controlados por outras opções.

**Returns:**
a opção de converter páginas em imagens.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

Obtém um valor que indica se os formulários no documento devem ser achatados durante o processo de sanitização. O achatamento de formulários converte campos interativos em conteúdo estático, tornando-os não editáveis ou preenchíveis.

**Returns:**
um valor que indica se os formulários no documento devem ser achatados durante o processo de sanitização.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

Obtém a opção de achatar as camadas no documento PDF. Quando habilitada, todas as camadas do documento são mescladas em uma única camada, removendo sua estrutura separada. Esta opção é útil para sanitizar documentos simplificando seu conteúdo e garantindo que nenhum dado oculto permaneça nas camadas.

**Returns:**
a opção de achatar as camadas no documento PDF.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Obtém a opção de conversão de imagens do documento. A opção deve ser habilitada manualmente ao usar o método {@code #All()} se for necessária.

**Returns:**
a opção de conversão de imagem do documento.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

Obtém a opção de resolver imagens de página durante a conversão.

**Returns:**
a opção de resolver imagens de página durante a conversão.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

Obtém um valor que indica se as anotações devem ser removidas do documento. Quando habilitado, todas as anotações presentes no documento serão removidas durante o processo de sanitização. Anotações de redação serão aplicadas.

**Returns:**
um valor que indica se as anotações devem ser removidas do documento.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

Obtém a opção de remover todos os arquivos anexados do documento. Quando habilitada, garante que quaisquer anexos dentro do PDF sejam eliminados durante o processo de sanitização.

**Returns:**
a opção de remover todos os arquivos anexados do documento.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

Obtém um valor que indica se o JavaScript e as ações associadas devem ser removidos do documento. Esta opção é útil para eliminar vulnerabilidades de segurança potenciais introduzidas por scripts incorporados.

**Returns:**
um valor que indica se o JavaScript e as ações associadas devem ser removidos do documento.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

Obtém uma opção para remover metadados do documento. Se definido como verdadeiro, metadados como propriedades do documento e informações adicionais de metadados incorporados serão removidos durante a sanitização.

**Returns:**
uma opção de remover metadados do documento.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

Obtém um valor que indica se o índice de pesquisa e as informações privadas devem ser removidos do documento. Habilita a remoção de índices de pesquisa incorporados e dados privados para melhorar a segurança e a privacidade do documento.

**Returns:**
um valor que indica se o índice de pesquisa e informações privadas devem ser removidos do documento.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

Define a opção de converter páginas em imagens. Se esta opção estiver habilitada, a opção ImageCompressionOptions será ignorada. A opção deve ser habilitada manualmente ao usar o método {@code #All()} se for necessária. A conversão de páginas em imagens ocorrerá após a limpeza dos principais dados ocultos, que são controlados por outras opções.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | a opção de converter páginas em imagens. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

Define um valor que indica se os formulários no documento devem ser achatados durante o processo de sanitização. O achatamento de formulários converte campos interativos em conteúdo estático, tornando-os não editáveis ou preenchíveis.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | um valor que indica se os formulários no documento devem ser achatados durante o processo de sanitização. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

Define a opção de achatar as camadas no documento PDF. Quando habilitada, todas as camadas do documento são mescladas em uma única camada, removendo sua estrutura separada. Esta opção é útil para sanitizar documentos simplificando seu conteúdo e garantindo que nenhum dado oculto permaneça nas camadas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | a opção de achatar as camadas no documento PDF. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Define a opção de conversão de imagens do documento. A opção deve ser habilitada manualmente ao usar o método {@code #All()} se for necessária.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

Define a opção de resolver imagens de página durante a conversão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | a opção de resolver imagens de página durante a conversão. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

Define um valor que indica se as anotações devem ser removidas do documento. Quando habilitado, todas as anotações presentes no documento serão removidas durante o processo de sanitização. Anotações de redação serão aplicadas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | um valor que indica se as anotações devem ser removidas do documento. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

Define a opção de remover todos os arquivos anexados do documento. Quando habilitada, garante que quaisquer anexos dentro do PDF sejam eliminados durante o processo de sanitização.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | a opção de remover todos os arquivos anexados do documento. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

Define um valor que indica se o JavaScript e as ações associadas devem ser removidos do documento. Esta opção é útil para eliminar vulnerabilidades de segurança potenciais introduzidas por scripts incorporados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | um valor que indica se o JavaScript e as ações associadas devem ser removidos do documento. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

Define uma opção para remover metadados do documento. Se definido como verdadeiro, metadados como propriedades do documento e informações adicionais de metadados incorporados serão removidos durante a sanitização.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | uma opção de remover metadados do documento. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

Define um valor que indica se o índice de pesquisa e informações privadas devem ser removidos do documento. Permite a remoção de índices de pesquisa incorporados e dados privados para melhorar a segurança e a privacidade do documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | um valor que indica se o índice de pesquisa e informações privadas devem ser removidos do documento. |
