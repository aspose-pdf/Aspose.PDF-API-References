---
title: "page_merge_layers"
second_title: Aspose.PDF for Rust via C++
description: "Merges all layers on the page into a single layer with the specified new layer name."
type: docs
url: /rust-cpp/organize/page_merge_layers/
---

_Merges all layers on the page into a single layer with the specified new layer name._

```rust
pub fn page_merge_layers(&self, num: i32, new_layer_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **new_layer_name** - the name of the new layer after merging

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document from file
    let pdf = Document::open("sample.pdf")?;

    // Merge all layers on the page into a single layer with the specified new layer name
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```