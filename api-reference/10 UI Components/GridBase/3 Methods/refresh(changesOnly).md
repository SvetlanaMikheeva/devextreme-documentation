---
id: GridBase.refresh(changesOnly)
---
---
##### shortDescription
Reloads data and repaints all or only updated data rows.

##### return: Promise<void>
A Promise that is resolved after data is loaded. It is a <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise" target="_blank">native Promise</a> or a <a href="http://api.jquery.com/Types/#Promise" target="_blank">jQuery.Promise</a> when you use jQuery.

##### param(changesOnly): Boolean
Pass **true** to repaint updated data rows; **false** to repaint all data rows.

---
Main article: [refresh()](/api-reference/10%20UI%20Components/GridBase/3%20Methods/refresh().md '/Documentation/ApiReference/UI_Components/dxDataGrid/Methods/#refresh')

#include common-demobutton with {
    url: "https://js.devexpress.com/Demos/WidgetsGallery/Demo/DataGrid/BatchUpdateRequest/"
}