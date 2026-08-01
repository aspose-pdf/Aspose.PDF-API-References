---
title: "Aspose.Pdf.AI"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "この Aspose.Pdf.AI 名前空間は、API クライアントやインテリジェントアシスタントを含む AI 機能のためのクラスを提供します。"
type: docs
weight: 40
url: /ja/net/aspose.pdf.ai/
---
**Aspose.Pdf.AI** 名前空間は、API クライアントやインテリジェントアシスタントなど、AI 機能向けのクラスを提供します。

## クラス

| クラス | 説明 |
| --- | --- |
| [AIClientBase](./aiclientbase/) | AI API にアクセスするクライアントを表します。 |
| [AIClientException](./aiclientexception/) | AI クライアントの操作に特化した例外を表します。 |
| [AICopilotException](./aicopilotexception/) | Copilot の操作に特化した例外を表します。 |
| [AICopilotFactory](./aicopilotfactory/) | さまざまなタイプの Copilot を作成するためのファクトリクラスです。 |
| [Annotation](./annotation/) | メッセージの一部であるテキストコンテンツを表します。 |
| [AssistantCreateRequest](./assistantcreaterequest/) | アシスタントを作成するためのリクエストオブジェクト。 |
| [AssistantListQueryParameters](./assistantlistqueryparameters/) | アシスタントの一覧取得用クエリパラメータオブジェクトを表します。 |
| [AssistantListResponse](./assistantlistresponse/) | アシスタント応答のリストを含むレスポンスを表します。 |
| [AssistantModifyRequest](./assistantmodifyrequest/) | アシスタントを変更するためのリクエストオブジェクト。 |
| [AssistantResponse](./assistantresponse/) | モデルを呼び出し、ツールを使用できるアシスタントを表します。 |
| [Attachment](./attachment/) | メッセージに添付されたファイルのリストと、追加すべきツールを表します。 |
| [BaseListQueryParameters](./baselistqueryparameters/) | オブジェクト一覧取得用の基本クエリパラメータ。 |
| [BaseResponse](./baseresponse/) | APIレスポンスの基本クラス。 |
| [CancellationTokenExtensions](./cancellationtokenextensions/) | CancellationToken の拡張メソッドを提供します。 |
| [ChatMessage](./chatmessage/) | モデルが生成したチャット完了メッセージ。 |
| [ChatMessageResponse](./chatmessageresponse/) | モデルが生成したチャット完了メッセージ。 |
| [Choice](./choice/) | チャット完了レスポンス内の選択肢を表します。 |
| [CodeInterpreter](./codeinterpreter/) | コードインタプリタツールのリソースを表します。 |
| [CompletionCreateRequest](./completioncreaterequest/) | Chat Completion 作成エンドポイントへのリクエストを表します。 |
| [CompletionFunction](./completionfunction/) | 関数オブジェクトを表します。 |
| [CompletionResponse](./completionresponse/) | 提供された入力に基づき、モデルが返すチャット完了レスポンスを表します。 |
| [CreateChatCompletionChunkResponse](./createchatcompletionchunkresponse/) | 提供された入力に基づき、モデルが返すチャット完了レスポンスのストリーミングチャンクを表します。 |
| [CreateEmbeddingRequest](./createembeddingrequest/) | Embeddings 作成エンドポイントへのリクエストを表します。 |
| [CreateEmbeddingResponse](./createembeddingresponse/) | Embeddings 作成エンドポイントからのレスポンスを表します。 |
| [CreateFineTuningJobRequest](./createfinetuningjobrequest/) | Fine-Tuning ジョブ作成エンドポイントへのリクエストを表します。 |
| [CreateFineTuningJobResponse](./createfinetuningjobresponse/) | Fine-Tuning ジョブ作成エンドポイントからのレスポンスを表します。 |
| [DataResponse&lt;T&gt;](./dataresponse-1/) | 指定されたデータを含むデータレスポンスを表します。 |
| [DeleteStatusResponse](./deletestatusresponse/) | オブジェクト削除のステータスを表します。 |
| [DocumentCollection](./documentcollection/) | 処理対象のドキュメントコレクションを表します。 |
| [Embedding](./embedding/) | Embedding エンドポイントから返される埋め込みベクトルを表します。 |
| [Error](./error/) | APIレスポンスのエラーを表します。 |
| [ExpiresAfter](./expiresafter/) | ベクトルストアの有効期限ポリシーを表します。 |
| [FileCitation](./filecitation/) | ファイルの引用を表します。 |
| [FileContentResponse&lt;T&gt;](./filecontentresponse-1/) |  |
| [FileCounts](./filecounts/) |  |
| [FileListResponse](./filelistresponse/) | ファイル応答のリストを含むファイルリスト応答を表します。 |
| [FileResponse](./fileresponse/) | FileResponse オブジェクトは、OpenAI にアップロードされたドキュメントを表します。 |
| [FileSearch](./filesearch/) | ファイル検索ツールのリソースを表します。 |
| [Function](./function/) | モデルから呼び出すことができる関数を表します。 |
| [Hyperparameters](./hyperparameters/) | ファインチューニングジョブで使用されるハイパーパラメータを表します。 |
| [ImageDescription](./imagedescription/) | 画像の説明を表します。 |
| [ImageDescriptionResult](./imagedescriptionresult/) | 画像の説明を含むレスポンスを表します。 |
| [ImageFile](./imagefile/) | メッセージの内容に含まれる画像ファイルを表します。 |
| [ImageUrl](./imageurl/) | メッセージの内容に含まれる画像 URL を表します。 |
| [IncompleteDetails](./incompletedetails/) | 実行が不完全である理由の詳細です。実行が不完全でない場合は null になります。 |
| [LastError](./lasterror/) | この実行に関連付けられた最後のエラーです。エラーがない場合は null になります。 |
| [ListDataResponse&lt;T&gt;](./listdataresponse-1/) | 最初と最後の ID、さらに項目が残っているかどうかなどの追加情報を含むリストデータレスポンスを表します。 |
| [LlamaChatCompletionRequest](./llamachatcompletionrequest/) | ChatGPT API リクエストのリクエストボディを表します。 |
| [LlamaChatCompletionResponse](./llamachatcompletionresponse/) | 提供された入力に基づき、モデルが返すチャット完了レスポンスを表します。 |
| [LlamaClient](./llamaclient/) | Llama API とやり取りするクライアントを表します。 |
| [LlamaCopilotOptionsBase](./llamacopilotoptionsbase/) | LlamaCopilot の設定に使用する基本オプションを表します。 |
| [LlamaModels](./llamamodels/) | さまざまな Llama モデルに関連する定数を含みます。 |
| [LlamaSummaryCopilot](./llamasummarycopilot/) | AI モデルを使用してドキュメントの要約を取得する機能を提供します。Llama クライアントの作成、オプションの設定、要約コパイロットの使用例です。注: このコパイロットは Completion API を使用するため、送信できるテキストの総量はモデルのコンテキストウィンドウで制限されます。 |
| [LlamaSummaryCopilotOptions](./llamasummarycopilotoptions/) | OpenAICopilot の設定オプションを表します。 |
| [Logprobs](./logprobs/) | 選択肢の対数確率情報を表します。 |
| [MessageContentBase](./messagecontentbase/) | テキストおよび/または画像の配列としてのメッセージ内容です。 |
| [MessageContentRequest](./messagecontentrequest/) | テキストおよび/または画像の配列としてのメッセージ内容です。 |
| [MessageContentResponse](./messagecontentresponse/) | テキストおよび/または画像の配列としてのレスポンスメッセージ内容です。 |
| [MessageCreation](./messagecreation/) | 一意の識別子を持つメッセージの作成を表します。 |
| [OcrDetail](./ocrdetail/) | ドキュメントの単一ページまたは単一画像ファイルの OCR 結果を表します。 |
| [OpenAIAssistantCopilotOptionsBase](./openaiassistantcopilotoptionsbase/) | Assistants API に基づいて OpenAICopilots を構成するための基本オプションを表します。 |
| [OpenAIChatCopilot](./openaichatcopilot/) | AI モデルを介してドキュメントとやり取りするためのチャットコパイロットを表します。OpenAI クライアントの作成、オプションの構成、および ChatCopilot を使用してユーザーの問い合わせに応答し、会話コンテキストを管理する例です。 |
| [OpenAIChatCopilotOptions](./openaichatcopilotoptions/) | OpenAICopilot の設定オプションを表します。 |
| [OpenAIClient](./openaiclient/) | ベクトルストアのファイルバッチを管理するために OpenAI API とやり取りするメソッドを提供します。 |
| [OpenAIContext](./openaicontext/) | アシスタントに関連するエンティティ ID を表します。 |
| [OpenAICopilotOptionsBase](./openaicopilotoptionsbase/) | OpenAICopilot を構成するための基本オプションを表します。 |
| [OpenAIImageDescriptionCopilot](./openaiimagedescriptioncopilot/) | OpenAICopilot クラスの画像処理機能を提供します。OpenAI クライアントの作成、ImageDescriptionCopilot オプションの構成、およびコパイロットを使用して画像の説明を生成し、添付ドキュメントに説明を追加する例です。 |
| [OpenAIImageDescriptionCopilotExtensions](./openaiimagedescriptioncopilotextensions/) | OpenAIImageDescriptionCopilot クラス向けの拡張メソッドを提供します。 |
| [OpenAIImageDescriptionCopilotOptions](./openaiimagedescriptioncopilotoptions/) | OpenAICopilot の設定オプションを表します。 |
| [OpenAIModels](./openaimodels/) | 利用可能な OpenAI モデル識別子を含みます。 |
| [OpenAIOcrCopilot](./openaiocrcopilot/) | PDF ドキュメントや画像からテキストを抽出する OCR 機能を提供します。サポートされている画像タイプ: PNG (.png)、JPEG (.jpeg および .jpg)、WEBP (.webp)、非アニメーション GIF (.gif)。OpenAI クライアントの作成、オプションの構成、OCR コパイロットの使用例です。 |
| [OpenAIOcrCopilotOptions](./openaiocrcopilotoptions/) | OpenAIOcrCopilot を構成するオプションを表します。 |
| [OpenAISummaryCopilot](./openaisummarycopilot/) | AI モデルを使用してドキュメントの要約を取得する機能を提供します。OpenAI クライアントの作成、オプションの構成、サマリーコパイロットの使用例です。 |
| [OpenAISummaryCopilotOptions](./openaisummarycopilotoptions/) | OpenAICopilot の設定オプションを表します。 |
| [PdfDocument](./pdfdocument/) | 名前付き PDF ドキュメントを表します。 |
| [RequiredAction](./requiredaction/) | 実行を続行するために必要なアクションの詳細です。アクションが不要な場合は null になります。 |
| [ResponseFormat](./responseformat/) | レスポンスの形式を表します。文字列値またはオブジェクト値のいずれかです。 |
| [RunCreateRequest](./runcreaterequest/) | 実行を作成するリクエストを表します。 |
| [RunListQueryParameters](./runlistqueryparameters/) | 実行一覧取得のクエリパラメータオブジェクトです。 |
| [RunListResponse](./runlistresponse/) | 実行データを含むリストレスポンスを表します。 |
| [RunModifyRequest](./runmodifyrequest/) | 実行を変更するリクエストを表します。 |
| [RunResponse](./runresponse/) | スレッド上の実行ランを表します。 |
| [RunStepDetails](./runstepdetails/) | 実行ステップの詳細です。 |
| [RunStepListQueryParameters](./runsteplistqueryparameters/) | 実行ステップ一覧取得のクエリパラメータオブジェクトです。 |
| [RunStepListResponse](./runsteplistresponse/) | 実行ステップデータを含むリストレスポンスを表します。 |
| [RunStepResponse](./runstepresponse/) | 実行の実行中のステップを表します。 |
| [RunThreadCreateRequest](./runthreadcreaterequest/) | スレッドを作成し、1 回のリクエストで実行するリクエストを表します。 |
| [SubmitToolOutputs](./submittooloutputs/) | 実行を続行するために必要なツール出力の詳細を表します。 |
| [TextDocument](./textdocument/) | 名前と内容を持つテキストドキュメントを表します。 |
| [TextRecognitionResult](./textrecognitionresult/) | 単一のソースドキュメントに対する集約されたOCR結果を表します。 |
| [TextResponse](./textresponse/) | メッセージの一部であるテキストコンテンツを表します。 |
| [ThreadCreateRequest](./threadcreaterequest/) | スレッドを作成するリクエストを表します。 |
| [ThreadMessageCreateRequest](./threadmessagecreaterequest/) | スレッド内にメッセージを作成するリクエストを表します。 |
| [ThreadMessageListQueryParameters](./threadmessagelistqueryparameters/) | スレッドメッセージの一覧取得用クエリパラメータオブジェクトです。 |
| [ThreadMessageListResponse](./threadmessagelistresponse/) | スレッドメッセージデータを含む一覧レスポンスを表します。 |
| [ThreadMessageModifyRequest](./threadmessagemodifyrequest/) | スレッド内のメッセージを変更するリクエストを表します。 |
| [ThreadMessageResponse](./threadmessageresponse/) | スレッド内のメッセージを表します。 |
| [ThreadModifyRequest](./threadmodifyrequest/) | スレッドを変更するリクエストを表します。 |
| [ThreadResponse](./threadresponse/) | メッセージを含むスレッドを表します。 |
| [Tool](./tool/) | モデルから呼び出すことができるツールを表します。 |
| [ToolCall](./toolcall/) | メッセージ内のツール呼び出しを表します。 |
| [ToolChoice](./toolchoice/) | ToolChoice を表します。これは文字列値またはオブジェクト値のいずれかです。 |
| [ToolResources](./toolresources/) | アシスタントのツールで使用されるリソースの集合を表します。リソースはツールの種類に固有です。例えば、code_interpreter ツールはファイルIDのリストを必要とし、file_search ツールはベクトルストアIDのリストを必要とします。 |
| [TruncationStrategy](./truncationstrategy/) | 実行前にスレッドがどのように切り詰められるかを制御するトランケーション戦略を表します。 |
| [Usage](./usage/) | リクエストの使用統計情報を表します。 |
| [VectorStore](./vectorstore/) | file_ids を使用してベクトルストアを作成し、このスレッドに添付するためのヘルパーです。スレッドに添付できるベクトルストアは最大で1つです。 |
| [VectorStoreCreateRequest](./vectorstorecreaterequest/) | ベクトルストア作成リクエストです。 |
| [VectorStoreFileBatchCreateRequest](./vectorstorefilebatchcreaterequest/) | ベクトルストアファイルバッチ作成リクエストです。 |
| [VectorStoreFileBatchFileListQueryParameters](./vectorstorefilebatchfilelistqueryparameters/) | ベクトルストアファイルバッチのファイル一覧取得用クエリパラメータオブジェクトです。 |
| [VectorStoreFileBatchFileListResponse](./vectorstorefilebatchfilelistresponse/) | ベクトルストアファイルバッチデータを含む一覧レスポンスを表します。 |
| [VectorStoreFileBatchResponse](./vectorstorefilebatchresponse/) | ベクトルストアファイルバッチレスポンスオブジェクトです。 |
| [VectorStoreFileCreateRequest](./vectorstorefilecreaterequest/) | ベクトルストアファイル作成リクエストです。 |
| [VectorStoreFileListQueryParameters](./vectorstorefilelistqueryparameters/) | ベクトルストアファイル一覧取得用クエリパラメータオブジェクトです。 |
| [VectorStoreFileListResponse](./vectorstorefilelistresponse/) | ベクトルストアファイルデータを含む一覧レスポンスを表します。 |
| [VectorStoreFileResponse](./vectorstorefileresponse/) | ベクトルストア ファイルのレスポンスです。 |
| [VectorStoreListQueryParameters](./vectorstorelistqueryparameters/) | ベクトルストアの一覧取得用クエリパラメータオブジェクトです。 |
| [VectorStoreListResponse](./vectorstorelistresponse/) | ベクトルストアデータを含むリストレスポンスを表します。 |
| [VectorStoreModifyRequest](./vectorstoremodifyrequest/) | ベクトルストアのリクエストを変更します。 |
| [VectorStoreResponse](./vectorstoreresponse/) | ベクトルストアオブジェクトです。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IAIClient](./iaiclient/) | AI クライアントのインターフェイスを表します。 |
| [IAICopilot](./iaicopilot/) | AI インタラクション用のコパイロットを表します。 |
| [IChatClient&lt;TOptions&gt;](./ichatclient-1/) | 特定のオプションを持つチャットクライアントのインターフェイスを表します。 |
| [IChatCopilot](./ichatcopilot/) | AI モデルを介してドキュメントとやり取りするチャットコパイロットを表します。 |
| [IChatCopilotOptions&lt;TOptions&gt;](./ichatcopilotoptions-1/) | 特定のタイプを持つチャットコパイロットオプションのインターフェイスを表します。 |
| [IEntityId](./ientityid/) | ID を持つエンティティを表します。 |
| [IImageDescriptionClient&lt;TOptions&gt;](./iimagedescriptionclient-1/) | 特定のオプションを持つ画像説明クライアントのインターフェイスを表します。 |
| [IImageDescriptionCopilot](./iimagedescriptioncopilot/) | AI モデルを使用して画像説明を抽出する画像説明コパイロットを表します。 |
| [IImageDescriptionCopilotOptions&lt;TOptions&gt;](./iimagedescriptioncopilotoptions-1/) | 特定のタイプを持つ画像説明コパイロットオプションのインターフェイスを表します。 |
| [ILlamaClient](./illamaclient/) | Llama API とやり取りするクライアントインターフェイスを表します。 |
| [IOcrClient&lt;TOptions&gt;](./iocrclient-1/) | 特定のオプションを持つ OCR クライアントのインターフェイスを表します。 |
| [IOcrCopilot](./iocrcopilot/) | AI モデルを介してスキャンされた PDF と画像を処理する OCR コパイロットを表します。 |
| [IOcrCopilotOptions&lt;TOptions&gt;](./iocrcopilotoptions-1/) | 特定のタイプを持つチャットコパイロットオプションのインターフェイスを表します。 |
| [IOpenAIClient](./iopenaiclient/) | 基本的な AI クライアント機能を拡張し、OpenAI API とやり取りするクライアントインターフェイスを表します。 |
| [IQueryParameters](./iqueryparameters/) | API リクエスト用のクエリパラメータを表します。 |
| [IStatus](./istatus/) | 操作のステータスを表します。 |
| [IStringOrObject&lt;T&gt;](./istringorobject-1/) | 文字列値またはオブジェクト値のいずれかを取ることができるオブジェクトを表します。 |
| [ISummaryClient&lt;TOptions&gt;](./isummaryclient-1/) | 特定のオプションを持つサマリークライアントのインターフェイスを表します。 |
| [ISummaryCopilot](./isummarycopilot/) | AI モデルを使用してドキュメントの要約を生成するサマリーコパイロットを表します。 |
| [ISummaryCopilotOptions&lt;TOptions&gt;](./isummarycopilotoptions-1/) | 特定のタイプを持つサマリーコパイロットオプションのインターフェイスを表します。 |
## 列挙体

| 列挙体 | 説明 |
| --- | --- |
| [Detail](./detail/) | 画像解析の詳細レベルを指定します。 |


