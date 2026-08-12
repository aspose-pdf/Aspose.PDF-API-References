---
title: "remove_signs"
second_title: "Aspose.PDF para Rust via C++"
description: "Remover assinaturas do PDF-document."
type: docs
url: /pt/rust-cpp/security/remove_signs/
---

_Remover assinaturas do documento PDF._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF chamado "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Remover assinaturas do documento PDF
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```