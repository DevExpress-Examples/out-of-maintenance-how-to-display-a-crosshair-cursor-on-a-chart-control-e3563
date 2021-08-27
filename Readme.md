<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128569704/11.2.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3563)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/CrosshairCursor/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/CrosshairCursor/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/CrosshairCursor/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/CrosshairCursor/MainWindow.xaml.vb))
<!-- default file list end -->
# How to display a crosshair cursor on a chart control


<p><strong>Note: This example applies to a DXCharts version prior to v2012 vol 1. Starting from v2012 vol 1, a crosshair cursor is provided out-of-the-box and is enabled by default for all XY-series views.</strong></p><p>In some cases, you may need to analyze how data is changing on a chart. This can be easily done using a crosshair cursor.</p><p>The following example demonstrates how to display a crosshair cursor on the <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsLineSeries2Dtopic"><u>LineSeries2D</u></a> chart and show the current series coordinates on the crosshair labels.</p>


<h3>Description</h3>

<p>To accomplish this task, you need to convert mouse coordinates to diagram coordinates  and vice versa using the<strong> XYDiagram2D.PointToDiagram </strong>and <strong>XYDiagram2D.DiagramToPoint</strong>  methods accordingly.</p><p>After the coordinate transformation is done, it becomes possible to draw the crosshair cursor on the diagram and do other required customizations that are shown in code.</p>

<br/>


