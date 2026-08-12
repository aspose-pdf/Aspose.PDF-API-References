---
title: "save"
second_title: "Aspose.PDF para Rust via C++"
description: "Salva o PDF-document aberto anteriormente."
type: docs
url: /pt/rust-cpp/core/save/
---

_Salva o PDF-document aberto anteriormente._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document chamado "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Salvar o PDF-document aberto anteriormente
    pdf.save()?;

    Ok(())
}

```