---
title: "page_add_page_num"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge il numero di pagina sulla pagina."
type: docs
url: /it/rust-cpp/organize/page_add_page_num/
---

_Aggiunge il numero di pagina sulla pagina._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Aggiungi il numero di pagina sulla pagina
    pdf.page_add_page_num(1)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```