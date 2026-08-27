---
title: "optimize_file_size"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ottimizza le dimensioni del PDF-document con la qualità di compressione dell'immagine."
type: docs
url: /it/rust-cpp/organize/optimize_file_size/
---

_Ottimizza le dimensioni del PDF-document con la qualità di compressione dell'immagine._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Ottimizza le dimensioni del PDF-document con la qualità di compressione dell'immagine
    pdf.optimize_file_size(50)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```