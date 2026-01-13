# How to apply line break mode support to the header cells in .NET MAUI DataGrid?

This sample demonstrates how to apply line break mode support to the header cells in the Syncfusion [.NET MAUI DataGrid](https://help.syncfusion.com/maui/datagrid/overview) (`SfDataGrid`). It allows users to apply line break mode support to the header cells.

## Xaml
```
    <ContentPage.Content>
        <syncfusion:SfDataGrid x:Name="sfdatagrid" 
                            ItemsSource="{Binding Employees}">

            <syncfusion:SfDataGrid.Columns>
                <syncfusion:DataGridTextColumn MappingName="EmployeeID" HeaderText="Employee ID" HeaderLineBreakMode="TailTruncation" />
            </syncfusion:SfDataGrid.Columns>

        </syncfusion:SfDataGrid>
    </ContentPage.Content>
```

### ScreenShot
<img src="https://support.syncfusion.com/kb/agent/attachment/inline?token=eyJhbGciOiJodHRwOi8vd3d3LnczLm9yZy8yMDAxLzA0L3htbGRzaWctbW9yZSNobWFjLXNoYTI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjU3NTg0Iiwib3JnaWQiOiIzIiwiaXNzIjoic3VwcG9ydC5zeW5jZnVzaW9uLmNvbSJ9.RnCwEEEew9TOZ7-zKc2dciEZk7mO3Vr8_6HkndLNZ_4" width=800/>

[View sample in GitHub](https://github.com/SyncfusionExamples/How-to-apply-line-break-mode-support-to-the-header-cells-in-.NET-MAUI-DataGrid-SfDataGrid.git)

 Take a moment to explore this [documentation](https://help.syncfusion.com/maui/datagrid/overview), where you can find more information about Syncfusion .NET MAUI DataGrid (SfDataGrid) with code examples. Please refer to this [link](https://www.syncfusion.com/maui-controls/maui-datagrid) to learn about the essential features of Syncfusion .NET MAUI DataGrid (SfDataGrid).

### Conclusion
I hope you enjoyed learning about how to apply line break mode support to the header cells in SfDataGrid.

You can refer to our [.NET MAUI DataGrid’s feature tour](https://www.syncfusion.com/maui-controls/maui-datagrid) page to learn about its other groundbreaking feature representations. You can also explore our [.NET MAUI DataGrid Documentation](https://help.syncfusion.com/maui/datagrid/getting-started) to understand how to present and manipulate data. For current customers, you can check out our .NET MAUI components on the [License and Downloads](https://www.syncfusion.com/sales/teamlicense) page. If you are new to Syncfusion, you can try our 30-day [free trial](https://www.syncfusion.com/downloads/maui) to explore our .NET MAUI DataGrid and other .NET MAUI components.

If you have any queries or require clarifications, please let us know in the comments below. You can also contact us through our [support forums](https://www.syncfusion.com/forums),[Direct-Trac](https://support.syncfusion.com/create) or [feedback portal](https://www.syncfusion.com/feedback/maui?control=sfdatagrid), or the feedback portal. We are always happy to assist you!