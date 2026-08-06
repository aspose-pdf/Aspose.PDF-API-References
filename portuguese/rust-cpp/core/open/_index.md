---
title: "abrir"
second_title: "Aspose.PDF para Rust via C++"
description: "Abre um documento PDF com o nome de arquivo."
type: docs
url: /pt/rust-cpp/core/open/
---

_Abre um documento PDF com o nome de arquivo._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document chamado "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```