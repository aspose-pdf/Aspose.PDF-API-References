---
title: "add_page_num"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt einer PDF-document Seitenzahl hinzu."
type: docs
url: /de/rust-cpp/organize/add_page_num/
---

_Fügt einer PDF-document Seitenzahl hinzu._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Fügen Sie einem PDF-Dokument eine Seitenzahl hinzu
    pdf.add_page_num()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```