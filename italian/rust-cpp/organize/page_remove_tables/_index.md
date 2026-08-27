---
title: "page_remove_tables"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove le tabelle nella pagina."
type: docs
url: /it/rust-cpp/organize/page_remove_tables/
---

_Rimuove le tabelle nella pagina._

```rust
pub fn page_remove_tables(&self, num: i32) -> Result<(), PdfError>
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

    // Rimuovi le tabelle nella pagina
    pdf.page_remove_tables(1)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_remove_tables.pdf")?;

    Ok(())
}

```