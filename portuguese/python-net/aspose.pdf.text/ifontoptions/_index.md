---
title: "IFontOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Propriedades úteis para ajustar o comportamento da Fonte"
type: docs
weight: 180
url: /pt/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

Propriedades úteis para ajustar o comportamento da Fonte

O tipo IFontOptions expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| notify_about_font_embedding_error | Às vezes não é possível incorporar a fonte desejada ao documento. Existem muitas razões, por exemplo<br/>            restrições de licença ou quando a fonte desejada não foi encontrada no computador de destino.<br/>            Quando essa situação ocorre não é simples detectá‑la, porque a fonte desejada é incorporada via definição <br/>            da bandeira de propriedade Font.IsEmbedded = true; É claro que é possível ler essa propriedade imediatamente após ser definida, mas<br/>            não é uma abordagem conveniente. A bandeira NotifyAboutFontEmbeddingError impõe um mecanismo de exceção <br/>            para casos em que a tentativa de incorporar a fonte falhou. Se essa bandeira estiver definida, uma exceção do tipo<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) será lançada. Por padrão, false. |

### Veja Também

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

