# Blazor Demo Keep Page State

When switch pages , keep state of some pages by code.

In this sampe, 

The state of Index.razor will be persisted until browser reload.

The Counter.razor will be expired in 10 seconds if continue switch to more pages.

## Advanced Demo : Multiple Tabs of pages 

https://github.com/BlazorPlus/BlazorDemoMultiPagesTab


## Install this idea to your app

1 - copy the KeepPageStateRouteView.cs

2 - In App.razor , replace to KeepPageStateRouteView

3 - copy the MainLayout.razor , modify the GetUrlMaxLifeSpan and UI as you like .



