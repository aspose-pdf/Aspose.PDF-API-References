---
title: "page_set_size"
second_title: "Aspose.PDF für Rust über C++"
description: "Legt die Größe einer Seite im PDF-Dokument fest."
type: docs
url: /de/rust-cpp/organize/page_set_size/
---

_Legt die Größe einer Seite im PDF-Dokument fest._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Setze die Größe einer Seite im PDF-Dokument
    pdf.page_set_size(1, PageSize::A1)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```