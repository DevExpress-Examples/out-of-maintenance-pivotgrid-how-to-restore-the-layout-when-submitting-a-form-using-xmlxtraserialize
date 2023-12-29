
*Files to look at*:

* [HomeController.cs](./CS/WebSite/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/WebSite/Controllers/HomeController.vb))
* [PivotGridHelper.cs](./CS/WebSite/Controllers/PivotGridHelper.cs) (VB: [PivotGridHelper.vb](./VB/WebSite/Controllers/PivotGridHelper.vb))
* [Index.cshtml](./CS/WebSite/Views/Home/Index.cshtml)
* [PivotGridPartial.cshtml](./CS/WebSite/Views/Home/PivotGridPartial.cshtml)

# PivotGrid - How to restore the layout when submitting a form using XmlXtraSerializer


The PivotGrid extension does not have the built-in capability to restore a form state when submitting the form or refreshing a page. This example illustrates how to do this manually. To accomplish this task, execute the following steps:

- Assign a delegate to the PreRender property;
- Deserialize data from an XML file, which contains saved PivotGrid data. It is necessary to make sure that the structure of a file meets the PivotGrid data or add a check-up to the empty file;
- Assign a delegate to the [PivotGridSettings.AfterPerformCallback](https://docs.devexpress.com/AspNetMvc/DevExpress.Web.Mvc.PivotGridSettings.AfterPerformCallback) property;
- Serialize the PivotGrid data to the XML file.


## More Examples 

- [PivotGrid - How to save/load field values' collapsed states together with pivot grid's layout](https://github.com/DevExpress-Examples/pivotgrid-how-to-save-load-field-values-collapsed-states-together-with-pivot-grids-layout-e4219)
- [Save/load field values' collapsed states together with pivot grid's layout](https://github.com/DevExpress-Examples/save-load-field-values-collapsed-states-together-with-pivot-grids-layout-e20015)


