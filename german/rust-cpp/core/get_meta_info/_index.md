---
title: "get_meta_info"
second_title: "Aspose.PDF für Rust über C++"
description: "Ermittelt den Metainformationswert des PDF-Dokuments."
type: docs
url: /de/rust-cpp/core/get_meta_info/
---

_Ermittelt den Metainformationswert des PDF-Dokuments._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Erhalte den Metainformationswert des PDF-Dokuments
    let author = pdf.get_meta_info("Author")?;

    // Gib das Ergebnis aus
    println!("Author: {}", author);

    Ok(())
}

```