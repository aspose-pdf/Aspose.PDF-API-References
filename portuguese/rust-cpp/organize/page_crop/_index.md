---
title: "page_crop"
second_title: "Aspose.PDF para Rust via C++"
description: "Recorta uma página."
type: docs
url: /pt/rust-cpp/organize/page_crop/
---

_Recorta uma página._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Recortar uma página
    pdf.page_crop(1, 1.0)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```