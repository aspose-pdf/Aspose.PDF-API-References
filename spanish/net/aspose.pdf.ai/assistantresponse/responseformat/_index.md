---
title: AssistantResponse.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de AssistantResponse. Obtiene o establece el formato que el modelo debe generar. Compatible con GPT-4o, GPT-4 Turbo y todos los modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Configurar a { "type": "json_object" } habilita el modo JSON, lo que garantiza que el mensaje que genera el modelo sea un JSON válido. Importante: al usar el modo JSON, también debes instruir al modelo para que produzca JSON tú mismo a través de un mensaje del sistema o del usuario. Sin esto, el modelo puede generar un flujo interminable de espacios en blanco hasta que la generación alcance el límite de tokens, lo que resulta en una solicitud de larga duración y aparentemente "atascada". También ten en cuenta que el contenido del mensaje puede cortarse parcialmente si finish_reason="length", lo que indica que la generación excedió max_tokens o la conversación excedió la longitud máxima del contexto.
type: docs
weight: 100
url: /es/net/aspose.pdf.ai/assistantresponse/responseformat/
---
## Propiedad AssistantResponse.ResponseFormat

Obtiene o establece el formato que el modelo debe generar. Compatible con GPT-4o, GPT-4 Turbo y todos los modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Configurar a { "type": "json_object" } habilita el modo JSON, lo que garantiza que el mensaje que genera el modelo sea un JSON válido. Importante: al usar el modo JSON, también debes instruir al modelo para que produzca JSON tú mismo a través de un mensaje del sistema o del usuario. Sin esto, el modelo puede generar un flujo interminable de espacios en blanco hasta que la generación alcance el límite de tokens, lo que resulta en una solicitud de larga duración y aparentemente "atascada". También ten en cuenta que el contenido del mensaje puede cortarse parcialmente si finish_reason="length", lo que indica que la generación excedió max_tokens o la conversación excedió la longitud máxima del contexto.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Ver También

* clase [ResponseFormat](../../responseformat/)
* clase [AssistantResponse](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../../)