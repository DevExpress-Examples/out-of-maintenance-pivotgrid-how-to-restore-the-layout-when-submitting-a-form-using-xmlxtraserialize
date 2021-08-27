<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128579502/12.1.7%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4215)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [HomeController.cs](./CS/WebSite/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/WebSite/Controllers/HomeController.vb))
* [PivotGridHelper.cs](./CS/WebSite/Controllers/PivotGridHelper.cs) (VB: [PivotGridHelper.vb](./VB/WebSite/Controllers/PivotGridHelper.vb))
* [Index.cshtml](./CS/WebSite/Views/Home/Index.cshtml)
* [PivotGridPartial.cshtml](./CS/WebSite/Views/Home/PivotGridPartial.cshtml)
<!-- default file list end -->
# PivotGrid - How to restore the layout when submitting a form using XmlXtraSerializer
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e4215)**
<!-- run online end -->


<p>The PivotGrid extension does not have the built-in capability to restore a form state when submitting the form or refreshing a page. This example illustrates how to do this manually.</p><p>To accomplish this task, execute the following steps:</p><p>- Assign a delegate to the PreRender property;<br />
- Deserialize data from an XML file, which contains saved PivotGrid data. It is necessary to make sure that the structure of a file meets the PivotGrid data or add a check-up to the empty file;<br />
- Assign a delegate to the <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebMvcPivotGridSettings_AfterPerformCallbacktopic"><u>AfterPerformCallback</u></a> property;<br />
- Serialize the PivotGrid data to the XML file.</p><p><strong>See also:</strong><strong><br />
</strong><a href="https://www.devexpress.com/Support/Center/p/E4219">PivotGrid - How to save/load field values' collapsed states together with pivot grid's layout</a><br />
<a href="https://www.devexpress.com/Support/Center/p/E20015">Save/load field values' collapsed states together with pivot grid's layout</a></p>

<br/>


