---
title: "page_delete"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Elimina la pagina specificata dal PDF-document."
type: docs
url: /it/rust-cpp/core/page_delete/
---

_Elimina la pagina specificata dal PDF-document._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
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
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Elimina la pagina specificata nel PDF-document
    pdf.page_delete(1)?;

    // Salva il PDF-document precedentemente aperto
    pdf.save()?;

    Ok(())
}

```