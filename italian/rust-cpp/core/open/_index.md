---
title: "open"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Apre un PDF-document con nome file."
type: docs
url: /it/rust-cpp/core/open/
---

_Apre un PDF-document con nome file._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un PDF-document chiamato "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```