---
title: "Espacio de nombres Aspose::Pdf::Annotations"
linktitle: "Aspose::Pdf::Annotations"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Espacio de nombres Aspose::Pdf::Annotations. El espacio de nombres Aspose.Pdf.Annotations proporciona clases para trabajar con varios tipos de acciones, destinos y otras características del documento que tradicionalmente se denominan interactivas, proporcionando medios para que el usuario pueda intercomunicarse con él en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.annotations/
---

El espacio de nombres **[Aspose.Pdf.Annotations](./)** proporciona clases para trabajar con varios tipos de acciones, destinos y otras características del documento que tradicionalmente se denominan interactivas, proporcionando medios para que el usuario pueda intercomunicarse con él.

## Clases

| Clase | Descripción |
| --- | --- |
| [ActionCollection](./actioncollection/) | [Collection](../aspose.pdf/collection/) de acciones. |
| [Annotation](./annotation/) | Clase que representa un objeto de anotación. |
| [AnnotationActionCollection](./annotationactioncollection/) | Representa la colección de acciones de anotación. |
| [AnnotationCollection](./annotationcollection/) | Clase que representa una colección de anotaciones. |
| [AnnotationFlagsConverter](./annotationflagsconverter/) |  |
| [AnnotationSelector](./annotationselector/) | Esta clase se usa para seleccionar anotaciones utilizando la idea de plantilla Visitor. |
| [AnnotationStateConverter](./annotationstateconverter/) |  |
| [AnnotationStateModelConverter](./annotationstatemodelconverter/) |  |
| [AppearanceDictionary](./appearancedictionary/) | [Annotation](./annotation/) diccionario de apariencia que especifica cómo se presentará visualmente la anotación en la página. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Representa una anotación de Marca de Sangrado. |
| [Border](./border/) | Clase que representa las características del borde de la anotación. |
| [BorderEffectConverter](./bordereffectconverter/) |  |
| [BorderStyleConverter](./borderstyleconverter/) |  |
| [CaptionPositionConverter](./captionpositionconverter/) |  |
| [CaretAnnotation](./caretannotation/) | Clase que representa una anotación de Cursor. |
| [CaretSymbolConverter](./caretsymbolconverter/) |  |
| [Characteristics](./characteristics/) | Representa características de la anotación. |
| [CircleAnnotation](./circleannotation/) | Clase que representa una anotación de Círculo. |
| [ColorBarAnnotation](./colorbarannotation/) | Clase que representa la anotación [ColorBarAnnotation](./colorbarannotation/). La propiedad [Color](../aspose.pdf/color/) se ignora, en su lugar se usa el color [ColorsOfCMYK](./colorsofcmyk/). Al crearla, la proporción entre ancho y alto determina la orientación de la anotación: horizontal o vertical. Luego, verifica que el rectángulo de la anotación esté fuera del TrimBox y, si no lo está, se desplaza a la ubicación más cercana fuera del TrimBox, teniendo en cuenta la orientación de la anotación. Es posible reducir el ancho (alto) para que la anotación quepa fuera del TrimBox. Si no hay espacio para el diseño, el ancho/alto puede establecerse en cero (en este caso, la anotación está presente en la página, pero no se muestra). |
| [ColorsOfCMYKConverter](./colorsofcmykconverter/) |  |
| [CommonFigureAnnotation](./commonfigureannotation/) | Clase abstracta que representa una anotación de figura común. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Representa tipos de anotación que se colocan en las esquinas de la página impresa. |
| [CustomExplicitDestination](./customexplicitdestination/) | Representa un destino explícito personalizado. |
| [Dash](./dash/) | Clase que representa el patrón de guiones de línea. |
| [DefaultAppearance](./defaultappearance/) | Describe la apariencia predeterminada del campo (fuente, tamaño de texto y color). |
| [DocumentActionCollection](./documentactioncollection/) | Clase que describe acciones realizadas sobre algunas acciones con el documento. |
| [ExplicitDestination](./explicitdestination/) | Representa la clase base para destinos explícitos en un documento PDF. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) |  |
| [FdfReader](./fdfreader/) | Clase que realiza la lectura del formato FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Clase que describe la anotación de adjunto de archivo. |
| [FileIconConverter](./fileiconconverter/) |  |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que su caja delimitadora quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando la caja delimitadora dentro de la ventana en la otra dimensión. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo justo para que el ancho total de su caja delimitadora quepa dentro de la ventana. Un valor nulo para top indica que se debe conservar sin cambios el valor actual de ese parámetro. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo justo para que la altura total de su caja delimitadora quepa dentro de la ventana. Un valor nulo para left indica que se debe conservar sin cambios el valor actual de ese parámetro. |
| [FitExplicitDestination](./fitexplicitdestination/) | Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que la página completa quepa dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando la página dentro de la ventana en la otra dimensión. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo justo para que el ancho total de la página quepa dentro de la ventana. Un valor nulo para top indica que se debe conservar sin cambios el valor actual de ese parámetro. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que el rectángulo especificado por las coordenadas izquierda, inferior, derecha y superior quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede producir un comportamiento impredecible. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo justo para que la altura total de la página quepa dentro de la ventana. Un valor nulo para left indica que se debe conservar sin cambios el valor actual de ese parámetro. |
| [FixedPrint](./fixedprint/) | Representa datos de impresión fijos de [Watermark](../aspose.pdf/watermark/)[Annotation](./annotation/). |
| [FreeTextAnnotation](./freetextannotation/) | Representa una anotación de texto libre que muestra el texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible. |
| [FreeTextIntentConverter](./freetextintentconverter/) |  |
| [GenericAnnotation](./genericannotation/) | La clase describe una anotación general. |
| [GoToAction](./gotoaction/) | Representa una acción ir a que cambia la vista a un destino especificado (página, ubicación y factor de magnificación). |
| [GoToRemoteAction](./gotoremoteaction/) | Representa una acción ir a remota que es similar a una acción ir a ordinaria pero salta a un destino en otro archivo PDF en lugar del archivo actual. |
| [GoToURIAction](./gotouriaction/) | Representa una acción URI que hace que se resuelva un URI. |
| [HideAction](./hideaction/) | Representa una acción ocultar que oculta o muestra una o más anotaciones en la pantalla estableciendo o borrando sus banderas Oculto. |
| [HighlightAnnotation](./highlightannotation/) | Representa una anotación de resaltado que destaca un rango de texto en el documento. |
| [HighlightingModeConverter](./highlightingmodeconverter/) |  |
| [IAnnotationVisitor](./iannotationvisitor/) | Define Visitor para visitar diferentes anotaciones del documento. |
| [IAppointment](./iappointment/) | Representa una interfaz general para acciones y destinos. |
| [ImportDataAction](./importdataaction/) | Al invocar una acción import-data, los datos del Formato de Datos de Formularios (FDF) [Forms](../aspose.pdf.forms/) deberán importarse al formulario interactivo del documento desde un archivo especificado. |
| [InkAnnotation](./inkannotation/) | Representa un garabato a mano alzada "scribble" compuesto por una o más rutas disjuntas. |
| [JavascriptAction](./javascriptaction/) | Clase que representa una acción javascript. |
| [JustificationConverter](./justificationconverter/) |  |
| [LaunchAction](./launchaction/) | Representa una acción de lanzamiento que inicia una aplicación o abre o imprime un documento. |
| [LaunchActionOperationConverter](./launchactionoperationconverter/) |  |
| [LineAnnotation](./lineannotation/) | Clase que representa una anotación de línea. |
| [LineEndingConverter](./lineendingconverter/) |  |
| [LineIntentConverter](./lineintentconverter/) |  |
| [LinkAnnotation](./linkannotation/) | Representa ya sea un enlace hipervínculo a un destino en otra parte del documento o una acción a realizar. |
| [MarkupAnnotation](./markupannotation/) | Clase abstracta que representa una anotación de marcado. |
| [Measure](./measure/) | Clase que describe el sistema de coordenadas [Measure](./measure/). |
| [MediaClip](./mediaclip/) | Clase que describe el objeto de clip multimedia de la representación. |
| [MediaClipData](./mediaclipdata/) | Clase que describe los datos del clip multimedia. |
| [MediaClipSection](./mediaclipsection/) | Esta clase describe la sección de clip multimedia. |
| [MediaRendition](./mediarendition/) | Clase que describe la representación multimedia. |
| [MovieAnnotation](./movieannotation/) | Representa una anotación de película que contiene gráficos animados y sonido para presentarse en la pantalla del ordenador y a través de los altavoces. Cuando la anotación se activa, la película se reproduce. |
| [NamedAction](./namedaction/) | Representa acciones nombradas que se espera que soporten las aplicaciones visor de PDF. |
| [NamedDestination](./nameddestination/) | En lugar de definirse directamente con la sintaxis explícita, un destino puede referirse indirectamente mediante un objeto de nombre o una cadena de bytes. |
| [PageInformationAnnotation](./pageinformationannotation/) | Representa una anotación de Información de [Page](../aspose.pdf/page/) en un documento PDF. Esta anotación contiene el nombre del archivo, el número de página y la fecha y hora de creación de la anotación. |
| [PDF3DAnnotation](./pdf3dannotation/) | Clase [PDF3DAnnotation](./pdf3dannotation/). Esta clase no puede heredarse. |
| [PDF3DArtwork](./pdf3dartwork/) | Clase [PDF3DArtwork](./pdf3dartwork/). |
| [PDF3DContent](./pdf3dcontent/) | Clase [PDF3DContent](./pdf3dcontent/). |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Clase [PDF3DCrossSection](./pdf3dcrosssection/). |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Clase [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/). |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Clase [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/). |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Clase [PDF3DLightingScheme](./pdf3dlightingscheme/). |
| [PDF3DRenderMode](./pdf3drendermode/) | Clase [PDF3DRenderMode](./pdf3drendermode/). |
| [PDF3DStream](./pdf3dstream/) | Clase [PDF3DStream](./pdf3dstream/). |
| [PDF3DView](./pdf3dview/) | Clase [PDF3DView](./pdf3dview/). |
| [PDF3DViewArray](./pdf3dviewarray/) | Clase [PDF3DViewArray](./pdf3dviewarray/). |
| [PdfAction](./pdfaction/) | Representa una acción en el documento PDF. |
| [PdfActionCollection](./pdfactioncollection/) | Clase que describe una lista de acciones. |
| [PolyAnnotation](./polyannotation/) | Clase base abstracta para anotaciones poligonales. |
| [PolygonAnnotation](./polygonannotation/) | Clase que representa una anotación de polígono. |
| [PolyIntentConverter](./polyintentconverter/) |  |
| [PolylineAnnotation](./polylineannotation/) | Representa una anotación de polilínea que es similar a un polígono, excepto que el primer y último vértice no están conectados implícitamente. |
| [PopupAnnotation](./popupannotation/) | Representa la anotación emergente que muestra texto en una ventana emergente para la introducción y edición. |
| [PredefinedActionConverter](./predefinedactionconverter/) |  |
| [PrinterMarkAnnotation](./printermarkannotation/) | Clase abstracta que representa una anotación de marca de impresora. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Proporciona métodos de extensión para la enumeración [PrinterMarksKind](./printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Representa una anotación de redacción. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Representa una anotación de marca de registro. |
| [Rendition](./rendition/) | Clase que describe el objeto de representación de RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Una acción de representación que controla la reproducción de contenido multimedia. |
| [ReplyTypeConverter](./replytypeconverter/) |  |
| [RichMediaAnnotation](./richmediaannotation/) | Clase que describe [RichMediaAnnotation](./richmediaannotation/) que permite incrustar datos de video/audio en el documento PDF. |
| [ScreenAnnotation](./screenannotation/) | Una anotación de pantalla que especifica una región de una página en la que se pueden reproducir clips de medios. |
| [SelectorRendition](./selectorrendition/) | Clase que describe la representación del selector. |
| [SoundAnnotation](./soundannotation/) | Representa una anotación de sonido que contiene audio grabado desde el micrófono de la computadora o importado desde un archivo. |
| [SoundData](./sounddata/) | Representa datos de sonido que definen el audio que se reproducirá cuando se active la anotación. |
| [SoundEncodingConverter](./soundencodingconverter/) |  |
| [SoundIconConverter](./soundiconconverter/) |  |
| [SoundSampleData](./soundsampledata/) | Representa entradas adicionales específicas de un objeto de sonido (Sección 9.2 PDF1-7). |
| [SquareAnnotation](./squareannotation/) | Clase que representa una anotación cuadrada. |
| [SquigglyAnnotation](./squigglyannotation/) | Representa la anotación ondulada que aparece como un subrayado irregular en el texto de un documento. |
| [StampAnnotation](./stampannotation/) | Representa una anotación de sello de goma. Este tipo de anotación muestra texto o gráficos que parecen haber sido estampados en la página con un sello de goma. |
| [StampIconConverter](./stampiconconverter/) |  |
| [StrikeOutAnnotation](./strikeoutannotation/) | Representa una anotación de tachado que aparece como un tachado en el texto del documento. |
| [SubmitFormAction](./submitformaction/) | Clase que describe la acción de envío de formulario. |
| [TextAnnotation](./textannotation/) | Representa una anotación de texto que es una 'nota adhesiva' adjunta a un punto en el documento PDF. |
| [TextIconConverter](./texticonconverter/) |  |
| [TextMarkupAnnotation](./textmarkupannotation/) | Clase base abstracta para anotaciones de marcado de texto. |
| [TextStyle](./textstyle/) | Clase que representa el estilo del texto en la anotación. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Representa una anotación de marca de recorte. |
| [UnderlineAnnotation](./underlineannotation/) | Representa una anotación de subrayado que aparece como un subrayado en el texto del documento. |
| [WatermarkAnnotation](./watermarkannotation/) | Clase que describe el objeto de anotación [Watermark](../aspose.pdf/watermark/). |
| [WidgetAnnotation](./widgetannotation/) | Clase que representa una anotación de widget. |
| [XfdfReader](./xfdfreader/) | Clase que realiza la lectura del formato XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Representa un destino explícito que muestra la página con las coordenadas (izquierda, arriba) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, arriba o zoom indica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo. |
## Enums

| Enumeración | Descripción |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Un conjunto de indicadores que especifican diversas características de la anotación. |
| [AnnotationState](./annotationstate/) | La enumeración de estados a los que se puede establecer la anotación original. |
| [AnnotationStateModel](./annotationstatemodel/) | El modelo de estado correspondiente al estado de la anotación. |
| [AnnotationType](./annotationtype/) | Enumeración de tipos de anotación. |
| [BorderEffect](./bordereffect/) | Describe el efecto que debe aplicarse al borde de las anotaciones. |
| [BorderStyle](./borderstyle/) | Describe el estilo del borde de la anotación. |
| [CapStyle](./capstyle/) | Estilo del extremo de línea de la línea de anotación de tinta. |
| [CaptionPosition](./captionposition/) | Enumeración de la posición del subtítulo de la anotación. |
| [CaretSymbol](./caretsymbol/) | Un símbolo que se asociará con el cursor. |
| [ColorsOfCMYK](./colorsofcmyk/) | Colores incluidos en el modelo de color CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumera los tipos de destinos explícitos. |
| [FileIcon](./fileicon/) | Un ícono que se usará al mostrar la anotación. |
| [FreeTextIntent](./freetextintent/) | Enumera los propósitos de la anotación de texto libre. |
| [HighlightingMode](./highlightingmode/) | Enumera el modo de resaltado de la anotación, el efecto visual que se usará cuando se presione o mantenga pulsado el botón del ratón dentro de su área activa. |
| [Justification](./justification/) | Enumera las formas de alineación (justificación) que se usarán al mostrar el texto de la anotación. |
| [LaunchActionOperation](./launchactionoperation/) | Enumera las operaciones a realizar con el documento durante la ejecución de la acción de lanzamiento. |
| [LightingSchemeType](./lightingschemetype/) | Enum [LightingSchemeType](./lightingschemetype/): conjunto de tipos de esquema de iluminación. |
| [LineEnding](./lineending/) | Enumera los estilos de terminación de línea que se usarán al dibujar la línea. |
| [LineIntent](./lineintent/) | Enumera los propósitos de la anotación de línea. |
| [PDF3DActivation](./pdf3dactivation/) | Enum [PDF3DActivation](./pdf3dactivation/): conjunto de modos de activación de anotaciones 3D. |
| [PolyIntent](./polyintent/) | Enumera los propósitos de la anotación de polígono o polilínea. |
| [PredefinedAction](./predefinedaction/) | Define diferentes acciones que pueden activarse desde un archivo PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Representa una posición de una marca en una esquina de una página. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Representa una posición de una marca de registro en una página. |
| [PrinterMarksKind](./printermarkskind/) | Especifica los tipos de marcas de impresora que se añadirán a un documento. |
| [RenderModeType](./rendermodetype/) | Enum [RenderModeType](./rendermodetype/): conjunto de tipos de modo de renderizado. |
| [RenditionOperation](./renditionoperation/) | La operación a realizar cuando se activa la acción. |
| [RenditionType](./renditiontype/) | La enumeración describe los tipos posibles de [Rendition](./rendition/). |
| [ReplyType](./replytype/) | Enumera los tipos de relaciones (el "tipo de respuesta") entre la anotación y una especificada por InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | Opciones para dar estilo a fragmentos de texto en RichText. |
| [SoundEncoding](./soundencoding/) | El formato de codificación para los datos de ejemplo. |
| [SoundIcon](./soundicon/) | Enumera los íconos que se usarán al mostrar la anotación. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | El formato de codificación de los datos de muestra de sonido. |
| [StampIcon](./stampicon/) | Enumera los íconos que se usarán al mostrar la anotación. |
| [TextAlignment](./textalignment/) | Alineación del texto en la anotación. |
| [TextIcon](./texticon/) | Enumera los íconos que se usarán al mostrar la anotación. |
