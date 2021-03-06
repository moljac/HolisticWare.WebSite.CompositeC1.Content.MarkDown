# `dotnet tool` Samples

dotnet-tool-samples.md

## Binderator

*   https://www.nuget.org/packages/Xamarin.AndroidBinderator.Tool/

*   https://github.com/xamarin/XamarinComponents/tree/master/Util/Xamarin.AndroidBinderator

```
dotnet tool uninstall   --global Xamarin.AndroidBinderator.Tool
dotnet tool install     --global Xamarin.AndroidBinderator.Tool
```

```
 dotnet tool \                      
    uninstall --global \
    xamarin.androidbinderator.tool

dotnet tool \
    install --global \
    --add-source ./output/ \
    --version 0.4.4-alpha01 \
    xamarin.androidbinderator.tool
```



## Migration Tool

*   https://www.nuget.org/packages/Xamarin.AndroidX.Migration.Tool

*   https://github.com/xamarin/AndroidX

```
dotnet tool uninstall   --global Xamarin.AndroidX.Migration.Tool
dotnet tool install     --global Xamarin.AndroidX.Migration.Tool
```

## Cake Tool

*   https://www.nuget.org/packages/Cake.Tool/

*   https://github.com/cake-build/cake

*   https://github.com/cake-build/cake/blob/main/src/Cake/Cake.csproj#L10-L20

```
dotnet tool uninstall --global \
    Cake.Tool 
dotnet tool install --global \
    Cake.Tool 
```

```
dotnet tool uninstall --global \
    Cake.Tool 
dotnet tool install --global \
    Cake.Tool \
    --version 0.38.5
```

## `boots`

*   https://www.nuget.org/packages/boots/

*   https://github.com/jonathanpeppers/boots

```
dotnet tool uninstall   --global boots
dotnet tool install     --global boots
```

## MAUI check

```
dotnet tool uninstall -g Redth.Net.Maui.Check
dotnet tool   install -g Redth.Net.Maui.Check
```

```
maui-check
```

## `dotnet try-convert`

*   https://github.com/dotnet/try-convert


```
dotnet tool uninstall   -g try-convert
dotnet tool install     -g try-convert
```

Then restart the terminal and check if it was installed correctly with:

```
dotnet tool list -g 
```

Which lists all the tools and tells user what command to use. 

The help for try-convert is pretty useful, so user can get it with:

```
try-convert --help
```

*   https://docs.microsoft.com/en-us/dotnet/core/porting/tools

*   https://medium.com/c-sharp-progarmming/migrate-net-framework-to-net-core-66746acb4092

*   https://channel9.msdn.com/Events/dotnetConf/NET-Conf-2019/B104

*   https://github.com/BornToBeRoot/NETworkManager


## Android SDK

*   https://github.com/redth/androidsdk.tools
