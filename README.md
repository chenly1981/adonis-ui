# AdonisUI 💪
Lightweight UI toolkit for WPF applications offering classic but enhanced windows visuals

## Usage

1. Reference `AdonisUI` and `AdonisUI.ClassicTheme`
2. Add resources to your application in your `App.xaml` like so:

```xml
<Application xmlns:adonisUi="clr-namespace:AdonisUI;assembly=AdonisUI">
    <Application.Resources>
        <ResourceDictionary>
            <ResourceDictionary.MergedDictionaries>
                <ResourceDictionary Source="{x:Static adonisUi:ResourceLocator.LightColorScheme}"/>
                <ResourceDictionary Source="{x:Static adonisUi:ResourceLocator.ClassicTheme}"/>
            </ResourceDictionary.MergedDictionaries>
        </ResourceDictionary>
    </Application.Resources>
</Application>
```