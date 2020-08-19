---
id: BaseWidgetAnnotationConfig.textOverflow
acceptValues: 'ellipsis' | 'hide' | 'none'
type: String
default: 'ellipsis'
---
---
##### shortDescription
Specifies what to do with the annotation's [text]({basewidgetpath}/Configuration/annotations/#text) when it overflows the allocated space after applying [wordWrap]({basewidgetpath}/Configuration/annotations/#wordWrap): hide, truncate it and display an ellipsis, or do nothing.

---
#include common-ref-enum with {
    enum: "`VizTextOverflow`",
    values: "`Ellipsis`, `Hide`, and `None`"
}