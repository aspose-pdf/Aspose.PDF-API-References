---
title: Aspose.Pdf.AI
second_title: Aspose.PDF for .NET API Reference
description: L'espace de noms Aspose.Pdf.AI fournit des classes pour des fonctionnalités d'IA, y compris des clients API et des assistants intelligents
type: docs
weight: 40
url: /fr/net/aspose.pdf.ai/
---
L'espace de noms **Aspose.Pdf.AI** fournit des classes pour des fonctionnalités d'IA, y compris des clients API et des assistants intelligents.

## Classes

| Classe | Description |
| --- | --- |
| [AIClientBase](./aiclientbase/) | Représente un client pour accéder à l'API IA. |
| [AIClientException](./aiclientexception/) | Représente une exception spécifique aux opérations du client IA. |
| [AICopilotException](./aicopilotexception/) | Représente une exception spécifique aux opérations des copilotes. |
| [AICopilotFactory](./aicopilotfactory/) | Classe de fabrique pour créer différents types de copilotes. |
| [Annotation](./annotation/) | Représente le contenu textuel qui fait partie d'un message. |
| [AssistantCreateRequest](./assistantcreaterequest/) | Objet de requête pour créer un assistant. |
| [AssistantListQueryParameters](./assistantlistqueryparameters/) | Représente l'objet des paramètres de requête pour lister les assistants. |
| [AssistantListResponse](./assistantlistresponse/) | Représente la réponse contenant une liste de réponses d'assistants. |
| [AssistantModifyRequest](./assistantmodifyrequest/) | Objet de requête pour modifier un assistant. |
| [AssistantResponse](./assistantresponse/) | Représente un assistant qui peut appeler le modèle et utiliser des outils. |
| [Attachment](./attachment/) | Représente une liste de fichiers attachés au message, et les outils auxquels ils doivent être ajoutés. |
| [BaseListQueryParameters](./baselistqueryparameters/) | Paramètres de requête de base pour lister des objets. |
| [BaseResponse](./baseresponse/) | Classe de base pour les réponses API. |
| [CancellationTokenExtensions](./cancellationtokenextensions/) | Fournit des méthodes d'extension pour CancellationToken. |
| [ChatMessage](./chatmessage/) | Un message de complétion de chat généré par le modèle. |
| [Choice](./choice/) | Représente un choix dans une réponse de complétion de chat. |
| [CodeInterpreter](./codeinterpreter/) | Représente les ressources de l'outil d'interprétation de code. |
| [CompletionCreateRequest](./completioncreaterequest/) | Représente une requête pour le point de terminaison Créer une complétion de chat. |
| [CompletionFunction](./completionfunction/) | Représente l'objet fonction. |
| [CompletionResponse](./completionresponse/) | Représente une réponse de complétion de chat renvoyée par le modèle, basée sur l'entrée fournie. |
| [CreateChatCompletionChunkResponse](./createchatcompletionchunkresponse/) | Représente un morceau de réponse de complétion de chat en streaming renvoyé par le modèle, basé sur l'entrée fournie. |
| [CreateEmbeddingRequest](./createembeddingrequest/) | Représente une requête pour le point de terminaison Créer des embeddings. |
| [CreateEmbeddingResponse](./createembeddingresponse/) | Représente une réponse du point de terminaison Créer des embeddings. |
| [CreateFineTuningJobRequest](./createfinetuningjobrequest/) | Représente une requête pour le point de terminaison Créer un travail de fine-tuning. |
| [CreateFineTuningJobResponse](./createfinetuningjobresponse/) | Représente une réponse du point de terminaison Créer un travail de fine-tuning. |
| [DataResponse&lt;T&gt;](./dataresponse-1/) | Représente une réponse de données contenant les données spécifiées. |
| [DeleteStatusResponse](./deletestatusresponse/) | Représente le statut d'une suppression d'objet. |
| [DocumentCollection](./documentcollection/) | Représente une collection de documents à traiter. |
| [Embedding](./embedding/) | Représente un vecteur d'embedding renvoyé par le point de terminaison d'embedding. |
| [Error](./error/) | Représente une erreur dans la réponse API. |
| [ExpiresAfter](./expiresafter/) | Représente la politique d'expiration pour un magasin de vecteurs. |
| [FileCitation](./filecitation/) | Représente la citation de fichier. |
| [FileContentResponse&lt;T&gt;](./filecontentresponse-1/) |  |
| [FileCounts](./filecounts/) |  |
| [FileListResponse](./filelistresponse/) | Représente une réponse de liste de fichiers contenant une liste de réponses de fichiers. |
| [FileResponse](./fileresponse/) | L'objet FileResponse représente un document qui a été téléchargé sur OpenAI. |
| [FileSearch](./filesearch/) | Représente les ressources de l'outil de recherche de fichiers. |
| [Function](./function/) | Représente une fonction qui peut être appelée par le modèle. |
| [Hyperparameters](./hyperparameters/) | Représente les hyperparamètres utilisés pour un travail de fine-tuning. |
| [ImageDescription](./imagedescription/) | Représente une description d'image. |
| [ImageDescriptionResult](./imagedescriptionresult/) | Représente la réponse contenant des descriptions d'images. |
| [ImageFile](./imagefile/) | Représente un fichier image dans le contenu d'un message. |
| [ImageUrl](./imageurl/) | Représente une URL d'image dans le contenu d'un message. |
| [IncompleteDetails](./incompletedetails/) | Détails sur pourquoi l'exécution est incomplète. Sera nul si l'exécution n'est pas incomplète. |
| [LastError](./lasterror/) | La dernière erreur associée à cette exécution. Sera nul s'il n'y a pas d'erreurs. |
| [ListDataResponse&lt;T&gt;](./listdataresponse-1/) | Représente une réponse de données de liste contenant des informations supplémentaires telles que les premiers et derniers ID et si d'autres éléments existent. |
| [LlamaChatCompletionRequest](./llamachatcompletionrequest/) | Représente le corps de la requête pour les requêtes API ChatGPT. |
| [LlamaChatCompletionResponse](./llamachatcompletionresponse/) | Représente une réponse de complétion de chat renvoyée par le modèle, basée sur l'entrée fournie. |
| [LlamaClient](./llamaclient/) | Représente un client pour interagir avec l'API Llama. |
| [LlamaCopilotOptionsBase](./llamacopilotoptionsbase/) | Représente les options de base pour configurer le LlamaCopilot. |
| [LlamaModels](./llamamodels/) | Contient des constantes liées à différents modèles Llama. |
| [LlamaSummaryCopilot](./llamasummarycopilot/) | Fournit des fonctionnalités pour obtenir des résumés de documents en utilisant des modèles d'IA. Exemple d'utilisation de la création d'un client Llama, de la configuration des options et de l'utilisation du copilote de résumé. Remarque : Ce copilote utilise l'API de complétion, donc la quantité totale de texte pouvant être envoyée est limitée par la fenêtre de contexte du modèle. |
| [LlamaSummaryCopilotOptions](./llamasummarycopilotoptions/) | Représente les options pour configurer le OpenAICopilot. |
| [Logprobs](./logprobs/) | Représente les informations de probabilité logarithmique pour un choix. |
| [MessageContentBase](./messagecontentbase/) | Le contenu du message dans un tableau de texte et/ou d'images. |
| [MessageContentRequest](./messagecontentrequest/) | Le contenu du message dans un tableau de texte et/ou d'images. |
| [MessageContentResponse](./messagecontentresponse/) | Le contenu du message de réponse dans un tableau de texte et/ou d'images. |
| [MessageCreation](./messagecreation/) | Représente la création d'un message avec son identifiant unique. |
| [OpenAIAssistantCopilotOptionsBase](./openaiassistantcopilotoptionsbase/) | Représente les options de base pour configurer les OpenAICopilots basés sur l'API des assistants. |
| [OpenAIChatCopilot](./openaichatcopilot/) | Représente un copilote de chat pour interagir avec des documents via des modèles d'IA. Exemple d'utilisation de la création d'un client OpenAI, de la configuration des options et de l'utilisation du ChatCopilot pour interagir avec les requêtes des utilisateurs et gérer le contexte de la conversation. |
| [OpenAIChatCopilotOptions](./openaichatcopilotoptions/) | Représente les options pour configurer le OpenAICopilot. |
| [OpenAIClient](./openaiclient/) | Fournit des méthodes pour interagir avec l'API OpenAI pour gérer des lots de fichiers de magasin de vecteurs. |
| [OpenAIContext](./openaicontext/) | Représente les ID d'entité liés à un assistant. |
| [OpenAICopilotOptionsBase](./openaicopilotoptionsbase/) | Représente les options de base pour configurer le OpenAICopilot. |
| [OpenAIImageDescriptionCopilot](./openaiimagedescriptioncopilot/) | Fournit des fonctionnalités de traitement d'image pour la classe OpenAICopilot. Exemple d'utilisation de la création d'un client OpenAI, de la configuration des options de ImageDescriptionCopilot, et de l'utilisation du copilote pour générer des descriptions d'images et ajouter des descriptions aux documents attachés. |
| [OpenAIImageDescriptionCopilotExtensions](./openaiimagedescriptioncopilotextensions/) | Fournit des méthodes d'extension pour la classe OpenAIImageDescriptionCopilot. |
| [OpenAIImageDescriptionCopilotOptions](./openaiimagedescriptioncopilotoptions/) | Représente les options pour configurer le OpenAICopilot. |
| [OpenAIModels](./openaimodels/) | Contient les identifiants de modèles OpenAI disponibles. |
| [OpenAISummaryCopilot](./openaisummarycopilot/) | Fournit des fonctionnalités pour obtenir des résumés de documents en utilisant des modèles d'IA. Exemple d'utilisation de la création d'un client OpenAI, de la configuration des options et de l'utilisation du copilote de résumé. |
| [OpenAISummaryCopilotOptions](./openaisummarycopilotoptions/) | Représente les options pour configurer le OpenAICopilot. |
| [PdfDocument](./pdfdocument/) | Représente un document PDF avec un nom. |
| [RequiredAction](./requiredaction/) | Détails sur l'action requise pour continuer l'exécution. Sera nul si aucune action n'est requise. |
| [ResponseFormat](./responseformat/) | Représente le format d'une réponse, qui peut être soit une valeur de chaîne, soit une valeur d'objet. |
| [RunCreateRequest](./runcreaterequest/) | Représente une requête pour créer une exécution. |
| [RunListQueryParameters](./runlistqueryparameters/) | Objet des paramètres de requête pour lister les exécutions. |
| [RunListResponse](./runlistresponse/) | Représente une réponse de liste contenant des données d'exécution. |
| [RunModifyRequest](./runmodifyrequest/) | Représente une requête pour modifier une exécution. |
| [RunResponse](./runresponse/) | Représente une exécution sur un fil. |
| [RunStepDetails](./runstepdetails/) | Les détails de l'étape d'exécution. |
| [RunStepListQueryParameters](./runsteplistqueryparameters/) | Objet des paramètres de requête pour lister les étapes d'exécution. |
| [RunStepListResponse](./runsteplistresponse/) | Représente une réponse de liste contenant des données d'étape d'exécution. |
| [RunStepResponse](./runstepresponse/) | Représente une étape dans l'exécution d'une exécution. |
| [RunThreadCreateRequest](./runthreadcreaterequest/) | Représente une requête pour créer un fil et l'exécuter en une seule requête. |
| [SubmitToolOutputs](./submittooloutputs/) | Représente des détails sur les sorties d'outil nécessaires pour que l'exécution continue. |
| [TextDocument](./textdocument/) | Représente un document texte avec un nom et un contenu. |
| [TextResponse](./textresponse/) | Représente le contenu textuel qui fait partie d'un message. |
| [ThreadCreateRequest](./threadcreaterequest/) | Représente une requête pour créer un fil. |
| [ThreadMessageCreateRequest](./threadmessagecreaterequest/) | Représente une requête pour créer un message dans un fil. |
| [ThreadMessageListQueryParameters](./threadmessagelistqueryparameters/) | Objet des paramètres de requête pour lister les messages de fil. |
| [ThreadMessageListResponse](./threadmessagelistresponse/) | Représente une réponse de liste contenant des données de message de fil. |
| [ThreadMessageModifyRequest](./threadmessagemodifyrequest/) | Représente une requête pour modifier un message dans un fil. |
| [ThreadMessageResponse](./threadmessageresponse/) | Représente un message dans un fil. |
| [ThreadModifyRequest](./threadmodifyrequest/) | Représente une requête pour modifier un fil. |
| [ThreadResponse](./threadresponse/) | Représente un fil qui contient des messages. |
| [Tool](./tool/) | Représente un outil qui peut être appelé par le modèle. |
| [ToolCall](./toolcall/) | Représente un appel d'outil dans un message. |
| [ToolChoice](./toolchoice/) | Représente le ToolChoice, qui peut être soit une valeur de chaîne, soit une valeur d'objet. |
| [ToolResources](./toolresources/) | Représente un ensemble de ressources utilisées par les outils de l'assistant. Les ressources sont spécifiques au type d'outil. Par exemple, l'outil code_interpreter nécessite une liste d'ID de fichiers, tandis que l'outil file_search nécessite une liste d'ID de magasin de vecteurs. |
| [TruncationStrategy](./truncationstrategy/) | Représente la stratégie de troncature qui contrôle comment un fil sera tronqué avant l'exécution. |
| [Usage](./usage/) | Représente des statistiques d'utilisation pour une requête. |
| [VectorStore](./vectorstore/) | Un helper pour créer un magasin de vecteurs avec des file_ids et l'attacher à ce fil. Il peut y avoir un maximum de 1 magasin de vecteurs attaché au fil. |
| [VectorStoreCreateRequest](./vectorstorecreaterequest/) | Créer une requête de magasin de vecteurs. |
| [VectorStoreFileBatchCreateRequest](./vectorstorefilebatchcreaterequest/) | Créer une requête de lot de fichiers de magasin de vecteurs. |
| [VectorStoreFileBatchFileListQueryParameters](./vectorstorefilebatchfilelistqueryparameters/) | Objet des paramètres de requête pour lister les fichiers de lot de fichiers de magasin de vecteurs. |
| [VectorStoreFileBatchFileListResponse](./vectorstorefilebatchfilelistresponse/) | Représente une réponse de liste contenant des données de lot de fichiers de magasin de vecteurs. |
| [VectorStoreFileBatchResponse](./vectorstorefilebatchresponse/) | L'objet de réponse de lot de fichiers de magasin de vecteurs. |
| [VectorStoreFileCreateRequest](./vectorstorefilecreaterequest/) | Créer une requête de fichier de magasin de vecteurs. |
| [VectorStoreFileListQueryParameters](./vectorstorefilelistqueryparameters/) | Objet des paramètres de requête pour lister les fichiers de magasin de vecteurs. |
| [VectorStoreFileListResponse](./vectorstorefilelistresponse/) | Représente une réponse de liste contenant des données de fichier de magasin de vecteurs. |
| [VectorStoreFileResponse](./vectorstorefileresponse/) | Une réponse de fichier de magasin de vecteurs. |
| [VectorStoreListQueryParameters](./vectorstorelistqueryparameters/) | Objet des paramètres de requête pour lister les magasins de vecteurs. |
| [VectorStoreListResponse](./vectorstorelistresponse/) | Représente une réponse de liste contenant des données de magasin de vecteurs. |
| [VectorStoreModifyRequest](./vectorstoremodifyrequest/) | Modifier une requête de magasin de vecteurs. |
| [VectorStoreResponse](./vectorstoreresponse/) | L'objet de magasin de vecteurs. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IAIClient](./iaiclient/) | Représente une interface pour un client IA. |
| [IAICopilot](./iaicopilot/) | Représente un copilote pour les interactions IA. |
| [IChatClient&lt;TOptions&gt;](./ichatclient-1/) | Représente une interface pour un client de chat avec des options spécifiques. |
| [IChatCopilot](./ichatcopilot/) | Représente un copilote de chat pour interagir avec des documents via des modèles d'IA. |
| [IChatCopilotOptions&lt;TOptions&gt;](./ichatcopilotoptions-1/) | Représente une interface pour les options de copilote de chat avec un type spécifique. |
| [IEntityId](./ientityid/) | Représente une entité avec un ID. |
| [IImageDescriptionClient&lt;TOptions&gt;](./iimagedescriptionclient-1/) | Représente une interface pour un client de description d'image avec des options spécifiques. |
| [IImageDescriptionCopilot](./iimagedescriptioncopilot/) | Représente un copilote de description d'image pour extraire des descriptions d'image en utilisant des modèles d'IA. |
| [IImageDescriptionCopilotOptions&lt;TOptions&gt;](./iimagedescriptioncopilotoptions-1/) | Représente une interface pour les options de copilote de description d'image avec un type spécifique. |
| [ILlamaClient](./illamaclient/) | Représente une interface de client pour interagir avec l'API Llama. |
| [IOpenAIClient](./iopenaiclient/) | Représente une interface de client pour interagir avec l'API OpenAI, étendant les fonctionnalités de base du client IA. |
| [IQueryParameters](./iqueryparameters/) | Représente des paramètres de requête pour les requêtes API. |
| [IStatus](./istatus/) | Représente le statut d'une opération. |
| [IStringOrObject&lt;T&gt;](./istringorobject-1/) | Représente un objet qui peut être soit une valeur de chaîne, soit une valeur d'objet. |
| [ISummaryClient&lt;TOptions&gt;](./isummaryclient-1/) | Représente une interface pour un client de résumé avec des options spécifiques. |
| [ISummaryCopilot](./isummarycopilot/) | Représente un copilote de résumé pour générer des résumés pour des documents en utilisant des modèles d'IA. |
| [ISummaryCopilotOptions&lt;TOptions&gt;](./isummarycopilotoptions-1/) | Représente une interface pour les options de copilote de résumé avec un type spécifique. |