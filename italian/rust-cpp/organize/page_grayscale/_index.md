---
title: "page_grayscale"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte una pagina in bianco e nero."
type: docs
url: /it/rust-cpp/organize/page_grayscale/
---

_Converte una pagina in bianco e nero._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
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

    // Converti la pagina in bianco e nero
    pdf.page_grayscale(1)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```