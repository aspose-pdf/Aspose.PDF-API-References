---
title: Aspose.Pdf.AI
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI-namnområdet tillhandahåller klasser för AI-funktioner inklusive API-klienter och intelligenta assistenter
type: docs
weight: 40
url: /sv/net/aspose.pdf.ai/
---
Namnområdet **Aspose.Pdf.AI** tillhandahåller klasser för AI-funktioner, inklusive API-klienter och intelligenta assistenter.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AIClientBase](./aiclientbase/) | Representerar klient för att få tillgång till AI API. |
| [AIClientException](./aiclientexception/) | Representerar ett undantag specifikt för AI-klientoperationer. |
| [AICopilotException](./aicopilotexception/) | Representerar ett undantag specifikt för Copilot-operationer. |
| [AICopilotFactory](./aicopilotfactory/) | Fabrikklass för att skapa olika typer av copiloter. |
| [Annotation](./annotation/) | Representerar textinnehållet som är en del av ett meddelande. |
| [AssistantCreateRequest](./assistantcreaterequest/) | Begärningsobjekt för att skapa en assistent. |
| [AssistantListQueryParameters](./assistantlistqueryparameters/) | Representerar frågeparametrarna för att lista assistenter. |
| [AssistantListResponse](./assistantlistresponse/) | Representerar svaret som innehåller en lista över assistentsvar. |
| [AssistantModifyRequest](./assistantmodifyrequest/) | Begärningsobjekt för att modifiera en assistent. |
| [AssistantResponse](./assistantresponse/) | Representerar en assistent som kan anropa modellen och använda verktyg. |
| [Attachment](./attachment/) | Representerar en lista över filer som är bifogade meddelandet och de verktyg de ska läggas till. |
| [BaseListQueryParameters](./baselistqueryparameters/) | Grundläggande frågeparametrar för att lista objekt. |
| [BaseResponse](./baseresponse/) | Grundklass för API-svar. |
| [CancellationTokenExtensions](./cancellationtokenextensions/) | Tillhandahåller extensionsmetoder för CancellationToken. |
| [ChatMessage](./chatmessage/) | Ett chattkompletteringsmeddelande som genererats av modellen. |
| [Choice](./choice/) | Representerar ett val i ett chattkompletteringssvar. |
| [CodeInterpreter](./codeinterpreter/) | Representerar resurser för kodtolkverktyget. |
| [CompletionCreateRequest](./completioncreaterequest/) | Representerar en begäran för Create Chat Completion-endpointen. |
| [CompletionFunction](./completionfunction/) | Representerar funktionsobjektet. |
| [CompletionResponse](./completionresponse/) | Representerar ett chattkompletteringssvar som returnerats av modellen, baserat på den angivna inmatningen. |
| [CreateChatCompletionChunkResponse](./createchatcompletionchunkresponse/) | Representerar en strömmad del av ett chattkompletteringssvar som returnerats av modellen, baserat på den angivna inmatningen. |
| [CreateEmbeddingRequest](./createembeddingrequest/) | Representerar en begäran för Create Embeddings-endpointen. |
| [CreateEmbeddingResponse](./createembeddingresponse/) | Representerar ett svar från Create Embeddings-endpointen. |
| [CreateFineTuningJobRequest](./createfinetuningjobrequest/) | Representerar en begäran för Create Fine-Tuning Job-endpointen. |
| [CreateFineTuningJobResponse](./createfinetuningjobresponse/) | Representerar ett svar från Create Fine-Tuning Job-endpointen. |
| [DataResponse&lt;T&gt;](./dataresponse-1/) | Representerar ett datorsvar som innehåller de angivna uppgifterna. |
| [DeleteStatusResponse](./deletestatusresponse/) | Representerar statusen för en objekts borttagning. |
| [DocumentCollection](./documentcollection/) | Representerar en samling av dokument som ska behandlas. |
| [Embedding](./embedding/) | Representerar en inbäddningsvektor som returnerats av inbäddningsendpointen. |
| [Error](./error/) | Representerar ett fel i API-svaret. |
| [ExpiresAfter](./expiresafter/) | Representerar utgångspolicyn för en vektorbutik. |
| [FileCitation](./filecitation/) | Representerar filciteringen. |
| [FileContentResponse&lt;T&gt;](./filecontentresponse-1/) |  |
| [FileCounts](./filecounts/) |  |
| [FileListResponse](./filelistresponse/) | Representerar ett fil-lista svar som innehåller en lista över fil-svar. |
| [FileResponse](./fileresponse/) | FileResponse-objektet representerar ett dokument som har laddats upp till OpenAI. |
| [FileSearch](./filesearch/) | Representerar resurserna för fil sökverktyget. |
| [Function](./function/) | Representerar en funktion som kan anropas av modellen. |
| [Hyperparameters](./hyperparameters/) | Representerar hyperparametrarna som används för ett finjusteringsjobb. |
| [ImageDescription](./imagedescription/) | Representerar en bildbeskrivning. |
| [ImageDescriptionResult](./imagedescriptionresult/) | Representerar svaret som innehåller bildbeskrivningar. |
| [ImageFile](./imagefile/) | Representerar en bildfil i innehållet av ett meddelande. |
| [ImageUrl](./imageurl/) | Representerar en bild-URL i innehållet av ett meddelande. |
| [IncompleteDetails](./incompletedetails/) | Detaljer om varför körningen är ofullständig. Kommer att vara null om körningen inte är ofullständig. |
| [LastError](./lasterror/) | Det sista felet som är kopplat till denna körning. Kommer att vara null om det inte finns några fel. |
| [ListDataResponse&lt;T&gt;](./listdataresponse-1/) | Representerar ett listdata-svar som innehåller ytterligare information såsom första och sista ID:n och om det finns fler objekt. |
| [LlamaChatCompletionRequest](./llamachatcompletionrequest/) | Representerar begärningskroppen för ChatGPT API-begärningar. |
| [LlamaChatCompletionResponse](./llamachatcompletionresponse/) | Representerar ett chattkompletteringssvar som returnerats av modellen, baserat på den angivna inmatningen. |
| [LlamaClient](./llamaclient/) | Representerar en klient för att interagera med Llama API. |
| [LlamaCopilotOptionsBase](./llamacopilotoptionsbase/) | Representerar grundalternativen för att konfigurera LlamaCopilot. |
| [LlamaModels](./llamamodels/) | Innehåller konstanter relaterade till olika Llama-modeller. |
| [LlamaSummaryCopilot](./llamasummarycopilot/) | Tillhandahåller funktionalitet för att få dokument sammanfattningar med hjälp av AI-modeller. Exempel på användning av att skapa en Llama-klient, konfigurera alternativ och använda sammanfattningscopilot. Observera: Denna copilot använder kompletterings-API, så den totala mängden text som kan skickas begränsas av modellens kontextfönster. |
| [LlamaSummaryCopilotOptions](./llamasummarycopilotoptions/) | Representerar alternativen för att konfigurera OpenAICopilot. |
| [Logprobs](./logprobs/) | Representerar logg sannolikhetsinformation för ett val. |
| [MessageContentBase](./messagecontentbase/) | Innehållet i meddelandet i en array av text och/eller bilder. |
| [MessageContentRequest](./messagecontentrequest/) | Innehållet i meddelandet i en array av text och/eller bilder. |
| [MessageContentResponse](./messagecontentresponse/) | Innehållet i svarmeddelandet i en array av text och/eller bilder. |
| [MessageCreation](./messagecreation/) | Representerar skapandet av ett meddelande med dess unika identifierare. |
| [OpenAIAssistantCopilotOptionsBase](./openaiassistantcopilotoptionsbase/) | Representerar grundalternativen för att konfigurera OpenAICopilots baserat på Assistants API. |
| [OpenAIChatCopilot](./openaichatcopilot/) | Representerar en chattcopilot för att interagera med dokument via AI-modeller. Exempel på användning av att skapa en OpenAI-klient, konfigurera alternativ och använda ChatCopilot för att interagera med användarfrågor och hantera konversationskontext. |
| [OpenAIChatCopilotOptions](./openaichatcopilotoptions/) | Representerar alternativen för att konfigurera OpenAICopilot. |
| [OpenAIClient](./openaiclient/) | Tillhandahåller metoder för att interagera med OpenAI API för att hantera vektorbutik filbatchar. |
| [OpenAIContext](./openaicontext/) | Representerar enhets-ID:n relaterade till en assistent. |
| [OpenAICopilotOptionsBase](./openaicopilotoptionsbase/) | Representerar grundalternativen för att konfigurera OpenAICopilot. |
| [OpenAIImageDescriptionCopilot](./openaiimagedescriptioncopilot/) | Tillhandahåller bildbehandlingsfunktionalitet för OpenAICopilot-klassen. Exempel på användning av att skapa en OpenAI-klient, konfigurera alternativ för ImageDescriptionCopilot och använda copilot för att generera bildbeskrivningar och lägga till beskrivningar till bifogade dokument. |
| [OpenAIImageDescriptionCopilotExtensions](./openaiimagedescriptioncopilotextensions/) | Tillhandahåller extensionsmetoder för OpenAIImageDescriptionCopilot-klassen. |
| [OpenAIImageDescriptionCopilotOptions](./openaiimagedescriptioncopilotoptions/) | Representerar alternativen för att konfigurera OpenAICopilot. |
| [OpenAIModels](./openaimodels/) | Innehåller de tillgängliga identifierarna för OpenAI-modeller. |
| [OpenAISummaryCopilot](./openaisummarycopilot/) | Tillhandahåller funktionalitet för att få dokument sammanfattningar med hjälp av AI-modeller. Exempel på användning av att skapa en OpenAI-klient, konfigurera alternativ och använda sammanfattningscopilot. |
| [OpenAISummaryCopilotOptions](./openaisummarycopilotoptions/) | Representerar alternativen för att konfigurera OpenAICopilot. |
| [PdfDocument](./pdfdocument/) | Representerar ett PDF-dokument med ett namn. |
| [RequiredAction](./requiredaction/) | Detaljer om den åtgärd som krävs för att fortsätta körningen. Kommer att vara null om ingen åtgärd krävs. |
| [ResponseFormat](./responseformat/) | Representerar formatet för ett svar, vilket kan vara antingen ett strängvärde eller ett objektvärde. |
| [RunCreateRequest](./runcreaterequest/) | Representerar en begäran för att skapa en körning. |
| [RunListQueryParameters](./runlistqueryparameters/) | Frågeparametrarobjekt för att lista körningar. |
| [RunListResponse](./runlistresponse/) | Representerar ett list-svar som innehåller körningsdata. |
| [RunModifyRequest](./runmodifyrequest/) | Representerar en begäran för att modifiera en körning. |
| [RunResponse](./runresponse/) | Representerar en exekveringskörning på en tråd. |
| [RunStepDetails](./runstepdetails/) | Detaljer om körningssteget. |
| [RunStepListQueryParameters](./runsteplistqueryparameters/) | Frågeparametrarobjekt för att lista körningssteg. |
| [RunStepListResponse](./runsteplistresponse/) | Representerar ett list-svar som innehåller körningsstegsdata. |
| [RunStepResponse](./runstepresponse/) | Representerar ett steg i exekveringen av en körning. |
| [RunThreadCreateRequest](./runthreadcreaterequest/) | Representerar en begäran för att skapa en tråd och köra den i en begäran. |
| [SubmitToolOutputs](./submittooloutputs/) | Representerar detaljer om verktygsutgångarna som behövs för att körningen ska fortsätta. |
| [TextDocument](./textdocument/) | Representerar ett textdokument med ett namn och innehåll. |
| [TextResponse](./textresponse/) | Representerar textinnehållet som är en del av ett meddelande. |
| [ThreadCreateRequest](./threadcreaterequest/) | Representerar en begäran för att skapa en tråd. |
| [ThreadMessageCreateRequest](./threadmessagecreaterequest/) | Representerar en begäran för att skapa ett meddelande inom en tråd. |
| [ThreadMessageListQueryParameters](./threadmessagelistqueryparameters/) | Frågeparametrarobjekt för att lista trådmeddelanden. |
| [ThreadMessageListResponse](./threadmessagelistresponse/) | Representerar ett list-svar som innehåller trådmeddelandedata. |
| [ThreadMessageModifyRequest](./threadmessagemodifyrequest/) | Representerar en begäran för att modifiera ett meddelande inom en tråd. |
| [ThreadMessageResponse](./threadmessageresponse/) | Representerar ett meddelande inom en tråd. |
| [ThreadModifyRequest](./threadmodifyrequest/) | Representerar en begäran för att modifiera en tråd. |
| [ThreadResponse](./threadresponse/) | Representerar en tråd som innehåller meddelanden. |
| [Tool](./tool/) | Representerar ett verktyg som kan anropas av modellen. |
| [ToolCall](./toolcall/) | Representerar ett verktygsanrop inom ett meddelande. |
| [ToolChoice](./toolchoice/) | Representerar ToolChoice, som kan vara antingen ett strängvärde eller ett objektvärde. |
| [ToolResources](./toolresources/) | Representerar en uppsättning resurser som används av assistentens verktyg. Resurserna är specifika för typen av verktyg. Till exempel kräver kodtolkverktyget en lista över fil-ID:n, medan fil sökverktyget kräver en lista över vektorbutiks-ID:n. |
| [TruncationStrategy](./truncationstrategy/) | Representerar avkortningsstrategin som styr hur en tråd kommer att avkortas före körningen. |
| [Usage](./usage/) | Representerar användningsstatistik för en begäran. |
| [VectorStore](./vectorstore/) | En hjälpare för att skapa en vektorbutik med file_ids och koppla den till denna tråd. Det kan maximalt finnas 1 vektorbutik kopplad till tråden. |
| [VectorStoreCreateRequest](./vectorstorecreaterequest/) | Skapa en begäran för en vektorbutik. |
| [VectorStoreFileBatchCreateRequest](./vectorstorefilebatchcreaterequest/) | Skapa en begäran för en vektorbutik filbatch. |
| [VectorStoreFileBatchFileListQueryParameters](./vectorstorefilebatchfilelistqueryparameters/) | Frågeparametrarobjekt för att lista vektorbutiksfilbatchfiler. |
| [VectorStoreFileBatchFileListResponse](./vectorstorefilebatchfilelistresponse/) | Representerar ett list-svar som innehåller data för vektorbutiksfilbatch. |
| [VectorStoreFileBatchResponse](./vectorstorefilebatchresponse/) | Vektorbutiksfilbatchens svarobjekt. |
| [VectorStoreFileCreateRequest](./vectorstorefilecreaterequest/) | Skapa en begäran för en vektorbutiksfil. |
| [VectorStoreFileListQueryParameters](./vectorstorefilelistqueryparameters/) | Frågeparametrarobjekt för att lista vektorbutiksfiler. |
| [VectorStoreFileListResponse](./vectorstorefilelistresponse/) | Representerar ett list-svar som innehåller data för vektorbutiksfiler. |
| [VectorStoreFileResponse](./vectorstorefileresponse/) | Ett vektorbutiksfil-svar. |
| [VectorStoreListQueryParameters](./vectorstorelistqueryparameters/) | Frågeparametrarobjekt för att lista vektorbutiker. |
| [VectorStoreListResponse](./vectorstorelistresponse/) | Representerar ett list-svar som innehåller data för vektorbutiker. |
| [VectorStoreModifyRequest](./vectorstoremodifyrequest/) | Modifiera en begäran för en vektorbutik. |
| [VectorStoreResponse](./vectorstoreresponse/) | Vektorbutiksobjektet. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IAIClient](./iaiclient/) | Representerar ett gränssnitt för en AI-klient. |
| [IAICopilot](./iaicopilot/) | Representerar en copilot för AI-interaktioner. |
| [IChatClient&lt;TOptions&gt;](./ichatclient-1/) | Representerar ett gränssnitt för en chattklient med specifika alternativ. |
| [IChatCopilot](./ichatcopilot/) | Representerar en chattcopilot för att interagera med dokument via AI-modeller. |
| [IChatCopilotOptions&lt;TOptions&gt;](./ichatcopilotoptions-1/) | Representerar ett gränssnitt för chattcopilotalternativ med en specifik typ. |
| [IEntityId](./ientityid/) | Representerar en enhet med ett ID. |
| [IImageDescriptionClient&lt;TOptions&gt;](./iimagedescriptionclient-1/) | Representerar ett gränssnitt för en bildbeskrivningsklient med specifika alternativ. |
| [IImageDescriptionCopilot](./iimagedescriptioncopilot/) | Representerar en bildbeskrivningscopilot för att extrahera bildbeskrivningar med hjälp av AI-modeller. |
| [IImageDescriptionCopilotOptions&lt;TOptions&gt;](./iimagedescriptioncopilotoptions-1/) | Representerar ett gränssnitt för alternativ för bildbeskrivningscopilot med en specifik typ. |
| [ILlamaClient](./illamaclient/) | Representerar ett klientgränssnitt för att interagera med Llama API. |
| [IOpenAIClient](./iopenaiclient/) | Representerar ett klientgränssnitt för att interagera med OpenAI API, som utökar grundläggande AI-klientfunktioner. |
| [IQueryParameters](./iqueryparameters/) | Representerar frågeparametrar för API-begärningar. |
| [IStatus](./istatus/) | Representerar statusen för en operation. |
| [IStringOrObject&lt;T&gt;](./istringorobject-1/) | Representerar ett objekt som kan vara antingen ett strängvärde eller ett objektvärde. |
| [ISummaryClient&lt;TOptions&gt;](./isummaryclient-1/) | Representerar ett gränssnitt för en sammanfattningsklient med specifika alternativ. |
| [ISummaryCopilot](./isummarycopilot/) | Representerar en sammanfattningscopilot för att generera sammanfattningar för dokument med hjälp av AI-modeller. |
| [ISummaryCopilotOptions&lt;TOptions&gt;](./isummarycopilotoptions-1/) | Representerar ett gränssnitt för alternativ för sammanfattningscopilot med en specifik typ. |