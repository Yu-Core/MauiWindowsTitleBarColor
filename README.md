# MauiWindowsTitleBarColor

You can freely change MAUI Windows title bar color

Support Win 10/11

install [PInvoke.User32](https://www.nuget.org/packages/PInvoke.User32/0.7.124)

Copy [https://github.com/Yu-Core/MauiWindowsTitleBarColor/blob/master/MauiWindowsTitleBarColor/Platforms/Windows/WindowsTitleBar.cs](https://github.com/Yu-Core/MauiWindowsTitleBarColor/blob/master/MauiWindowsTitleBarColor/Platforms/Windows/WindowsTitleBar.cs)

Use
```
#if WINDOWS
        //The first parameter is the background color of the title bar, and the second parameter is the text color of the title bar
        WindowsTitleBar.SetColorForWindows(backgroundColor,foregroundColor);
#endif
```

https://user-images.githubusercontent.com/96511239/235290220-2de573ad-1f37-46f7-ac84-56c804f333d7.mp4
