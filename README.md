# asset_toast

A new flutter plugin project.

## Getting Started
![](https://github.com/ggichure/asset_toast/blob/master/sc/artgif.gif)  |
# usage

```dart
 AssetToast.show("hello there", context,
                          asset: "assets/img.jpeg",
                          duration: AssetToast.lengthLong,
                          prefixBadge: Colors.green,
                          gravity: AssetToast.bottom,
                          backgroundColor: Colors.indigo,
                          msgColor: Colors.white);
```
# constructors 
```dart
    String msg,
    String asset,
    BuildContext context,
    int duration,
    int gravity,
    Color prefixBadge,
    Color msgColor,
    Color backgroundColor,
```

# contribute

# support 
# credits
[github.com/illukinati](https://github.com/illukinati/card_ui_kit)

[github.com/appdev](https://github.com/appdev/FlutterToast)




This project is a starting point for a Flutter
[plug-in package](https://flutter.dev/developing-packages/),
a specialized package that includes platform-specific implementation code for
Android and/or iOS.

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
