---
title: "new"
second_title: "Aspose.PDF för Rust via C++"
description: "Skapar ett nytt PDF-dokument."
type: docs
url: /sv/rust-cpp/core/new/
---

_Skapar ett nytt PDF-dokument._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Skapa ett nytt PDF-dokument
    let pdf = Document::new()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```