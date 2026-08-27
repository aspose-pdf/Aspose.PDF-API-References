---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa um objeto absorvedor de objetos de posicionamento de imagem. Executa a busca de usos de imagens e fornece acesso aos resultados da busca via {@code."
type: docs
weight: 2340
url: /pt/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> Representa um objeto absorvedor de objetos de posicionamento de imagem. Executa a busca de usos de imagens e fornece acesso aos resultados da busca via {@code ImagePlacementAbsorber.ImagePlacements} collection. </p> <hr> <pre> O exemplo demonstra como encontrar imagens na primeira página do documento PDF e obter as propriedades de posicionamento da imagem. // Abrir documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\") ; // Criar objeto ImagePlacementAbsorber para executar a busca de posicionamento de imagem ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Aceitar o absorvedor para a primeira página doc.getPages().get_Item(1).accept(abs); // Exibir propriedades de posicionamento de imagem para todos os posicionamentos for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println(\"largura da imagem:\" + imagePlacement.getRectangle().getWidth()); System.out.println(\"altura da imagem:\" + imagePlacement.getRectangle().getHeight()); System.out.println(\"LLX da imagem:\" + imagePlacement.getRectangle(0).getX()); System.out.println(\"LLY da imagem:\" + imagePlacement.getRectangle.getY()); System.out.println(\"resolução horizontal da imagem:\" + imagePlacement.getResolution().getX()); System.out.println(\"resolução vertical da imagem:\" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> O objeto {@code ImagePlacementAbsorber} é basicamente usado no cenário de busca de imagens. Quando a busca é concluída, as ocorrências são representadas com objetos {@code ImagePlacement} que a coleção {@code ImagePlacementAbsorber.ImagePlacements} contém. O objeto {@code ImagePlacement} fornece acesso às propriedades de posicionamento da imagem: dimensões, resolução etc. </p> A rotação positiva da imagem é no sentido anti-horário; para a página, é no sentido horário. Aqui, precisamos representar o ângulo de rotação da imagem, portanto subtraímos o ângulo da página do ângulo da imagem.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | Inicializa uma nova instância do objeto {@code ImagePlacementAbsorber}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | Obtém a coleção de ocorrências de posicionamento de imagem que são apresentadas com objetos {@code ImagePlacement}. |
| [isReadOnlyMode](#isReadOnlyMode--) | Obtém/define o modo somente leitura para a coleção de operações de análise. Pode ajudar a evitar exceções de falta de memória. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | Obtém/define o modo somente leitura para a coleção de operações de análise. Pode ajudar a evitar exceções de falta de memória. |
| [visit](#visit-com.aspose.pdf.IDocument-) | Executa a busca no documento especificado. |
| [visit](#visit-com.aspose.pdf.Page-) | Executa a pesquisa na página especificada. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

Inicializa uma nova instância do objeto {@code ImagePlacementAbsorber}.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

Obtém a coleção de ocorrências de posicionamento de imagem que são apresentadas com objetos {@code ImagePlacement}.

**Returns:**
Objeto ImagePlacementCollection

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

Obtém/define o modo somente leitura para a coleção de operações de análise. Pode ajudar a evitar exceções de falta de memória.

**Returns:**
valor booleano

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

Obtém/define o modo somente leitura para a coleção de operações de análise. Pode ajudar a evitar exceções de falta de memória.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### visit {#visit-com.aspose.pdf.IDocument-}
Executa a busca no documento especificado.

### visit {#visit-com.aspose.pdf.Page-}
Executa a pesquisa na página especificada.
