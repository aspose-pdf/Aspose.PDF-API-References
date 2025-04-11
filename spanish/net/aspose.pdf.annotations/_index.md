---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: El espacio de nombres Aspose.Pdf.Annotations proporciona clases para trabajar con varios tipos de acciones, destinos y otras características del documento que tradicionalmente se llaman interactivas, proporcionando medios para que el usuario pueda intercomunicarse con él.
type: docs
weight: 50
url: /es/net/aspose.pdf.annotations/
---
El **espacio de nombres Aspose.Pdf.Annotations** proporciona clases para trabajar con varios tipos de acciones, destinos y otras características del documento que tradicionalmente se llaman interactivas, proporcionando medios para que el usuario pueda intercomunicarse con él.

## Clases

| Clase | Descripción |
| --- | --- |
| [ActionCollection](./actioncollection/) | Colección de acciones |
| [Annotation](./annotation/) | Clase que representa el objeto de anotación. |
| [AnnotationActionCollection](./annotationactioncollection/) | Representa la colección de acciones de anotación. |
| [AnnotationCollection](./annotationcollection/) | Clase que representa la colección de anotaciones. |
| [AnnotationSelector](./annotationselector/) | Esta clase se utiliza para seleccionar anotaciones utilizando la idea del patrón Visitor. |
| [AppearanceDictionary](./appearancedictionary/) | Diccionario de apariencia de anotación que especifica cómo se presentará visualmente la anotación en la página. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Representa una anotación de marca de sangrado. |
| [Border](./border/) | Clase que representa las características del borde de la anotación. |
| [CaretAnnotation](./caretannotation/) | Clase que representa la anotación de caret. |
| [Characteristics](./characteristics/) | Representa las características de la anotación |
| [CircleAnnotation](./circleannotation/) | Clase que representa la anotación de círculo. |
| [ColorBarAnnotation](./colorbarannotation/) | Clase que representa la anotación ColorBarAnnotation. La propiedad Color se ignora, en su lugar se utiliza ColorsOfCMYK. Al crearla, la relación entre ancho y alto determina la orientación de la anotación: horizontal o vertical. A continuación, verifica que el rectángulo de la anotación esté fuera del TrimBox, y si no, se desplaza a la ubicación más cercana fuera del TrimBox, teniendo en cuenta la orientación de la anotación. Es posible reducir el ancho (alto) para que la anotación quepa fuera del TrimBox. Si no hay espacio para el diseño, el ancho/alto se puede establecer en cero (en este caso, la anotación está presente en la página, pero no se muestra). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Clase abstracta que representa la anotación de figura común. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Representa tipos de anotaciones que se colocan en las esquinas de la página impresa. |
| [CustomExplicitDestination](./customexplicitdestination/) | Representa un destino explícito personalizado. |
| [Dash](./dash/) | Clase que representa el patrón de línea discontinua. |
| [DefaultAppearance](./defaultappearance/) | Describe la apariencia predeterminada del campo (fuente, tamaño de texto y color). |
| [DocumentActionCollection](./documentactioncollection/) | Clase que describe las acciones realizadas en algunas acciones con el documento |
| [ExplicitDestination](./explicitdestination/) | Representa la clase base para destinos explícitos en el documento PDF. |
| [FdfReader](./fdfreader/) | Clase que realiza la lectura del formato FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Clase que describe la anotación de archivo adjunto. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Representa un destino explícito que muestra la página con su contenido ampliado lo suficiente para que su cuadro delimitador quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el más pequeño de los dos, centrando el cuadro delimitador dentro de la ventana en la otra dimensión. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo suficiente para que quepa todo el ancho de su cuadro delimitador dentro de la ventana. Un valor nulo para la parte superior especifica que el valor actual de ese parámetro debe mantenerse sin cambios. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo suficiente para que quepa toda la altura de su cuadro delimitador dentro de la ventana. Un valor nulo para la izquierda especifica que el valor actual de ese parámetro debe mantenerse sin cambios. |
| [FitExplicitDestination](./fitexplicitdestination/) | Representa un destino explícito que muestra la página con su contenido ampliado lo suficiente para que toda la página quepa dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el más pequeño de los dos, centrando la página dentro de la ventana en la otra dimensión. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo suficiente para que quepa todo el ancho de la página dentro de la ventana. Un valor nulo para la parte superior especifica que el valor actual de ese parámetro debe mantenerse sin cambios. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Representa un destino explícito que muestra la página con su contenido ampliado lo suficiente para que quepa el rectángulo especificado por las coordenadas izquierda, inferior, derecha y superior completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el más pequeño de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede resultar en un comportamiento impredecible. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo suficiente para que quepa toda la altura de la página dentro de la ventana. Un valor nulo para la izquierda especifica que el valor actual de ese parámetro debe mantenerse sin cambios. |
| [FixedPrint](./fixedprint/) | Representa los datos de impresión fija de la anotación de marca de agua. |
| [FreeTextAnnotation](./freetextannotation/) | Representa una anotación de texto libre que muestra texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene un estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible. |
| [GoToAction](./gotoaction/) | Representa una acción de ir a que cambia la vista a un destino especificado (página, ubicación y factor de ampliación). |
| [GoToRemoteAction](./gotoremoteaction/) | Representa una acción de ir a remota que es similar a una acción de ir a ordinaria pero salta a un destino en otro archivo PDF en lugar del archivo actual. |
| [GoToURIAction](./gotouriaction/) | Representa una acción URI que hace que se resuelva una URI. |
| [HideAction](./hideaction/) | Representa una acción de ocultar que oculta o muestra una o más anotaciones en la pantalla configurando o desmarcando sus banderas Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Representa una anotación de resaltado que resalta un rango de texto en el documento. |
| [ImportDataAction](./importdataaction/) | Al invocar una acción de importación de datos, los datos del Formato de Datos de Formularios (FDF) se importarán al formulario interactivo del documento desde un archivo especificado. |
| [InkAnnotation](./inkannotation/) | Representa un "garabato" a mano alzada compuesto de uno o más caminos disjuntos. |
| [JavascriptAction](./javascriptaction/) | Clase que representa la acción de javascript. |
| [LaunchAction](./launchaction/) | Representa una acción de lanzamiento que inicia una aplicación o abre o imprime un documento. |
| [LineAnnotation](./lineannotation/) | Clase que representa la anotación de línea. |
| [LinkAnnotation](./linkannotation/) | Representa un enlace de hipertexto a un destino en otro lugar del documento o una acción a realizar. |
| [MarkupAnnotation](./markupannotation/) | Clase abstracta que representa la anotación de marcado. |
| [Measure](./measure/) | Clase que describe el sistema de coordenadas de Medida. |
| [MediaClip](./mediaclip/) | Clase que describe el objeto de clip de medios de la representación. |
| [MediaClipData](./mediaclipdata/) | Clase que describe los datos del clip de medios. |
| [MediaClipSection](./mediaclipsection/) | Esta clase describe la sección del clip de medios. |
| [MediaRendition](./mediarendition/) | Clase que describe la representación de medios. |
| [MovieAnnotation](./movieannotation/) | Representa una anotación de película que contiene gráficos animados y sonido que se presentarán en la pantalla de la computadora y a través de los altavoces. Cuando se activa la anotación, se reproduce la película. |
| [NamedAction](./namedaction/) | Representa acciones nombradas que se espera que las aplicaciones de visualización de PDF admitan. |
| [NamedDestination](./nameddestination/) | En lugar de definirse directamente con la sintaxis explícita, un destino puede referirse indirectamente mediante un objeto de nombre o una cadena de bytes. |
| [PageInformationAnnotation](./pageinformationannotation/) | Representa una anotación de Información de Página en un documento PDF. Esta anotación contiene el nombre del archivo, el número de página y la fecha y hora de creación de la anotación. |
| [PDF3DAnnotation](./pdf3dannotation/) | Clase PDF3DAnnotation. Esta clase no se puede heredar. |
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
| [PdfAction](./pdfaction/) | Representa la acción en el documento PDF |
| [PdfActionCollection](./pdfactioncollection/) | Clase que describe la lista de acciones. |
| [PolyAnnotation](./polyannotation/) | Clase base abstracta para anotaciones poligonales. |
| [PolygonAnnotation](./polygonannotation/) | Clase que representa la anotación de polígono. |
| [PolylineAnnotation](./polylineannotation/) | Representa la anotación de polilínea que es similar al polígono, excepto que el primer y último vértice no están conectados implícitamente. |
| [PopupAnnotation](./popupannotation/) | Representa la anotación emergente que muestra texto en una ventana emergente para entrada y edición. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Clase abstracta que representa la anotación de marca de impresora. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Proporciona métodos de extensión para la enumeración [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Representa la anotación de redacción. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Representa una anotación de Marca de Registro. |
| [Rendition](./rendition/) | Clase que describe el objeto de representación de RenditionAnnotation. |
| [RenditionAction](./renditionaction/) | Una acción de representación que controla la reproducción de contenido multimedia. |
| [RichMediaAnnotation](./richmediaannotation/) | Clase que describe RichMediaAnnotation que permite incrustar datos de video/audio en el documento PDF. |
| [ScreenAnnotation](./screenannotation/) | Una anotación de pantalla que especifica una región de una página sobre la cual se pueden reproducir clips de medios. |
| [SelectorRendition](./selectorrendition/) | Clase que describe la representación del selector. |
| [SoundAnnotation](./soundannotation/) | Representa una anotación de sonido que contiene sonido grabado desde el micrófono de la computadora o importado desde un archivo. |
| [SoundData](./sounddata/) | Representa datos de sonido que definen el sonido que se reproducirá cuando se active la anotación. |
| [SoundSampleData](./soundsampledata/) | Representa entradas adicionales específicas para un objeto de sonido (Sección 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Clase que representa la anotación de cuadrado. |
| [SquigglyAnnotation](./squigglyannotation/) | Representa la anotación ondulada que aparece como un subrayado en zigzag en el texto de un documento. |
| [StampAnnotation](./stampannotation/) | Representa la anotación de sello de goma. Este tipo de anotación muestra texto o gráficos que parecen haber sido estampados en la página con un sello de goma. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Representa una anotación de tachado que aparece como un tachado en el texto del documento. |
| [SubmitFormAction](./submitformaction/) | Clase que describe la acción de enviar formulario. |
| [TextAnnotation](./textannotation/) | Representa una anotación de texto que es una 'nota adhesiva' adjunta a un punto en el documento PDF. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Clase base abstracta para anotaciones de marcado de texto. |
| [TextStyle](./textstyle/) | Clase que representa el estilo del texto en la anotación |
| [TrimMarkAnnotation](./trimmarkannotation/) | Representa una anotación de marca de recorte. |
| [UnderlineAnnotation](./underlineannotation/) | Representa una anotación de subrayado que aparece como un subrayado en el texto del documento. |
| [WatermarkAnnotation](./watermarkannotation/) | Clase que describe el objeto de anotación de marca de agua. |
| [WidgetAnnotation](./widgetannotation/) | Clase que representa la anotación de widget. |
| [XfdfReader](./xfdfreader/) | Clase que realiza la lectura del formato XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Representa un destino explícito que muestra la página con las coordenadas (izquierda, arriba) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, arriba o zoom especifica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Define el Visitor para visitar diferentes anotaciones del documento. |
| [IAppointment](./iappointment/) | Representa la interfaz general para acciones y destinos. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Un conjunto de banderas que especifican varias características de la anotación. |
| [AnnotationState](./annotationstate/) | La enumeración de estados a los que se puede establecer la anotación original. |
| [AnnotationStateModel](./annotationstatemodel/) | El modelo de estado correspondiente al estado de la anotación. |
| [AnnotationType](./annotationtype/) | Enumeración de tipos de anotaciones. |
| [BorderEffect](./bordereffect/) | Describe el efecto que debe aplicarse al borde de las anotaciones. |
| [BorderStyle](./borderstyle/) | Describe el estilo del borde de la anotación. |
| [CapStyle](./capstyle/) | Estilo del extremo de línea de la línea de anotación de tinta. |
| [CaptionPosition](./captionposition/) | Enumeración de la posición del título de la anotación. |
| [CaretSymbol](./caretsymbol/) | Un símbolo que se asociará con el caret. |
| [ColorsOfCMYK](./colorsofcmyk/) | Colores incluidos en el modelo de color CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumera los tipos de destinos explícitos. |
| [FileIcon](./fileicon/) | Un ícono que se utilizará para mostrar la anotación. |
| [FreeTextIntent](./freetextintent/) | Enumera las intenciones de la anotación de texto libre. |
| [HighlightingMode](./highlightingmode/) | Enumera el modo de resaltado de la anotación, el efecto visual que se utilizará cuando se presione o mantenga presionado el botón del mouse dentro de su área activa. |
| [Justification](./justification/) | Enumera las formas de justificación que se utilizarán al mostrar el texto de la anotación. |
| [LaunchActionOperation](./launchactionoperation/) | Enumera las operaciones a realizar con el documento durante la ejecución de la acción de lanzamiento. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: conjunto de tipos de esquemas de iluminación. |
| [LineEnding](./lineending/) | Enumera los estilos de finalización de línea que se utilizarán al dibujar la línea. |
| [LineIntent](./lineintent/) | Enumera las intenciones de la anotación de línea. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: conjunto de modos de activación de anotaciones 3D. |
| [PolyIntent](./polyintent/) | Enumera las intenciones de la anotación de polígono o polilínea. |
| [PredefinedAction](./predefinedaction/) | Define diferentes acciones que pueden ser activadas desde un archivo PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Representa una posición de una marca en una esquina de una página. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Representa una posición de una marca de registro en una página. |
| [PrinterMarksKind](./printermarkskind/) | Especifica los tipos de marcas de impresora que se agregarán a un documento. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: conjunto de tipos de modo de representación |
| [RenditionOperation](./renditionoperation/) | La operación a realizar cuando se activa la acción. |
| [RenditionType](./renditiontype/) | Enumeración que describe los posibles tipos de representación. |
| [ReplyType](./replytype/) | Enumera los tipos de relaciones (el "tipo de respuesta") entre la anotación y una especificada por InReplyTo. |
| [SoundEncoding](./soundencoding/) | El formato de codificación para los datos de muestra. |
| [SoundIcon](./soundicon/) | Enumera los íconos que se utilizarán para mostrar la anotación. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | El formato de codificación para los datos de muestra de sonido. |
| [StampIcon](./stampicon/) | Enumera los íconos que se utilizarán para mostrar la anotación. |
| [TextIcon](./texticon/) | Enumera los íconos que se utilizarán para mostrar la anotación. |