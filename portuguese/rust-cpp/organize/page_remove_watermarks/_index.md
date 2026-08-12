---
title: "page_remove_watermarks"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove marcas d'água na página."
type: docs
url: /pt/rust-cpp/organize/page_remove_watermarks/
---

_Remove marcas d'água na página._

```rust
pub fn page_remove_watermarks(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Remove marcas d'água na página
    pdf.page_remove_watermarks(1)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_remove_watermarks.pdf")?;

    Ok(())
}

```