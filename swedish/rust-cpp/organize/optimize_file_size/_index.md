---
title: "optimize_file_size"
second_title: "Aspose.PDF för Rust via C++"
description: "Optimerar storleken på PDF-dokument med bildkomprimeringskvalitet."
type: docs
url: /sv/rust-cpp/organize/optimize_file_size/
---

_Optimerar storleken på PDF-dokument med bildkomprimeringskvalitet._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Optimera storleken på PDF-dokument med bildkomprimeringskvalitet
    pdf.optimize_file_size(50)?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```