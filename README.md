# GunaPatcher

> **Warning** The only official codes/examples are here or in one of the linked repositories if any and nowhere else.

[![CodeFactor](https://www.codefactor.io/repository/github/thehelltower/gunapatcher/badge)](https://www.codefactor.io/repository/github/thehelltower/gunapatcher)

## 📜 What it does ?

This patcher make you able to fully use Guna Products for free.<br>
Tested on:<br>
[Guna.UI2.WinForms](https://www.nuget.org/packages/Guna.UI2.WinForms) - `2.0.4.0` - `Latest`(**`2.0.4.6`**)
<br>
[Guna.Charts.WinForms](https://www.nuget.org/packages/Guna.Charts.WinForms) - `1.0.5` - `Latest`(**`1.0.9`**)

<br>

## 🎥 Preview

[Click Here For Video](https://i.imgur.com/isAADUd.mp4)
## ❓ Information

**THIS IS A FORKED REPOSITORY! All credits to `TheHellTower`'s repository.**\
Since there was no provided documentation on the program, and no releases requiring you to
manually build the program yourself, this repository with the required instructions will do
it for you.

### Documentation
Running the program requires one parameter.
```
Format:
    - GunaPatcher.exe ( your patcher )
    - Guna.UI2.dll ( your Guna DLL. )
```

The name of your Guna DLL must follow this line of code.
```
static string[] ModuleNames = new string[] { "Guna.UI2", "Guna.Charts.WinForms.dll" }, AssemblyNames = new string[] { "Guna.UI2", "Guna.Charts.WinForms" };
```
> [!TIP]
> List of names that are readable by the program\
>     __Guna.UI2.dll__\
>     __Guna.Charts.WinForms.dll__

> [!IMPORTANT]
> It's easier to have the Guna dll in the same folder as the program.
> Example:
> ```GunaPatcher.exe Guna.UI2.dll```
## 📢 Credits

- [@SoheilMV](https://github.com/SoheilMV) for Enum Idea
- [@TheHellTower](https://github.com/TheHellTower) for the repository
