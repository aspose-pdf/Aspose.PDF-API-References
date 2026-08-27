---
title: "Класс OpenAIChatCopilot"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.OpenAIChatCopilot. Представляет чат‑помощника для взаимодействия с документами через AI‑модели. Пример использования: создание клиента OpenAI, настройка параметров и использование ChatCopilot для взаимодействия с запросами пользователей и управления контекстом беседы."
type: docs
weight: 880
url: /ru/net/aspose.pdf.ai/openaichatcopilot/
---
## OpenAIChatCopilot class

Представляет чат‑копилот для взаимодействия с документами через модели ИИ. Пример использования создания клиента OpenAI, настройки параметров и использования ChatCopilot для взаимодействия с запросами пользователей и управления контекстом разговора.

```csharp
// Создать AI‑клиент.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Создать параметры помощника.
var options = OpenAIChatCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...создать с помощью делегата.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
    .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
    .WithRestoreContextFromBackup(true); // If set to true, the context 

// Создать помощника резюме.
var chatCopilot = AICopilotFactory.CreateChatCopilot(openAiClient, options);

// Получить ответ на запрос пользователя.
string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");

// Получить ответ на список запросов.
string copilotResponse2 = await chatCopilot.GetResponseAsync(new List<string>
{
    "message1",
    "message2"
});

// Сохранить резюме как PDF‑документ.
await chatCopilot.SaveResponseAsync("message1", "outputPath");

// Сохранить резюме в указанном формате.
await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);

// Сохранить резюме как PDF‑документ.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath");

// Сохранить резюме в указанном формате.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath", SaveFormat.DocX);

// Сохранить контекст.
await chatCopilot.SaveContextAsync("outputPath");

// Удалить контекст.
await chatCopilot.DeleteContextAsync();
```

```csharp
public class OpenAIChatCopilot : IChatCopilot
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OpenAIChatCopilot](openaichatcopilot/)(IOpenAIClient, IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Инициализирует новый экземпляр класса `OpenAIChatCopilot` с указанным клиентом и параметрами. |

## Свойства

| Имя | Описание |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaichatcopilot/hascontext/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/openaichatcopilot/deletecontextasync/)(CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) |  |
| [SaveContextAsync](../../aspose.pdf.ai/openaichatcopilot/savecontextasync/)(string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) |  |

### См. также

* interface [IChatCopilot](../ichatcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


