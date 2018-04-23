# How to update a Boolean field using the ASPxGridView selection


<p>The example demonstrates how to bind a Boolean field with the ASPxGridView selection.</p><p>The complex OnSelectionChanged event is used to prevent the grid from sending two simultaneous callbacks when the <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxGridViewASPxGridViewBehaviorSettings_AllowMultiSelectiontopic">ASPxGridViewBehaviorSettings.AllowMultiSelection</a> property is used. There are two callbacks in this case:<br />
1. Deselect all rows;<br />
2. Select the single row.</p><p><strong>See Also:</strong><br />
<a href="https://www.devexpress.com/Support/Center/p/E1405">Instant editing of boolean field value using two columns</a><br />
<a href="https://www.devexpress.com/Support/Center/p/E2313">How to update a Boolean field using the ASPxCheckBox in a DataItem template</a></p>

<br/>

