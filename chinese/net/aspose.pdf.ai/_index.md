---
title: Aspose.Pdf.AI
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI 命名空间提供用于 AI 功能的类，包括 API 客户端和智能助手
type: docs
weight: 40
url: /zh/net/aspose.pdf.ai/
---
**Aspose.Pdf.AI** 命名空间提供用于 AI 功能的类，包括 API 客户端和智能助手。

## 类

| 类 | 描述 |
| --- | --- |
| [AIClientBase](./aiclientbase/) | 表示访问 AI API 的客户端。 |
| [AIClientException](./aiclientexception/) | 表示特定于 AI 客户端操作的异常。 |
| [AICopilotException](./aicopilotexception/) | 表示特定于 Copilots 操作的异常。 |
| [AICopilotFactory](./aicopilotfactory/) | 创建不同类型的 copilots 的工厂类。 |
| [Annotation](./annotation/) | 表示消息的一部分的文本内容。 |
| [AssistantCreateRequest](./assistantcreaterequest/) | 创建助手的请求对象。 |
| [AssistantListQueryParameters](./assistantlistqueryparameters/) | 表示用于列出助手的查询参数对象。 |
| [AssistantListResponse](./assistantlistresponse/) | 表示包含助手响应列表的响应。 |
| [AssistantModifyRequest](./assistantmodifyrequest/) | 修改助手的请求对象。 |
| [AssistantResponse](./assistantresponse/) | 表示可以调用模型并使用工具的助手。 |
| [Attachment](./attachment/) | 表示附加到消息的文件列表，以及它们应添加到的工具。 |
| [BaseListQueryParameters](./baselistqueryparameters/) | 列出对象的基本查询参数。 |
| [BaseResponse](./baseresponse/) | API 响应的基类。 |
| [CancellationTokenExtensions](./cancellationtokenextensions/) | 提供 CancellationToken 的扩展方法。 |
| [ChatMessage](./chatmessage/) | 模型生成的聊天完成消息。 |
| [Choice](./choice/) | 表示聊天完成响应中的一个选择。 |
| [CodeInterpreter](./codeinterpreter/) | 表示代码解释器工具资源。 |
| [CompletionCreateRequest](./completioncreaterequest/) | 表示创建聊天完成端点的请求。 |
| [CompletionFunction](./completionfunction/) | 表示函数对象。 |
| [CompletionResponse](./completionresponse/) | 表示模型根据提供的输入返回的聊天完成响应。 |
| [CreateChatCompletionChunkResponse](./createchatcompletionchunkresponse/) | 表示模型根据提供的输入返回的聊天完成响应的流式块。 |
| [CreateEmbeddingRequest](./createembeddingrequest/) | 表示创建嵌入端点的请求。 |
| [CreateEmbeddingResponse](./createembeddingresponse/) | 表示来自创建嵌入端点的响应。 |
| [CreateFineTuningJobRequest](./createfinetuningjobrequest/) | 表示创建微调作业端点的请求。 |
| [CreateFineTuningJobResponse](./createfinetuningjobresponse/) | 表示来自创建微调作业端点的响应。 |
| [DataResponse&lt;T&gt;](./dataresponse-1/) | 表示包含指定数据的数据响应。 |
| [DeleteStatusResponse](./deletestatusresponse/) | 表示对象删除的状态。 |
| [DocumentCollection](./documentcollection/) | 表示要处理的文档集合。 |
| [Embedding](./embedding/) | 表示嵌入端点返回的嵌入向量。 |
| [Error](./error/) | 表示 API 响应中的错误。 |
| [ExpiresAfter](./expiresafter/) | 表示向量存储的过期策略。 |
| [FileCitation](./filecitation/) | 表示文件引用。 |
| [FileContentResponse&lt;T&gt;](./filecontentresponse-1/) |  |
| [FileCounts](./filecounts/) |  |
| [FileListResponse](./filelistresponse/) | 表示包含文件响应列表的文件列表响应。 |
| [FileResponse](./fileresponse/) | FileResponse 对象表示已上传到 OpenAI 的文档。 |
| [FileSearch](./filesearch/) | 表示文件搜索工具资源。 |
| [Function](./function/) | 表示可以被模型调用的函数。 |
| [Hyperparameters](./hyperparameters/) | 表示用于微调作业的超参数。 |
| [ImageDescription](./imagedescription/) | 表示图像描述。 |
| [ImageDescriptionResult](./imagedescriptionresult/) | 表示包含图像描述的响应。 |
| [ImageFile](./imagefile/) | 表示消息内容中的图像文件。 |
| [ImageUrl](./imageurl/) | 表示消息内容中的图像 URL。 |
| [IncompleteDetails](./incompletedetails/) | 运行不完整的原因的详细信息。如果运行没有不完整，则为 null。 |
| [LastError](./lasterror/) | 与此运行相关的最后一个错误。如果没有错误，则为 null。 |
| [ListDataResponse&lt;T&gt;](./listdataresponse-1/) | 表示包含附加信息（如第一个和最后一个 ID 以及是否有更多项目）的列表数据响应。 |
| [LlamaChatCompletionRequest](./llamachatcompletionrequest/) | 表示 ChatGPT API 请求的请求体。 |
| [LlamaChatCompletionResponse](./llamachatcompletionresponse/) | 表示模型根据提供的输入返回的聊天完成响应。 |
| [LlamaClient](./llamaclient/) | 表示与 Llama API 交互的客户端。 |
| [LlamaCopilotOptionsBase](./llamacopilotoptionsbase/) | 表示配置 LlamaCopilot 的基本选项。 |
| [LlamaModels](./llamamodels/) | 包含与不同 Llama 模型相关的常量。 |
| [LlamaSummaryCopilot](./llamasummarycopilot/) | 提供使用 AI 模型获取文档摘要的功能。示例用法包括创建 Llama 客户端、配置选项和使用摘要 copilots。注意：此 copilot 使用完成 API，因此可以发送的文本总量受模型上下文窗口的限制。 |
| [LlamaSummaryCopilotOptions](./llamasummarycopilotoptions/) | 表示配置 OpenAICopilot 的选项。 |
| [Logprobs](./logprobs/) | 表示选择的对数概率信息。 |
| [MessageContentBase](./messagecontentbase/) | 消息内容的文本和/或图像数组。 |
| [MessageContentRequest](./messagecontentrequest/) | 消息内容的文本和/或图像数组。 |
| [MessageContentResponse](./messagecontentresponse/) | 响应消息的内容，包含文本和/或图像数组。 |
| [MessageCreation](./messagecreation/) | 表示具有唯一标识符的消息的创建。 |
| [OpenAIAssistantCopilotOptionsBase](./openaiassistantcopilotoptionsbase/) | 表示基于 Assistants API 配置 OpenAICopilots 的基本选项。 |
| [OpenAIChatCopilot](./openaichatcopilot/) | 表示用于通过 AI 模型与文档交互的聊天 copilot。示例用法包括创建 OpenAI 客户端、配置选项和使用 ChatCopilot 与用户查询交互并管理对话上下文。 |
| [OpenAIChatCopilotOptions](./openaichatcopilotoptions/) | 表示配置 OpenAICopilot 的选项。 |
| [OpenAIClient](./openaiclient/) | 提供与 OpenAI API 交互以管理向量存储文件批次的方法。 |
| [OpenAIContext](./openaicontext/) | 表示与助手相关的实体 ID。 |
| [OpenAICopilotOptionsBase](./openaicopilotoptionsbase/) | 表示配置 OpenAICopilot 的基本选项。 |
| [OpenAIImageDescriptionCopilot](./openaiimagedescriptioncopilot/) | 提供 OpenAICopilot 类的图像处理功能。示例用法包括创建 OpenAI 客户端、配置 ImageDescriptionCopilot 选项，并使用 copilot 生成图像描述并将描述添加到附加文档中。 |
| [OpenAIImageDescriptionCopilotExtensions](./openaiimagedescriptioncopilotextensions/) | 提供 OpenAIImageDescriptionCopilot 类的扩展方法。 |
| [OpenAIImageDescriptionCopilotOptions](./openaiimagedescriptioncopilotoptions/) | 表示配置 OpenAICopilot 的选项。 |
| [OpenAIModels](./openaimodels/) | 包含可用的 OpenAI 模型标识符。 |
| [OpenAISummaryCopilot](./openaisummarycopilot/) | 提供使用 AI 模型获取文档摘要的功能。示例用法包括创建 OpenAI 客户端、配置选项和使用摘要 copilot。 |
| [OpenAISummaryCopilotOptions](./openaisummarycopilotoptions/) | 表示配置 OpenAICopilot 的选项。 |
| [PdfDocument](./pdfdocument/) | 表示具有名称的 PDF 文档。 |
| [RequiredAction](./requiredaction/) | 继续运行所需的操作的详细信息。如果不需要任何操作，则为 null。 |
| [ResponseFormat](./responseformat/) | 表示响应的格式，可以是字符串值或对象值。 |
| [RunCreateRequest](./runcreaterequest/) | 表示创建运行的请求。 |
| [RunListQueryParameters](./runlistqueryparameters/) | 列出运行的查询参数对象。 |
| [RunListResponse](./runlistresponse/) | 表示包含运行数据的列表响应。 |
| [RunModifyRequest](./runmodifyrequest/) | 表示修改运行的请求。 |
| [RunResponse](./runresponse/) | 表示在线程上执行的运行。 |
| [RunStepDetails](./runstepdetails/) | 运行步骤的详细信息。 |
| [RunStepListQueryParameters](./runsteplistqueryparameters/) | 列出运行步骤的查询参数对象。 |
| [RunStepListResponse](./runsteplistresponse/) | 表示包含运行步骤数据的列表响应。 |
| [RunStepResponse](./runstepresponse/) | 表示运行执行中的一步。 |
| [RunThreadCreateRequest](./runthreadcreaterequest/) | 表示创建线程并在一个请求中运行的请求。 |
| [SubmitToolOutputs](./submittooloutputs/) | 表示继续运行所需的工具输出的详细信息。 |
| [TextDocument](./textdocument/) | 表示具有名称和内容的文本文档。 |
| [TextResponse](./textresponse/) | 表示消息的一部分的文本内容。 |
| [ThreadCreateRequest](./threadcreaterequest/) | 表示创建线程的请求。 |
| [ThreadMessageCreateRequest](./threadmessagecreaterequest/) | 表示在线程内创建消息的请求。 |
| [ThreadMessageListQueryParameters](./threadmessagelistqueryparameters/) | 列出线程消息的查询参数对象。 |
| [ThreadMessageListResponse](./threadmessagelistresponse/) | 表示包含线程消息数据的列表响应。 |
| [ThreadMessageModifyRequest](./threadmessagemodifyrequest/) | 表示修改线程内消息的请求。 |
| [ThreadMessageResponse](./threadmessageresponse/) | 表示线程内的消息。 |
| [ThreadModifyRequest](./threadmodifyrequest/) | 表示修改线程的请求。 |
| [ThreadResponse](./threadresponse/) | 表示包含消息的线程。 |
| [Tool](./tool/) | 表示可以被模型调用的工具。 |
| [ToolCall](./toolcall/) | 表示消息中的工具调用。 |
| [ToolChoice](./toolchoice/) | 表示 ToolChoice，可以是字符串值或对象值。 |
| [ToolResources](./toolresources/) | 表示助手工具使用的一组资源。资源特定于工具类型。例如，code_interpreter 工具需要文件 ID 列表，而 file_search 工具需要向量存储 ID 列表。 |
| [TruncationStrategy](./truncationstrategy/) | 表示控制线程在运行之前如何被截断的截断策略。 |
| [Usage](./usage/) | 表示请求的使用统计信息。 |
| [VectorStore](./vectorstore/) | 帮助创建一个带有 file_ids 的向量存储并将其附加到此线程。线程最多可以附加 1 个向量存储。 |
| [VectorStoreCreateRequest](./vectorstorecreaterequest/) | 创建向量存储请求。 |
| [VectorStoreFileBatchCreateRequest](./vectorstorefilebatchcreaterequest/) | 创建向量存储文件批次请求。 |
| [VectorStoreFileBatchFileListQueryParameters](./vectorstorefilebatchfilelistqueryparameters/) | 列出向量存储文件批次文件的查询参数对象。 |
| [VectorStoreFileBatchFileListResponse](./vectorstorefilebatchfilelistresponse/) | 表示包含向量存储文件批次数据的列表响应。 |
| [VectorStoreFileBatchResponse](./vectorstorefilebatchresponse/) | 向量存储文件批次响应对象。 |
| [VectorStoreFileCreateRequest](./vectorstorefilecreaterequest/) | 创建向量存储文件请求。 |
| [VectorStoreFileListQueryParameters](./vectorstorefilelistqueryparameters/) | 列出向量存储文件的查询参数对象。 |
| [VectorStoreFileListResponse](./vectorstorefilelistresponse/) | 表示包含向量存储文件数据的列表响应。 |
| [VectorStoreFileResponse](./vectorstorefileresponse/) | 向量存储文件响应。 |
| [VectorStoreListQueryParameters](./vectorstorelistqueryparameters/) | 列出向量存储的查询参数对象。 |
| [VectorStoreListResponse](./vectorstorelistresponse/) | 表示包含向量存储数据的列表响应。 |
| [VectorStoreModifyRequest](./vectorstoremodifyrequest/) | 修改向量存储请求。 |
| [VectorStoreResponse](./vectorstoreresponse/) | 向量存储对象。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IAIClient](./iaiclient/) | 表示 AI 客户端的接口。 |
| [IAICopilot](./iaicopilot/) | 表示用于 AI 交互的 copilot。 |
| [IChatClient&lt;TOptions&gt;](./ichatclient-1/) | 表示具有特定选项的聊天客户端接口。 |
| [IChatCopilot](./ichatcopilot/) | 表示用于通过 AI 模型与文档交互的聊天 copilot。 |
| [IChatCopilotOptions&lt;TOptions&gt;](./ichatcopilotoptions-1/) | 表示具有特定类型的聊天 copilot 选项的接口。 |
| [IEntityId](./ientityid/) | 表示具有 ID 的实体。 |
| [IImageDescriptionClient&lt;TOptions&gt;](./iimagedescriptionclient-1/) | 表示具有特定选项的图像描述客户端接口。 |
| [IImageDescriptionCopilot](./iimagedescriptioncopilot/) | 表示用于提取图像描述的图像描述 copilot，使用 AI 模型。 |
| [IImageDescriptionCopilotOptions&lt;TOptions&gt;](./iimagedescriptioncopilotoptions-1/) | 表示具有特定类型的图像描述 copilot 选项的接口。 |
| [ILlamaClient](./illamaclient/) | 表示与 Llama API 交互的客户端接口。 |
| [IOpenAIClient](./iopenaiclient/) | 表示与 OpenAI API 交互的客户端接口，扩展基本 AI 客户端功能。 |
| [IQueryParameters](./iqueryparameters/) | 表示 API 请求的查询参数。 |
| [IStatus](./istatus/) | 表示操作的状态。 |
| [IStringOrObject&lt;T&gt;](./istringorobject-1/) | 表示可以是字符串值或对象值的对象。 |
| [ISummaryClient&lt;TOptions&gt;](./isummaryclient-1/) | 表示具有特定选项的摘要客户端接口。 |
| [ISummaryCopilot](./isummarycopilot/) | 表示用于生成文档摘要的摘要 copilot，使用 AI 模型。 |
| [ISummaryCopilotOptions&lt;TOptions&gt;](./isummarycopilotoptions-1/) | 表示具有特定类型的摘要 copilot 选项的接口。 |