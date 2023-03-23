# wpf.instyle

A test repository for an application revolving around WPF styling and theming that can help facilitate the community's use of the resulting styles, themes, layouts, and behaviors, along with other modernization investments, and ensure that applications can benefit from cutting edge design layouts, elements, and behaviors.The plan is to be able to import a style, such as a generic.xaml file. The generic.xaml file is resource dictionary which defines a control's default style, as well as its structure, in the form of a ControlTemplate.

The WPF Team, in an effort to prioritize their upcoming focus on modernization investments, with the community's input, has announced [a roadmap for the goals they plan to accomplish in 2023](https://github.com/dotnet/wpf/blob/main/roadmap.md#modernizing-wpf). The community, at-large, voted on what we felt was the best course of action in the prioritization of these goals, and Windows 11 Theming was the top priority.  More specifically, "Bringing the look and feel of the current operating system, Windows 11, to the majority of currently existing WPF controls, and supporting new OS features such as snap layout, rounded corners for controls, and newer color schemes". With the modernization investment fully realized, updating the styles will ultimately enable developers to create a more consistent Windows experience, and ensuring that the WPF UI Framework, when running on Windows 11, "can take advantage of moder design elements and behaviors."

## Notes

For generic.xaml files (case insensitive) to be something special, two conditions must be met:

-  It must be in the Themes sub-root folder in the project
-  The assembly must be marked with the ThemeInfoAttribute (usually in AssemblyInfo.cs)

## Useful Links

-  [Windows 11 design principles](https://learn.microsoft.com/en-us/windows/apps/design/signature-experiences/design-principles)
-  [Xaml Resource Dictionary](https://learn.microsoft.com/en-us/windows/apps/design/style/xaml-resource-dictionary)
