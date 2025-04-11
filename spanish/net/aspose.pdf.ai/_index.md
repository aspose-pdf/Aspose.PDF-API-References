---
title: Aspose.Pdf.AI
second_title: Aspose.PDF for .NET API Reference
description: El espacio de nombres Aspose.Pdf.AI proporciona clases para funcionalidades de IA, incluidos clientes de API y asistentes inteligentes
type: docs
weight: 40
url: /es/net/aspose.pdf.ai/
---
El **espacio de nombres Aspose.Pdf.AI** proporciona clases para funcionalidades de IA, incluidos clientes de API y asistentes inteligentes.

## Clases

| Clase | Descripción |
| --- | --- |
| [AIClientBase](./aiclientbase/) | Representa un cliente para acceder a la API de IA. |
| [AIClientException](./aiclientexception/) | Representa una excepción específica de las operaciones del cliente de IA. |
| [AICopilotException](./aicopilotexception/) | Representa una excepción específica de las operaciones de Copilotos. |
| [AICopilotFactory](./aicopilotfactory/) | Clase de fábrica para crear diferentes tipos de copilotos. |
| [Annotation](./annotation/) | Representa el contenido de texto que es parte de un mensaje. |
| [AssistantCreateRequest](./assistantcreaterequest/) | Objeto de solicitud para crear un asistente. |
| [AssistantListQueryParameters](./assistantlistqueryparameters/) | Representa el objeto de parámetros de consulta para listar asistentes. |
| [AssistantListResponse](./assistantlistresponse/) | Representa la respuesta que contiene una lista de respuestas de asistentes. |
| [AssistantModifyRequest](./assistantmodifyrequest/) | Objeto de solicitud para modificar un asistente. |
| [AssistantResponse](./assistantresponse/) | Representa un asistente que puede llamar al modelo y usar herramientas. |
| [Attachment](./attachment/) | Representa una lista de archivos adjuntos al mensaje y las herramientas a las que deben ser añadidos. |
| [BaseListQueryParameters](./baselistqueryparameters/) | Parámetros de consulta base para listar objetos. |
| [BaseResponse](./baseresponse/) | Clase base para respuestas de API. |
| [CancellationTokenExtensions](./cancellationtokenextensions/) | Proporciona métodos de extensión para CancellationToken. |
| [ChatMessage](./chatmessage/) | Un mensaje de finalización de chat generado por el modelo. |
| [Choice](./choice/) | Representa una elección en una respuesta de finalización de chat. |
| [CodeInterpreter](./codeinterpreter/) | Representa los recursos de la herramienta de intérprete de código. |
| [CompletionCreateRequest](./completioncreaterequest/) | Representa una solicitud para el punto final de Crear Finalización de Chat. |
| [CompletionFunction](./completionfunction/) | Representa el objeto de función. |
| [CompletionResponse](./completionresponse/) | Representa una respuesta de finalización de chat devuelta por el modelo, basada en la entrada proporcionada. |
| [CreateChatCompletionChunkResponse](./createchatcompletionchunkresponse/) | Representa un fragmento transmitido de una respuesta de finalización de chat devuelta por el modelo, basada en la entrada proporcionada. |
| [CreateEmbeddingRequest](./createembeddingrequest/) | Representa una solicitud para el punto final de Crear Embeddings. |
| [CreateEmbeddingResponse](./createembeddingresponse/) | Representa una respuesta del punto final de Crear Embeddings. |
| [CreateFineTuningJobRequest](./createfinetuningjobrequest/) | Representa una solicitud para el punto final de Crear Trabajo de Ajuste Fino. |
| [CreateFineTuningJobResponse](./createfinetuningjobresponse/) | Representa una respuesta del punto final de Crear Trabajo de Ajuste Fino. |
| [DataResponse&lt;T&gt;](./dataresponse-1/) | Representa una respuesta de datos que contiene los datos especificados. |
| [DeleteStatusResponse](./deletestatusresponse/) | Representa el estado de una eliminación de objeto. |
| [DocumentCollection](./documentcollection/) | Representa una colección de documentos a ser procesados. |
| [Embedding](./embedding/) | Representa un vector de embedding devuelto por el punto final de embedding. |
| [Error](./error/) | Representa un error en la respuesta de la API. |
| [ExpiresAfter](./expiresafter/) | Representa la política de expiración para un almacén de vectores. |
| [FileCitation](./filecitation/) | Representa la cita del archivo. |
| [FileContentResponse&lt;T&gt;](./filecontentresponse-1/) |  |
| [FileCounts](./filecounts/) |  |
| [FileListResponse](./filelistresponse/) | Representa una respuesta de lista de archivos que contiene una lista de respuestas de archivos. |
| [FileResponse](./fileresponse/) | El objeto FileResponse representa un documento que ha sido subido a OpenAI. |
| [FileSearch](./filesearch/) | Representa los recursos de la herramienta de búsqueda de archivos. |
| [Function](./function/) | Representa una función que puede ser llamada por el modelo. |
| [Hyperparameters](./hyperparameters/) | Representa los hiperparámetros utilizados para un trabajo de ajuste fino. |
| [ImageDescription](./imagedescription/) | Representa una descripción de imagen. |
| [ImageDescriptionResult](./imagedescriptionresult/) | Representa la respuesta que contiene descripciones de imágenes. |
| [ImageFile](./imagefile/) | Representa un archivo de imagen en el contenido de un mensaje. |
| [ImageUrl](./imageurl/) | Representa una URL de imagen en el contenido de un mensaje. |
| [IncompleteDetails](./incompletedetails/) | Detalles sobre por qué la ejecución está incompleta. Será nulo si la ejecución no está incompleta. |
| [LastError](./lasterror/) | El último error asociado con esta ejecución. Será nulo si no hay errores. |
| [ListDataResponse&lt;T&gt;](./listdataresponse-1/) | Representa una respuesta de datos de lista que contiene información adicional como los primeros y últimos ID y si hay más elementos. |
| [LlamaChatCompletionRequest](./llamachatcompletionrequest/) | Representa el cuerpo de la solicitud para las solicitudes de la API de ChatGPT. |
| [LlamaChatCompletionResponse](./llamachatcompletionresponse/) | Representa una respuesta de finalización de chat devuelta por el modelo, basada en la entrada proporcionada. |
| [LlamaClient](./llamaclient/) | Representa un cliente para interactuar con la API de Llama. |
| [LlamaCopilotOptionsBase](./llamacopilotoptionsbase/) | Representa las opciones base para configurar el LlamaCopilot. |
| [LlamaModels](./llamamodels/) | Contiene constantes relacionadas con diferentes modelos de Llama. |
| [LlamaSummaryCopilot](./llamasummarycopilot/) | Proporciona funcionalidad para obtener resúmenes de documentos utilizando modelos de IA. Ejemplo de uso de creación de un cliente Llama, configuración de opciones y uso del copiloto de resumen. Nota: Este copiloto utiliza la API de finalización, por lo que la cantidad total de texto que se puede enviar está limitada por la ventana de contexto del modelo. |
| [LlamaSummaryCopilotOptions](./llamasummarycopilotoptions/) | Representa las opciones para configurar el OpenAICopilot. |
| [Logprobs](./logprobs/) | Representa información de probabilidad logarítmica para una elección. |
| [MessageContentBase](./messagecontentbase/) | El contenido del mensaje en un array de texto y/o imágenes. |
| [MessageContentRequest](./messagecontentrequest/) | El contenido del mensaje en un array de texto y/o imágenes. |
| [MessageContentResponse](./messagecontentresponse/) | El contenido de la respuesta del mensaje en un array de texto y/o imágenes. |
| [MessageCreation](./messagecreation/) | Representa la creación de un mensaje con su identificador único. |
| [OpenAIAssistantCopilotOptionsBase](./openaiassistantcopilotoptionsbase/) | Representa las opciones base para configurar los OpenAICopilots basados en la API de Asistentes. |
| [OpenAIChatCopilot](./openaichatcopilot/) | Representa un copiloto de chat para interactuar con documentos a través de modelos de IA. Ejemplo de uso de creación de un cliente OpenAI, configuración de opciones y uso del ChatCopilot para interactuar con consultas de usuarios y gestionar el contexto de la conversación. |
| [OpenAIChatCopilotOptions](./openaichatcopilotoptions/) | Representa las opciones para configurar el OpenAICopilot. |
| [OpenAIClient](./openaiclient/) | Proporciona métodos para interactuar con la API de OpenAI para gestionar lotes de archivos de almacén de vectores. |
| [OpenAIContext](./openaicontext/) | Representa los ID de entidad relacionados con un asistente. |
| [OpenAICopilotOptionsBase](./openaicopilotoptionsbase/) | Representa las opciones base para configurar el OpenAICopilot. |
| [OpenAIImageDescriptionCopilot](./openaiimagedescriptioncopilot/) | Proporciona funcionalidad de procesamiento de imágenes para la clase OpenAICopilot. Ejemplo de uso de creación de un cliente OpenAI, configuración de opciones de ImageDescriptionCopilot y uso del copiloto para generar descripciones de imágenes y añadir descripciones a documentos adjuntos. |
| [OpenAIImageDescriptionCopilotExtensions](./openaiimagedescriptioncopilotextensions/) | Proporciona métodos de extensión para la clase OpenAIImageDescriptionCopilot. |
| [OpenAIImageDescriptionCopilotOptions](./openaiimagedescriptioncopilotoptions/) | Representa las opciones para configurar el OpenAICopilot. |
| [OpenAIModels](./openaimodels/) | Contiene los identificadores de modelos de OpenAI disponibles. |
| [OpenAISummaryCopilot](./openaisummarycopilot/) | Proporciona funcionalidad para obtener resúmenes de documentos utilizando modelos de IA. Ejemplo de uso de creación de un cliente OpenAI, configuración de opciones y uso del copiloto de resumen. |
| [OpenAISummaryCopilotOptions](./openaisummarycopilotoptions/) | Representa las opciones para configurar el OpenAICopilot. |
| [PdfDocument](./pdfdocument/) | Representa un documento PDF con un nombre. |
| [RequiredAction](./requiredaction/) | Detalles sobre la acción requerida para continuar la ejecución. Será nulo si no se requiere ninguna acción. |
| [ResponseFormat](./responseformat/) | Representa el formato de una respuesta, que puede ser un valor de cadena o un valor de objeto. |
| [RunCreateRequest](./runcreaterequest/) | Representa una solicitud para crear una ejecución. |
| [RunListQueryParameters](./runlistqueryparameters/) | Objeto de parámetros de consulta para listar ejecuciones. |
| [RunListResponse](./runlistresponse/) | Representa una respuesta de lista que contiene datos de ejecución. |
| [RunModifyRequest](./runmodifyrequest/) | Representa una solicitud para modificar una ejecución. |
| [RunResponse](./runresponse/) | Representa una ejecución en un hilo. |
| [RunStepDetails](./runstepdetails/) | Los detalles del paso de ejecución. |
| [RunStepListQueryParameters](./runsteplistqueryparameters/) | Objeto de parámetros de consulta para listar pasos de ejecución. |
| [RunStepListResponse](./runsteplistresponse/) | Representa una respuesta de lista que contiene datos de pasos de ejecución. |
| [RunStepResponse](./runstepresponse/) | Representa un paso en la ejecución de una ejecución. |
| [RunThreadCreateRequest](./runthreadcreaterequest/) | Representa una solicitud para crear un hilo y ejecutarlo en una sola solicitud. |
| [SubmitToolOutputs](./submittooloutputs/) | Representa detalles sobre las salidas de la herramienta necesarias para que la ejecución continúe. |
| [TextDocument](./textdocument/) | Representa un documento de texto con un nombre y contenido. |
| [TextResponse](./textresponse/) | Representa el contenido de texto que es parte de un mensaje. |
| [ThreadCreateRequest](./threadcreaterequest/) | Representa una solicitud para crear un hilo. |
| [ThreadMessageCreateRequest](./threadmessagecreaterequest/) | Representa una solicitud para crear un mensaje dentro de un hilo. |
| [ThreadMessageListQueryParameters](./threadmessagelistqueryparameters/) | Objeto de parámetros de consulta para listar mensajes de hilo. |
| [ThreadMessageListResponse](./threadmessagelistresponse/) | Representa una respuesta de lista que contiene datos de mensajes de hilo. |
| [ThreadMessageModifyRequest](./threadmessagemodifyrequest/) | Representa una solicitud para modificar un mensaje dentro de un hilo. |
| [ThreadMessageResponse](./threadmessageresponse/) | Representa un mensaje dentro de un hilo. |
| [ThreadModifyRequest](./threadmodifyrequest/) | Representa una solicitud para modificar un hilo. |
| [ThreadResponse](./threadresponse/) | Representa un hilo que contiene mensajes. |
| [Tool](./tool/) | Representa una herramienta que puede ser llamada por el modelo. |
| [ToolCall](./toolcall/) | Representa una llamada a la herramienta dentro de un mensaje. |
| [ToolChoice](./toolchoice/) | Representa la ToolChoice, que puede ser un valor de cadena o un valor de objeto. |
| [ToolResources](./toolresources/) | Representa un conjunto de recursos que son utilizados por las herramientas del asistente. Los recursos son específicos del tipo de herramienta. Por ejemplo, la herramienta code_interpreter requiere una lista de ID de archivos, mientras que la herramienta file_search requiere una lista de ID de almacén de vectores. |
| [TruncationStrategy](./truncationstrategy/) | Representa la estrategia de truncamiento que controla cómo se truncará un hilo antes de la ejecución. |
| [Usage](./usage/) | Representa estadísticas de uso para una solicitud. |
| [VectorStore](./vectorstore/) | Un ayudante para crear un almacén de vectores con file_ids y adjuntarlo a este hilo. Puede haber un máximo de 1 almacén de vectores adjunto al hilo. |
| [VectorStoreCreateRequest](./vectorstorecreaterequest/) | Crear una solicitud de almacén de vectores. |
| [VectorStoreFileBatchCreateRequest](./vectorstorefilebatchcreaterequest/) | Crear una solicitud de lote de archivos de almacén de vectores. |
| [VectorStoreFileBatchFileListQueryParameters](./vectorstorefilebatchfilelistqueryparameters/) | Objeto de parámetros de consulta para listar archivos de lote de almacén de vectores. |
| [VectorStoreFileBatchFileListResponse](./vectorstorefilebatchfilelistresponse/) | Representa una respuesta de lista que contiene datos de lote de archivos de almacén de vectores. |
| [VectorStoreFileBatchResponse](./vectorstorefilebatchresponse/) | El objeto de respuesta de lote de archivos de almacén de vectores. |
| [VectorStoreFileCreateRequest](./vectorstorefilecreaterequest/) | Crear una solicitud de archivo de almacén de vectores. |
| [VectorStoreFileListQueryParameters](./vectorstorefilelistqueryparameters/) | Objeto de parámetros de consulta para listar archivos de almacén de vectores. |
| [VectorStoreFileListResponse](./vectorstorefilelistresponse/) | Representa una respuesta de lista que contiene datos de archivos de almacén de vectores. |
| [VectorStoreFileResponse](./vectorstorefileresponse/) | Una respuesta de archivo de almacén de vectores. |
| [VectorStoreListQueryParameters](./vectorstorelistqueryparameters/) | Objeto de parámetros de consulta para listar almacenes de vectores. |
| [VectorStoreListResponse](./vectorstorelistresponse/) | Representa una respuesta de lista que contiene datos de almacén de vectores. |
| [VectorStoreModifyRequest](./vectorstoremodifyrequest/) | Modificar una solicitud de almacén de vectores. |
| [VectorStoreResponse](./vectorstoreresponse/) | El objeto de almacén de vectores. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IAIClient](./iaiclient/) | Representa una interfaz para un cliente de IA. |
| [IAICopilot](./iaicopilot/) | Representa un copiloto para interacciones de IA. |
| [IChatClient&lt;TOptions&gt;](./ichatclient-1/) | Representa una interfaz para un cliente de chat con opciones específicas. |
| [IChatCopilot](./ichatcopilot/) | Representa un copiloto de chat para interactuar con documentos a través de modelos de IA. |
| [IChatCopilotOptions&lt;TOptions&gt;](./ichatcopilotoptions-1/) | Representa una interfaz para opciones de copiloto de chat con un tipo específico. |
| [IEntityId](./ientityid/) | Representa una entidad con un ID. |
| [IImageDescriptionClient&lt;TOptions&gt;](./iimagedescriptionclient-1/) | Representa una interfaz para un cliente de descripción de imagen con opciones específicas. |
| [IImageDescriptionCopilot](./iimagedescriptioncopilot/) | Representa un copiloto de descripción de imagen para extraer descripciones de imágenes utilizando modelos de IA. |
| [IImageDescriptionCopilotOptions&lt;TOptions&gt;](./iimagedescriptioncopilotoptions-1/) | Representa una interfaz para opciones de copiloto de descripción de imagen con un tipo específico. |
| [ILlamaClient](./illamaclient/) | Representa una interfaz de cliente para interactuar con la API de Llama. |
| [IOpenAIClient](./iopenaiclient/) | Representa una interfaz de cliente para interactuar con la API de OpenAI, extendiendo las funcionalidades básicas del cliente de IA. |
| [IQueryParameters](./iqueryparameters/) | Representa parámetros de consulta para solicitudes de API. |
| [IStatus](./istatus/) | Representa el estado de una operación. |
| [IStringOrObject&lt;T&gt;](./istringorobject-1/) | Representa un objeto que puede ser un valor de cadena o un valor de objeto. |
| [ISummaryClient&lt;TOptions&gt;](./isummaryclient-1/) | Representa una interfaz para un cliente de resumen con opciones específicas. |
| [ISummaryCopilot](./isummarycopilot/) | Representa un copiloto de resumen para generar resúmenes de documentos utilizando modelos de IA. |
| [ISummaryCopilotOptions&lt;TOptions&gt;](./isummarycopilotoptions-1/) | Representa una interfaz para opciones de copiloto de resumen con un tipo específico. |