# What does this plugin do?
#### TLDR : Fixes the Maximum number shown in some Engine events (32,767 -> 2,147,483,647).
This Plugin fixes many Events that can flow over the `short` limit (32,767) by setting them to use a `long` instead
<br><br>

> [!IMPORTANT]
> **Reload Map or Restart Server after adding plugin and data For Plugin to take Effect**
<br>

> [!WARNING]
> **There is currently No Windows 64 Signature for `CGameEventManager::CreateEvent`**
> > If you want to help out, make a Pull Request

## Thanks to CookieCat From RF2 for making this possible.
### Link to RF2 -> [Risk Fortress 2](https://github.com/CookieCat45/Risk-Fortress-2/tree/main)
