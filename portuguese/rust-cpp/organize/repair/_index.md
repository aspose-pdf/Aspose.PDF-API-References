---
title: "repair"
second_title: "Aspose.PDF para Rust via C++"
description: "Repara o documento PDF."
type: docs
url: /pt/rust-cpp/organize/repair/
---

_Repara o PDF-document._

```rust
pub fn repair(&self) -> Result<(), PdfError>
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

    // Reparar PDF-document
    pdf.repair()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```