---
title: "is_signed"
second_title: "Aspose.PDF para Rust via C++"
description: "Obter status de assinatura do PDF-document."
type: docs
url: /pt/rust-cpp/security/is_signed/
---

_Obter status de assinatura do PDF-document._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF chamado "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Obter status de assinatura do PDF-document
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```