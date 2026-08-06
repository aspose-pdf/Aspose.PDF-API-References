---
title: "is_encrypted"
second_title: "Aspose.PDF para Rust via C++"
description: "Obter status de criptografia do PDF-document."
type: docs
url: /pt/rust-cpp/security/is_encrypted/
---

_Obter status de criptografia do documento PDF._

```rust
pub fn is_encrypted(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF protegido por senha
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Obter status de criptografia do documento PDF
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```