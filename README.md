# McTextBlock
McTextBlock is a WPF element for displaying Minecraft formatted text. It even supports obfuscated text (e.g. `"§k secret"`).

## Installation
You can either clone this repository and build the binaries from source or simply install the [NuGet package][nuget] using `PM> Install-Package Craften.Utilities.McTextBlock`.

[nuget]: https://www.nuget.org/packages/Craften.Utilities.McTextBlock/

## Usage
For now, `McTextBlock` is the only element provided by the library. The usage is pretty straightforward.

```xaml
<Window
    <!-- *snip* -->
    xmlns:mcf="clr-namespace:Craften.Utilities.McTextBlock;assembly=Craften.Utilities.McTextBlock">

    <mcf:McTextBlock
        Text="§k123§r §o§4Th§ce C§6ra§eft§aen§2 Se§3rv§1er §r§k123"
        FontSize="24"
        FontFamily="Lucida Console"
        VerticalAlignment="Center"
        x:Name="test"
        TextAlignment="Center" />

</Window>
```

# License
All files in this repository are licensed under the MIT license, see [the license file][license] for more information.

[license]: https://github.com/TeamWertarbyte/McTextBlock/blob/master/LICENSE.txt
