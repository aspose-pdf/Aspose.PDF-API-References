---
title: "com.aspose.pdf"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El com.aspose.pdf es un paquete raíz para todas las clases de la biblioteca Aspose.PDF para Java que están ya sea directamente en él como Document o indirectamente a través de varios subpaquetes."
type: docs
weight: 10
url: /es/java/com.aspose.pdf/
---
El com.aspose.pdf es un paquete raíz para todas las clases de la biblioteca Aspose.PDF para Java que están ya sea directamente en él como Document o indirectamente a través de varios subpaquetes.

## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | El procedimiento de devolución de llamada para el reconocimiento hocr. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | El procedimiento de devolución de llamada para el reconocimiento hocr. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | El procedimiento de devolución de llamada para el reconocimiento hocr. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | Contiene funcionalidad para ajustar fuentes |
| [IAnnotationVisitor](./iannotationvisitor/) | Define Visitor para visitar diferentes anotaciones de documentos. |
| [IAppointment](./iappointment/) | Representa la interfaz general para acciones y destinos. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Interfaz para estrategias de conversión de espacio de color. |
| [IDocument](./idocument/) | interfaz que representa un documento PDF |
| [IFontOptions](./ifontoptions/) | Propiedades útiles para ajustar el comportamiento de la fuente |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | Esta interfaz se declara para la personalización de algoritmos de cuantización. Los usuarios pueden implementar su propia realización de estos algoritmos (por ejemplo, algoritmos basados en código no administrado). |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | Esta interfaz se declara para la personalización de algoritmos de cuantización. Los usuarios pueden implementar su propia realización de estos algoritmos (por ejemplo, algoritmos basados en código no administrado). |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | Define Visitor para visitar diferentes operadores pdf. |
| [IPageSetOptions](./ipagesetoptions/) | Define opciones de conversión relacionadas con un conjunto de páginas a convertir. |
| [IPipelineOptions](./ipipelineoptions/) | Define opciones de conversión relacionadas con la configuración del pipeline. |
| [ITableElement](./itableelement/) | Esta interfaz representa un elemento de una tabla existente extraída por TableAbsorber. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado, que obtenga los recursos solicitados desde algún lugar. Por ejemplo, durante el uso de Aspose.PDf en la nube el acceso directo a los archivos referenciados es imposible, y se debe usar algún código personalizado colocado en un método especial. Este delegado define la firma de dicho método personalizado. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * Establecer la bandera que indica si la carpeta temporal se usará para alojar datos de fuentes temporales. / * Verdadero por defecto. / * Usar memoria del heap si el valor = false; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | Para una propiedad de este tipo puedes asignar un delegado creado a partir de un método personalizado que implemente el procesamiento del guardado externo de una imagen extraída de un SVG generado a partir de un PDF y que debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardado propio en un flujo o en disco) puede realizarse en ese código personalizado y dicho código debe devolver una ruta (o cualquier otra cadena sin comillas) que luego se incorporará al SVG generado en lugar de la ruta original supuesta del recurso de imagen. En este caso todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento de este u otro archivo, por alguna razón, debe ser realizado por el propio código del convertidor y no por el código personalizado, por favor establece en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo'. Esto indica al convertidor que todos los pasos necesarios para procesar ese recurso deben realizarse en el propio convertidor como si no existiera ningún código personalizado externo. |
## Clases

| Clase | Descripción |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Representa una celda de tabla que existe en la página |
| [AbsorbedRow](./absorbedrow/) | Representa una fila de tabla que existe en la página |
| [AbsorbedTable](./absorbedtable/) | Representa una tabla que existe en la página |
| [ActionCollection](./actioncollection/) | Colección de acciones |
| [Annotation](./annotation/) | Clase que representa un objeto de anotación. |
| [AnnotationActionCollection](./annotationactioncollection/) | Representa la colección de acciones de anotación. |
| [AnnotationCollection](./annotationcollection/) | Clase que representa una colección de anotaciones. |
| [AnnotationFlags](./annotationflags/) | Flags Conjunto de banderas binarias que especifican diversas características de la anotación. |
| [AnnotationSelector](./annotationselector/) | Esta clase se usa para seleccionar anotaciones utilizando la idea de plantilla Visitor. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | Clase para renderizar texto normal y enriquecido. |
| [AppearanceDictionary](./appearancedictionary/) | Diccionario de apariencia de anotación que especifica cómo debe presentarse visualmente la anotación en la página. |
| [ApsLoadOptions](./apsloadoptions/) | Clase que describe opciones de carga de APS. Opción para importar desde formato XML de APS. |
| [ApsSaveOptions](./apssaveoptions/) | Opciones de guardado para exportar al formato XML de APS. |
| [ApsToFlowConverter](./apstoflowconverter/) | Conversión de APS a Flow |
| [Artifact](./artifact/) | Clase que representa un objeto PDF Artifact. |
| [ArtifactCollection](./artifactcollection/) | Clase que representa una colección de artefactos. |
| [AutoTaggingSettings](./autotaggingsettings/) | Proporciona configuraciones para la funcionalidad de autoetiquetado en documentos PDF. La clase {@link AutoTaggingSettings} permite configurar opciones para el etiquetado automático del contenido PDF. Incluye propiedades para habilitar o deshabilitar el autoetiquetado, especificar una estrategia para el reconocimiento de encabezados y definir niveles de encabezado basados en tamaños de fuente. |
| [BackgroundArtifact](./backgroundartifact/) | Clase que describe un artefacto de fondo. Este artefacto permite establecer el fondo de la página. |
| [BarcodeField](./barcodefield/) | Clase que representa un campo de código de barras. |
| [BaseActionCollection](./baseactioncollection/) | Clase que encapsula acciones básicas con acciones interactivas de página/anotación/campo. |
| [BaseOperatorCollection](./baseoperatorcollection/) | Representa la clase base para la colección de operadores. |
| [BaseParagraph](./baseparagraph/) | Representa un objeto base abstracto que puede añadirse a la página (doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | Clase que describe el artefacto de numeración Bates. |
| [BitmapInfo](./bitmapinfo/) | Objeto que contiene una matriz de píxeles e información de mapa de bits. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | Formato de píxel de mapa de bits. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Representa una anotación de marca de sangrado. Las marcas de sangrado se colocan en las esquinas de una página impresa para indicar dónde se debe recortar la página y cuán lejos se permite que se desvíe de las marcas de recorte. |
| [Border](./border/) | Clase que representa las características del borde de la anotación. |
| [BorderInfo](./borderinfo/) | Esta clase representa el borde para elementos gráficos. |
| [BorderSide](./borderside/) | Banderas que enumeran los lados del borde en binario. |
| [BorderStyleConverter](./borderstyleconverter/) | Representa la clase BorderStyleConverter |
| [Brush](./brush/) | Esta clase representa un pincel abstracto |
| [BuildVersionInfo](./buildversioninfo/) | Esta clase proporciona información sobre la compilación actual del producto. |
| [ButtonField](./buttonfield/) | Clase que representa un campo de botón pulsador. |
| [CaretAnnotation](./caretannotation/) | Clase que representa una anotación de cursor. |
| [CaretSymbolConverter](./caretsymbolconverter/) | Representa la clase CaretSymbolConverter |
| [CdrLoadOptions](./cdrloadoptions/) | Clase que describe las opciones de carga CDR. |
| [Cell](./cell/) | Representa una celda de la fila de la tabla. |
| [Cells](./cells/) | Representa una colección de celdas de la fila. |
| [CgmImportOptions](./cgmimportoptions/) | Opción de importación para importar desde el formato Computer Graphics Metafile (CGM). |
| [CgmLoadOptions](./cgmloadoptions/) | Contiene opciones para cargar/importar un archivo CGM en un documento pdf. |
| [Characteristics](./characteristics/) | Representa las características de la anotación |
| [CharInfo](./charinfo/) | Representa un objeto de información de carácter. Proporciona información de posicionamiento de caracteres. |
| [CharInfoCollection](./charinfocollection/) | <p> Representa la colección de objetos CharInfo. </p> <hr> <pre> El ejemplo demuestra cómo iterar a través de todos los caracteres y recuperar el carácter //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Proporciona acceso a la información de posicionamiento de los caracteres del segmento de texto. </p> |
| [CheckboxField](./checkboxfield/) | Clase que representa un campo de casilla de verificación |
| [ChoiceField](./choicefield/) | Representa la clase base para campos de opción. |
| [CircleAnnotation](./circleannotation/) | Clase que representa una anotación de círculo. |
| [Collection](./collection/) | Representa la clase para Collection(12.3.5 Collections). |
| [CollectionField](./collectionfield/) | Representa una clase de campo de esquema de colección de documentos. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Representa el parámetro de subtipo de un campo en una colección de esquema. |
| [CollectionItem](./collectionitem/) | Representa una clase de elemento de colección. El elemento de colección contiene los datos descritos por el esquema de la colección. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | Representa una clase para un valor de elemento de colección. |
| [CollectionSchema](./collectionschema/) | Representa una clase que describe el \"Esquema\" de una colección de documentos. |
| [Color](./color/) | Representa una clase para valor de color que puede expresarse en diferentes espacios de color. |
| [ColorBarAnnotation](./colorbarannotation/) | Clase que representa la anotación ColorBarAnnotation. La propiedad Color se ignora, en su lugar se utiliza el color ColorsOfCMYK. Al crearla, la proporción de ancho y alto determina la orientación de la anotación: horizontal o vertical. A continuación, verifica que el rectángulo de la anotación esté fuera del TrimBox y, si no lo está, se desplaza a la ubicación más cercana fuera del TrimBox, teniendo en cuenta la orientación de la anotación. Es posible reducir el ancho (alto) para que la anotación encaje fuera del TrimBox. Si no hay espacio para el diseño, el ancho/alto puede establecerse en cero (en este caso, la anotación está presente en la página, pero no se muestra). |
| [ColumnInfo](./columninfo/) | Esta clase representa la información de una columna. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | Clase que representa eventos |
| [ComboBoxField](./comboboxfield/) | Clase que representa el campo Combobox del formulario. |
| [ComHelper](./comhelper/) | <p> Proporciona métodos para clientes COM para cargar un documento en Aspose.PDF. </p> <hr> <p> Utilice la clase ComHelper para cargar un documento desde un archivo o flujo en un objeto Document en una aplicación COM. La clase Document proporciona un constructor predeterminado para crear un nuevo documento y también ofrece constructores sobrecargados para cargar un documento desde un archivo o flujo. Si está usando Aspose.Words desde una aplicación .NET, puede usar todos los constructores de Document directamente, pero si está usando Aspose.PDF desde una aplicación COM, solo está disponible el constructor predeterminado de Document. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | Clase abstracta que representa una anotación de figura común. |
| [CompositingParameters](./compositingparameters/) | Representa un objeto que contiene los parámetros de composición gráfica del estado gráfico actual. |
| [ContentsAppender](./contentsappender/) | Realiza modificaciones de contenido solo en modo APPEND. Este modo permite evitar el análisis innecesario y pesado del contenido antes de que se realice algún cambio. Solo agrega nuevos operadores al final o al inicio del contenido. |
| [Copier](./copier/) | Clase para copiar objetos. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Representa tipos de anotación que se colocan en las esquinas de la página impresa. |
| [CustomExplicitDestination](./customexplicitdestination/) | Representa un destino explícito personalizado. |
| [CustomSign](./customsign/) | Delegado para firmar el documento de forma personalizada (Beta). |
| [Dash](./dash/) | Clase que representa el patrón de guiones de línea. |
| [DateField](./datefield/) | Campo de fecha con vista de calendario. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | Describe la apariencia predeterminada del campo (fuente, tamaño de texto y color). |
| [DefaultDirectory](./defaultdirectory/) | Especifica la ruta predeterminada para algún propósito |
| [DestinationCollection](./destinationcollection/) | Clase que representa la colección de todos los destinos (un árbol de nombres que asigna cadenas de nombres a destinos (ver 12.3.2.3, \"Named Destinations\") y (ver 7.7.4, \"Name Dictionary\")) en el documento pdf. |
| [DestinationFactory](./destinationfactory/) | Representa la clase DestinationFactory |
| [DjvuLoadOptions](./djvuloadoptions/) | Clase que describe las opciones de carga DJVU. |
| [DocMDPSignature](./docmdpsignature/) | Representa la clase de documento MDP (detección y prevención de modificaciones) tipo de firma. |
| [DocSaveOptions](./docsaveoptions/) | Opciones de guardado para exportar al formato Doc |
| [Document](./document/) | Clase que representa un documento PDF. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | Clase que describe el algoritmo de optimización de documentos. Una instancia de esta clase puede usarse como parámetro del método OptimizeResources(). @deprecated Esta clase está obsoleta. Por favor use com.aspose.pdf.optimization.OptimizationOptions en su lugar. |
| [Document.RepairOptions](./document.repairoptions/) | Representa opciones para reparar un documento PDF. Esta clase proporciona una forma de personalizar el proceso de reparación de un documento PDF. |
| [DocumentActionCollection](./documentactioncollection/) | Clase que describe acciones realizadas sobre algunas acciones con el documento |
| [DocumentExtensions](./documentextensions/) | Proporciona capacidades adicionales para la clase Document. |
| [DocumentFactory](./documentfactory/) | Clase que permite crear/cargar documentos de diferentes tipos. |
| [DocumentInfo](./documentinfo/) | Representa la información meta de un documento PDF. |
| [DocumentWeb](./documentweb/) | Representa la clase DocumentWeb |
| [Element](./element/) | Clase que representa el elemento base de la estructura lógica. |
| [ElementCollection](./elementcollection/) | Colección de elementos base de la estructura lógica. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Clase que representa la colección de archivos incrustados. |
| [EncryptedPayload](./encryptedpayload/) | Representa la carga útil cifrada en la especificación de archivo. |
| [EpubLoadOptions](./epubloadoptions/) | Contiene opciones para cargar/importar un archivo EPUB en un documento pdf. |
| [EpubSaveOptions](./epubsaveoptions/) | Opciones de guardado para exportar al formato EPUB |
| [ExcelSaveOptions](./excelsaveoptions/) | Opciones de guardado para exportar al formato Excel |
| [ExplicitDestination](./explicitdestination/) | Representa la clase base para destinos explícitos en un documento PDF. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | Representa la clase ExplicitDestinationTypeConverter |
| [ExportFieldsOptions](./exportfieldsoptions/) | Representa la clase base de opciones para exportar campos de formulario. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Representa opciones para exportar campos de formulario al formato Json. Hereda de {@link ExportFieldsOptions} y agrega opciones específicas para la exportación Json. |
| [ExportImportMessages](./exportimportmessages/) | Contiene varios mensajes de error para operaciones de exportación e importación de campos de formulario. |
| [ExternalSignature](./externalsignature/) | Crea una firma PKCS#7Detached separada usando un X509Certificate2. Soporta tarjetas inteligentes usb, tokens sin claves privadas exportables. |
| [FdfReader](./fdfreader/) | Clase que realiza la lectura del formato FDF. Document doc = new Document(\"example.pdf\"); InputStream fdfStream = FileInputStream(\"file.fdf\"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save(\"example_out.pdf\"); |
| [Field](./field/) | Clase base para campos de formulario acro. |
| [FieldSerializationResult](./fieldserializationresult/) | Representa el resultado de un proceso de serialización de campos de formulario. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Representa el estado de la serialización de campos de formulario. |
| [FieldValueType](./fieldvaluetype/) | Representa el tipo de valor de campo en una colección de esquemas. |
| [FigureElement](./figureelement/) | Clase que representa la figura de estructura lógica. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Clase que describe la anotación de archivo adjunto. |
| [FileFontSource](./filefontsource/) | Representa una única fuente de archivo de fuente. |
| [FileHyperlink](./filehyperlink/) | Representa un objeto de hipervínculo de archivo. |
| [FileIconConverter](./fileiconconverter/) | Representa la clase FileIconConverter |
| [FileParams](./fileparams/) | Define un diccionario de parámetros de archivo incrustado que debe contener información adicional específica del archivo. |
| [FileSelectBoxField](./fileselectboxfield/) | Campo para el elemento de cuadro de selección de archivo. |
| [FileSpecification](./filespecification/) | Clase que representa un archivo incrustado. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que su cuadro delimitador quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el cuadro delimitador dentro de la ventana en la otra dimensión. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo justo para que el ancho completo de su cuadro delimitador quepa dentro de la ventana. Un valor nulo para top indica que el valor actual de ese parámetro debe conservarse sin cambios. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo justo para que la altura completa de su cuadro delimitador quepa dentro de la ventana. Un valor nulo para left indica que el valor actual de ese parámetro debe conservarse sin cambios. |
| [FitExplicitDestination](./fitexplicitdestination/) | Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que la página completa quepa dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando la página dentro de la ventana en la otra dimensión. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo justo para que el ancho completo de la página quepa dentro de la ventana. Un valor nulo para top indica que el valor actual de ese parámetro debe conservarse sin cambios. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que el rectángulo especificado por las coordenadas izquierda, inferior, derecha y superior quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede resultar en un comportamiento impredecible. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo justo para que la altura completa de la página quepa dentro de la ventana. Un valor nulo para left indica que el valor actual de ese parámetro debe conservarse sin cambios. |
| [FixedPrint](./fixedprint/) | Representa datos de impresión fija de la anotación de marca de agua. |
| [FloatingBox](./floatingbox/) | Representa un FloatingBox en un documento PDF. FloatingBox está posicionado de forma personalizada. |
| [FlowConverter](./flowconverter/) | Convertir documento PDF a formatos Flow (XLSX, ODS, XMLSpreedSheet2003, CSV) DOCX en modo EnchanedFlow, TableAbsorber en modo FlowEngine. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Transmitiendo datos de la biblioteca Flow a TableAbsorber |
| [FolderFontSource](./folderfontsource/) | Representa la carpeta que contiene archivos de fuentes. |
| [Font](./font/) | <p> Representa un objeto de fuente. </p> <hr> <pre> El ejemplo muestra cómo buscar texto en la primera página y cambiar la fuente de la primera aparición encontrada. // Abrir documento Document doc = new Document(\"input.pdf\"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias de texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Crear fuente y marcarla para incrustarla Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Cambiar la fuente de la primera aparición de texto absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Guardar documento doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | Representa un objeto absorber de fuentes. Realiza búsquedas de fuentes y proporciona acceso a los resultados de búsqueda a través de la colección {@code FontAbsorber.Fonts}. |
| [FontCollection](./fontcollection/) | <p> Representa una colección de fuentes. </p> <hr> <pre> El ejemplo muestra cómo hacer que todas las fuentes declaradas en la página estén incrustadas. // Abrir documento Document doc = new Document(\"D:\\\\\\Tests\\\\\\\input.pdf\"); // asegurar que todas las fuentes declaradas en los recursos de la página estén incrustadas // notar que si las fuentes se declaran en los recursos del formulario no son accesibles desde los recursos de la página for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save(\"D:\\\\\\Tests\\\\\\\input.pdf\"); </pre> <hr> <p> Las colecciones de fuentes representadas por la clase {@code FontCollection} se utilizan en varios escenarios. Por ejemplo, en recursos con la propiedad {@code Resources.Fonts}. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | El estándar PDF/A requiere que todas las fuentes estén incrustadas en el documento. Esta clase incluye indicadores para los casos en que no es posible incrustar alguna fuente porque dicha fuente está ausente en el PC de destino. |
| [FontRepository](./fontrepository/) | <p> Realiza búsquedas de fuentes. Busca en fuentes instaladas en el sistema y fuentes PDF estándar. También proporciona funcionalidad para abrir fuentes personalizadas. </p> <hr> <pre> El ejemplo muestra cómo encontrar una fuente y reemplazar la fuente del texto de la primera página. // Encontrar fuente Font font = FontRepository.findFont(\"Arial\"); // Abrir documento Document doc = new Document(\"D:\\\\\\Tests\\\\\\\input.pdf\"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias de texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Cambiar la fuente de la primera aparición de texto absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Guardar documento doc.save(\"D:\\\\\\Tests\\\\\\\output.pdf\"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | Representa una clase base para la fuente. |
| [FontStyles](./fontstyles/) | Bandera binaria <p> Especifica la información de estilo aplicada al texto. </p> <hr> <p> Esta enumeración tiene un atributo {@code FlagsAttribute} que permite una combinación de sus valores de miembros. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Bandera binaria enumera estrategias para la subdivisión de fuentes |
| [FooterArtifact](./footerartifact/) | Describe el artefacto de pie de página. Esto puede usarse para establecer el pie de página de la página. |
| [Form](./form/) | Clase que representa un objeto de formulario. |
| [Form.FlattenSettings](./form.flattensettings/) | Clase que describe la configuración del procedimiento de aplanado de formularios. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | Los formularios pueden contener información de firma y pueden estar firmados o no. A veces la vista de los formularios en el visor debe depender de si el formulario está firmado o no. Esta enumeración enumera los posibles modos de renderizado durante la conversión del tipo de formulario con respecto a la firma. |
| [FormattedFragment](./formattedfragment/) | Representa un fragmento formateado abstracto. |
| [FreeTextAnnotation](./freetextannotation/) | Representa una anotación de texto libre que muestra texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible. |
| [GoToAction](./gotoaction/) | Representa una acción ir a que cambia la vista a un destino especificado (página, ubicación y factor de ampliación). |
| [GoToRemoteAction](./gotoremoteaction/) | Representa una acción ir a remota que es similar a una acción ir a ordinaria pero salta a un destino en otro archivo PDF en lugar del archivo actual. |
| [GoToURIAction](./gotouriaction/) | Representa una acción URI que provoca que se resuelva un URI. |
| [GraphInfo](./graphinfo/) | Representa información gráfica. |
| [Group](./group/) | Una clase de atributos de grupo que especifica los atributos del grupo de página para su uso en el modelo de imágenes transparente. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | Clase que describe el artefacto Heaader. Este artefacto puede usarse para establecer el encabezado de la página. |
| [HeaderFooter](./headerfooter/) | Clase que representa la página pdf de encabezado o pie de página. |
| [Heading](./heading/) | Representa el encabezado. |
| [HideAction](./hideaction/) | Representa una acción de ocultar que oculta o muestra una o más anotaciones en la pantalla estableciendo o borrando sus banderas Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Representa una anotación de resaltado que destaca un rango de texto en el documento. |
| [HtmlFragment](./htmlfragment/) | Representa un fragmento html. |
| [HtmlLoadOptions](./htmlloadoptions/) | Representa opciones para cargar/importar un archivo html en un documento pdf. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Bandera binaria que especifica banderas que, junto con otras opciones, determinan los tamaños y disposiciones de las páginas. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Opciones de guardado para exportar al formato Html |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | Este enum describe posibles medidas de antialiasing durante la conversión |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | Esta clase representa un conjunto de datos relacionados con el guardado personalizado de CSS durante la conversión de PDF a formato HTML |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | Puede asignar a esta propiedad una estrategia personalizada que implemente el procesamiento y/o guardado de una parte de CSS que se creó durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar en un flujo o disco) debe realizarse en ese código personalizado |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente la creación de la URL del CSS referenciado en el documento HTML generado. Por ejemplo, si desea que el CSS sea referenciado en HTML, por ejemplo como \"otherPage.ASPX?CssID=zjjkklj\", entonces dicha estrategia personalizada debe devolver \"otherPage.ASPX?CssID=zjjkklj\" |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | Representa un conjunto de datos relacionados con la solicitud del conversor al código personalizado destinada a obtener la URL deseada (o plantilla de URL) del CSS en cuestión |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | Esta enumeración define reglas que afinan la lógica de codificación |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | Enumera los modos que pueden usarse para guardar fuentes referenciadas en el PDF guardado. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | Esta clase representa un conjunto de datos relacionados con el guardado de archivos de imagen de recursos externos durante la conversión de PDF a HTML. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | Enumera los tipos posibles de archivos de imagen que pueden guardarse como recursos externos durante la conversión de Pdf a Html. |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | A veces existen requisitos específicos para el HTML creado. Este enum define los modos de preparación de HTML que pueden usarse durante la conversión de PDF a HTML para cumplir dichos requisitos específicos. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | Si la propiedad SplitToPages de HtmlSaveOptions está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión de PDF a HTML. Esta clase representa un conjunto de datos relacionados con el guardado personalizado del marcado de una página HTML durante la conversión de PDF a HTML. |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | El resultado de la conversión puede contener una o varias páginas HTML (que también pueden referenciar archivos externos como imágenes o fuentes). Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente el procesamiento de la página HTML obtenida (el propio HTML) que se creó durante la conversión. En tal caso, el procesamiento (como guardar en un flujo o disco) puede realizarse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar el marcado de la página HTML deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del conversor no se utilizará. Si el procesamiento para este u otro caso, por alguna razón, debe ser realizado por el propio código del conversor y no por código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'htmlSavingInfo': indica al conversor que todos los pasos necesarios para procesar ese recurso deben realizarse en el conversor mismo, de la misma manera que si no hubiera ningún código externo de guardado personalizado. |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | Enumera los tipos posibles de padres de una imagen; la imagen puede pertenecer a una página HTML o a una imagen padre SVG. |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | Este enum enumera los modos posibles de incrustación de archivos referenciados en HTML. Permite controlar si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas. |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | El PDF convertido puede contener imágenes raster (.png, *.jpeg, etc.). Este enum define los métodos de cómo pueden manejarse las imágenes raster durante la conversión de PDF a HTML. |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | A esta propiedad puedes asignar un delegado creado a partir de un método personalizado que implementa el procesamiento de un recurso externo (Fuente o Imagen) que fue extraído del PDF y debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar en un flujo o en disco) puede realizarse en ese código personalizado y ese código personalizado debe devolver una ruta (o cualquier otra cadena sin comillas) que luego se incorporará al HTML generado en lugar de la ruta original supuesta para ese recurso de imagen. En tal caso, todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método suministrado, porque guardar el resultado en el código del convertidor no se utilizará. Si el procesamiento de este u otro archivo por alguna razón debe ser realizado por el código del convertidor mismo, no en el código personalizado, por favor establece en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'resourceSavingInfo'. Señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor como si no hubiera ningún código personalizado externo. |
| [Hyperlink](./hyperlink/) | Representa un hipervínculo abstracto. |
| [IconFit](./iconfit/) | Describe cómo se debe mostrar el ícono de la anotación de widget dentro de su rectángulo de anotación. |
| [Id](./id/) | <p> Representa la estructura del identificador de archivo. </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | Representa una imagen. |
| [ImageDeleteAction](./imagedeleteaction/) | Acción que se realiza con el objeto de imagen cuando la imagen se elimina de la colección. Si el objeto de imagen se elimina |
| [ImagePlacement](./imageplacement/) | <p> Representa las características de una imagen colocada en una página de documento Pdf. </p> <hr> <pre> El ejemplo muestra cómo encontrar imágenes en la primera página del documento PDF y obtener las imágenes como mapas de bits con dimensiones visibles. // Abrir documento Document doc = new Document(\"D:\\\\\\Tests\\\\\\\input.pdf\"); // Crear objeto ImagePlacementAbsorber para realizar la búsqueda de colocación de imágenes ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Aceptar el absorbente para la primera página doc.getPages().get_Item(1).accept(abs); // Recuperar imágenes con dimensiones visibles for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Recuperar imagen de los recursos imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Crear nuevo bitmap con dimensiones reales scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Cuando una imagen se coloca en una página puede tener dimensiones diferentes a las dimensiones físicas definidas en {@code Resources}. El objeto {@code ImagePlacement} está destinado a proporcionar dicha información como dimensiones, resolución, etc. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> Representa un objeto absorbente de objetos de colocación de imágenes. Realiza la búsqueda de usos de imágenes y proporciona acceso a los resultados de búsqueda a través de la colección {@code ImagePlacementAbsorber.ImagePlacements}. </p> <hr> <pre> El ejemplo muestra cómo encontrar imágenes en la primera página del documento PDF y obtener las propiedades de colocación de la imagen. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> El objeto {@code ImagePlacementAbsorber} se utiliza fundamentalmente en escenarios de búsqueda de imágenes. Cuando la búsqueda se completa, las ocurrencias se representan con objetos {@code ImagePlacement} que contiene la colección {@code ImagePlacementAbsorber.ImagePlacements}. El objeto {@code ImagePlacement} proporciona acceso a las propiedades de colocación de la imagen: dimensiones, resolución, etc. </p> La rotación positiva de la imagen es en sentido antihorario, para la página es en sentido horario. Aquí, necesitamos representar el ángulo de rotación de la imagen, por lo que deducimos el ángulo de la página del ángulo de la imagen. |
| [ImagePlacementCollection](./imageplacementcollection/) | Representa una colección de colocaciones de imágenes |
| [ImageStamp](./imagestamp/) | Representa un sello gráfico. |
| [ImageType](./imagetype/) | Representa tipos de formato de imagen. |
| [ImportDataAction](./importdataaction/) | Al invocar una acción de importación de datos, los datos del Formato de Datos de Formularios (FDF) se importarán al formulario interactivo del documento desde un archivo especificado. |
| [ImportFieldsOptions](./importfieldsoptions/) | Representa la clase base de opciones para importar campos de formulario. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Representa opciones para importar campos de formulario al formato Json. Hereda de {@code ImportFieldsOptions} y agrega opciones específicas para la importación Json. |
| [ImportOptions](./importoptions/) | El tipo ImportOptions mantiene un nivel de abstracción sobre opciones de importación individuales. |
| [InkAnnotation](./inkannotation/) | Representa un \"garabato\" a mano alzada compuesto por una o más rutas disjuntas. |
| [InternalHelper](./internalhelper/) | Clase interna |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | La excepción que se lanza cuando una operación con el tipo de formulario no es válida. |
| [JavascriptAction](./javascriptaction/) | Clase que representa una acción JavaScript. |
| [JavaScriptCollection](./javascriptcollection/) | Esta clase representa una colección de JavaScript. |
| [LatexFragment](./latexfragment/) | Representa un fragmento TeX. @deprecated Por favor use TeXFragment en su lugar |
| [LatexLoadOptions](./latexloadoptions/) | Representa opciones para cargar/importar un archivo TeX en un documento PDF. @deprecated Use TeXLoadOptions instead. |
| [LaTeXSaveOptions](./latexsaveoptions/) | Opciones de guardado para exportar al formato TeX. @deprecated Use TeXSaveOptions instead |
| [LaunchAction](./launchaction/) | Representa una acción de lanzamiento que inicia una aplicación o abre o imprime un documento. |
| [Layer](./layer/) | Representa una capa dentro de una página PDF. |
| [LevelFormat](./levelformat/) | Representa el formato de la tabla de contenidos. |
| [License](./license/) | Proporciona métodos para licenciar el componente. En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama. License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | Representa información de licencia. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | Colección ligera de operadores. Destinada a usarse en escenarios donde el flujo de contenido subyacente no está adjunto, y solo se requiere la colección de operadores como resultado. |
| [LineAnnotation](./lineannotation/) | Clase que representa una anotación de línea. |
| [LineEndingConverter](./lineendingconverter/) | Representa la clase LineEndingConverter |
| [LineEndingsDrawer](./lineendingsdrawer/) | Dibuja terminaciones de línea para anotaciones. Clase interna solo para uso interno. |
| [LinkAnnotation](./linkannotation/) | Representa ya sea un enlace hipertexto a un destino en otra parte del documento o una acción a realizar. |
| [ListBoxField](./listboxfield/) | La clase representa el campo ListBox. |
| [LoadOptions](./loadoptions/) | El tipo LoadOptions mantiene un nivel de abstracción en opciones de carga individuales. |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | Representa el modo de uso del área de márgenes durante la conversión (como HTML, EPUB, etc.), define el tratamiento de las instrucciones del formato importado relacionadas con el uso de los márgenes. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | ¡ATENCIÓN! La característica está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED detectado en el documento de ejemplo. Representa el modo de uso del tamaño de página durante la conversión. Los formatos (como HTML, EPUB, etc.), suelen tener un diseño flotante, por lo que permite ajustar el tamaño de página requerido. Pero a veces el contenido especifica posiciones horizontales o un tamaño que no permite colocar el contenido en el tamaño de página requerido. En tal caso podemos definir qué debe hacerse (es decir, cuando el tamaño del contenido no encaja en el tamaño de página inicial requerido del documento PDF resultante). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | Resultado de la carga personalizada del recurso |
| [LocaleOptions](./localeoptions/) | El tipo LocaleOptions especifica la configuración regional para Aspose.PDF. |
| [LocalHyperlink](./localhyperlink/) | Representa un objeto de hipervínculo local. |
| [MarginInfo](./margininfo/) | Esta clase representa un margen para diferentes objetos. |
| [MarkupAnnotation](./markupannotation/) | Clase abstracta que representa una anotación de marcado. |
| [MarkupParagraph](./markupparagraph/) | Representa un párrafo. |
| [MarkupSection](./markupsection/) | Representa una sección de marcado: la región rectangular de una página que contiene texto y puede dividirse visualmente de otros bloques de texto. |
| [Matrix](./matrix/) | Clase que representa una matriz de transformación. |
| [Matrix3D](./matrix3d/) | Clase que representa una matriz de transformación. |
| [MdLoadOptions](./mdloadoptions/) | Opciones de carga para la conversión de formato Markdown. |
| [Measure](./measure/) | Clase que describe el sistema de coordenadas Measure. |
| [Measure.NumberFormat](./measure.numberformat/) | Formato numérico para medida. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | Representa una lista de formatos numéricos. |
| [MediaClip](./mediaclip/) | Clase que describe el objeto de clip multimedia de la representación. |
| [MediaClipData](./mediaclipdata/) | Clase que describe los datos del clip multimedia. |
| [MediaClipSection](./mediaclipsection/) | Esta clase describe la sección del clip multimedia. |
| [MediaRendition](./mediarendition/) | Clase que describe la representación multimedia. |
| [MemoryCleaner](./memorycleaner/) | Representa la clase MemoryCleaner |
| [MemoryExtender](./memoryextender/) | Representa la clase MemoryExtender. Al usar archivos grandes en un sistema con memoria heap limitada, se puede habilitar para usar espacio en disco como memoria de intercambio temporal. |
| [MemoryFontSource](./memoryfontsource/) | Representa una única fuente de archivo de fuente. |
| [Metadata](./metadata/) | Proporciona acceso al flujo de metadatos XMP. |
| [Metered](./metered/) | <p> Proporciona métodos para establecer la clave medida. </p> <hr> En este ejemplo, se intentará establecer la clave pública y privada medida <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | Representa opciones para cargar/importar un archivo .mht en un documento pdf. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Opciones de guardado para exportar al formato Xml |
| [MovieAnnotation](./movieannotation/) | Representa una anotación de película que contiene gráficos animados y sonido para ser presentados en la pantalla del ordenador y a través de los altavoces. Cuando la anotación se activa, la película se reproduce. |
| [NamedAction](./namedaction/) | Representa acciones nombradas que se espera que soporten las aplicaciones visor de PDF. |
| [NamedDestination](./nameddestination/) | En lugar de definirse directamente con la sintaxis explícita, un destino puede referirse indirectamente mediante un objeto de nombre o una cadena de bytes. |
| [Note](./note/) | Esta clase representa una nota de párrafo generador. |
| [NumberField](./numberfield/) | Campo de texto con caracteres válidos especificados @see TextBoxField |
| [NumberTree](./numbertree/) | Clase que representa la estructura de árbol de números de un archivo PDF. 7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | Representa la configuración OCSP utilizada durante el proceso de firma. |
| [OfdLoadOptions](./ofdloadoptions/) | Opciones de carga para el formato OFD. |
| [Operator](./operator/) | Clase abstracta que representa un operador. |
| [OperatorCollection](./operatorcollection/) | Clase que representa una colección de operadores |
| [OperatorSelector](./operatorselector/) | Esta clase se usa para seleccionar operadores utilizando la idea del patrón Visitor. |
| [Opi](./opi/) | Representa la Interfaz de Preimpresión Abierta (OPI), que es un mecanismo para crear marcadores de posición de baja resolución, o proxies, para imágenes de alta resolución. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Define un MemoryStream que puede contener una mayor capacidad estándar |
| [Option](./option/) | Clase que representa una opción de campo de selección. |
| [OptionCollection](./optioncollection/) | Clase que representa la colección de opciones del campo de selección. |
| [OutlineCollection](./outlinecollection/) | Representa la jerarquía del esquema del documento. |
| [OutlineItemCollection](./outlineitemcollection/) | Representa una entrada del esquema en la jerarquía del esquema de un documento PDF. |
| [Outlines](./outlines/) | Clase que describe una colección de esquemas. |
| [OutputIntent](./outputintent/) | Representa una intención de salida que coincide con las características de color de un documento PDF con las de un dispositivo de salida objetivo o entorno de producción en el que se imprimirá el documento. |
| [OutputIntents](./outputintents/) | Representa la colección de {@link OutputIntent}. |
| [Page](./page/) | Clase que representa una página de un documento PDF. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | Procedimiento para personalizar el encabezado y el pie de página. |
| [PageActionCollection](./pageactioncollection/) | Esta clase describe acciones de página |
| [PageCollection](./pagecollection/) | Colección de páginas de documentos PDF. |
| [PageExtensions](./pageextensions/) | Proporciona capacidades adicionales para la clase Page. |
| [PageInfo](./pageinfo/) | Representa la información de página para el generador de PDF. |
| [PageInformationAnnotation](./pageinformationannotation/) | Representa una anotación Page Information en un documento PDF. Esta anotación contiene el nombre del archivo, el número de página y la fecha y hora de creación de la anotación. Esta clase se utiliza principalmente para agregar metadatos a una página específica del documento PDF, lo que puede ser útil para fines de seguimiento y referencia. Por ejemplo, puede usarse para marcar páginas durante el proceso de impresión o para proporcionar información adicional sobre la página al visualizar el documento. |
| [PageLabel](./pagelabel/) | Clase que representa el rango de Page Label. |
| [PageLabelCollection](./pagelabelcollection/) | Clase que representa la colección de page label. |
| [PageMarkup](./pagemarkup/) | Marcado de página representado por colecciones de {@code MarkupSection} y {@code MarkupParagraph}. |
| [PageNumberStamp](./pagenumberstamp/) | Representa el sello de número de página y se usa para numerar páginas. |
| [PageSize](./pagesize/) | Clase que representa el tamaño de página en un documento PDF. |
| [PaginationArtifact](./paginationartifact/) | Representa una clase base abstracta para artefactos de paginación en un documento. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> Representa un objeto absorbente de objetos de estructura de página como secciones y párrafos. Realiza búsquedas de secciones y párrafos de texto y proporciona acceso a rectángulos y polígonos que lo describen en el espacio de coordenadas del texto. También realiza búsquedas de segmentos de texto y proporciona acceso a los resultados de búsqueda mediante colecciones de {@code TextFragments} agrupadas por elementos de estructura. </p> El ejemplo muestra cómo encontrar el primer segmento de texto de cada párrafo en la primera página del documento PDF y resaltarlo. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Cuando la búsqueda se completa, la colección {@code ParagraphAbsorber.PageMarkups} contendrá objetos {@code PageMarkup} que representan la estructura de la página mediante colecciones de {@code MarkupSection} y {@code MarkupParagraph}. El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, a sus propiedades y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc). |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Representa opciones para el {@link ParagraphAbsorber}. |
| [Paragraphs](./paragraphs/) | Esta clase representa una colección de párrafos. |
| [PasswordBoxField](./passwordboxfield/) | Clase que describe un campo de texto para ingresar la contraseña. |
| [PclLoadOptions](./pclloadoptions/) | Representa opciones para cargar (importar) un archivo PCL en un documento PDF. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | Enumera los motores de conversión que pueden usarse para la conversión. |
| [PDF3DAnnotation](./pdf3dannotation/) | Clase PDF3DAnnotation. Esta clase no puede heredarse. @see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | Clase PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Clase PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Clase PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Clase PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Clase PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Clase PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Clase PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Clase PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Clase PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Clase PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Representa Acción en el documento PDF |
| [PdfActionCollection](./pdfactioncollection/) | Clase describe lista de acciones. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | Esta clase describe reglas que pueden usarse para ajustar el proceso de copia de datos de codificación en casos en que una fuente TrueType simbólica tiene más de una codificación. Algunos documentos PDF después de la conversión al formato PDF/A pueden generar un error \"More than one encoding in symbolic TrueType font's cmap\". ¿Cuál es la razón de este error? Todas las fuentes TrueType simbólicas tienen una tabla especial \"cmap\" en sus datos internos. Esta tabla asigna códigos de caracteres a índices de glifos. Y esta tabla puede contener diferentes subtablas de codificación que describen las codificaciones usadas. Consulte información avanzada sobre las tablas cmap en https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Normalmente la tabla cmap contiene varias subtablas de codificación, pero la norma PDF/A requiere que o bien solo quede una subtabla de codificación para esta fuente en el documento PDF/A o que exista una subtabla de codificación (3,0) entre las subtablas de esta fuente. Y la pregunta clave aquí: ¿qué datos deben tomarse de otras subtablas para copiar en la tabla de codificación de destino (3,0)? La mayoría de las fuentes tienen tablas cmap "bien formadas" donde cada subtabla de codificación es completamente consistente con otra subtabla. Pero algunas fuentes tienen tablas cmap con colisiones, por ejemplo una subtabla tiene el índice de glifo 100 para unicode 100, pero otra subtabla tiene el índice de glifo 200 para el mismo unicode 100. Para resolver estos problemas se necesita una estrategia especial. Por defecto se usa la siguiente estrategia: se busca la subtabla mac (1,0). Si se encuentra esta tabla, solo esos datos se usan para rellenar la tabla de destino (3,0). Si la subtabla mac no se encuentra, entonces se iteran todas las subtablas excepto la (3,0) y se usan para copiar datos a la subtabla de destino (3,0). Además, el mapeo para cada unicode (unicode, índice de glifo) se copia a la tabla de destino solo si la tabla de destino no tiene ese unicode en ese momento. Así, por ejemplo, si la primera subtabla tiene el índice de glifo 100 para unicode 100, y la siguiente subtabla tiene el índice de glifo 200 para el mismo unicode 100, solo se copiarán los datos de la primera subtabla (unicode=100, índice de glifo = 100). Por lo tanto, cada subtabla anterior tiene precedencia sobre la siguiente. Las propiedades de esta clase { PdfASymbolicFontEncodingStrategy} ayudan a ajustar el comportamiento predeterminado. Si la propiedad {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) de tipo { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} está establecida, entonces la subtabla relevante se usará con precedencia sobre la subtabla mac (1,0). El valor 'MacTable' de la enumeración {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} no tiene sentido en este caso, ya que apunta a la misma subtabla mac (1,0) que se usa por defecto. La propiedad {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) descarta todas las prioridades para cualquier subtabla. Si esta propiedad está establecida, solo se usarán las subtablas de la cola declarada en el orden especificado. Si las subtablas especificadas no se encuentran, se usará la iteración predeterminada de todas las subtablas y la estrategia de copia descrita arriba. El objeto { PdfASymbolicFontEncodingStrategy.QueueItem} especifica la subtabla de codificación utilizada. Esta subtabla puede establecerse mediante una combinación de miembros (PlatformID, PlatformSpecificId) o mediante la enumeración { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. En caso de que la fuente no tenga subtabla (3,0), se usará otra subtabla para mantener la compatibilidad PDF/A. La elección de la subtabla a usar se realiza bajo las mismas reglas descritas anteriormente, de modo que las propiedades {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) y {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) se utilizan para determinar la subtabla resultante, y si la fuente no tiene la(s) subtabla(s) solicitada(s), se usará cualquier subtabla existente. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | Especifica la subtabla de codificación. Cada subtabla de codificación tiene una combinación única de parámetros (PlatformID, PlatformSpecificID). La enumeración {@code CMapEncodingTableType} y la propiedad {@code CMapEncodingTable} se implementaron para facilitar el conjunto de subtablas de codificación necesario. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | Declara un conjunto de algunas subtablas de codificación conocidas |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | representa un conjunto de opciones para convertir un documento PDF |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | Esta clase contiene banderas para controlar la conversión a PDF/A en los casos en que el documento PDF de origen no cumpla con la especificación PDF. Si se utilizan las banderas de esta clase, disminuye el rendimiento, pero es necesario cuando el documento PDF de origen no puede convertirse al formato PDF/A de manera habitual. Por defecto, todas las banderas están establecidas en false. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | Algunos documentos PDF tienen símbolos unicode especiales, que pertenecen al Área de Uso Privado (PUA); vea la descripción en https://en.wikipedia.org/wiki/Private_Use_Areas. Estos símbolos provocan errores de cumplimiento PDF/A como "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Esta enumeración declara estrategias que pueden usarse para manejar los símbolos PUA. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | Algunos documentos tienen un tamaño grande después de la conversión al formato PDF/A. Para reducir el tamaño de archivo de estos documentos es necesario definir una estrategia de eliminación de fuentes. Esta enumeración declara estrategias que pueden usarse para optimizar el uso de fuentes. Cada estrategia de esta enumeración tiene sentido solo cuando la bandera {@code OptimizeFileSize} está establecida. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | Describe las estrategias utilizadas para alinear los segmentos de texto del documento. Actualmente solo se admite la estrategia para restaurar los segmentos a sus límites originales. En el futuro se podrían añadir otras estrategias. |
| [PdfPageStamp](./pdfpagestamp/) | La clase representa un sello que utiliza una página PDF como sello. |
| [PdfSaveOptions](./pdfsaveoptions/) | Opciones de guardado para exportar al formato Pdf |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | Opciones de carga para el formato PdfXml. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | Opciones de guardado para el formato PdfXml. |
| [Permissions](./permissions/) | Bandera binaria Este enum representa los permisos del usuario para un pdf. |
| [PKCS1](./pkcs1/) | Representa un objeto de firma según el estándar PKCS#1. Se utilizan el algoritmo de cifrado RSA y el método de digestión SHA-1 para la firma. |
| [PKCS7](./pkcs7/) | Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, PKCS #7: Cryptographic Message Syntax, Versión 1.5. El digest SHA1 del rango de bytes del documento está encapsulado en el campo SignedData de PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, PKCS #7: Cryptographic Message Syntax, Versión 1.5. El digest original del mensaje firmado sobre el rango de bytes del documento se incorpora como el campo SignedData normal de PKCS#7. No se encapsulan datos en el campo SignedData de PKCS#7. |
| [Point](./point/) | Representa un punto con coordenadas fraccionarias. |
| [Point3D](./point3d/) | Representa un punto con coordenadas fraccionarias. |
| [PolyAnnotation](./polyannotation/) | Clase base abstracta para poly-annotations. |
| [PolygonAnnotation](./polygonannotation/) | Clase que representa una anotación de polígono. |
| [PolylineAnnotation](./polylineannotation/) | Representa una anotación de polilínea que es similar a un polígono, excepto que el primer y último vértice no están implícitamente conectados. |
| [PopupAnnotation](./popupannotation/) | Representa la anotación emergente que muestra texto en una ventana emergente para la introducción y edición. |
| [Position](./position/) | Representa un objeto de posición |
| [PptxSaveOptions](./pptxsaveoptions/) | Opciones de guardado para exportar al formato SVG |
| [PrintController](./printcontroller/) | Representa el controlador de impresión. |
| [PrintDuplex](./printduplex/) | La opción de manejo de papel a usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Clase abstracta que representa una anotación de marca de impresora. |
| [PrinterMarksKind](./printermarkskind/) | Especifica los tipos de marcas de impresora que se agregarán a un documento. Esta enumeración tiene un atributo {@link FlagsAttribute} que permite una combinación bit a bit de sus valores de miembros. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Proporciona métodos de extensión para la enumeración {@link PrinterMarksKind}. |
| [PrintScaling](./printscaling/) | La opción de escalado de página que se debe seleccionar cuando se muestra un cuadro de diálogo de impresión para este documento. |
| [ProgressEventType](./progresseventtype/) | Esta enumeración describe los posibles tipos de eventos de progreso que pueden ocurrir durante la conversión. |
| [PsLoadOptions](./psloadoptions/) | Representa opciones para cargar/importar un archivo .mht en un documento pdf. |
| [PsSaveOptions](./pssaveoptions/) | Opciones de guardado para exportar a formato PS (PostScript) o EPS. |
| [RadioButtonField](./radiobuttonfield/) | Clase que representa un campo de botón de opción. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Clase que representa un elemento del campo RadioButton. |
| [Rectangle](./rectangle/) | Clase que representa un rectángulo. |
| [Redaction](./redaction/) | Solo para uso interno @author User |
| [RedactionAnnotation](./redactionannotation/) | Representa la anotación Redact. |
| [RegexManager](./regexmanager/) | Proporciona un contenedor para operaciones de expresiones regulares con configuraciones de tiempo de espera configurables. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Representa una anotación de Marca de Registro. Las marcas de registro son símbolos añadidos a planchas o pantallas de impresión para garantizar la alineación adecuada de los colores durante el proceso de impresión. |
| [RenderingOptions](./renderingoptions/) | Representa opciones de renderizado |
| [RenderModeType](./rendermodetype/) | Enumeración RenderModeType: conjunto de tipos de modo de renderizado |
| [Rendition](./rendition/) | Clase que describe el objeto de representación de RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Una acción de representación que controla la reproducción de contenido multimedia. |
| [RenditionOperation](./renditionoperation/) | La operación a realizar cuando se activa la acción. |
| [RenditionType](./renditiontype/) | Enumeración que describe los posibles tipos de Rendition. |
| [Resources](./resources/) | Clase que representa recursos de página. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | Representa ExtGStates con algunos valores. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | Representa la estrategia de conversión de espacios de color rgb a gris de dispositivo. |
| [RichMediaAnnotation](./richmediaannotation/) | Clase que describe RichMediaAnnotation, que permite incrustar datos de video/audio en un documento PDF. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | Evento que activa la anotación. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | Tipo del contenido multimedia. |
| [RichTextBoxField](./richtextboxfield/) | Clase que describe el componente de editor de texto enriquecido. |
| [RichTextFontStyles](./richtextfontstyles/) | Opciones para dar estilo a fragmentos de texto en RichText. |
| [RootElement](./rootelement/) | Elemento raíz de la estructura. |
| [Row](./row/) | Representa una fila de la tabla. |
| [Rows](./rows/) | Representa una colección de filas de la tabla. |
| [RtfLoadOptions](./rtfloadoptions/) | Opciones de carga para el formato RTF. |
| [SaveOptions](./saveoptions/) | El tipo SaveOptions mantiene el nivel de abstracción sobre opciones de guardado individuales. |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | Una instancia de esta clase representa información sobre el borde que puede dibujarse en algún documento resultante. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | Representa información de una parte del borde (superior, inferior, lado izquierdo o derecho). |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | Una instancia de esta clase representa información sobre el margen de página que puede dibujarse en algún documento resultante. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | Representa información de una parte del margen (superior, inferior, lado izquierdo o derecho). |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | Esta clase representa un conjunto de datos relacionados con el guardado de archivos de recursos externos que ocurre durante la conversión de PDF a otro formato (p. ej. HTML). |
| [ScalingMode](./scalingmode/) | El tipo de escalado que se debe usar. |
| [ScalingReason](./scalingreason/) | Las circunstancias bajo las cuales el ícono debe escalarse dentro del rectángulo de anotación. |
| [ScreenAnnotation](./screenannotation/) | Una anotación de pantalla que especifica una región de una página en la que se pueden reproducir clips de medios. |
| [SelectorRendition](./selectorrendition/) | La clase describe la representación del selector. |
| [Signature](./signature/) | Una clase abstracta que representa un objeto de firma en el documento PDF. Las firmas son campos con valores de objetos de firma, los cuales contienen datos que se utilizan para verificar la validez del documento. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Una clase abstracta que representa un objeto de apariencia personalizada de firma. |
| [SignatureField](./signaturefield/) | Representa un campo de formulario de firma. |
| [SignHash](./signhash/) | Delegado para firmar de forma personalizada el hash del documento (Beta). |
| [SoundAnnotation](./soundannotation/) | Representa una anotación de sonido que contiene audio grabado desde el micrófono del ordenador o importado desde un archivo. |
| [SoundData](./sounddata/) | Representa datos de sonido que definen el audio a reproducir cuando se activa la anotación. |
| [SoundEncoding](./soundencoding/) | El formato de codificación para los datos de muestra. |
| [SoundIcon](./soundicon/) | Enumera los íconos que se usarán al mostrar la anotación. |
| [SoundIconConverter](./soundiconconverter/) | Representa la clase SoundIconConverter. |
| [SoundSampleData](./soundsampledata/) | Representa entradas adicionales específicas de un objeto de sonido (Sección 9.2 PDF1-7). |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | El formato de codificación para los datos de muestra de sonido. |
| [SquareAnnotation](./squareannotation/) | Clase que representa la anotación cuadrada. |
| [SquigglyAnnotation](./squigglyannotation/) | Representa la anotación ondulada que aparece como subrayado irregular en el texto de un documento. |
| [Stamp](./stamp/) | Una clase abstracta para varios tipos de sellos que aparecen como descendientes. |
| [StampAnnotation](./stampannotation/) | <p> Representa la anotación de sello de goma. Este tipo de anotación muestra texto o gráficos diseñados para parecer como si estuvieran estampados en la página con un sello de goma. </p> <hr> <pre> El siguiente fragmento de código demuestra cómo agregar 2 sellos en la primera página del documento PDF. El documento de entrada proviene de inFile y los cambios se guardan en outFile. El primer sello tiene el ícono NotForPublicRelease y el segundo proviene de la imagen rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | Representa la clase StampIconConverter |
| [StrikeOutAnnotation](./strikeoutannotation/) | Representa una anotación de tachado que aparece como tachado en el texto del documento. |
| [StructElement](./structelement/) | Elemento de estructura general. |
| [SubjectNameElements](./subjectnameelements/) | La enumeración describe los elementos en la cadena de asunto de la firma. |
| [SubmitFormAction](./submitformaction/) | Clase que describe la acción submit-form. |
| [SvgLoadOptions](./svgloadoptions/) | Representa opciones para cargar/importar un archivo SVG en un documento PDF. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | Enumera los motores de conversión que pueden usarse para la conversión. |
| [SvgSaveOptions](./svgsaveoptions/) | Opciones de guardado para exportar al formato SVG |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | Esta clase representa un conjunto de datos relacionados con el guardado de archivos de imagen de recursos externos durante la conversión de PDF a HTML. |
| [Symbology](./symbology/) | Una simbología (Código de barras) define los detalles técnicos de un tipo particular de código de barras: el ancho de las barras, el conjunto de caracteres, el método de codificación, las especificaciones de suma de verificación, etc. |
| [SystemFontSource](./systemfontsource/) | Representa todas las fuentes instaladas en el sistema. |
| [TabAlignmentType](./tabalignmenttype/) | Enumera los tipos de alineación de pestañas. |
| [Table](./table/) | Representa una tabla que se puede agregar a la página. |
| [TableAbsorber](./tableabsorber/) | <p> Representa un objeto absorbente de elementos de tabla. Realiza búsquedas y proporciona acceso a los resultados de búsqueda a través de la colección {@code TableAbsorber.TableList}. </p> <hr> <pre> El ejemplo demuestra cómo encontrar una tabla en la primera página del documento PDF y reemplazar el texto en una celda de tabla. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Crear objeto TableAbsorber para encontrar tablas TableAbsorber absorber = new TableAbsorber(); // Visitar la primera página con el absorbente absorber.visit(doc.getPages().get_Item(1)); // Obtener acceso a la primera tabla en la página, su primera celda y fragmentos de texto en ella TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Cambiar el texto del primer fragmento de texto en la celda fragment.setText("hi world"); // Guardar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | Enumera los tipos de líder de pestaña. |
| [TableBroken](./tablebroken/) | Enumera la tabla rota. |
| [TabOrder](./taborder/) | Orden de pestañas en la página |
| [TabStop](./tabstop/) | Representa una posición personalizada de parada de pestaña en un párrafo. |
| [TabStops](./tabstops/) | Representa una colección de objetos {@code TabStop}. |
| [TeXFragment](./texfragment/) | Representa un fragmento LaTeX. |
| [TeXLoadOptions](./texloadoptions/) | Representa opciones para cargar/importar un archivo TeX en un documento PDF. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Implementa la obtención de un flujo de salida desde la memoria. Puedes usarlo, por ejemplo, cuando no deseas que la salida adjunta (como un archivo de registro) se escriba en disco pero te gustaría leerla después desde la memoria. |
| [TeXSaveOptions](./texsaveoptions/) | Opciones de guardado para exportar al formato TeX |
| [TextAbsorber](./textabsorber/) | <p> Representa un objeto absorbente de texto. Realiza la extracción de texto y proporciona acceso al resultado mediante el objeto {@code TextAbsorber.Text}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto en la primera página del documento PDF.\n// abrir documento Document doc = new Document(inFile);\n// crear objeto TextAbsorber para extraer texto TextAbsorber absorber = new TextAbsorber();\n// aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber);\n// obtener el texto extraído String extractedText = absorber.getText();\n</pre> <hr> <p> El objeto {@code TextAbsorber} se usa para extraer texto de un documento Pdf o de la página del documento. </p> |
| [TextAnnotation](./textannotation/) | Representa una anotación de texto que es una \"nota adhesiva\" adjunta a un punto en el documento PDF. |
| [TextBoxField](./textboxfield/) | Clase que representa un campo de cuadro de texto. |
| [TextBuilder](./textbuilder/) | Añade un objeto de texto a la página Pdf. |
| [TextDefaults](./textdefaults/) | Define los valores predeterminados del subsistema de texto |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | Especifica el tipo de valores predeterminados del subsistema de texto |
| [TextEditOptions](./texteditoptions/) | Describe opciones de operaciones de edición de texto. |
| [TextElement](./textelement/) | Elemento de texto general de la estructura lógica del documento. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | Describe que ha aparecido un error de extracción de texto en el documento PDF. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Representa la ubicación en el documento PDF donde ha aparecido un error de extracción de texto. |
| [TextExtractionOptions](./textextractionoptions/) | Representa opciones de extracción de texto |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | Define diferentes modos que pueden usarse al convertir un documento pdf a texto. Vea la clase {@code TextDevice}. |
| [TextFormattingOptions](./textformattingoptions/) | Representa opciones de formato de texto |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Define especificaciones de interlineado |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Define estrategias de ajuste de palabras |
| [TextFragment](./textfragment/) | <p> Representa un fragmento de texto PDF. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente. // Open document Document doc = new Document(\"input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"output.pdf\"); </pre> <hr> <pre> En pocas palabras, el objeto {@code TextFragment} contiene una lista de objetos {@code TextSegment}. En detalle: el texto del documento PDF en {@code com.aspose.pdf} está representado por dos objetos básicos: {@code TextFragment} y {@code TextSegment}. Las diferencias entre ellos son mayormente dependientes del contexto. Consideremos el siguiente escenario. El usuario busca el texto \"hello world\" para operar con él, cambiar sus propiedades, etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> La representación física del texto PDF es muy compleja. El texto \"hello world\" puede consistir en varios segmentos de texto físicamente independientes. El modelo de texto de Aspose.Pdf establece básicamente que el objeto {@code TextFragment} proporciona un conjunto de operaciones lógicas único sobre el conjunto de objetos {@code TextSegment} físicos que representan la consulta del usuario. En el escenario de búsqueda de texto, {@code TextFragment} es la representación lógica del texto \"hello world\", y la colección de objetos {@code TextSegment} representa todos los segmentos físicos que construyen el objeto de texto \"hello world\". Así, {@code TextFragment} se acerca a la representación lógica del texto. Y {@code TextSegment} se acerca a la representación física del texto. Obviamente, cada objeto {@code TextSegment} puede tener su propia fuente, coloración y propiedades de posicionamiento. {@code TextFragment} proporciona una forma sencilla de cambiar el texto con sus propiedades: establecer la fuente, el tamaño de fuente, el color de fuente, etc. Mientras tanto, los objetos {@code TextSegment} son accesibles y los usuarios pueden operar con los objetos {@code TextSegment} de forma independiente. <p> Tenga en cuenta que cambiar las propiedades de TextFragment puede modificar la colección interna {@code Segments} porque TextFragment es un objeto agregado y puede reorganizar los segmentos internos o fusionarlos en un solo segmento. Si su requisito es dejar la colección {@code Segments} sin cambios, por favor modifique los segmentos internos individualmente. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> Representa un objeto absorbente de fragmentos de texto. Realiza búsquedas de texto y proporciona acceso a los resultados de la búsqueda mediante la colección {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente. // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\input.pdf\"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\output.pdf\"); </pre> <hr> <p> El objeto {@code TextFragmentAbsorber} se utiliza principalmente en escenarios de búsqueda de texto. Cuando la búsqueda se completa, las ocurrencias se representan con objetos {@code TextFragment} que contiene la colección {@code TextFragmentAbsorber.TextFragments}. El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, a sus propiedades y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc.). </p> |
| [TextFragmentCollection](./textfragmentcollection/) | Representa una colección de fragmentos de texto |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> Representa el estado de texto de un fragmento de texto. </p> <hr> <pre> El ejemplo muestra cómo cambiar el color del texto y el tamaño de fuente del texto con el objeto {@code TextState}. // Open document Document doc = new Document(\"D:\\\\\\Tests\\\\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save(\"D:\\\\\\Tests\\\\\\\output.pdf\"); </pre> <hr> <p> Proporciona una forma de cambiar las siguientes propiedades del texto: fuente ({@code TextFragmentState.Font} property) tamaño de fuente ({@code TextFragmentState.FontSize} property) estilo de fuente ({@code TextFragmentState.FontStyle} property) color de primer plano ({@code TextFragmentState.ForegroundColor} property) color de fondo ({@code TextFragmentState.BackgroundColor} property) </p> <p> Tenga en cuenta que cambiar las propiedades de {@code TextFragmentState} puede modificar la colección interna {@code TextFragment.Segments} porque TextFragment es un objeto agregado y puede reorganizar los segmentos internos o combinarlos en un solo segmento. Si su requisito es dejar la colección {@code TextFragment.Segments} sin cambios, por favor modifique los segmentos internos individualmente. </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | Enumera los íconos que se usarán al mostrar la anotación. |
| [TextIconConverter](./texticonconverter/) | Representa la clase TextIconConverter |
| [TextMarkupAnnotation](./textmarkupannotation/) | Clase base abstracta para anotaciones de marcado de texto. |
| [TextOptions](./textoptions/) | Representa opciones de procesamiento de texto |
| [TextParagraph](./textparagraph/) | <p> Representa párrafos de texto como un objeto de texto multilínea. </p> <hr> <pre> El ejemplo muestra cómo crear un objeto de párrafo de texto y añadirlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // crear párrafo de texto TextParagraph paragraph = new TextParagraph(); // establecer el rectángulo del párrafo paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // establecer opciones de ajuste de palabras paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // añadir líneas de cadena paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // añadir el párrafo a la página Pdf con el TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // guardar documento Pdf doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | Modo de fondo para TextParagraph |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Representa un objeto absorbente de párrafos de texto. Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda mediante la colección {@code TextParagraphAbsorber.TextParagraphs}. |
| [TextParagraphCollection](./textparagraphcollection/) | Representa una colección de párrafos de texto |
| [TextReplaceOptions](./textreplaceoptions/) | Representa opciones de reemplazo de texto |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Determina la acción que se realizará después de reemplazar un fragmento de texto por uno más corto. None - sin acción, el texto reemplazado puede superponerse al resto de la línea; AdjustSpaceWidth - intenta ajustar los espacios entre palabras para mantener la longitud de la línea; WholeWordsHyphenation - intenta distribuir las palabras entre las líneas del párrafo para mantener el margen derecho del párrafo; ShiftRestOfLine - desplaza el resto de la línea según la longitud cambiada del texto, la longitud de la línea puede modificarse; El valor predeterminado es ShiftRestOfLine. |
| [TextSearchOptions](./textsearchoptions/) | Representa opciones de búsqueda de texto |
| [TextSegment](./textsegment/) | <p> Representa un segmento de texto PDF. </p> <hr> <pre> // Abre el documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Crea el objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Acepta el absorber para la primera página doc.getPages().get(1).accept(absorber); // Cambia el color de primer plano del primer segmento de texto de la primera ocurrencia de texto absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Cambia el tamaño de fuente del primer segmento de texto de la primera ocurrencia de texto absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Guarda el documento doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <pre> En pocas palabras, los objetos {@code TextSegment} son hijos del objeto {@code TextFragment}. En detalle: el texto del documento pdf en {@code Aspose.Pdf} está representado por dos objetos básicos: {@code TextFragment} y {@code TextSegment}. Las diferencias entre ellos dependen mayormente del contexto. Consideremos el siguiente escenario. El usuario busca el texto \"hello world\" para operar con él, cambiar sus propiedades, etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> <p> La representación física del texto pdf es muy compleja. El texto \"hello world\" puede consistir en varios segmentos de texto físicamente independientes. El modelo de texto de Aspose.PDF establece básicamente que el objeto {@code TextFragment} proporciona un conjunto de operaciones lógicas sobre el conjunto de objetos {@code TextSegment} físicos que representan la consulta del usuario. En el escenario de búsqueda de texto, {@code TextFragment} es la representación lógica del texto \"hello world\", y la colección de objetos {@code TextSegment} representa todos los segmentos físicos que construyen el objeto de texto \"hello world\". Así, {@code TextFragment} se acerca a la representación lógica del texto. Y {@code TextSegment} se acerca a la representación física del texto. Evidentemente, cada objeto {@code TextSegment} puede tener su propia fuente, coloración y propiedades de posicionamiento. {@code TextFragment} ofrece una forma sencilla de cambiar el texto con sus propiedades: establecer fuente, tamaño de fuente, color de fuente, etc. Mientras tanto, los objetos {@code TextSegment} son accesibles y los usuarios pueden operar con los objetos {@code TextSegment} de forma independiente.</p> |
| [TextSegmentCollection](./textsegmentcollection/) | Representa una colección de segmentos de texto |
| [TextStamp](./textstamp/) | Representa un sello textual. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | Acción a realizar si la fuente no contiene el carácter requerido. |
| [TextState](./textstate/) | Representa el estado de un texto |
| [TextStyle](./textstyle/) | Clase que representa un campo de casilla de verificación |
| [TimestampSettings](./timestampsettings/) | Representa la configuración OCSP utilizada durante el proceso de firma. |
| [TocInfo](./tocinfo/) | Representa la información del índice. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | Esta clase describe reglas que pueden usarse para resolver el error de Adobe Preflight "Text cannot be mapped to Unicode". |
| [TrimMarkAnnotation](./trimmarkannotation/) | Representa una anotación de marca de recorte. Las marcas de recorte se colocan en las esquinas de una página impresa para indicar dónde debe recortarse la página. |
| [TxtLoadOptions](./txtloadoptions/) | Opciones de carga para la conversión de TXT a PDF. |
| [UnderlineAnnotation](./underlineannotation/) | Representa una anotación de subrayado que aparece como subrayado en el texto del documento. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | Esta clase representa opciones de guardado que utilizan una forma de conversión unificada (con un modelo interno de documento unificado) |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | Representa una clase con un método abstracto que normalmente es suministrado por el llamador y maneja eventos de progreso que provienen del convertidor. Por lo general, dicho controlador proporcionado por el cliente puede usarse para mostrar el progreso total de la conversión en la consola o en una barra de progreso. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | Esta clase representa información sobre el progreso de la conversión que puede usarse en una aplicación externa para mostrar el progreso de la conversión al usuario final. |
| [WarningCallback](./warningcallback/) | Interfaz para soporte del mecanismo de devolución de llamada del usuario. |
| [WarningInfo](./warninginfo/) | Objeto inmutable para encapsular información de advertencia. |
| [WarningType](./warningtype/) | / * Enum que representa el tipo de advertencia. / * / |
| [Watermark](./watermark/) | Representa una marca de agua de la página. |
| [WatermarkAnnotation](./watermarkannotation/) | Clase que describe el objeto de anotación de marca de agua. |
| [WatermarkArtifact](./watermarkartifact/) | Clase que describe el artefacto de marca de agua. Esto puede usarse para |
| [WebHyperlink](./webhyperlink/) | Representa un objeto de hipervínculo web. |
| [WidgetAnnotation](./widgetannotation/) | Clase que representa una anotación de widget. |
| [XFA](./xfa/) | Representa un formulario XML respecto a la arquitectura de formularios XML (XFA). |
| [XfaParserOptions](./xfaparseroptions/) | Clase para manejar la encapsulación de datos relacionados |
| [XfdfReader](./xfdfreader/) | <p> Clase que realiza la lectura del formato XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | Agrupa métodos para escribir anotaciones y campos al formato de archivo XFDF |
| [XForm](./xform/) | Clase que representa XForm |
| [XFormCollection](./xformcollection/) | Clase que representa la colección de XFormCollection. |
| [XImage](./ximage/) | Clase que representa el objeto de imagen X-Object. |
| [XImage.RawParameters](./ximage.rawparameters/) | Clase que representa los parámetros sin procesar de XImage. |
| [XImageCollection](./ximagecollection/) | Clase que representa la colección de XImage. |
| [XmlLoadOptions](./xmlloadoptions/) | Representa opciones para cargar/importar un archivo XML en un documento PDF. |
| [XmlSaveOptions](./xmlsaveoptions/) | Opciones de guardado para exportar al formato Xml |
| [XmpField](./xmpfield/) | Representa el campo XMP. |
| [XmpFieldType](./xmpfieldtype/) | Este enumerado representa los tipos de un campo XMP. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Categoría de propiedad: interna o externa. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | Este esquema describe un campo en un tipo estructurado. Es muy similar al esquema PDF/A Property Value Type, pero define un campo en una estructura en lugar de una propiedad. URI del espacio de nombres del esquema: http://www.aiim.org/pdfa/ns/field# Prefijo de espacio de nombres requerido del esquema: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Representa la clase base para instancias de campo, propiedad y tipo de valor. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Describe una única propiedad. URI del espacio de nombres del esquema: http://www.aiim.org/pdfa/ns/property# Prefijo de espacio de nombres requerido del esquema: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | Describe el esquema de extensión XMP que proporciona PDF/A-1. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | Representa la descripción del esquema de extensión XMP que proporciona PDF/A-1. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | El esquema PDF/A ValueType es necesario para todos los tipos de valor de propiedad que no están definidos en la especificación XMP 2004, es decir, para los tipos de valor fuera de la siguiente lista: - Tipos de matriz (son tipos contenedores que pueden contener uno o más campos): Alt, Bag, Seq - Tipos de valor básicos: Boolean, (abierta y cerrada) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipos de valor de gestión de medios: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo de valor básico de trabajo/flujo: Job - Tipos de valor del esquema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI del espacio de nombres del esquema: http://www.aiim.org/pdfa/ns/type# Prefijo de espacio de nombres requerido del esquema: pdfaType |
| [XmpValue](./xmpvalue/) | Representa el valor XMP |
| [XpsLoadOptions](./xpsloadoptions/) | Representa opciones para cargar/importar un archivo XPS en un documento PDF. |
| [XpsSaveOptions](./xpssaveoptions/) | Opciones de guardado para exportar al formato XPS |
| [XslFoLoadOptions](./xslfoloadoptions/) | Representa opciones para cargar/importar un archivo XSL-FO en un documento PDF. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | El documento XSLFO de origen puede contener errores de formato. Este enumerado enumera las posibles estrategias para manejar dichos errores de formato. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> Representa un destino explícito que muestra la página con las coordenadas (izquierda, arriba) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, arriba o zoom indica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| Enum | Descripción |
| --- | --- |
| [AFRelationship](./afrelationship/) | La enumeración describe la relación de archivos asociados. |
| [AnnotationState](./annotationstate/) | La enumeración de estados a los que se puede establecer la anotación original. |
| [AnnotationStateModel](./annotationstatemodel/) | El modelo de estado correspondiente al estado de la anotación. |
| [AnnotationType](./annotationtype/) | Enumeración de tipos de anotación. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | Enumeración del subtipo posible de artefactos. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | Enumeración de tipos posibles de artefactos. |
| [BlendMode](./blendmode/) | La enumeración de modos de fusión. |
| [BorderCornerStyle](./bordercornerstyle/) | Enumera los estilos de esquina del borde. |
| [BorderEffect](./bordereffect/) | Describe el efecto que debe aplicarse al borde de las anotaciones. |
| [BorderStyle](./borderstyle/) | Describe el estilo del borde de la anotación. |
| [BoxStyle](./boxstyle/) | Representa los estilos para dibujar la marca en la casilla de verificación. |
| [CapStyle](./capstyle/) | Estilo del extremo de línea de la anotación de tinta. |
| [CaptionPosition](./captionposition/) | Enumeración de la posición del subtítulo de la anotación. |
| [CaretSymbol](./caretsymbol/) | Un símbolo que se asociará con el cursor. |
| [ColorsOfCMYK](./colorsofcmyk/) | Colores incluidos en el modelo de color CMYK. |
| [ColorSpace](./colorspace/) | La enumeración de espacios de color. |
| [ColorType](./colortype/) | Especifica el tipo de color de los elementos en la página. |
| [ColumnAdjustment](./columnadjustment/) | Enumera los tipos de ajuste de columna. |
| [ContentDisposition](./contentdisposition/) | Encabezado Content-Disposition del protocolo MIME. |
| [ConvertErrorAction](./converterroraction/) | Esta clase representa la acción para errores de conversión. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | Esta acción representa acciones para la conversión de imágenes con máscara suave. |
| [ConvertTransparencyAction](./converttransparencyaction/) | Esta clase representa la acción para la conversión de transparencia. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | Representa el tipo de algoritmo criptográfico que se usa en rutinas de cifrado/descifrado. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * El espacio de nombres {@code Aspose.Pdf.Security } contiene clases utilizadas para el cifrado y la firma digital. / * / |
| [DefaultState](./defaultstate/) | Representa el estado predeterminado de una capa PDF. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Representa el tipo de algoritmo que asigna datos a un "hash" |
| [Direction](./direction/) | Dirección del texto. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Los permisos de acceso concedidos para este documento. Los valores válidos son: 1 - No se permiten cambios en el documento; cualquier cambio en el documento invalida la firma. 2 - Los cambios permitidos son rellenar formularios, instanciar plantillas de página y firmar; otros cambios invalidan la firma. 3 - Los cambios permitidos son los mismos que para el 2, además de la creación, eliminación y modificación de anotaciones; otros cambios invalidan la firma. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | Permite especificar el formato de archivo .doc o .docx. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto. Use el modo RecognitionMode.Textbox cuando el documento resultante no va a ser editado intensamente. Los cuadros de texto son fáciles de modificar cuando no hay mucho que hacer. Use el modo RecognitionMode.Flow cuando el documento de salida necesita una edición adicional. Los párrafos y líneas de texto en el modo flujo permiten una fácil modificación del texto, pero los objetos de formato no compatibles se verán peor que en el modo RecognitionMode.Textbox. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | Cuando se convierte un archivo PDF (que normalmente tiene un diseño fijo), el motor de conversión intenta realizar agrupación y análisis multinivel para restaurar la intención original del autor del documento y producir un resultado en diseño fluido. Esta propiedad ajusta esa conversión para este u otro método deseable de reconocimiento del contenido. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumera los tipos de destinos explícitos. |
| [ExtendedBoolean](./extendedboolean/) | Representa un tipo booleano que admite el valor Undefined. |
| [ExtractImageMode](./extractimagemode/) | Define diferentes modos que pueden usarse al extraer imágenes de documentos. |
| [FileEncoding](./fileencoding/) | Codificación del archivo adjunto. Valores posibles: Zip - el archivo está comprimido con ZIP, None - el archivo no está comprimido. |
| [FileIcon](./fileicon/) | Un ícono que se usará al mostrar la anotación. |
| [Fixup](./fixup/) | Este enum representa un tipo de Fixup. |
| [FormType](./formtype/) | Enumeración de los tipos posibles de Acro Form. |
| [FreeTextIntent](./freetextintent/) | Enumera las intenciones de la anotación de texto libre. |
| [HighlightingMode](./highlightingmode/) | Enumera el modo de resaltado de la anotación, el efecto visual que se usará cuando se presione o mantenga pulsado el botón del ratón dentro de su área activa. |
| [HorizontalAlignment](./horizontalalignment/) | Describe la alineación horizontal. |
| [HtmlDocumentType](./htmldocumenttype/) | Representa la enumeración de los tipos de documentos Html. |
| [HtmlMediaType](./htmlmediatype/) | Especifica los tipos de medios posibles utilizados durante el renderizado. |
| [IconCaptionPosition](./iconcaptionposition/) | Describe la posición del ícono. |
| [ImageFileType](./imagefiletype/) | Enumera los tipos de archivo de imagen. |
| [ImageFilterType](./imagefiltertype/) | Enumeración que representa el tipo de filtro de imagen. |
| [ImageFormat](./imageformat/) | Este enum representa formatos de imagen. |
| [ImportFormat](./importformat/) | Especifica el formato de importación. |
| [Justification](./justification/) | Enumera las formas de justificación (quadding) que se usarán al mostrar el texto de la anotación. |
| [LaunchActionOperation](./launchactionoperation/) | Enumera las operaciones a realizar con el documento durante la ejecución de la acción de lanzamiento. |
| [LettersPositioningMethods](./letterspositioningmethods/) | Enumera los posibles modos de posicionamiento de letras en palabras en el HTML resultante |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: conjunto de tipos de esquema de iluminación. |
| [LineEnding](./lineending/) | Enumera los estilos de terminación de línea que se usarán al dibujar la línea. |
| [LineIntent](./lineintent/) | Enumera los propósitos de la anotación de línea. |
| [LoadFormat](./loadformat/) | Especifica el formato de carga. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | Valor que indica de qué manera se muestran los valores fraccionarios. |
| [NumberingStyle](./numberingstyle/) | Enumeración del estilo de numeración de página compatible para la clase PageLabel. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | Especifica la posición en un flujo que se usará para buscar. |
| [PageCoordinateType](./pagecoordinatetype/) | Describe el tipo de coordenada de página. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | Describe el diseño de página. |
| [PageMode](./pagemode/) | La clase describe los componentes utilizados de la página del documento. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Especifica la variante para determinar la ubicación del elemento en la página. |
| [PasswordType](./passwordtype/) | Este enum representa los tipos de contraseña conocidos utilizados para documentos PDF protegidos con contraseña. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: conjunto de modos de activación de anotaciones 3D. |
| [PdfFormat](./pdfformat/) | Esta clase representa un formato PDF. |
| [PdfVersion](./pdfversion/) | Este enum representa la versión del archivo PDF. |
| [PolyIntent](./polyintent/) | Enumera los propósitos de la anotación de polígono o polilínea. |
| [PredefinedAction](./predefinedaction/) | Define diferentes acciones que pueden activarse desde un archivo PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Representa una posición de una marca en una esquina de una página. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Representa una posición de una marca de registro en una página. |
| [ReplyType](./replytype/) | Enumera los tipos de relaciones (el "tipo de respuesta") entre la anotación y una especificada por InReplyTo. |
| [ReturnAction](./returnaction/) | Enum representa una acción del flujo de trabajo del programa en caso de invocar el método {@code IWarningCallback.Warning(WarningInfo)}. |
| [Rotation](./rotation/) | Enumeración de valores de rotación posibles. |
| [SaveFormat](./saveformat/) | Especifica el formato |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | Representa tipos de línea que pueden usarse en el documento resultante para dibujar bordes u otras líneas |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | Enumera los tipos posibles de recursos externos guardados |
| [StampIcon](./stampicon/) | Enumera los íconos que se usarán al mostrar la anotación. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | Enumera los tipos posibles de archivos de imagen que pueden guardarse como recursos externos durante la conversión de Pdf a SVG |
| [TextAlignment](./textalignment/) | Alineación del texto en la anotación. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Modos de procesamiento de rutas de recorte |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Comportamiento de sustitución de fuentes. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Modos de transformación de idioma |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Acción a realizar si la fuente no contiene el carácter requerido |
| [TextRenderingMode](./textrenderingmode/) | El modo de renderizado de texto, Tmode, determina si la visualización del texto debe provocar que los contornos de los glifos se tracen, rellenen, se usen como límite de recorte, o alguna combinación de los tres. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Especifica una política sobre cómo debe ajustarse el tamaño de fuente del texto para encajar dentro de un área contenedora. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Ámbito donde se aplica la operación de reemplazo de texto REPLACE_FIRST por defecto. Esta opción obsoleta se mantuvo por compatibilidad. Afecta a PdfContentEditor y no tiene efecto en TextFragmentAbsorber. |
| [VerticalAlignment](./verticalalignment/) | Enumeración de los valores posibles de alineación vertical. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
