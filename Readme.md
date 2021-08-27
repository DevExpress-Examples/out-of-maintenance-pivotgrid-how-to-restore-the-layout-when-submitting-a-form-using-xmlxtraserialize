<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128579502/14.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4215)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

*Files to look at*:

* [HomeController.cs](./CS/WebSite/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/WebSite/Controllers/HomeController.vb))
* [PivotGridHelper.cs](./CS/WebSite/Controllers/PivotGridHelper.cs) (VB: [PivotGridHelper.vb](./VB/WebSite/Controllers/PivotGridHelper.vb))
* [Index.cshtml](./CS/WebSite/Views/Home/Index.cshtml)
* [PivotGridPartial.cshtml](./CS/WebSite/Views/Home/PivotGridPartial.cshtml)

# PivotGrid - How to restore the layout when submitting a form using XmlXtraSerializer
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e4215/)**
<!-- run online end -->


The PivotGrid extension does not have the built-in capability to restore a form state when submitting the form or refreshing a page. This example illustrates how to do this manually. To accomplish this task, execute the following steps:

- Assign a delegate to the PreRender property;
- Deserialize data from an XML file, which contains saved PivotGrid data. It is necessary to make sure that the structure of a file meets the PivotGrid data or add a check-up to the empty file;
- Assign a delegate to the [PivotGridSettings.AfterPerformCallback](https://docs.devexpress.com/AspNetMvc/DevExpress.Web.Mvc.PivotGridSettings.AfterPerformCallback) property;
- Serialize the PivotGrid data to the XML file.


## More Examples 

- [PivotGrid - How to save/load field values' collapsed states together with pivot grid's layout](https://github.com/DevExpress-Examples/pivotgrid-how-to-save-load-field-values-collapsed-states-together-with-pivot-grids-layout-e4219)
- [Save/load field values' collapsed states together with pivot grid's layout](https://github.com/DevExpress-Examples/save-load-field-values-collapsed-states-together-with-pivot-grids-layout-e20015)


