---
title: "page_replace_font"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Sostituisce il carattere nella pagina."
type: docs
url: /it/rust-cpp/organize/page_replace_font/
---

_Sostituisce il carattere nella pagina._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Sostituisci il carattere nella pagina
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```