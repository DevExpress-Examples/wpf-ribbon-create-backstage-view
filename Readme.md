<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128655517/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T325047)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
<!-- default file list end -->
# How to: Create Backstage View 


RibbonControl supports displaying the Office2007-like Application Menu as well as the <a href="https://learn.microsoft.com/en-us/previous-versions/office/developer/office-2010/ee691833(v=office.14)">Backstage View</a> that is available in Office2010 and higher. In this example, we demonstrated how to create a Backstage View. It's presented by <strong>BackstageViewControl</strong>. To learn more on how to use this control, please refer to the <a href="https://documentation.devexpress.com/#WPF/CustomDocument10507">Backstage View</a> documentation page.<br><br>Please note that BackstageViewControl can be displayed in two modes:<br><br>- The control occupies the entire client area.<br><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-create-backstage-view-t325047/15.2.4+/media/33d5c805-a3d4-11e5-80bf-00155d62480c.png"><br>- The client area is not fully occupied, and the ribbon page headers remain visible.<br><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-create-backstage-view-t325047/15.2.4+/media/3ad2750e-a3d4-11e5-80bf-00155d62480c.png"><br>By default, the display mode depends on the selected theme. To switch it manually, use the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfRibbonBackstageViewControl_IsFullScreentopic">BackstageViewControl.IsFullScreen</a> property.<br><br><strong>See also:</strong><br><a href="https://documentation.devexpress.com/#WPF/CustomDocument8182">How to create an Application Menu</a>

<br/>


