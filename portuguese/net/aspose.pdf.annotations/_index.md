---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: O namespace Aspose.Pdf.Annotations fornece classes para trabalhar com vários tipos de ações, destinos e outras características do documento que tradicionalmente são chamadas de interativas, proporcionando meios para que o usuário possa se comunicar com ele.
type: docs
weight: 50
url: /pt/net/aspose.pdf.annotations/
---
O **namespace Aspose.Pdf.Annotations** fornece classes para trabalhar com vários tipos de ações, destinos e outras características do documento que tradicionalmente são chamadas de interativas, proporcionando meios para que o usuário possa se comunicar com ele.

## Classes

| Classe | Descrição |
| --- | --- |
| [ActionCollection](./actioncollection/) | Coleção de ações |
| [Annotation](./annotation/) | Classe que representa o objeto de anotação. |
| [AnnotationActionCollection](./annotationactioncollection/) | Representa a coleção de ações de anotação. |
| [AnnotationCollection](./annotationcollection/) | Classe que representa a coleção de anotações. |
| [AnnotationSelector](./annotationselector/) | Esta classe é usada para selecionar anotações usando a ideia do template Visitor. |
| [AppearanceDictionary](./appearancedictionary/) | Dicionário de aparência da anotação que especifica como a anotação deve ser apresentada visualmente na página. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Representa uma anotação de marca de sangramento. |
| [Border](./border/) | Classe que representa as características da borda da anotação. |
| [CaretAnnotation](./caretannotation/) | Classe que representa a anotação de cursor. |
| [Characteristics](./characteristics/) | Representa as características da anotação |
| [CircleAnnotation](./circleannotation/) | Classe que representa a anotação de círculo. |
| [ColorBarAnnotation](./colorbarannotation/) | Classe que representa a anotação ColorBarAnnotation. A propriedade Color é ignorada, em vez disso, usa-se a cor ColorsOfCMYK. Na criação, a proporção de largura e altura determina a orientação da anotação - horizontal ou vertical. Em seguida, verifica-se se o retângulo da anotação está fora do TrimBox, e se não estiver, ele é deslocado para a localização mais próxima fora do TrimBox, levando em conta a orientação da anotação. É possível reduzir a largura (altura) para que a anotação se encaixe fora do TrimBox. Se não houver espaço para o layout, a largura/altura pode ser definida como zero (neste caso, a anotação está presente na página, mas não é exibida). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Classe abstrata que representa a anotação de figura comum. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Representa tipos de anotações que são colocadas nos cantos da página impressa. |
| [CustomExplicitDestination](./customexplicitdestination/) | Representa um destino explícito personalizado. |
| [Dash](./dash/) | Classe que representa o padrão de linha tracejada. |
| [DefaultAppearance](./defaultappearance/) | Descreve a aparência padrão do campo (fonte, tamanho e cor do texto). |
| [DocumentActionCollection](./documentactioncollection/) | Classe que descreve ações realizadas em algumas ações com o documento |
| [ExplicitDestination](./explicitdestination/) | Representa a classe base para destinos explícitos em documentos PDF. |
| [FdfReader](./fdfreader/) | Classe que realiza a leitura do formato FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Classe que descreve a anotação de anexo de arquivo. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Representa um destino explícito que exibe a página com seu conteúdo ampliado o suficiente para caber completamente dentro da janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical exigidos forem diferentes, use o menor dos dois, centralizando a caixa delimitadora dentro da janela na outra dimensão. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Representa um destino explícito que exibe a página com a coordenada vertical superior posicionada na borda superior da janela e o conteúdo da página ampliado o suficiente para caber em toda a largura de sua caixa delimitadora dentro da janela. Um valor nulo para o topo especifica que o valor atual desse parâmetro deve ser mantido inalterado. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Representa um destino explícito que exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página ampliado o suficiente para caber em toda a altura de sua caixa delimitadora dentro da janela. Um valor nulo para a esquerda especifica que o valor atual desse parâmetro deve ser mantido inalterado. |
| [FitExplicitDestination](./fitexplicitdestination/) | Representa um destino explícito que exibe a página com seu conteúdo ampliado o suficiente para caber em toda a página dentro da janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical exigidos forem diferentes, use o menor dos dois, centralizando a página dentro da janela na outra dimensão. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Representa um destino explícito que exibe a página com a coordenada vertical superior posicionada na borda superior da janela e o conteúdo da página ampliado o suficiente para caber em toda a largura da página dentro da janela. Um valor nulo para o topo especifica que o valor atual desse parâmetro deve ser mantido inalterado. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Representa um destino explícito que exibe a página com seu conteúdo ampliado o suficiente para caber no retângulo especificado pelas coordenadas esquerda, inferior, direita e superior completamente dentro da janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical exigidos forem diferentes, use o menor dos dois, centralizando o retângulo dentro da janela na outra dimensão. Um valor nulo para qualquer um dos parâmetros pode resultar em comportamento imprevisível. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Representa um destino explícito que exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página ampliado o suficiente para caber em toda a altura da página dentro da janela. Um valor nulo para a esquerda especifica que o valor atual desse parâmetro deve ser mantido inalterado. |
| [FixedPrint](./fixedprint/) | Representa os dados de impressão fixa da Anotação de Marca d'Água. |
| [FreeTextAnnotation](./freetextannotation/) | Representa uma anotação de texto livre que exibe texto diretamente na página. Ao contrário de uma anotação de texto comum, uma anotação de texto livre não tem estado aberto ou fechado; em vez de ser exibida em uma janela pop-up, o texto está sempre visível. |
| [GoToAction](./gotoaction/) | Representa uma ação de ir para que muda a visualização para um destino especificado (página, localização e fator de ampliação). |
| [GoToRemoteAction](./gotoremoteaction/) | Representa uma ação de ir para remota que é semelhante a uma ação de ir para comum, mas salta para um destino em outro arquivo PDF em vez do arquivo atual. |
| [GoToURIAction](./gotouriaction/) | Representa uma ação URI que faz com que uma URI seja resolvida. |
| [HideAction](./hideaction/) | Representa uma ação de ocultar que oculta ou mostra uma ou mais anotações na tela, definindo ou limpando suas flags Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Representa uma anotação de destaque que destaca um intervalo de texto no documento. |
| [ImportDataAction](./importdataaction/) | Ao invocar uma ação de importação de dados, os dados do Formato de Dados de Formulários (FDF) devem ser importados para o formulário interativo do documento a partir de um arquivo especificado. |
| [InkAnnotation](./inkannotation/) | Representa um "rabisco" à mão livre composto por um ou mais caminhos desconexos. |
| [JavascriptAction](./javascriptaction/) | Classe que representa a ação javascript. |
| [LaunchAction](./launchaction/) | Representa uma ação de lançamento que inicia um aplicativo ou abre ou imprime um documento. |
| [LineAnnotation](./lineannotation/) | Classe que representa a anotação de linha. |
| [LinkAnnotation](./linkannotation/) | Representa um link de hipertexto para um destino em outro lugar no documento ou uma ação a ser realizada. |
| [MarkupAnnotation](./markupannotation/) | Classe abstrata que representa a anotação de marcação. |
| [Measure](./measure/) | Classe que descreve o sistema de coordenadas Measure. |
| [MediaClip](./mediaclip/) | Classe que descreve o objeto de clipe de mídia de rendição. |
| [MediaClipData](./mediaclipdata/) | Classe que descreve os dados do clipe de mídia. |
| [MediaClipSection](./mediaclipsection/) | Esta classe descreve a seção do clipe de mídia. |
| [MediaRendition](./mediarendition/) | Classe que descreve a rendição de mídia. |
| [MovieAnnotation](./movieannotation/) | Representa uma anotação de filme que contém gráficos animados e som a serem apresentados na tela do computador e pelos alto-falantes. Quando a anotação é ativada, o filme é reproduzido. |
| [NamedAction](./namedaction/) | Representa ações nomeadas que se espera que os aplicativos visualizadores de PDF suportem. |
| [NamedDestination](./nameddestination/) | Em vez de ser definido diretamente com a sintaxe explícita, um destino pode ser referido indiretamente por meio de um objeto de nome ou uma string de bytes. |
| [PageInformationAnnotation](./pageinformationannotation/) | Representa uma anotação de Informação da Página em um documento PDF. Esta anotação contém o nome do arquivo, número da página e a data e hora da criação da anotação. |
| [PDF3DAnnotation](./pdf3dannotation/) | Classe PDF3DAnnotation. Esta classe não pode ser herdada. |
| [PDF3DArtwork](./pdf3dartwork/) | Classe PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Classe PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Classe PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Classe PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Classe PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Classe PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Classe PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Classe PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Classe PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Classe PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Representa a Ação no documento PDF |
| [PdfActionCollection](./pdfactioncollection/) | Classe que descreve a lista de ações. |
| [PolyAnnotation](./polyannotation/) | Classe base abstrata para anotações poligonais. |
| [PolygonAnnotation](./polygonannotation/) | Classe que representa a anotação de polígono. |
| [PolylineAnnotation](./polylineannotation/) | Representa a anotação de polilinha que é semelhante ao polígono, exceto que o primeiro e o último vértice não estão implicitamente conectados. |
| [PopupAnnotation](./popupannotation/) | Representa a anotação pop-up que exibe texto em uma janela pop-up para entrada e edição. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Classe abstrata que representa a anotação de marca de impressora. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Fornece métodos de extensão para a enumeração [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Representa a anotação de Redação. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Representa uma anotação de Marca de Registro. |
| [Rendition](./rendition/) | Classe que descreve o objeto de rendição da Anotação de Rendição. |
| [RenditionAction](./renditionaction/) | Uma ação de rendição que controla a reprodução de conteúdo multimídia. |
| [RichMediaAnnotation](./richmediaannotation/) | Classe que descreve a RichMediaAnnotation que permite incorporar dados de vídeo/áudio em um documento PDF. |
| [ScreenAnnotation](./screenannotation/) | Uma anotação de tela que especifica uma região de uma página na qual clipes de mídia podem ser reproduzidos. |
| [SelectorRendition](./selectorrendition/) | Classe que descreve a rendição do seletor. |
| [SoundAnnotation](./soundannotation/) | Representa uma anotação de som que contém som gravado do microfone do computador ou importado de um arquivo. |
| [SoundData](./sounddata/) | Representa dados de som definindo o som a ser reproduzido quando a anotação é ativada. |
| [SoundSampleData](./soundsampledata/) | Representa entradas adicionais específicas para um objeto de som (Seção 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Classe que representa a anotação de quadrado. |
| [SquigglyAnnotation](./squigglyannotation/) | Representa a anotação ondulada que aparece como um sublinhado irregular no texto de um documento. |
| [StampAnnotation](./stampannotation/) | Representa a anotação de carimbo. Este tipo de anotação exibe texto ou gráficos que parecem ter sido carimbados na página com um carimbo de borracha. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Representa uma anotação de riscado que aparece como um riscado no texto do documento. |
| [SubmitFormAction](./submitformaction/) | Classe que descreve a ação de envio de formulário. |
| [TextAnnotation](./textannotation/) | Representa uma anotação de texto que é uma 'nota adesiva' anexada a um ponto no documento PDF. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Classe base abstrata para anotações de marcação de texto. |
| [TextStyle](./textstyle/) | Classe que representa o estilo do texto na anotação |
| [TrimMarkAnnotation](./trimmarkannotation/) | Representa uma anotação de Marca de Corte. |
| [UnderlineAnnotation](./underlineannotation/) | Representa uma anotação de sublinhado que aparece como um sublinhado no texto do documento. |
| [WatermarkAnnotation](./watermarkannotation/) | Classe que descreve o objeto de anotação de Marca d'Água. |
| [WidgetAnnotation](./widgetannotation/) | Classe que representa a anotação de widget. |
| [XfdfReader](./xfdfreader/) | Classe que realiza a leitura do formato XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Representa um destino explícito que exibe a página com as coordenadas (esquerda, topo) posicionadas no canto superior esquerdo da janela e o conteúdo da página ampliado pelo fator de zoom. Um valor nulo para qualquer um dos parâmetros esquerda, topo ou zoom especifica que o valor atual desse parâmetro deve ser mantido inalterado. Um valor de zoom de 0 tem o mesmo significado que um valor nulo. |
## Interfaces

| Interface | Descrição |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Define o Visitor para visitar diferentes anotações de documentos. |
| [IAppointment](./iappointment/) | Representa a interface geral para ações e destinos. |
## Enumeração

| Enumeração | Descrição |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Um conjunto de flags que especifica várias características da anotação. |
| [AnnotationState](./annotationstate/) | A enumeração de estados para os quais a anotação original pode ser definida. |
| [AnnotationStateModel](./annotationstatemodel/) | O modelo de estado correspondente ao estado da anotação. |
| [AnnotationType](./annotationtype/) | Enumeração dos tipos de anotações. |
| [BorderEffect](./bordereffect/) | Descreve o efeito que deve ser aplicado à borda das anotações. |
| [BorderStyle](./borderstyle/) | Descreve o estilo da borda da anotação. |
| [CapStyle](./capstyle/) | Estilo de término de linha da linha da anotação de tinta. |
| [CaptionPosition](./captionposition/) | Enumeração das posições da legenda da anotação. |
| [CaretSymbol](./caretsymbol/) | Um símbolo a ser associado ao cursor. |
| [ColorsOfCMYK](./colorsofcmyk/) | Cores incluídas no modelo de cor CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumera os tipos de destinos explícitos. |
| [FileIcon](./fileicon/) | Um ícone a ser usado na exibição da anotação. |
| [FreeTextIntent](./freetextintent/) | Enumera as intenções da anotação de texto livre. |
| [HighlightingMode](./highlightingmode/) | Enumera o modo de destaque da anotação, o efeito visual a ser usado quando o botão do mouse é pressionado ou mantido pressionado dentro de sua área ativa. |
| [Justification](./justification/) | Enumera as formas de justificação a serem usadas na exibição do texto da anotação. |
| [LaunchActionOperation](./launchactionoperation/) | Enumera as operações a serem realizadas com o documento durante a execução da ação de lançamento. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: conjunto de tipos de esquema de iluminação. |
| [LineEnding](./lineending/) | Enumera os estilos de término de linha a serem usados ao desenhar a linha. |
| [LineIntent](./lineintent/) | Enumera as intenções da anotação de linha. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: conjunto de modos de ativação de anotações 3D. |
| [PolyIntent](./polyintent/) | Enumera as intenções da anotação de polígono ou polilinha. |
| [PredefinedAction](./predefinedaction/) | Define diferentes ações que podem ser acionadas a partir de um arquivo PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Representa uma posição de uma marca em um canto de uma página. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Representa uma posição de uma marca de registro em uma página. |
| [PrinterMarksKind](./printermarkskind/) | Especifica os tipos de marcas de impressora a serem adicionadas a um documento. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: conjunto de tipos de modo de renderização |
| [RenditionOperation](./renditionoperation/) | A operação a ser realizada quando a ação é acionada. |
| [RenditionType](./renditiontype/) | Enumeração que descreve os possíveis tipos de Rendição. |
| [ReplyType](./replytype/) | Enumera os tipos de relacionamentos (o "tipo de resposta") entre a anotação e uma especificada por InReplyTo. |
| [SoundEncoding](./soundencoding/) | O formato de codificação para os dados de amostra. |
| [SoundIcon](./soundicon/) | Enumera os ícones a serem usados na exibição da anotação. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | O formato de codificação para os dados de amostra de som. |
| [StampIcon](./stampicon/) | Enumera os ícones a serem usados na exibição da anotação. |
| [TextIcon](./texticon/) | Enumera os ícones a serem usados na exibição da anotação. |