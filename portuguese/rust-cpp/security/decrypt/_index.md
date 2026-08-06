---
title: "descriptografar"
second_title: "Aspose.PDF para Rust via C++"
description: "Descriptografar PDF-document."
type: docs
url: /pt/rust-cpp/security/decrypt/
---

_Descriptografar documento PDF._

```rust
pub fn decrypt(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF protegido por senha
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Descriptografar documento PDF
    pdf.decrypt()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```