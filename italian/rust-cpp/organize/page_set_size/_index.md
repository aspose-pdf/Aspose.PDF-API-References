---
title: "page_set_size"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Imposta le dimensioni di una pagina nel PDF-document."
type: docs
url: /it/rust-cpp/organize/page_set_size/
---

_Imposta le dimensioni di una pagina nel PDF-document._

```rust
pub fn page_set_size(&self, num: i32, page_size: PageSize) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **page_size** - page size as enum `PageSize`: `A0`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `B5`, `PageLetter`, `PageLegal`, `PageLedger`, or `P11x17`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PageSize};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Imposta le dimensioni di una pagina nel PDF-document
    pdf.page_set_size(1, PageSize::A1)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```