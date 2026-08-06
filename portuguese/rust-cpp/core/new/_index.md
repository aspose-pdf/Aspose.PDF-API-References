---
title: "novo"
second_title: "Aspose.PDF para Rust via C++"
description: "Cria um novo documento PDF."
type: docs
url: /pt/rust-cpp/core/new/
---

_Cria um novo documento PDF._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crie um novo PDF-document
    let pdf = Document::new()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```