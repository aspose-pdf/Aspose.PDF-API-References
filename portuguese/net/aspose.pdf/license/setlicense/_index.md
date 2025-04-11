---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: Método de licença. Licencia o componente
type: docs
weight: 20
url: /pt/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licencia o componente.

```csharp
public void SetLicense(string licenseName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| licenseName | String | Pode ser um nome de arquivo completo ou curto ou o nome de um recurso incorporado. Use uma string vazia para mudar para o modo de avaliação. |

## Observações

Tenta encontrar a licença nos seguintes locais:

1. Caminho explícito.

2. A pasta que contém a montagem do componente Aspose.

3. A pasta que contém a montagem de chamada do cliente.

4. A pasta que contém a montagem de entrada (inicialização).

5. Um recurso incorporado na montagem de chamada do cliente.

**Nota:** No .NET Compact Framework, tenta encontrar a licença apenas nesses locais:

1. Caminho explícito.

2. Um recurso incorporado na montagem de chamada do cliente.

[Java]

2. A pasta que contém o arquivo JAR do componente Aspose.

3. A pasta que contém o arquivo JAR de chamada do cliente.

### Veja Também

* classe [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Licencia o componente.

```csharp
public void SetLicense(Stream stream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | Um stream que contém a licença. |

## Observações

Use este método para carregar uma licença de um stream.

### Veja Também

* classe [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)