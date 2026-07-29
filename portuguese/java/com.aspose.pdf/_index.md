---
title: "com.aspose.pdf"
second_title: "Referência da API Aspose.PDF para Java"
description: "O com.aspose.pdf é um pacote raiz para todas as classes da biblioteca Aspose.PDF para Java que estão diretamente nele, como Document, ou indiretamente através de vários subpacotes."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf/
---
O com.aspose.pdf é um pacote raiz para todas as classes da biblioteca Aspose.PDF para Java que estão diretamente nele, como Document, ou indiretamente através de vários subpacotes.

## Interfaces

| Interface | Descrição |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | O procedimento de retorno de chamada para reconhecimento hocr. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | O procedimento de retorno de chamada para reconhecimento hocr. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | O procedimento de retorno de chamada para reconhecimento hocr. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | Contém funcionalidade para ajustar fontes |
| [IAnnotationVisitor](./iannotationvisitor/) | Define Visitor para visitar diferentes anotações de documento. |
| [IAppointment](./iappointment/) | Representa interface geral para ações e destinos. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Interface para estratégias de conversão de espaço de cores. |
| [IDocument](./idocument/) | interface que representa documento PDF |
| [IFontOptions](./ifontoptions/) | Propriedades úteis para ajustar o comportamento da fonte |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | Esta interface foi declarada para algoritmos de personalização de quantização. Usuários podem implementar sua própria realização desses algoritmos (por exemplo, algoritmos baseados em código não gerenciado). |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | Esta interface foi declarada para algoritmos de personalização de quantização. Usuários podem implementar sua própria realização desses algoritmos (por exemplo, algoritmos baseados em código não gerenciado). |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | Define Visitor para visitar diferentes operadores pdf. |
| [IPageSetOptions](./ipagesetoptions/) | Define opções de conversão relacionadas a um conjunto de páginas a converter. |
| [IPipelineOptions](./ipipelineoptions/) | Define opções de conversão relacionadas à configuração do pipeline. |
| [ITableElement](./itableelement/) | Esta interface representa um elemento de tabela existente extraído pelo TableAbsorber. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | Às vezes é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSS) e fornecer um método personalizado, que obterá os recursos solicitados de algum lugar. Por exemplo, durante o uso do Aspose.PDf na nuvem, o acesso direto aos arquivos referenciados é impossível, e algum código personalizado colocado em um método especial deve ser usado. Este delegate define a assinatura de tal método personalizado. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * Defina a bandeira se a pasta temporária será usada para hospedar dados de fontes temporárias. / * Verdadeiro por padrão. / * Usa memória heap se o valor = false; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | Para a propriedade desse tipo, você pode atribuir um delegate criado a partir de um método personalizado que implementa o processamento de salvamento externo de uma imagem que foi extraída de um SVG criado a partir de PDF e deve ser salva como recurso externo durante a conversão de PDF para HTML. Nesse caso, o processamento (como salvamento feito manualmente em um stream ou em disco) pode ser feito nesse código personalizado e esse código deve retornar o caminho (ou qualquer outra string sem aspas) que será posteriormente incorporado ao SVG gerado em vez do caminho original suposto para esse recurso de imagem. Nesse caso, todas as ações necessárias para salvar a imagem devem ser realizadas no código do método fornecido, pois o salvamento do resultado no código do conversor não será utilizado. Se o processamento deste ou daquele arquivo, por algum motivo, precisar ser feito pelo próprio código do conversor, e não no código personalizado, por favor defina no código personalizado a bandeira 'CustomProcessingCancelled' da variável do parâmetro 'imageSavingInfo'. Isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas no próprio conversor como se não houvesse nenhum código personalizado externo. |
## Classes

| Classe | Descrição |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Representa uma célula de tabela que existe na página |
| [AbsorbedRow](./absorbedrow/) | Representa uma linha de tabela que existe na página |
| [AbsorbedTable](./absorbedtable/) | Representa uma tabela que existe na página |
| [ActionCollection](./actioncollection/) | Coleção de ações |
| [Annotation](./annotation/) | Classe que representa um objeto de anotação. |
| [AnnotationActionCollection](./annotationactioncollection/) | Representa a coleção de ações de anotação. |
| [AnnotationCollection](./annotationcollection/) | Classe que representa a coleção de anotações. |
| [AnnotationFlags](./annotationflags/) | Flags Um conjunto de bandeiras binárias que especificam várias características da anotação. |
| [AnnotationSelector](./annotationselector/) | Esta classe é usada para selecionar anotações usando a ideia de template Visitor. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | Classe para renderizar texto normal e rico. |
| [AppearanceDictionary](./appearancedictionary/) | Dicionário de aparência da anotação que especifica como a anotação deve ser apresentada visualmente na página. |
| [ApsLoadOptions](./apsloadoptions/) | Classe que descreve opções de carregamento APS. Opção para importação do formato APS XML. |
| [ApsSaveOptions](./apssaveoptions/) | Opções de salvamento para exportação para o formato APS XML. |
| [ApsToFlowConverter](./apstoflowconverter/) | Conversão de APS para Flow |
| [Artifact](./artifact/) | Classe que representa um objeto PDF Artifact. |
| [ArtifactCollection](./artifactcollection/) | Classe que representa a coleção de artefatos. |
| [AutoTaggingSettings](./autotaggingsettings/) | Fornece configurações para a funcionalidade de autoetiquetagem em documentos PDF. A classe {@link AutoTaggingSettings} permite configurar opções para a etiquetagem automática do conteúdo PDF. Ela inclui propriedades para habilitar ou desabilitar a autoetiquetagem, especificar uma estratégia para reconhecimento de títulos e definir níveis de título com base no tamanho das fontes. |
| [BackgroundArtifact](./backgroundartifact/) | Classe que descreve o artefato de fundo. Este artefato permite definir o plano de fundo da página. |
| [BarcodeField](./barcodefield/) | Classe que representa um campo de código de barras. |
| [BaseActionCollection](./baseactioncollection/) | Classe que encapsula ações básicas com ações interativas de página/anotação/campo |
| [BaseOperatorCollection](./baseoperatorcollection/) | Representa a classe base para a coleção de operadores. |
| [BaseParagraph](./baseparagraph/) | Representa um objeto base abstrato que pode ser adicionado à página (doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | Classe descreve o artefato de numeração Bates. |
| [BitmapInfo](./bitmapinfo/) | Objeto contendo array de pixels e informações de bitmap. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | Formato de pixel de bitmap. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Representa uma anotação de Marca de Sangria. As marcas de sangria são colocadas nos cantos de uma página impressa para indicar onde a página deve ser recortada e até que ponto pode se desviar das marcas de corte. |
| [Border](./border/) | Classe que representa as características da borda da anotação. |
| [BorderInfo](./borderinfo/) | Esta classe representa a borda para elementos gráficos. |
| [BorderSide](./borderside/) | Flags enumera os lados da borda em binário. |
| [BorderStyleConverter](./borderstyleconverter/) | Representa a classe BorderStyleConverter |
| [Brush](./brush/) | Esta classe representa um pincel abstrato |
| [BuildVersionInfo](./buildversioninfo/) | Esta classe fornece informações sobre a compilação atual do produto. |
| [ButtonField](./buttonfield/) | Classe representa um campo de botão de pressão. |
| [CaretAnnotation](./caretannotation/) | Classe que representa a anotação Caret. |
| [CaretSymbolConverter](./caretsymbolconverter/) | Representa a classe CaretSymbolConverter |
| [CdrLoadOptions](./cdrloadoptions/) | Classe descreve as opções de carregamento CDR. |
| [Cell](./cell/) | Representa uma célula da linha da tabela. |
| [Cells](./cells/) | Representa uma coleção de células da linha. |
| [CgmImportOptions](./cgmimportoptions/) | Opção de importação para importação do formato Computer Graphics Metafile (CGM). |
| [CgmLoadOptions](./cgmloadoptions/) | Contém opções para carregar/importar arquivo CGM em documento PDF. |
| [Characteristics](./characteristics/) | Representa as características da anotação |
| [CharInfo](./charinfo/) | Representa um objeto de informações de caractere. Fornece informações de posicionamento de caracteres. |
| [CharInfoCollection](./charinfocollection/) | <p> Representa a coleção de objetos CharInfo. </p> <hr> <pre> O exemplo demonstra como iterar por todos os caracteres e recuperar o caractere //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println(\"XIndent : \" + charInfo.getPosition().getXIndent()); System.out.println(\"YIndent : \" + charInfo.getPosition().getYIndent()); System.out.println(\"Width : \" + charInfo.getRectangle().getWidth()); System.out.println(\"Height : \" + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Fornece acesso às informações de posicionamento dos caracteres do segmento de texto. </p> |
| [CheckboxField](./checkboxfield/) | Classe que representa um campo de caixa de seleção. |
| [ChoiceField](./choicefield/) | Representa a classe base para campos de escolha. |
| [CircleAnnotation](./circleannotation/) | Classe que representa a anotação de Círculo. |
| [Collection](./collection/) | Representa a classe para Collection(12.3.5 Collections). |
| [CollectionField](./collectionfield/) | Representa uma classe de campo de esquema de coleção de documentos. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Representa o parâmetro de subtipo de um campo em uma coleção de esquema. |
| [CollectionItem](./collectionitem/) | Representa uma classe de item de coleção. O item de coleção contém os dados descritos pelo esquema da coleção. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | Representa uma classe para um valor de item de coleção. |
| [CollectionSchema](./collectionschema/) | Representa uma classe que descreve o "Schema" de uma coleção de documentos. |
| [Color](./color/) | Representa uma classe para valor de cor que pode ser expressado em diferentes espaços de cor. |
| [ColorBarAnnotation](./colorbarannotation/) | Classe que representa a anotação ColorBarAnnotation. A propriedade Color é ignorada, sendo usado o color ColorsOfCMYK. Na criação, a proporção entre largura e altura determina a orientação da anotação – horizontal ou vertical. Em seguida, verifica se o retângulo da anotação está fora da TrimBox e, caso não esteja, ele é deslocado para a posição mais próxima fora da TrimBox, levando em conta a orientação da anotação. É possível reduzir a largura (altura) para que a anotação caiba fora da TrimBox. Se não houver espaço para o layout, a largura/altura pode ser definida como zero (neste caso, a anotação está presente na página, mas não é exibida). |
| [ColumnInfo](./columninfo/) | Esta classe representa as informações de uma coluna. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | Classe que representa eventos |
| [ComboBoxField](./comboboxfield/) | Classe que representa o campo Combobox do formulário. |
| [ComHelper](./comhelper/) | <p> Fornece métodos para clientes COM carregarem um documento no Aspose.PDF. </p> <hr> <p> Use a classe ComHelper para carregar um documento de um arquivo ou fluxo em um objeto Document em uma aplicação COM. A classe Document fornece um construtor padrão para criar um novo documento e também fornece construtores sobrecarregados para carregar um documento de um arquivo ou fluxo. Se você estiver usando Aspose.Words a partir de uma aplicação .NET, pode usar todos os construtores de Document diretamente, mas se estiver usando Aspose.PDF a partir de uma aplicação COM, apenas o construtor padrão de Document está disponível. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | Classe abstrata que representa anotação de figura comum. |
| [CompositingParameters](./compositingparameters/) | Representa um objeto contendo parâmetros de composição gráfica do estado gráfico atual. |
| [ContentsAppender](./contentsappender/) | Executa modificações de conteúdo apenas no modo APPEND. Este modo permite evitar a análise desnecessária e pesada do conteúdo antes de qualquer alteração ser feita. Ele apenas adiciona novos operadores ao final ou ao início do conteúdo. |
| [Copier](./copier/) | Classe para copiar objeto |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Representa tipos de anotação que são posicionados nos cantos da página impressa. |
| [CustomExplicitDestination](./customexplicitdestination/) | Representa um destino explícito personalizado. |
| [CustomSign](./customsign/) | Delegate para assinatura personalizada do documento (Beta). |
| [Dash](./dash/) | Classe que representa o padrão de traço de linha. |
| [DateField](./datefield/) | Campo de data com visualização de calendário. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | Descreve a aparência padrão do campo (fonte, tamanho do texto e cor). |
| [DefaultDirectory](./defaultdirectory/) | Especifica o caminho padrão para algum propósito |
| [DestinationCollection](./destinationcollection/) | Classe que representa a coleção de todos os destinos (uma árvore de nomes que mapeia strings de nomes para destinos (veja 12.3.2.3, "Named Destinations") e (veja 7.7.4, "Name Dictionary")) no documento PDF. |
| [DestinationFactory](./destinationfactory/) | Representa a classe DestinationFactory |
| [DjvuLoadOptions](./djvuloadoptions/) | Classe que descreve as opções de carregamento DJVU. |
| [DocMDPSignature](./docmdpsignature/) | Representa a classe de assinatura do tipo MDP (detecção e prevenção de modificação) de documento. |
| [DocSaveOptions](./docsaveoptions/) | Opções de salvamento para exportação para o formato Doc |
| [Document](./document/) | Classe que representa um documento PDF. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | Classe que descreve o algoritmo de otimização de documento. Uma instância desta classe pode ser usada como parâmetro do método OptimizeResources(). @deprecated Esta classe está obsoleta. Por favor, use com.aspose.pdf.optimization.OptimizationOptions em vez disso. |
| [Document.RepairOptions](./document.repairoptions/) | Representa opções para reparar um documento PDF. Esta classe fornece uma forma de personalizar o processo de reparo de um documento PDF. |
| [DocumentActionCollection](./documentactioncollection/) | Classe que descreve ações realizadas em algumas operações com o documento |
| [DocumentExtensions](./documentextensions/) | Fornece capacidades adicionais para a classe Document. |
| [DocumentFactory](./documentfactory/) | Classe que permite criar/carregar documentos de diferentes tipos. |
| [DocumentInfo](./documentinfo/) | Representa as metainformações de um documento PDF. |
| [DocumentWeb](./documentweb/) | Representa a classe DocumentWeb |
| [Element](./element/) | Classe que representa o elemento base da estrutura lógica. |
| [ElementCollection](./elementcollection/) | Coleção de elementos base da estrutura lógica. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Classe que representa a coleção de arquivos incorporados. |
| [EncryptedPayload](./encryptedpayload/) | Representa a carga útil criptografada na especificação de arquivo. |
| [EpubLoadOptions](./epubloadoptions/) | Contém opções para carregar/importar arquivo EPUB em um documento PDF. |
| [EpubSaveOptions](./epubsaveoptions/) | Opções de salvamento para exportação para o formato EPUB |
| [ExcelSaveOptions](./excelsaveoptions/) | Opções de salvamento para exportação para o formato Excel |
| [ExplicitDestination](./explicitdestination/) | Representa a classe base para destinos explícitos em um documento PDF. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | Representa a classe ExplicitDestinationTypeConverter |
| [ExportFieldsOptions](./exportfieldsoptions/) | Representa a classe base de opções para exportação de campos de formulário. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Representa opções para exportar campos de formulário para o formato Json. Herda de {@link ExportFieldsOptions} e adiciona opções específicas para exportação Json. |
| [ExportImportMessages](./exportimportmessages/) | Contém várias mensagens de erro para operações de exportação e importação de campos de formulário. |
| [ExternalSignature](./externalsignature/) | Cria uma assinatura PKCS#7Detached destacada usando um X509Certificate2. Suporta smartcards USB, tokens sem chaves privadas exportáveis. |
| [FdfReader](./fdfreader/) | Classe que realiza a leitura do formato FDF. Document doc = new Document(\"example.pdf\"); InputStream fdfStream = FileInputStream(\"file.fdf\"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save(\"example_out.pdf\"); |
| [Field](./field/) | Classe base para campos de formulário Acro. |
| [FieldSerializationResult](./fieldserializationresult/) | Representa o resultado de um processo de serialização de campo de formulário. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Representa o status da serialização de campo de formulário. |
| [FieldValueType](./fieldvaluetype/) | Representa o tipo de valor de campo em uma coleção de esquema. |
| [FigureElement](./figureelement/) | Classe que representa a figura de estrutura lógica. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Classe que descreve a anotação de anexo de arquivo. |
| [FileFontSource](./filefontsource/) | Representa a fonte de arquivo de fonte única. |
| [FileHyperlink](./filehyperlink/) | Representa o objeto de hyperlink de arquivo. |
| [FileIconConverter](./fileiconconverter/) | Representa a classe FileIconConverter |
| [FileParams](./fileparams/) | Define um dicionário de parâmetros de arquivo incorporado que deve conter informações adicionais específicas do arquivo. |
| [FileSelectBoxField](./fileselectboxfield/) | Campo para elemento de caixa de seleção de arquivo. |
| [FileSpecification](./filespecification/) | Classe que representa um arquivo incorporado. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Representa um destino explícito que exibe a página com seu conteúdo ampliado apenas o suficiente para que sua caixa delimitadora caiba totalmente na janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando a caixa delimitadora na janela na outra dimensão. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Representa um destino explícito que exibe a página com a coordenada vertical superior posicionada na borda superior da janela e o conteúdo da página ampliado apenas o suficiente para que toda a largura de sua caixa delimitadora caiba na janela. Um valor nulo para top indica que o valor atual desse parâmetro deve ser mantido inalterado. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Representa um destino explícito que exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página ampliado apenas o suficiente para que toda a altura de sua caixa delimitadora caiba na janela. Um valor nulo para left indica que o valor atual desse parâmetro deve ser mantido inalterado. |
| [FitExplicitDestination](./fitexplicitdestination/) | Representa um destino explícito que exibe a página com seu conteúdo ampliado apenas o suficiente para que a página inteira caiba na janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando a página na janela na outra dimensão. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Representa um destino explícito que exibe a página com a coordenada vertical superior posicionada na borda superior da janela e o conteúdo da página ampliado apenas o suficiente para que toda a largura da página caiba na janela. Um valor nulo para top indica que o valor atual desse parâmetro deve ser mantido inalterado. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Representa um destino explícito que exibe a página com seu conteúdo ampliado apenas o suficiente para que o retângulo especificado pelas coordenadas left, bottom, right e top caiba totalmente na janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando o retângulo na janela na outra dimensão. Um valor nulo para qualquer um dos parâmetros pode resultar em comportamento imprevisível. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Representa um destino explícito que exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página ampliado apenas o suficiente para que toda a altura da página caiba na janela. Um valor nulo para left indica que o valor atual desse parâmetro deve ser mantido inalterado. |
| [FixedPrint](./fixedprint/) | Representa dados de impressão fixa da anotação de marca d'água. |
| [FloatingBox](./floatingbox/) | Representa um FloatingBox em um documento PDF. O FloatingBox tem posição personalizada. |
| [FlowConverter](./flowconverter/) | Converte documento PDF para formatos Flow (XLSX, ODS, XMLSpreedSheet2003, CSV) DOCX no modo EnchanedFlow, TableAbsorber no modo FlowEngine. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Passando dados da biblioteca Flow para TableAbsorber |
| [FolderFontSource](./folderfontsource/) | Representa a pasta que contém arquivos de fonte. |
| [Font](./font/) | <p> Representa objeto de fonte. </p> <hr> <pre> O exemplo demonstra como pesquisar texto na primeira página e alterar a fonte da primeira ocorrência encontrada. // Abrir documento Document doc = new Document("input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Criar fonte e marcá-la para incorporação Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Salvar documento doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | Representa um objeto absorvedor de fontes. Executa a pesquisa de fontes e fornece acesso aos resultados da pesquisa via coleção {@code FontAbsorber.Fonts}. |
| [FontCollection](./fontcollection/) | <p> Representa coleção de fontes. </p> <hr> <pre> O exemplo demonstra como tornar todas as fontes declaradas na página incorporadas. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // garantir que todas as fontes declaradas nos recursos da página sejam incorporadas // observar que se as fontes forem declaradas nos recursos de formulário elas não são acessíveis a partir dos recursos da página for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\\\Tests\\\\input.pdf"); </pre> <hr> <p> Coleções de fontes representadas pela classe {@code FontCollection} são usadas em vários cenários. Por exemplo, em recursos com a propriedade {@code Resources.Fonts}. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | O padrão PDF/A requer que todas as fontes sejam incorporadas ao documento. Esta classe inclui sinalizadores para casos em que não é possível incorporar alguma fonte porque essa fonte está ausente no PC de destino. |
| [FontRepository](./fontrepository/) | <p> Executa pesquisa de fontes. Pesquisa nas fontes instaladas no sistema e nas fontes padrão do PDF. Também fornece funcionalidade para abrir fontes personalizadas. </p> <hr> <pre> O exemplo demonstra como encontrar uma fonte e substituir a fonte do texto da primeira página. // Encontrar fonte Font font = FontRepository.findFont("Arial"); // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Salvar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | Representa uma classe base para a origem de fontes. |
| [FontStyles](./fontstyles/) | Binary Flag <p> Especifica informações de estilo aplicadas ao texto. </p> <hr> <p> Esta enumeração tem um atributo {@code FlagsAttribute} que permite a combinação de seus valores de membros. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag enumera estratégias para subdefinição de fontes |
| [FooterArtifact](./footerartifact/) | Descreve o artefato de rodapé. Isso pode ser usado para definir o rodapé da página. |
| [Form](./form/) | Classe que representa o objeto de formulário. |
| [Form.FlattenSettings](./form.flattensettings/) | Classe que descreve as configurações para o procedimento de achatamento de Formulário. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | Formulários podem conter informações de assinatura e podem estar assinados ou não assinados. Às vezes, a visualização dos formulários no visualizador deve depender de o formulário estar assinado ou não. Esta enumeração enumera os modos de renderização possíveis durante a conversão do tipo de formulário em relação à assinatura. |
| [FormattedFragment](./formattedfragment/) | Representa fragmento formatado abstrato. |
| [FreeTextAnnotation](./freetextannotation/) | Representa uma anotação de texto livre que exibe texto diretamente na página. Ao contrário de uma anotação de texto comum, uma anotação de texto livre não tem estado aberto ou fechado; em vez de ser exibida em uma janela pop-up, o texto está sempre visível. |
| [GoToAction](./gotoaction/) | Representa uma ação ir-para que altera a visualização para um destino especificado (página, localização e fator de ampliação). |
| [GoToRemoteAction](./gotoremoteaction/) | Representa uma ação ir-para remota que é semelhante a uma ação ir-para comum, mas salta para um destino em outro arquivo PDF em vez do arquivo atual. |
| [GoToURIAction](./gotouriaction/) | Representa uma ação URI que faz com que um URI seja resolvido. |
| [GraphInfo](./graphinfo/) | Representa informações gráficas. |
| [Group](./group/) | Uma classe de atributos de grupo que especifica os atributos do grupo de páginas da página para uso no modelo de imagem transparente. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | A classe descreve o artefato Heaader. Este artifacgt pode ser usado para definir o cabeçalho da página. |
| [HeaderFooter](./headerfooter/) | A classe representa a página PDF de cabeçalho ou rodapé. |
| [Heading](./heading/) | Representa o cabeçalho. |
| [HideAction](./hideaction/) | Representa uma ação de ocultar que esconde ou mostra uma ou mais anotações na tela definindo ou limpando seus sinalizadores Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Representa uma anotação de destaque que realça um intervalo de texto no documento. |
| [HtmlFragment](./htmlfragment/) | Representa um fragmento HTML. |
| [HtmlLoadOptions](./htmlloadoptions/) | Representa opções para carregar/importar arquivo HTML em documento PDF. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Flag Binária especifica sinalizadores que, juntamente com outras opções, determinam tamanhos e layouts das páginas. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Opções de salvamento para exportação para o formato HTML |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | Este enum descreve as possíveis medidas de antialiasing durante a conversão |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | Esta classe representa um conjunto de dados relacionados ao salvamento personalizado de CSS durante a conversão de PDF para formato HTML |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | Você pode atribuir a esta propriedade uma estratégia personalizada que implemente o processamento e/ou salvamento de uma parte de CSS que foi criada durante a conversão de PDF para HTML. Nesse caso, o processamento (como salvar em fluxo ou disco) deve ser feito nesse código personalizado |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | Você pode atribuir a esta propriedade um delegate criado a partir de um método personalizado que implemente a criação da URL do CSS referenciado no documento HTML gerado. Por exemplo, se você quiser que o CSS seja referenciado no HTML como "otherPage.ASPX?CssID=zjjkklj", então essa estratégia personalizada deve retornar "otherPage.ASPX?CssID=zjjkklj" |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | Representa um conjunto de dados relacionados à solicitação do conversor ao código personalizado destinada a obter a URL desejada (ou modelo de URL) do CSS em questão |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | Esta enumeração define regras que ajustam a lógica de codificação |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | Enumera modos que podem ser usados para salvar fontes referenciadas no PDF salvo. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de imagem de recursos externos durante a conversão de PDF para HTML. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | Enumera os tipos possíveis de arquivos de imagem que podem ser salvos como recursos externos durante a conversão de PDF para HTML. |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | Às vezes, requisitos específicos para o HTML criado estão presentes. Este enum define modos de preparação de HTML que podem ser usados durante a conversão de PDF para HTML para atender a esses requisitos específicos. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | Se a propriedade SplitToPages de HtmlSaveOptions estiver habilitada, vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão de PDF para HTML. Esta classe representa um conjunto de dados relacionados ao salvamento personalizado da marcação de uma página HTML durante a conversão de PDF para HTML. |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | O resultado da conversão pode conter uma ou várias páginas HTML (que também podem referenciar arquivos externos como imagens ou fontes). Você pode atribuir a esta propriedade um delegate criado a partir de um método personalizado que implemente o processamento da página HTML obtida (HTML em si) que foi criada durante a conversão. Nesse caso, o processamento (como salvar em fluxo ou disco) pode ser feito nesse código personalizado. Nesse caso, todas as ações necessárias para salvar a marcação da página HTML devem ser realizadas no código do método fornecido, pois a gravação do resultado no código do conversor não será utilizada. Se o processamento para este ou aquele caso, por algum motivo, precisar ser feito pelo próprio código do conversor, e não no código personalizado, defina no código personalizado a bandeira 'CustomProcessingCancelled' da variável do parâmetro 'htmlSavingInfo': isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas no próprio conversor, da mesma forma como se não houvesse nenhum código de salvamento personalizado externo. |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | Enumera os tipos possíveis de pais de imagem; a imagem pode pertencer a uma página HTML ou a uma imagem pai SVG. |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | Este enum enumera os modos possíveis de incorporação de arquivos referenciados em HTML. Ele permite controlar se os arquivos referenciados (HTML, fontes, imagens, CSS) serão incorporados ao arquivo HTML principal ou serão gerados como entidades binárias separadas. |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | Um PDF convertido pode conter imagens raster (.png, *.jpeg etc.). Este enum define os métodos de como as imagens raster podem ser tratadas durante a conversão de PDF para HTML. |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | Para esta propriedade você pode atribuir um delegate criado a partir de um método personalizado que implementa o processamento de recurso externo (Fonte ou Imagem) que foi extraído do PDF e deve ser salvo como recurso externo durante a conversão de PDF para HTML. Nesse caso, o processamento (como salvar em stream ou disco) pode ser feito nesse código personalizado e esse código deve retornar o caminho (ou qualquer outra string sem aspas) que será posteriormente incorporado ao HTML gerado em vez do caminho original suposto para esse recurso de imagem. Nesse caso, todas as ações necessárias para salvar a imagem devem ser realizadas no código do método fornecido, pois a gravação do resultado no código do conversor não será utilizada. Se o processamento deste ou daquele arquivo, por algum motivo, precisar ser feito pelo código do conversor próprio, e não pelo código personalizado, defina no código personalizado a bandeira 'CustomProcessingCancelled' da variável do parâmetro 'resourceSavingInfo'. Ela sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas no próprio conversor como se não houvesse nenhum código personalizado externo. |
| [Hyperlink](./hyperlink/) | Representa um hiperlink abstrato. |
| [IconFit](./iconfit/) | Descreve como o ícone da anotação de widget deve ser exibido dentro de seu retângulo de anotação. |
| [Id](./id/) | <p> Representa a estrutura de identificador de arquivo. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | Representa uma imagem. |
| [ImageDeleteAction](./imagedeleteaction/) | Ação que é executada com o objeto de imagem quando a imagem é removida da coleção. Se o objeto de imagem for removido |
| [ImagePlacement](./imageplacement/) | <p> Representa as características de uma imagem colocada em uma página de documento PDF. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Quando uma imagem é colocada em uma página, ela pode ter dimensões diferentes das dimensões físicas definidas em {@code Resources}. O objeto {@code ImagePlacement} tem a finalidade de fornecer tais informações, como dimensões, resolução e assim por diante. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> Representa um objeto absorvedor de objetos de posicionamento de imagem. Executa a busca de usos de imagens e fornece acesso aos resultados da busca via coleção {@code ImagePlacementAbsorber.ImagePlacements}. </p> <hr> <pre> O exemplo demonstra como encontrar imagens na primeira página do documento PDF e obter as propriedades de posicionamento da imagem. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> O objeto {@code ImagePlacementAbsorber} é basicamente usado no cenário de busca de imagens. Quando a busca é concluída, as ocorrências são representadas por objetos {@code ImagePlacement} que a coleção {@code ImagePlacementAbsorber.ImagePlacements} contém. O objeto {@code ImagePlacement} fornece acesso às propriedades de posicionamento da imagem: dimensões, resolução etc. </p> A rotação positiva da imagem é no sentido anti-horário, para a página, é no sentido horário. Aqui, precisamos representar o ângulo de rotação da imagem, então subtraímos o ângulo da página do ângulo da imagem. |
| [ImagePlacementCollection](./imageplacementcollection/) | Representa uma coleção de posicionamentos de imagem |
| [ImageStamp](./imagestamp/) | Representa um selo gráfico. |
| [ImageType](./imagetype/) | Representa tipos de formato de imagem. |
| [ImportDataAction](./importdataaction/) | Ao invocar uma ação de importação de dados, os dados do Forms Data Format (FDF) deverão ser importados para o formulário interativo do documento a partir de um arquivo especificado. |
| [ImportFieldsOptions](./importfieldsoptions/) | Representa a classe base de opções para importação de campos de formulário. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Representa opções para importação de campos de formulário para o formato Json. Herda de {@code ImportFieldsOptions} e adiciona opções específicas para importação Json. |
| [ImportOptions](./importoptions/) | O tipo ImportOptions mantém um nível de abstração sobre opções individuais de importação. |
| [InkAnnotation](./inkannotation/) | Representa um \"rabisco\" à mão livre composto por um ou mais caminhos desconexos. |
| [InternalHelper](./internalhelper/) | Classe interna |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | A exceção que é lançada quando uma operação com tipo de formulário não é válida. |
| [JavascriptAction](./javascriptaction/) | Classe que representa uma ação javascript. |
| [JavaScriptCollection](./javascriptcollection/) | Esta classe representa uma coleção de JavaScript. |
| [LatexFragment](./latexfragment/) | Representa um fragmento TeX. @deprecated Por favor, use TeXFragment em vez disso |
| [LatexLoadOptions](./latexloadoptions/) | Representa opções para carregar/importar arquivo TeX em um documento PDF. @deprecated Use TeXLoadOptions em vez disso. |
| [LaTeXSaveOptions](./latexsaveoptions/) | Opções de salvamento para exportação para o formato TeX. @deprecated Use TeXSaveOptions em vez disso |
| [LaunchAction](./launchaction/) | Representa uma ação de lançamento que inicia um aplicativo ou abre ou imprime um documento. |
| [Layer](./layer/) | Representa uma camada dentro de uma página PDF. |
| [LevelFormat](./levelformat/) | Representa o formato do índice. |
| [License](./license/) | Fornece métodos para licenciar o componente. Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na pasta que contém o assembly chamador, na pasta do assembly de entrada e então nos recursos incorporados do assembly chamador. License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | Representa informações de licença. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | Coleção de operadores leve. Destinada a ser usada em cenários onde o fluxo de conteúdo subjacente não está anexado, e apenas a coleção de operadores é necessária como resultado. |
| [LineAnnotation](./lineannotation/) | Classe que representa anotação de linha. |
| [LineEndingConverter](./lineendingconverter/) | Representa a classe LineEndingConverter |
| [LineEndingsDrawer](./lineendingsdrawer/) | Desenha terminações de linha para anotações. Classe interna apenas para uso interno. |
| [LinkAnnotation](./linkannotation/) | Representa um link hipertexto para um destino em outra parte do documento ou uma ação a ser executada. |
| [ListBoxField](./listboxfield/) | A classe representa o campo ListBox. |
| [LoadOptions](./loadoptions/) | O tipo LoadOptions contém nível de abstração nas opções de carregamento individuais. |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | Representa o modo de uso da área de margens durante a conversão (como HTML, EPUB etc.), define o tratamento das instruções do formato importado relacionadas ao uso das margens. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | ATTENTION! A funcionalidade foi implementada, mas ainda não foi disponibilizada na API pública devido a um problema bloqueador na camada OSHARED revelado para o documento de exemplo. Representa o modo de uso do tamanho da página durante a conversão. Formatos (como HTML, EPUB etc.) geralmente têm design fluido, portanto permitem ajustar o tamanho da página necessário. Mas às vezes o conteúdo especifica posições horizontais ou tamanho que não permitem colocar o conteúdo no tamanho de página requerido. Nesse caso podemos definir o que deve ser feito (por exemplo, quando o tamanho do conteúdo não cabe no tamanho de página inicial requerido do documento PDF resultante). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | Resultado do carregamento personalizado do recurso. |
| [LocaleOptions](./localeoptions/) | O tipo LocaleOptions especifica a configuração de localidade para Aspose.PDF. |
| [LocalHyperlink](./localhyperlink/) | Representa um objeto de hiperlink local. |
| [MarginInfo](./margininfo/) | Esta classe representa uma margem para diferentes objetos. |
| [MarkupAnnotation](./markupannotation/) | Classe abstrata que representa anotação de marcação. |
| [MarkupParagraph](./markupparagraph/) | Representa um parágrafo. |
| [MarkupSection](./markupsection/) | Representa uma seção de marcação – a região retangular de uma página que contém texto e pode ser visualmente separada de outros blocos de texto. |
| [Matrix](./matrix/) | Classe que representa a matriz de transformação. |
| [Matrix3D](./matrix3d/) | Classe que representa a matriz de transformação. |
| [MdLoadOptions](./mdloadoptions/) | Opções de carregamento para conversão de formato Markdown. |
| [Measure](./measure/) | Classe que descreve o sistema de coordenadas Measure. |
| [Measure.NumberFormat](./measure.numberformat/) | Formato numérico para medida. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | Representa uma lista de formatos numéricos. |
| [MediaClip](./mediaclip/) | Classe que descreve o objeto de clipe de mídia da renderização. |
| [MediaClipData](./mediaclipdata/) | Classe que descreve os dados do clipe de mídia. |
| [MediaClipSection](./mediaclipsection/) | Esta classe descreve a seção de clipe de mídia. |
| [MediaRendition](./mediarendition/) | Classe que descreve a renderização de mídia. |
| [MemoryCleaner](./memorycleaner/) | Representa a classe MemoryCleaner. |
| [MemoryExtender](./memoryextender/) | Representa a classe MemoryExtender. Ao usar arquivos grandes em um sistema com memória heap limitada, pode ser habilitado para usar espaço em disco como memória swap temporária. |
| [MemoryFontSource](./memoryfontsource/) | Representa a fonte de arquivo de fonte única. |
| [Metadata](./metadata/) | Fornece acesso ao fluxo de metadados XMP. |
| [Metered](./metered/) | <p> Fornece métodos para definir a chave metered. </p> <hr> Neste exemplo, será feita uma tentativa de definir a chave pública e privada metered <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | Representa opções para carregamento/importação de arquivo .mht em documento PDF. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Opções de salvamento para exportação para o formato Xml |
| [MovieAnnotation](./movieannotation/) | Representa uma anotação de filme que contém gráficos animados e som a serem apresentados na tela do computador e pelos alto-falantes. Quando a anotação é ativada, o filme é reproduzido. |
| [NamedAction](./namedaction/) | Representa ações nomeadas que se espera que aplicativos visualizadores de PDF suportem. |
| [NamedDestination](./nameddestination/) | Em vez de ser definido diretamente com a sintaxe explícita, um destino pode ser referenciado indiretamente por meio de um objeto de nome ou uma sequência de bytes. |
| [Note](./note/) | Esta classe representa a nota de parágrafo do gerador. |
| [NumberField](./numberfield/) | Campo de texto com caracteres válidos especificados @see TextBoxField |
| [NumberTree](./numbertree/) | Classe que representa a estrutura de árvore de números de um arquivo PDF. 7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | Representa as configurações OCSP usadas durante o processo de assinatura. |
| [OfdLoadOptions](./ofdloadoptions/) | Opções de carregamento para o formato OFD. |
| [Operator](./operator/) | Classe abstrata que representa o operador. |
| [OperatorCollection](./operatorcollection/) | Classe que representa a coleção de operadores |
| [OperatorSelector](./operatorselector/) | Esta classe é usada para selecionar operadores usando a ideia de modelo Visitor. |
| [Opi](./opi/) | Representa o Open Prepress Interface (OPI), que é um mecanismo para criar marcadores de posição de baixa resolução, ou proxies, para tais imagens de alta resolução. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Define um MemoryStream que pode conter mais capacidade padrão. |
| [Option](./option/) | Classe que representa a opção de um campo de escolha. |
| [OptionCollection](./optioncollection/) | Classe que representa a coleção de opções do campo de escolha. |
| [OutlineCollection](./outlinecollection/) | Representa a hierarquia de contorno do documento. |
| [OutlineItemCollection](./outlineitemcollection/) | Representa a entrada de contorno na hierarquia de contorno de um documento PDF. |
| [Outlines](./outlines/) | Classe que descreve a coleção de contornos. |
| [OutputIntent](./outputintent/) | Representa uma intenção de saída que corresponde às características de cor de um documento PDF com as de um dispositivo de saída alvo ou ambiente de produção no qual o documento será impresso. |
| [OutputIntents](./outputintents/) | Representa a coleção de {@link OutputIntent}. |
| [Page](./page/) | Classe que representa a página de um documento PDF. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | Procedimento para personalizar cabeçalho e rodapé. |
| [PageActionCollection](./pageactioncollection/) | Esta classe descreve as ações de página |
| [PageCollection](./pagecollection/) | Coleção de páginas de documento PDF. |
| [PageExtensions](./pageextensions/) | Fornece recursos adicionais para a classe Page. |
| [PageInfo](./pageinfo/) | Representa as informações da página para o gerador de PDF. |
| [PageInformationAnnotation](./pageinformationannotation/) | Representa uma anotação Page Information em um documento PDF. Esta anotação contém o nome do arquivo, o número da página e a data e hora da criação da anotação. Esta classe é usada principalmente para adicionar metadados a uma página específica no documento PDF, o que pode ser útil para fins de rastreamento e referência. Por exemplo, pode ser usada para marcar páginas durante o processo de impressão ou para fornecer informações adicionais sobre a página ao visualizar o documento. |
| [PageLabel](./pagelabel/) | Classe que representa o intervalo de rótulo de página. |
| [PageLabelCollection](./pagelabelcollection/) | Classe que representa a coleção de rótulos de página. |
| [PageMarkup](./pagemarkup/) | Marcação de página representada por coleções de {@code MarkupSection} e {@code MarkupParagraph}. |
| [PageNumberStamp](./pagenumberstamp/) | Representa o selo de número de página e é usado para numerar páginas. |
| [PageSize](./pagesize/) | Classe que representa o tamanho da página em um documento PDF. |
| [PaginationArtifact](./paginationartifact/) | Representa uma classe base abstrata para artefatos de paginação em um documento. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> Representa um objeto absorvedor de objetos de estrutura de página, como seções e parágrafos. Executa busca por seções e parágrafos de texto e fornece acesso a retângulos e polígonos que os descrevem no espaço de coordenadas de texto. Também executa busca de segmentos de texto e fornece acesso aos resultados da busca via coleções {@code TextFragments} agrupadas por elementos de estrutura. </p> O exemplo demonstra como encontrar o primeiro segmento de texto de cada parágrafo na primeira página do documento PDF e destacá‑lo. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Quando a busca for concluída, a coleção {@code ParagraphAbsorber.PageMarkups} conterá objetos {@code PageMarkup} que representam a estrutura da página por coleções de {@code MarkupSection} e {@code MarkupParagraph}. O objeto {@code TextFragment} fornece acesso ao texto da ocorrência da busca, às propriedades do texto e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc). |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Representa opções para o {@link ParagraphAbsorber}. |
| [Paragraphs](./paragraphs/) | Esta classe representa a coleção de parágrafos. |
| [PasswordBoxField](./passwordboxfield/) | Classe que descreve o campo de texto para inserção de senha. |
| [PclLoadOptions](./pclloadoptions/) | Representa opções para carregar (importar) arquivo PCL em um documento PDF. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | Enumera os mecanismos de conversão que podem ser usados para conversão |
| [PDF3DAnnotation](./pdf3dannotation/) | Classe PDF3DAnnotation. Esta classe não pode ser herdada. @see Annotation |
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
| [PdfAction](./pdfaction/) | Representa Ação em documento PDF |
| [PdfActionCollection](./pdfactioncollection/) | Classe descreve lista de ações. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | Esta classe descreve regras que podem ser usadas para ajustar o processo de cópia de dados de codificação para casos em que a fonte simbólica TrueType tem mais de uma codificação. Alguns documentos PDF após a conversão para o formato PDF/A podem gerar um erro \"More than one encoding in symbolic TrueType font's cmap\". Qual é a razão desse erro? Todas as fontes simbólicas TrueType têm uma tabela especial \"cmap\" em seus dados internos. Essa tabela mapeia códigos de caracteres para índices de glifos. E essa tabela pode conter diferentes subtabelas de codificação que descrevem as codificações usadas. Veja informações avançadas sobre tabelas cmap em https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Normalmente a tabela cmap contém várias subtabelas de codificação, mas o padrão PDF/A exige que ou apenas uma subtabela de codificação seja deixada para essa fonte no documento PDF/A ou que exista uma subtabela de codificação (3,0) entre as subtabelas dessa fonte. E a questão principal aqui – quais dados devem ser obtidos de outras subtabelas para copiar para a tabela de codificação de destino (3,0)? A maioria das fontes possui tabelas cmap "bem‑formadas" onde cada subtabela de codificação é totalmente consistente com outra subtabela. Mas algumas fontes têm tabelas cmap com colisões – onde, por exemplo, uma subtabela tem índice de glifo 100 para unicode 100, mas outra subtabela tem índice de glifo 200 para o mesmo unicode 100. Para resolver esses problemas é necessária uma estratégia especial. Por padrão, a seguinte estratégia é usada: procura‑se a subtabela mac (1,0). Se essa tabela for encontrada, apenas esses dados são usados para preencher a tabela de destino (3,0). Se a subtabela mac não for encontrada, então todas as subtabelas exceto (3,0) são iteradas e usadas para copiar dados para a subtabela de destino (3,0). Também o mapeamento para cada unicode (unicode, índice de glifo) é copiado para a tabela de destino somente se a tabela de destino não possuir esse unicode no momento. Assim, por exemplo, se a primeira subtabela tem índice de glifo 100 para unicode 100, e a próxima subtabela tem índice de glifo 200 para o mesmo unicode 100, apenas os dados da primeira subtabela (unicode=100, índice de glifo = 100) serão copiados. Portanto, cada subtabela anterior tem precedência sobre a seguinte. As propriedades desta classe { PdfASymbolicFontEncodingStrategy} ajudam a ajustar o comportamento padrão. Se a propriedade {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) do tipo { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} estiver definida, então a subtabela relevante será usada com precedência sobre a subtabela mac (1,0). O valor 'MacTable' da enumeração {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} não faz sentido neste caso, pois aponta para a mesma subtabela mac (1,0) que será usada por padrão. A propriedade {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) descarta todas as prioridades para qualquer subtabela. Se essa propriedade for definida, então apenas as subtabelas da fila declarada serão usadas na ordem especificada. Se as subtabelas especificadas não forem encontradas, então a iteração padrão de todas as subtabelas e a estratégia de cópia descrita acima serão usadas. O objeto { PdfASymbolicFontEncodingStrategy.QueueItem} especifica a subtabela de codificação usada. Essa subtabela pode ser definida via combinação de membros (PlatformID, PlatformSpecificId) ou via enumeração { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. No caso de a fonte não ter subtabela (3,0), outra subtabela será usada para manter a compatibilidade PDF/A. A escolha da subtabela a ser usada é feita sob as mesmas regras descritas anteriormente, de modo que as propriedades {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) e {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) são usadas para determinar a subtabela resultante, e se a fonte não possuir a(s) subtabela(s) solicitada(s), então qualquer subtabela existente será usada. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | Especifica a sub‑tabela de codificação. Cada sub‑tabela de codificação tem combinação única de parâmetros (PlatformID, PlatformSpecificID). A enumeração {@code CMapEncodingTableType} e a propriedade {@code CMapEncodingTable} foram implementadas para facilitar o conjunto de sub‑tabelas de codificação necessárias. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | Declara um conjunto de algumas sub‑tabelas de codificação conhecidas. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | representa um conjunto de opções para converter documento PDF. |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | Esta classe contém flags para controlar a conversão PDF/A em casos em que o documento PDF de origem não corresponde à especificação PDF. Se as flags desta classe forem usadas, o desempenho diminui, mas é necessário quando o documento PDF de origem não pode ser convertido para o formato PDF/A da maneira usual. Por padrão, todas as flags são definidas como false. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | Alguns documentos PDF contêm símbolos unicode especiais, que pertencem à Área de Uso Privado (PUA); veja a descrição em https://en.wikipedia.org/wiki/Private_Use_Areas. Esses símbolos causam erros de conformidade PDF/A como "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Esta enumeração declara estratégias que podem ser usadas para lidar com símbolos PUA. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | Alguns documentos têm tamanho grande após a conversão para o formato PDF/A. Para reduzir o tamanho do arquivo desses documentos, é necessário definir uma estratégia de remoção de fontes. Esta enumeração declara estratégias que podem ser usadas para otimizar o uso de fontes. Cada estratégia desta enumeração só faz sentido quando a flag {@code OptimizeFileSize} está definida. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | Descreve estratégias usadas para alinhar segmentos de texto do documento. Atualmente, apenas a estratégia de restaurar os segmentos aos limites originais é suportada. No futuro, outras estratégias podem ser adicionadas. |
| [PdfPageStamp](./pdfpagestamp/) | Classe que representa um carimbo que usa a página PDF como carimbo. |
| [PdfSaveOptions](./pdfsaveoptions/) | Opções de salvamento para exportação para o formato Pdf. |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | Opções de carregamento para o formato PdfXml. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | Opções de salvamento para o formato PdfXml. |
| [Permissions](./permissions/) | Flag binária. Esta enumeração representa as permissões do usuário para um pdf. |
| [PKCS1](./pkcs1/) | Representa um objeto de assinatura de acordo com o padrão PKCS#1. O algoritmo de criptografia RSA e o método de digestão SHA-1 são usados para assinatura. |
| [PKCS7](./pkcs7/) | Representa o objeto PKCS#7 que está em conformidade com a especificação PKCS#7 na RFC 2315 da Internet, PKCS #7: Cryptographic Message Syntax, Versão 1.5. O digest SHA1 do intervalo de bytes do documento é encapsulado no campo SignedData do PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Representa o objeto PKCS#7 que está em conformidade com a especificação PKCS#7 na RFC 2315 da Internet, PKCS #7: Cryptographic Message Syntax, Versão 1.5. O digest da mensagem assinada original sobre o intervalo de bytes do documento é incorporado como o campo SignedData normal do PKCS#7. Nenhum dado deve ser encapsulado no campo SignedData do PKCS#7. |
| [Point](./point/) | Representa um ponto com coordenadas fracionárias. |
| [Point3D](./point3d/) | Representa um ponto com coordenadas fracionárias. |
| [PolyAnnotation](./polyannotation/) | Classe base abstrata para poly‑annotations. |
| [PolygonAnnotation](./polygonannotation/) | Classe que representa uma anotação de polígono. |
| [PolylineAnnotation](./polylineannotation/) | Representa uma anotação de polilinha que é semelhante a um polígono, exceto que o primeiro e o último vértice não são implicitamente conectados. |
| [PopupAnnotation](./popupannotation/) | Representa a anotação pop‑up que exibe texto em uma janela pop‑up para inserção e edição. |
| [Position](./position/) | Representa um objeto de posição. |
| [PptxSaveOptions](./pptxsaveoptions/) | Opções de salvamento para exportação para o formato SVG. |
| [PrintController](./printcontroller/) | Representa o controlador de impressão. |
| [PrintDuplex](./printduplex/) | A opção de manuseio de papel a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Classe abstrata que representa anotação de marca de impressora. |
| [PrinterMarksKind](./printermarkskind/) | Especifica os tipos de marcas da impressora a serem adicionados a um documento. Esta enumeração possui um atributo {@link FlagsAttribute} que permite uma combinação bit a bit de seus valores de membros. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Fornece métodos de extensão para a enumeração {@link PrinterMarksKind}. |
| [PrintScaling](./printscaling/) | A opção de dimensionamento de página que deve ser selecionada quando uma caixa de diálogo de impressão for exibida para este documento. |
| [ProgressEventType](./progresseventtype/) | Esta enumeração descreve os possíveis tipos de eventos de progresso que podem ocorrer durante a conversão. |
| [PsLoadOptions](./psloadoptions/) | Representa opções para carregamento/importação de arquivo .mht em documento PDF. |
| [PsSaveOptions](./pssaveoptions/) | Opções de salvamento para exportação para o formato PS (PostScript) ou EPS. |
| [RadioButtonField](./radiobuttonfield/) | Classe que representa um campo de botão de opção. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Classe que representa um item de campo RadioButton. |
| [Rectangle](./rectangle/) | Classe que representa um retângulo. |
| [Redaction](./redaction/) | Somente para uso interno @author User |
| [RedactionAnnotation](./redactionannotation/) | Representa a anotação Redact. |
| [RegexManager](./regexmanager/) | Fornece um wrapper para operações de expressão regular com configurações de tempo limite configuráveis. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Representa uma anotação de Marca de Registro. Marcas de registro são símbolos adicionados a chapas ou telas de impressão para garantir o alinhamento adequado das cores durante o processo de impressão. |
| [RenderingOptions](./renderingoptions/) | Representa opções de renderização |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: conjunto de tipos de modo de renderização |
| [Rendition](./rendition/) | Classe que descreve o objeto de renderização da RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Uma ação de renderização que controla a reprodução de conteúdo multimídia. |
| [RenditionOperation](./renditionoperation/) | A operação a ser executada quando a ação for acionada. |
| [RenditionType](./renditiontype/) | Enumeração que descreve os possíveis tipos de Rendition. |
| [Resources](./resources/) | Classe que representa recursos de página. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | Representa ExtGStates com alguns valores. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | Representa a estratégia de conversão de espaços de cor rgb para cinza de dispositivo. |
| [RichMediaAnnotation](./richmediaannotation/) | Classe que descreve RichMediaAnnotation, que permite incorporar dados de vídeo/áudio em documento PDF. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | Evento que ativa a anotação. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | Tipo da multimídia. |
| [RichTextBoxField](./richtextboxfield/) | Classe que descreve o componente editor de texto rico. |
| [RichTextFontStyles](./richtextfontstyles/) | Opções para estilizar fragmentos de texto em RichText. |
| [RootElement](./rootelement/) | Elemento de estrutura raiz. |
| [Row](./row/) | Representa uma linha da tabela. |
| [Rows](./rows/) | Representa uma coleção de linhas da tabela. |
| [RtfLoadOptions](./rtfloadoptions/) | Opções de carregamento para o formato RTF. |
| [SaveOptions](./saveoptions/) | O tipo SaveOptions mantém nível de abstração nas opções individuais de salvamento. |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | Instância desta classe representa informações sobre a borda que pode ser desenhada em algum documento resultante. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | Representa informações de uma parte da borda (superior, inferior, lado esquerdo ou lado direito). |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | Instância desta classe representa informações sobre a margem da página que pode ser desenhada em algum documento resultante. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | Representa informações de uma parte da margem (superior, inferior, lado esquerdo ou lado direito). |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de recursos externos que ocorre durante a conversão de PDF para outro formato (por exemplo, HTML). |
| [ScalingMode](./scalingmode/) | O tipo de dimensionamento que deve ser usado. |
| [ScalingReason](./scalingreason/) | As circunstâncias sob as quais o ícone deve ser dimensionado dentro do retângulo da anotação. |
| [ScreenAnnotation](./screenannotation/) | Uma anotação de tela que especifica uma região de uma página na qual clipes de mídia podem ser reproduzidos. |
| [SelectorRendition](./selectorrendition/) | Classe que descreve a renderização do seletor. |
| [Signature](./signature/) | Uma classe abstrata que representa um objeto de assinatura no documento PDF. Assinaturas são campos com valores de objetos de assinatura, que contêm dados usados para verificar a validade do documento. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Uma classe abstrata que representa um objeto de aparência personalizada de assinatura. |
| [SignatureField](./signaturefield/) | Representa um campo de formulário de assinatura. |
| [SignHash](./signhash/) | Delegado para assinatura personalizada do hash do documento (Beta). |
| [SoundAnnotation](./soundannotation/) | Representa uma anotação de som que contém áudio gravado do microfone do computador ou importado de um arquivo. |
| [SoundData](./sounddata/) | Representa dados de som que definem o áudio a ser reproduzido quando a anotação é ativada. |
| [SoundEncoding](./soundencoding/) | O formato de codificação para os dados de amostra. |
| [SoundIcon](./soundicon/) | Enumera os ícones a serem usados na exibição da anotação. |
| [SoundIconConverter](./soundiconconverter/) | Representa a classe SoundIconConverter. |
| [SoundSampleData](./soundsampledata/) | Representa entradas adicionais específicas a um objeto de som (Seção 9.2 PDF1-7). |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | O formato de codificação dos dados de amostra de áudio. |
| [SquareAnnotation](./squareannotation/) | Classe que representa anotação quadrada. |
| [SquigglyAnnotation](./squigglyannotation/) | Representa a anotação ondulada que aparece como sublinhado irregular no texto de um documento. |
| [Stamp](./stamp/) | Uma classe abstrata para vários tipos de carimbos que vêm como descendentes. |
| [StampAnnotation](./stampannotation/) | <p> Representa anotação de carimbo de borracha. Este tipo de anotação exibe texto ou gráficos que parecem ter sido carimbados na página com um carimbo de borracha. </p> <hr> <pre> O próximo trecho de código demonstra como adicionar 2 carimbos na primeira página do documento PDF. O documento de entrada vem de inFile e as alterações são salvas em outFile. O primeiro carimbo tem o ícone NotForPublicRelease e o segundo vem com a imagem de rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | Representa a classe StampIconConverter |
| [StrikeOutAnnotation](./strikeoutannotation/) | Representa uma anotação de tachado que aparece como tachado no texto do documento. |
| [StructElement](./structelement/) | Elemento de estrutura geral. |
| [SubjectNameElements](./subjectnameelements/) | Enumeração que descreve elementos na string de assunto da assinatura. |
| [SubmitFormAction](./submitformaction/) | Classe que descreve a ação submit-form. |
| [SvgLoadOptions](./svgloadoptions/) | Representa opções para carregar/importar arquivo SVG em documento PDF. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | Enumera os mecanismos de conversão que podem ser usados para conversão |
| [SvgSaveOptions](./svgsaveoptions/) | Opções de salvamento para exportação para o formato SVG. |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de imagem de recursos externos durante a conversão de PDF para HTML. |
| [Symbology](./symbology/) | Uma (Barcode) Symbology define os detalhes técnicos de um tipo específico de código de barras: a largura das barras, conjunto de caracteres, método de codificação, especificações de checksum, etc. |
| [SystemFontSource](./systemfontsource/) | Representa todas as fontes instaladas no sistema. |
| [TabAlignmentType](./tabalignmenttype/) | Enumera os tipos de alinhamento de tabulação. |
| [Table](./table/) | Representa uma tabela que pode ser adicionada à página. |
| [TableAbsorber](./tableabsorber/) | <p> Representa um objeto absorvedor de elementos de tabela. Executa busca e fornece acesso aos resultados da pesquisa via coleção {@code TableAbsorber.TableList}. </p> <hr> <pre> O exemplo demonstra como encontrar uma tabela na primeira página do documento PDF e substituir o texto em uma célula da tabela. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | Enumera os tipos de líder de tabulação. |
| [TableBroken](./tablebroken/) | Enumera a quebra de tabela. |
| [TabOrder](./taborder/) | Ordem de tabulação na página |
| [TabStop](./tabstop/) | Representa uma posição personalizada de parada de tabulação em um parágrafo. |
| [TabStops](./tabstops/) | Representa uma coleção de objetos {@code TabStop}. |
| [TeXFragment](./texfragment/) | Representa fragmento LaTeX. |
| [TeXLoadOptions](./texloadoptions/) | Representa opções para carregar/importar arquivo TeX em documento PDF. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Implementa a obtenção de um fluxo de saída a partir da memória. Você pode usá-lo, por exemplo, quando não deseja que a saída associada (como um arquivo de log) seja gravada em disco, mas gostaria de lê-la posteriormente a partir da memória. |
| [TeXSaveOptions](./texsaveoptions/) | Opções de salvamento para exportação ao formato TeX |
| [TextAbsorber](./textabsorber/) | <p> Representa um objeto absorvedor de texto. Executa a extração de texto e fornece acesso ao resultado via {@code TextAbsorber.Text} objeto. </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. // abrir documento Document doc = new Document(inFile); // criar objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber); // obter o texto extraído String extractedText = absorber.getText(); </pre> <hr> <p> O objeto {@code TextAbsorber} é usado para extrair texto de um documento Pdf ou da página do documento. </p> |
| [TextAnnotation](./textannotation/) | Representa uma anotação de texto que é um \"sticky note\" anexado a um ponto no documento PDF. |
| [TextBoxField](./textboxfield/) | Classe que representa o campo de caixa de texto. |
| [TextBuilder](./textbuilder/) | Anexa objeto de texto à página Pdf. |
| [TextDefaults](./textdefaults/) | Define padrões do subsistema de texto |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | Especifica o tipo de padrões do subsistema de texto |
| [TextEditOptions](./texteditoptions/) | Descreve opções de operações de edição de texto. |
| [TextElement](./textelement/) | Elemento de texto geral da estrutura lógica do documento. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | Descreve o erro de extração de texto que apareceu no documento PDF. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Representa a localização no documento PDF onde o erro de extração de texto apareceu. |
| [TextExtractionOptions](./textextractionoptions/) | Representa opções de extração de texto |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | Define diferentes modos que podem ser usados ao converter documento pdf em texto. Veja a classe {@code TextDevice}. |
| [TextFormattingOptions](./textformattingoptions/) | Representa opções de formatação de texto |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Define especificações de espaçamento entre linhas |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Define estratégias de quebra de linha |
| [TextFragment](./textfragment/) | <p> Representa fragmento de texto PDF. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto e sua fonte. // Abrir documento Document doc = new Document(\"input.pdf\"); // Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont(\"Arial\"); // Criar o objeto TextFragmentAbsorber para encontrar todas as ocorrências do texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceitar o absorvedor na primeira página doc.getPages().get(1).accept(absorber); // Alterar o texto e a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salvar o documento doc.save(\"output.pdf\"); </pre> <hr> <pre> Em poucas palavras, o objeto {@code TextFragment} contém uma lista de objetos {@code TextSegment}. Em detalhes: O texto do documento pdf em {@code com.aspose.pdf} é representado por dois objetos básicos: {@code TextFragment} e {@code TextSegment} As diferenças entre eles são principalmente dependentes do contexto. Vamos considerar o seguinte cenário. O usuário procura o texto \"hello world\" para operar com ele, alterar suas propriedades, visualizar etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> A representação física do texto PDF é muito complexa. O texto \"hello world\" pode consistir em vários segmentos de texto fisicamente independentes. O modelo de texto Aspose.Pdf basicamente estabelece que o objeto {@code TextFragment} fornece um conjunto único de operações lógicas sobre o conjunto de objetos {@code TextSegment} físicos que representam a consulta do usuário. No cenário de busca de texto, {@code TextFragment} é a representação lógica do texto \"hello world\", e a coleção de objetos {@code TextSegment} representa todos os segmentos físicos que constroem o objeto de texto \"hello world\". Portanto, {@code TextFragment} está próximo da representação lógica do texto. E {@code TextSegment} está próximo da representação física do texto. Obviamente, cada objeto {@code TextSegment} pode ter sua própria fonte, cor e propriedades de posicionamento. {@code TextFragment} fornece uma maneira simples de alterar o texto com suas propriedades: definir fonte, definir tamanho da fonte, definir cor da fonte etc. Enquanto isso, os objetos {@code TextSegment} são acessíveis e os usuários podem operar com os objetos {@code TextSegment} de forma independente. <p> Observe que alterar as propriedades do TextFragment pode mudar a coleção interna {@code Segments}, pois o TextFragment é um objeto agregado e pode reorganizar os segmentos internos ou mesclá-los em um único segmento. Se sua necessidade for deixar a coleção {@code Segments} inalterada, por favor altere os segmentos internos individualmente. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> Representa um objeto absorvedor de fragmentos de texto. Executa busca de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto e sua fonte. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> O objeto {@code TextFragmentAbsorber} é basicamente usado em cenários de busca de texto. Quando a pesquisa é concluída, as ocorrências são representadas por objetos {@code TextFragment} que a coleção {@code TextFragmentAbsorber.TextFragments} contém. O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de busca, às propriedades do texto e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc). </p> |
| [TextFragmentCollection](./textfragmentcollection/) | Representa uma coleção de fragmentos de texto |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> Representa o estado de texto de um fragmento de texto. </p> <hr> <pre> O exemplo demonstra como alterar a cor do texto e o tamanho da fonte do texto com o objeto {@code TextState}. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Fornece uma maneira de alterar as seguintes propriedades do texto: fonte ({@code TextFragmentState.Font} property) tamanho da fonte ({@code TextFragmentState.FontSize} property) estilo da fonte ({@code TextFragmentState.FontStyle} property) cor de primeiro plano ({@code TextFragmentState.ForegroundColor} property) cor de fundo ({@code TextFragmentState.BackgroundColor} property) </p> <p> Observe que a alteração das propriedades {@code TextFragmentState} pode mudar a coleção interna {@code TextFragment.Segments} porque TextFragment é um objeto agregado e pode reorganizar os segmentos internos ou mesclá‑los em um único segmento. Se sua necessidade for deixar a coleção {@code TextFragment.Segments} inalterada, altere os segmentos internos individualmente. </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | Enumera os ícones a serem usados na exibição da anotação. |
| [TextIconConverter](./texticonconverter/) | Representa a classe TextIconConverter |
| [TextMarkupAnnotation](./textmarkupannotation/) | Classe base abstrata para anotações de marcação de texto. |
| [TextOptions](./textoptions/) | Representa opções de processamento de texto |
| [TextParagraph](./textparagraph/) | <p> Representa parágrafos de texto como objeto de texto multilinha. </p> <hr> <pre> O exemplo demonstra como criar um objeto de parágrafo de texto e adicioná‑lo à página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // cria parágrafo de texto TextParagraph paragraph = new TextParagraph(); // define o retângulo do parágrafo paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // define opções de quebra de linha paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // adiciona linhas de string paragraph.appendLine("a rápida raposa marrom pula sobre o cão preguiçoso"); paragraph.appendLine("linha2"); paragraph.appendLine("linha3"); // adiciona o parágrafo à página Pdf com o TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // salva o documento Pdf doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | Modo de plano de fundo para TextParagraph |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Representa um objeto absorvedor de parágrafos de texto. Executa pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextParagraphAbsorber.TextParagraphs}. |
| [TextParagraphCollection](./textparagraphcollection/) | Representa uma coleção de parágrafos de texto |
| [TextReplaceOptions](./textreplaceoptions/) | Representa opções de substituição de texto |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Determina a ação que será realizada após a substituição de um fragmento de texto por um mais curto. None - nenhuma ação, o texto substituído pode sobrepor o restante da linha; AdjustSpaceWidth - tenta ajustar os espaços entre palavras para manter o comprimento da linha; WholeWordsHyphenation - tenta distribuir palavras entre as linhas do parágrafo para manter o campo direito do parágrafo; ShiftRestOfLine - desloca o restante da linha de acordo com a mudança no comprimento do texto, o comprimento da linha pode ser alterado; O valor padrão é ShiftRestOfLine. |
| [TextSearchOptions](./textsearchoptions/) | Representa opções de pesquisa de texto |
| [TextSegment](./textsegment/) | <p> Representa um segmento de texto PDF. </p> <hr> <pre> O exemplo demonstra como alterar a cor do texto e o tamanho da fonte do texto com o objeto {@code TextState} do objeto {@code TextSegment}. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber); // Alterar a cor de primeiro plano do primeiro segmento de texto da primeira ocorrência de texto absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Alterar o tamanho da fonte do primeiro segmento de texto da primeira ocorrência de texto absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Salvar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <pre> Em poucas palavras, objetos {@code TextSegment} são filhos do objeto {@code TextFragment}. Em detalhes: O texto de um documento PDF em {@code Aspose.Pdf} é representado por dois objetos básicos: {@code TextFragment} e {@code TextSegment} As diferenças entre eles são principalmente dependentes do contexto. Vamos considerar o seguinte cenário. O usuário procura o texto "hello world" para operar com ele, alterar suas propriedades, visualizar etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> A representação física do texto PDF é muito complexa. O texto "hello world" pode consistir em vários segmentos de texto fisicamente independentes. O modelo de texto Aspose.PDF basicamente estabelece que o objeto {@code TextFragment} fornece um conjunto de operação lógica única sobre o conjunto de objetos {@code TextSegment} físicos que representam a consulta do usuário. No cenário de busca de texto, {@code TextFragment} é a representação lógica do texto "hello world", e a coleção de objetos {@code TextSegment} representa todos os segmentos físicos que constroem o objeto de texto "hello world". Assim, {@code TextFragment} está próximo da representação lógica do texto. E {@code TextSegment} está próximo da representação física do texto. Obviamente, cada objeto {@code TextSegment} pode ter sua própria fonte, coloração e propriedades de posicionamento. {@code TextFragment} fornece uma maneira simples de alterar o texto com suas propriedades: definir fonte, definir tamanho da fonte, definir cor da fonte etc. Enquanto isso, os objetos {@code TextSegment} são acessíveis e os usuários podem operar com os objetos {@code TextSegment} de forma independente. </p> |
| [TextSegmentCollection](./textsegmentcollection/) | Representa uma coleção de segmentos de texto |
| [TextStamp](./textstamp/) | Representa um selo textual. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | Ação a ser executada se a fonte não contiver o caractere necessário. |
| [TextState](./textstate/) | Representa o estado de texto de um texto |
| [TextStyle](./textstyle/) | Classe que representa um campo de caixa de seleção. |
| [TimestampSettings](./timestampsettings/) | Representa as configurações OCSP usadas durante o processo de assinatura. |
| [TocInfo](./tocinfo/) | Representa informações do índice. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | Esta classe descreve regras que podem ser usadas para resolver o erro do Adobe Preflight "Text cannot be mapped to Unicode". |
| [TrimMarkAnnotation](./trimmarkannotation/) | Representa uma anotação de Marca de Corte. As marcas de corte são colocadas nos cantos de uma página impressa para indicar onde a página deve ser recortada. |
| [TxtLoadOptions](./txtloadoptions/) | Opções de carregamento para conversão de TXT para PDF. |
| [UnderlineAnnotation](./underlineannotation/) | Representa uma anotação de sublinhado que aparece como sublinhado no texto do documento. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | Esta classe representa opções de salvamento que utilizam um método de conversão unificado (com modelo interno de documento unificado). |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | Representa uma classe com método abstrato que geralmente é fornecido pelo chamador e lida com eventos de progresso que vêm do conversor. Normalmente, esse manipulador fornecido pelo cliente pode ser usado para mostrar o progresso total da conversão no console ou em uma barra de progresso. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | Esta classe representa informações sobre o progresso da conversão que podem ser usadas em uma aplicação externa para mostrar o progresso da conversão ao usuário final. |
| [WarningCallback](./warningcallback/) | Interface para suporte ao mecanismo de callback do usuário. |
| [WarningInfo](./warninginfo/) | Objeto imutável para encapsular informações de aviso. |
| [WarningType](./warningtype/) | /* Enum representado tipo de aviso. */ |
| [Watermark](./watermark/) | Representa uma marca d'água da página. |
| [WatermarkAnnotation](./watermarkannotation/) | Classe descreve o objeto de anotação Watermark. |
| [WatermarkArtifact](./watermarkartifact/) | Classe descreve o artefato de marca d'água. Isso pode ser usado para |
| [WebHyperlink](./webhyperlink/) | Representa um objeto de hyperlink da web. |
| [WidgetAnnotation](./widgetannotation/) | Classe que representa anotação de widget. |
| [XFA](./xfa/) | Representa formulário XML relativo à Arquitetura de Formulários XML (XFA). |
| [XfaParserOptions](./xfaparseroptions/) | classe para lidar com a encapsulação de dados relacionados |
| [XfdfReader](./xfdfreader/) | <p> Classe que realiza a leitura do formato XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | Agrupa métodos de gravação de anotações e campos no formato de arquivo XFDF |
| [XForm](./xform/) | Classe que representa XForm |
| [XFormCollection](./xformcollection/) | Classe que representa a coleção XFormCollection. |
| [XImage](./ximage/) | Classe que representa o objeto de imagem X-Object. |
| [XImage.RawParameters](./ximage.rawparameters/) | Classe que representa os parâmetros brutos de imagem XImage. |
| [XImageCollection](./ximagecollection/) | Classe que representa a coleção XImage. |
| [XmlLoadOptions](./xmlloadoptions/) | Representa opções para carregar/importar arquivo XML em documento PDF. |
| [XmlSaveOptions](./xmlsaveoptions/) | Opções de salvamento para exportação para o formato Xml |
| [XmpField](./xmpfield/) | Representa campo XMP. |
| [XmpFieldType](./xmpfieldtype/) | Este enum representa tipos de um campo XMP. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Categoria da propriedade: interna ou externa. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | Este esquema descreve um campo em um tipo estruturado. É muito semelhante ao esquema PDF/A Property Value Type, mas define um campo em uma estrutura em vez de uma propriedade. URI do namespace do esquema: http://www.aiim.org/pdfa/ns/field# Prefixo de namespace do esquema obrigatório: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Representa a classe base para instâncias de campo, propriedade e tipo de valor. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Descreve uma única propriedade. URI do namespace do esquema: http://www.aiim.org/pdfa/ns/property# Prefixo de namespace do esquema obrigatório: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | Descreve o esquema de extensão XMP fornecido pelo PDF/A-1. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | Representa a descrição do esquema de extensão XMP fornecido pelo PDF/A-1. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | O esquema PDF/A ValueType é necessário para todos os tipos de valor de propriedade que não estão definidos na especificação XMP 2004, ou seja, para tipos de valor fora da lista a seguir: - Tipos de array (são tipos contêiner que podem conter um ou mais campos): Alt, Bag, Seq - Tipos de valor básicos: Boolean, Choice (aberto e fechado), Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipos de valor de Gerenciamento de Mídia: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo de valor básico de Trabalho/Fluxo: Job - Tipos de valor do esquema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI do namespace do esquema: http://www.aiim.org/pdfa/ns/type# Prefixo de namespace do esquema obrigatório: pdfaType |
| [XmpValue](./xmpvalue/) | Representa valor XMP |
| [XpsLoadOptions](./xpsloadoptions/) | Representa opções para carregar/importar arquivo XPS em documento PDF. |
| [XpsSaveOptions](./xpssaveoptions/) | Opções de salvamento para exportação para o formato XPS |
| [XslFoLoadOptions](./xslfoloadoptions/) | Representa opções para carregar/importar arquivo XSL-FO em documento PDF. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | O documento XSLFO de origem pode conter erros de formatação. Este enum enumera possíveis estratégias de tratamento desses erros de formatação. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> Representa destino explícito que exibe a página com as coordenadas (esquerda, superior) posicionadas no canto superior esquerdo da janela e o conteúdo da página ampliado pelo fator zoom. Um valor nulo para qualquer um dos parâmetros esquerda, superior ou zoom especifica que o valor atual desse parâmetro deve ser mantido inalterado. Um valor de zoom igual a 0 tem o mesmo significado que um valor nulo. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </code> </p> |
## Enums

| Enum | Descrição |
| --- | --- |
| [AFRelationship](./afrelationship/) | Enumeração descreve a relação de arquivos associados. |
| [AnnotationState](./annotationstate/) | A enumeração dos estados para os quais a anotação original pode ser definida. |
| [AnnotationStateModel](./annotationstatemodel/) | O modelo de estado correspondente ao estado da anotação. |
| [AnnotationType](./annotationtype/) | Enumeração de tipos de anotação. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | Enumeração do subtipo de artefatos possíveis. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | Enumeração de tipos de artefato possíveis. |
| [BlendMode](./blendmode/) | A enumeração dos modos de mesclagem. |
| [BorderCornerStyle](./bordercornerstyle/) | Enumera os estilos de canto da borda. |
| [BorderEffect](./bordereffect/) | Descreve o efeito que deve ser aplicado à borda das anotações. |
| [BorderStyle](./borderstyle/) | Descreve o estilo da borda da anotação. |
| [BoxStyle](./boxstyle/) | Representa estilos para desenhar marca em caixa de seleção. |
| [CapStyle](./capstyle/) | Estilo da extremidade da linha da anotação de tinta. |
| [CaptionPosition](./captionposition/) | Enumeração do posicionamento da legenda da anotação. |
| [CaretSymbol](./caretsymbol/) | Um símbolo a ser associado ao cursor. |
| [ColorsOfCMYK](./colorsofcmyk/) | Cores incluídas no modelo de cores CMYK. |
| [ColorSpace](./colorspace/) | A enumeração dos espaços de cor. |
| [ColorType](./colortype/) | Especifica o tipo de cor dos elementos na página. |
| [ColumnAdjustment](./columnadjustment/) | Enumera os tipos de ajuste de coluna. |
| [ContentDisposition](./contentdisposition/) | Cabeçalho Content-Disposition do protocolo MIME. |
| [ConvertErrorAction](./converterroraction/) | Esta classe representa a ação para erros de conversão. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | Esta ação representa as ações para conversão de imagens com máscara suave. |
| [ConvertTransparencyAction](./converttransparencyaction/) | Esta classe representa a ação para conversão de transparência. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | Representa o tipo de algoritmo criptográfico usado em rotinas de criptografia/descriptografia. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * O namespace {@code Aspose.Pdf.Security } contém classes usadas para criptografia e assinatura digital. / * / |
| [DefaultState](./defaultstate/) | Representa o estado padrão de uma camada PDF. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Representa o tipo de algoritmo que mapeia dados para um "hash" |
| [Direction](./direction/) | Direção do texto. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | As permissões de acesso concedidas para este documento. Valores válidos são: 1 - Nenhuma alteração no documento é permitida; qualquer alteração no documento invalida a assinatura. 2 - Alterações permitidas são o preenchimento de formulários, a instanciação de modelos de página e a assinatura; outras alterações invalida a assinatura. 3 - Alterações permitidas são as mesmas da opção 2, além da criação, exclusão e modificação de anotações; outras alterações invalida a assinatura. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | Permite especificar o formato de arquivo .doc ou .docx. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | Permite controlar como um documento PDF é convertido em um documento de processamento de texto. Use o modo RecognitionMode.Textbox quando o documento resultante não for editado extensivamente. Caixas de texto são fáceis de modificar quando há pouco a fazer. Use o modo RecognitionMode.Flow quando o documento de saída precisar de edição adicional. Parágrafos e linhas de texto no modo fluxo permitem fácil modificação do texto, mas objetos de formatação não suportados ficarão com aparência pior do que no modo RecognitionMode.Textbox. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | Quando um arquivo PDF (que geralmente tem layout fixo) está sendo convertido, o motor de conversão tenta realizar agrupamento e análise multinível para restaurar a intenção original do autor do documento e produzir o resultado em layout fluido. Esta propriedade ajusta essa conversão para o método desejável de reconhecimento de conteúdo. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumera os tipos de destinos explícitos. |
| [ExtendedBoolean](./extendedboolean/) | Representa um tipo booleano que suporta o valor Undefined. |
| [ExtractImageMode](./extractimagemode/) | Define diferentes modos que podem ser usados ao extrair imagens de documentos. |
| [FileEncoding](./fileencoding/) | Codificação do arquivo anexado. Valores possíveis: Zip - o arquivo está comprimido com ZIP, None - o arquivo não está comprimido. |
| [FileIcon](./fileicon/) | Um ícone a ser usado na exibição da anotação. |
| [Fixup](./fixup/) | Este enum representa um tipo de Fixup. |
| [FormType](./formtype/) | Enumeração dos tipos possíveis de Acro Form. |
| [FreeTextIntent](./freetextintent/) | Enumera as intenções da anotação de texto livre. |
| [HighlightingMode](./highlightingmode/) | Enumera o modo de realce da anotação, o efeito visual a ser usado quando o botão do mouse é pressionado ou mantido dentro de sua área ativa. |
| [HorizontalAlignment](./horizontalalignment/) | Descreve o alinhamento horizontal. |
| [HtmlDocumentType](./htmldocumenttype/) | Representa a enumeração dos tipos de documento Html. |
| [HtmlMediaType](./htmlmediatype/) | Especifica os tipos de mídia possíveis usados durante a renderização. |
| [IconCaptionPosition](./iconcaptionposition/) | Descreve a posição do ícone. |
| [ImageFileType](./imagefiletype/) | Enumera os tipos de arquivo de imagem. |
| [ImageFilterType](./imagefiltertype/) | Enumeração que representa o tipo de filtro de imagem. |
| [ImageFormat](./imageformat/) | Este enum representa formatos de imagem. |
| [ImportFormat](./importformat/) | Especifica o formato de importação. |
| [Justification](./justification/) | Enumera as formas de justificação (quadding) a serem usadas na exibição do texto da anotação. |
| [LaunchActionOperation](./launchactionoperation/) | Enumera as operações a serem realizadas com o documento durante a execução da ação de lançamento. |
| [LettersPositioningMethods](./letterspositioningmethods/) | Ele enumera os modos possíveis de posicionamento de letras em palavras no HTML resultante. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: conjunto de tipos de esquema de iluminação. |
| [LineEnding](./lineending/) | Enumera os estilos de terminação de linha a serem usados ao desenhar a linha. |
| [LineIntent](./lineintent/) | Enumera as intenções da anotação de linha. |
| [LoadFormat](./loadformat/) | Especifica o formato de carregamento. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | Valor que indica de que maneira os valores fracionários são exibidos. |
| [NumberingStyle](./numberingstyle/) | Enumeração do estilo de numeração de página suportado para a classe PageLabel. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | Especifica a posição em um fluxo a ser usada para busca. |
| [PageCoordinateType](./pagecoordinatetype/) | Descreve o tipo de coordenada da página. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | Descreve o layout da página. |
| [PageMode](./pagemode/) | A classe descreve os componentes usados da página do documento. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Especifica a variante para determinar a localização do elemento na página. |
| [PasswordType](./passwordtype/) | Este enum representa os tipos de senha conhecidos usados para documentos PDF protegidos por senha. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: conjunto de modos de ativação de anotação 3D. |
| [PdfFormat](./pdfformat/) | Esta classe representa um formato PDF. |
| [PdfVersion](./pdfversion/) | Este enum representa a versão do arquivo PDF. |
| [PolyIntent](./polyintent/) | Enumera as intenções da anotação de polígono ou polilinha. |
| [PredefinedAction](./predefinedaction/) | Define diferentes ações que podem ser acionadas a partir de um arquivo PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Representa uma posição de uma marca em um canto da página. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Representa uma posição de uma marca de registro em uma página. |
| [ReplyType](./replytype/) | Enumera os tipos de relacionamentos (o "tipo de resposta") entre a anotação e a especificada por InReplyTo. |
| [ReturnAction](./returnaction/) | Enum representa uma ação de fluxo de trabalho do programa no caso de invocar o método {@code IWarningCallback.Warning(WarningInfo)}. |
| [Rotation](./rotation/) | Enumeração dos valores de rotação possíveis. |
| [SaveFormat](./saveformat/) | Especifica o formato |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | Representa tipos de linha que podem ser usados no documento resultante para desenhar bordas ou outras linhas |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | Enumera os tipos possíveis de recursos externos salvos |
| [StampIcon](./stampicon/) | Enumera os ícones a serem usados na exibição da anotação. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | Enumera os tipos possíveis de arquivos de imagem que podem ser salvos como recursos externos durante a conversão de Pdf para SVG |
| [TextAlignment](./textalignment/) | Alinhamento do texto na anotação. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Modos de processamento de caminho de recorte |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Comportamento de substituição de fonte. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Modos de transformação de idioma |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Ação a ser executada se a fonte não contiver o caractere necessário |
| [TextRenderingMode](./textrenderingmode/) | O modo de renderização de texto, Tmode, determina se a exibição do texto deve causar contorno de glifos traçado, preenchido, usado como limite de recorte ou alguma combinação dos três. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Especifica uma política de como o tamanho da fonte do texto deve ser ajustado para caber dentro de uma área contêiner. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Escopo onde a operação de substituir texto é aplicada REPLACE_FIRST por padrão. Esta opção obsoleta foi mantida por compatibilidade. Ela afeta o PdfContentEditor e não tem efeito no TextFragmentAbsorber. |
| [VerticalAlignment](./verticalalignment/) | Enumeração dos possíveis valores de alinhamento vertical. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
