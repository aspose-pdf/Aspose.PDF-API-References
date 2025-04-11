---
title: Aspose.Pdf.Forms
second_title: Aspose.PDF for .NET API Reference
description: O namespace Aspose.Pdf.Forms possui classes que descrevem formulários (padrão, estático, dinâmico) e vários tipos de campos, como caixa de texto, caixa de lista, botão de opção, etc.
type: docs
weight: 110
url: /pt/net/aspose.pdf.forms/
---
O **namespace Aspose.Pdf.Forms** possui classes que descrevem formulários (padrão, estático, dinâmico) e vários tipos de campos, como caixa de texto, caixa de lista, botão de opção, etc.

## Classes

| Classe | Descrição |
| --- | --- |
| [BarcodeField](./barcodefield/) | Classe que representa o campo de código de barras. |
| [ButtonField](./buttonfield/) | Classe que representa o campo de botão pressionável. |
| [CheckboxField](./checkboxfield/) | Classe que representa o campo de caixa de seleção. |
| [ChoiceField](./choicefield/) | Representa a classe base para campos de escolha. |
| [ComboBoxField](./comboboxfield/) | Classe que representa o campo ComboBox do formulário. |
| [DateField](./datefield/) | Campo de data com visualização de calendário. |
| [DocMDPSignature](./docmdpsignature/) | Representa a classe do tipo de assinatura MDP (detecção e prevenção de modificação) do documento. |
| [ExternalSignature](./externalsignature/) | Cria uma assinatura PKCS#7 destacada usando um X509Certificate2. Suporta cartões inteligentes USB, tokens sem chaves privadas exportáveis. |
| [Field](./field/) | Classe base para campos de formulário acro. |
| [FileSelectBoxField](./fileselectboxfield/) | Campo para o elemento de caixa de seleção de arquivo. |
| [Form](./form/) | Classe que representa o objeto formulário. |
| [IconFit](./iconfit/) | Descreve como o ícone da anotação do widget deve ser exibido dentro de seu retângulo de anotação. |
| [ListBoxField](./listboxfield/) | Classe que representa o campo ListBox. |
| [NumberField](./numberfield/) | Campo de texto com caracteres válidos especificados. |
| [Option](./option/) | Classe que representa a opção do campo de escolha. |
| [OptionCollection](./optioncollection/) | Classe que representa a coleção de opções do campo de escolha. |
| [PasswordBoxField](./passwordboxfield/) | Classe que descreve o campo de texto para entrada de senha. |
| [PKCS1](./pkcs1/) | Representa o objeto de assinatura em relação ao padrão PKCS#1. O algoritmo de criptografia RSA e o método de resumo SHA-1 são usados para assinar. |
| [PKCS7](./pkcs7/) | Representa o objeto PKCS#7 que está em conformidade com a especificação PKCS#7 no RFC da Internet 2315, PKCS #7: Sintaxe de Mensagem Criptográfica, Versão 1.5. O `resumo SHA1` da faixa de bytes do documento está encapsulado no campo SignedData do PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Representa o objeto PKCS#7 que está em conformidade com a especificação PKCS#7 no RFC da Internet 2315, PKCS #7: Sintaxe de Mensagem Criptográfica, Versão 1.5. O resumo da mensagem assinada original sobre a faixa de bytes do documento é incorporado como o campo SignedData normal do PKCS#7. Nenhum dado deve ser encapsulado no campo SignedData do PKCS#7. |
| [RadioButtonField](./radiobuttonfield/) | Classe que representa o campo de botão de opção. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Classe que representa um item do campo de botão de opção. |
| [RichTextBoxField](./richtextboxfield/) | Classe que descreve o componente do editor de texto rico. |
| [Signature](./signature/) | Uma classe abstrata que representa o objeto de assinatura no documento PDF. Assinaturas são campos com valores de objetos de assinatura, os últimos contêm dados que são usados para verificar a validade do documento. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Uma classe abstrata que representa o objeto de aparência personalizada da assinatura. |
| [SignatureField](./signaturefield/) | Representa o campo de formulário de assinatura. |
| [SignHash](./signhash/) | Delegado para assinar o hash do documento de forma personalizada. |
| [TextBoxField](./textboxfield/) | Classe que representa o campo de caixa de texto. |
| [XFA](./xfa/) | Representa o formulário XML em relação à Arquitetura de Formulários XML (XFA). |
## Enumeração

| Enumeração | Descrição |
| --- | --- |
| [BoxStyle](./boxstyle/) | Representa estilos para desenhar o check na caixa de seleção. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | As permissões de acesso concedidas para este documento. Os valores válidos são: 1 - Nenhuma alteração no documento é permitida; qualquer alteração no documento invalida a assinatura. 2 - As alterações permitidas são preencher formulários, instanciar modelos de página e assinar; outras alterações invalidam a assinatura. 3 - As alterações permitidas são as mesmas que para 2, bem como criação, exclusão e modificação de anotações; outras alterações invalidam a assinatura. |
| [FormType](./formtype/) | Enumeração dos possíveis tipos de Acro Form. |
| [IconCaptionPosition](./iconcaptionposition/) | Descreve a posição do ícone. |
| [ScalingMode](./scalingmode/) | O tipo de escala que deve ser usado. |
| [ScalingReason](./scalingreason/) | As circunstâncias sob as quais o ícone deve ser escalado dentro do retângulo de anotação. |
| [SubjectNameElements](./subjectnameelements/) | Enumeração que descreve os elementos na string do assunto da assinatura. |
| [Symbology](./symbology/) | Uma (Código de Barras) Simbologia define os detalhes técnicos de um tipo particular de código de barras: a largura das barras, conjunto de caracteres, método de codificação, especificações de soma de verificação, etc. |