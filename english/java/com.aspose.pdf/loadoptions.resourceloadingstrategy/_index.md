---
title: LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for Java API Reference
description: Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere.
type: docs
weight: 2830
url: /java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere. For example during usage of Aspose.PDf in cloud direct access to referenced files impossible, and some custom code put into special method should be used. This delegate defines signature of such custom method.

## Methods

| Method | Description |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
