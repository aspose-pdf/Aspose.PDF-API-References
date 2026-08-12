---
title: "save_as"
second_title: "Aspose.PDF para Rust via C++"
description: "Salva o PDF-document aberto anteriormente com um novo nome de arquivo."
type: docs
url: /pt/rust-cpp/core/save_as/
---

_Salva o PDF-document aberto anteriormente com um novo nome de arquivo._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crie um novo PDF-document
    let pdf = Document::new()?;

    // Salve o PDF-document com um novo nome de arquivo
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```