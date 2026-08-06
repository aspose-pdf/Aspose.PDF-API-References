---
title: "remove_text_footers"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove rodapés de texto do documento PDF."
type: docs
url: /pt/rust-cpp/organize/remove_text_footers/
---

_Remove rodapés de texto do documento PDF._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Remove rodapés de texto do documento PDF
    pdf.remove_text_footers()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```