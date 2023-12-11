<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128655517/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T325047)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# WPF Ribbon - Create a Backstage View 

This example demonstrates how to create a [WPF Backstage View](https://docs.devexpress.com/WPF/DevExpress.Xpf.Ribbon.BackstageViewControl) (a full screen application menu) inspired by Microsoft Office 2010.

![WPF Ribbon - Backstage View, DevExpress](https://raw.githubusercontent.com/DevExpress-Examples/wpf-ribbon-create-backstage-view/22.2.2%2B/media/wpf-ribbon-backstageview-devexpress.png)

```xaml
<dxr:RibbonControl RibbonStyle="Office2010">
    ...
    <dxr:RibbonControl.ApplicationMenu>
        <dxr:BackstageViewControl>
            <dxr:BackstageButtonItem Content="New" Glyph="{dx:DXImage Image=New_16x16.png}"/>
            <dxr:BackstageButtonItem Content="Open" Glyph="{dx:DXImage Image=Open_16x16.png}" />
            <dxr:BackstageTabItem Content="Recent">
                <dxr:BackstageTabItem.ControlPane>
                    <ContentControl/>
                </dxr:BackstageTabItem.ControlPane>
            </dxr:BackstageTabItem>
            <dxr:BackstageButtonItem Content="Close" Glyph="{dx:DXImage Image=Close_16x16.png}" />
        </dxr:BackstageViewControl>
    </dxr:RibbonControl.ApplicationMenu>
</dxr:RibbonControl>
```

## Files to Review

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))


## Documentation

* [BackstageViewControl Class](https://docs.devexpress.com/WPF/DevExpress.Xpf.Ribbon.BackstageViewControl)
* [RibbonControl.ApplicationMenu](https://docs.devexpress.com/WPF/DevExpress.Xpf.Ribbon.RibbonControl.ApplicationMenu)
* [BackstageViewControl.IsFullScreen](https://docs.devexpress.com/WPF/DevExpress.Xpf.Ribbon.BackstageViewControl.IsFullScreen)
