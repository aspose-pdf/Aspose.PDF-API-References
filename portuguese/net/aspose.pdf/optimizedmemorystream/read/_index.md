---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: Método OptimizedMemoryStream. Quando substituído em uma classe derivada, lê uma sequência de bytes do fluxo atual e avança a posição dentro do fluxo pelo número de bytes lidos
type: docs
weight: 100
url: /pt/net/aspose.pdf/optimizedmemorystream/read/
---
## Método OptimizedMemoryStream.Read

Quando substituído em uma classe derivada, lê uma sequência de bytes do fluxo atual e avança a posição dentro do fluxo pelo número de bytes lidos.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | Byte[] | Um array de bytes. Quando este método retorna, o buffer contém o array de bytes especificado com os valores |
| offset | Int32 | O deslocamento de byte baseado em zero em que começar a armazenar os dados lidos do fluxo atual. |
| count | Int32 | O número máximo de bytes a serem lidos do fluxo atual. |

### Valor de Retorno

O número total de bytes lidos no buffer. Isso pode ser menor do que o número de bytes solicitados se essa quantidade de bytes não estiver disponível no momento, ou zero (0) se o final do fluxo tiver sido alcançado.

### Veja Também

* classe [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)