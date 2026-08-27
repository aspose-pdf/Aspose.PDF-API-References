---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Referência da API Aspose.PDF para Java"
description: "Uma classe abstrata que representa um objeto de aparência personalizada de assinatura."
type: docs
weight: 4500
url: /pt/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

Uma classe abstrata que representa um objeto de aparência personalizada de assinatura.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | Inicializa nova instância da classe {@link SignatureCustomAppearance}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | Obtém/define a cor de fundo. Valor padrão: Transparent. |
| [getContactInfoLabel](#getContactInfoLabel--) | Obtém/define o rótulo de informações de contato. Valor padrão: "Contact". |
| [getCulture](#getCulture--) | Obtém/define o valor de informação cultural. Valor padrão: InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | Obtém/define o rótulo de data de assinatura. Valor padrão: "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | Obtém/define o formato de data/hora. Valor padrão: "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | Obtém/define o formato local de data/hora. Valor padrão: "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | Obtém/define o rótulo de assinatura digital. Valor padrão: "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Obtém/define o formato para a ordem dos elementos na string Subject. Exemplos de resultado: C=UK, CN=Org, O=Organization ou CN=Org, C=UK, O=Organization ou O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | Obtém/define o nome da família de fontes. Deve existir no documento. Valor padrão: Arial. |
| [getFontSize](#getFontSize--) | Obtém/define o tamanho da fonte. Valor padrão: 10. |
| [getForegroundColor](#getForegroundColor--) | Obtém/define a cor de primeiro plano (cor do texto). Valor padrão: Blue. |
| [getLocationLabel](#getLocationLabel--) | Obtém/define o rótulo de localização. Valor padrão: "Location". |
| [getReasonLabel](#getReasonLabel--) | Obtém/define o rótulo de motivo. Valor padrão: "Reason". |
| [getRotation](#getRotation--) | Obtém ou define a rotação da assinatura. |
| [isForegroundImage](#isForegroundImage--) | Obtém ou define um valor que indica se a imagem na aparência da assinatura é desenhada como imagem de primeiro plano. Valor padrão: false. |
| [isShowContactInfo](#isShowContactInfo--) | Obtém/define a visibilidade das informações de contato. Valor padrão: true. |
| [isShowLocation](#isShowLocation--) | Obtém/define a visibilidade da localização. Valor padrão: true. |
| [isShowReason](#isShowReason--) | Obtém/define a visibilidade do motivo. Valor padrão: true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | Obtém/define o estado de uso do {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtém/define a cor de fundo. Valor padrão: Transparent. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | Obtém/define o rótulo de informações de contato. Valor padrão: "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | Obtém/define o valor da informação cultural. |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | Obtém/define o rótulo de data de assinatura. Valor padrão: "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | Obtém/define o formato de data/hora. Valor padrão: "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | Obtém/define o formato local de data/hora. Valor padrão: "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | Obtém/define o rótulo de assinatura digital. Valor padrão: "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Obtém/define o formato para a ordem dos elementos na string Subject. Exemplos de resultado: C=UK, CN=Org, O=Organization ou CN=Org, C=UK, O=Organization ou O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | Obtém/define o nome da família de fontes. Deve existir no documento. Valor padrão: Arial. |
| [setFontSize](#setFontSize-double-) | Obtém/define o tamanho da fonte. Valor padrão: 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Obtém/define a cor de primeiro plano (cor do texto). Valor padrão: Blue. |
| [setForegroundImage](#setForegroundImage-boolean-) | Obtém ou define um valor que indica se a imagem na aparência da assinatura é desenhada como imagem de primeiro plano. Valor padrão: false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | Obtém/define o rótulo de localização. Valor padrão: "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | Obtém/define o rótulo de motivo. Valor padrão: "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | Obtém ou define a rotação da assinatura. |
| [setShowContactInfo](#setShowContactInfo-boolean-) | Obtém/define a visibilidade das informações de contato. Valor padrão: true. |
| [setShowLocation](#setShowLocation-boolean-) | Obtém/define a visibilidade da localização. Valor padrão: true. |
| [setShowReason](#setShowReason-boolean-) | Obtém/define a visibilidade do motivo. Valor padrão: true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | Obtém/define o estado de uso do {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

Inicializa nova instância da classe {@link SignatureCustomAppearance}.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtém/define a cor de fundo. Valor padrão: Transparent.

**Returns:**
instância de com.aspose.pdf.Color

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

Obtém/define o rótulo de informações de contato. Valor padrão: "Contact".

**Returns:**
valor String

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

Obtém/define o valor de informação cultural. Valor padrão: InvariantCulture.

**Returns:**
Valor de localidade

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

Obtém/define o rótulo de data de assinatura. Valor padrão: "Date".

**Returns:**
valor String

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

Obtém/define o formato de data/hora. Valor padrão: "yyyy.MM.dd HH:mm:ss".

**Returns:**
valor String

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

Obtém/define o formato local de data/hora. Valor padrão: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
valor String

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

Obtém/define o rótulo de assinatura digital. Valor padrão: "Digitally signed by".

**Returns:**
valor String

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Obtém/define o formato para a ordem dos elementos na string Subject. Exemplos de resultado: C=UK, CN=Org, O=Organization ou CN=Org, C=UK, O=Organization ou O=Organization

**Returns:**
matriz de int @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

Obtém/define o nome da família de fontes. Deve existir no documento. Valor padrão: Arial.

**Returns:**
valor String

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

Obtém/define o tamanho da fonte. Valor padrão: 10.

**Returns:**
valor double

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Obtém/define a cor de primeiro plano (cor do texto). Valor padrão: Blue.

**Returns:**
instância de com.aspose.pdf.Color

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

Obtém/define o rótulo de localização. Valor padrão: "Location".

**Returns:**
valor String

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

Obtém/define o rótulo de motivo. Valor padrão: "Reason".

**Returns:**
valor String

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

Obtém ou define a rotação da assinatura.

**Returns:**
Elemento de rotação

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

Obtém ou define um valor que indica se a imagem na aparência da assinatura é desenhada como imagem de primeiro plano. Valor padrão: false.

**Returns:**
valor booleano

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

Obtém/define a visibilidade das informações de contato. Valor padrão: true.

**Returns:**
valor booleano

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

Obtém/define a visibilidade da localização. Valor padrão: true.

**Returns:**
valor booleano

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

Obtém/define a visibilidade do motivo. Valor padrão: true.

**Returns:**
valor booleano

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

Obtém/define o estado de uso do {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Returns:**
valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtém/define a cor de fundo. Valor padrão: Transparent.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
Obtém/define o rótulo de informações de contato. Valor padrão: "Contact".

### setCulture {#setCulture-java.util.Locale-}
Obtém/define o valor da informação cultural.

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
Obtém/define o rótulo de data de assinatura. Valor padrão: "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
Obtém/define o formato de data/hora. Valor padrão: "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
Obtém/define o formato local de data/hora. Valor padrão: "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
Obtém/define o rótulo de assinatura digital. Valor padrão: "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Obtém/define o formato para a ordem dos elementos na string Subject. Exemplos de resultado: C=UK, CN=Org, O=Organization ou CN=Org, C=UK, O=Organization ou O=Organization

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | matriz de int @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
Obtém/define o nome da família de fontes. Deve existir no documento. Valor padrão: Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

Obtém/define o tamanho da fonte. Valor padrão: 10.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Obtém/define a cor de primeiro plano (cor do texto). Valor padrão: Blue.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

Obtém ou define um valor que indica se a imagem na aparência da assinatura é desenhada como imagem de primeiro plano. Valor padrão: false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setLocationLabel {#setLocationLabel-java.lang.String-}
Obtém/define o rótulo de localização. Valor padrão: "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
Obtém/define o rótulo de motivo. Valor padrão: "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
Obtém ou define a rotação da assinatura.

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

Obtém/define a visibilidade das informações de contato. Valor padrão: true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

Obtém/define a visibilidade da localização. Valor padrão: true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

Obtém/define a visibilidade do motivo. Valor padrão: true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

Obtém/define o estado de uso do {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
