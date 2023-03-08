### What's 5mja?
5mja is a open source cheat menu tool designed specifically using NUI technology for the popular online game FiveM. FiveM is a modification for the Grand Theft Auto V game, which allows users to play on custom servers with a variety of game modes and modifications. Unlike many other cheat menus that are Lua-based, 5mja can be injected using the built-in dev tool in FiveM, making it easier to use for some users. 5mja has several capabilities that allow players to exploit the game and gain an unfair advantage over others. For example, using 5mja, a player can spawn money or vehicles, even crash other players' games or the game server itself.<br/>

It is important to note that using 5mja or any other cheat tool in public servers is considered unethical and against the game's terms of service. Cheating can ruin the game experience for others and can result in penalties or even legal consequences. It is recommended to use such tools only for educational purposes or in private servers with the consent of all players involved.

#### Usage
- Enable devtool by switching update channel of fivem to Beta.
- Press F8 Tool->NUI->Open DevTools or visit http://localhost:13172/ in browser
- Navigate to Sources tab press `Ctrl+F8` (Disable breakpoints) & press `Ctrl+\` (Resume script execution)
- Navigate to Console tab select `top` in javaScript context.
- <img src="https://cdn.discordapp.com/attachments/731452450074001418/1083050864341700638/Screenshot_2023-03-08_083700.png">
- Copy & Paste menu injector javascript & press enter.
- Open any nui element like phone which allow you to use cursor.
- Press PageDown key for hide & show menu.

menu injector javascript
```
var iframe = document.createElement("iframe");
iframe.setAttribute("src", "http://5mja.ninjhacks.com/menu");
iframe.style.zIndex = "99999999999";
document.body.appendChild(iframe);
```

set zIndex to 0 for access other nui elements like phone.
set zIndex to 9999999 for access other 5mja menu like phone.
```
iframe.style.zIndex = "0";
```

For help & discussion join our discord server https://discord.gg/ninjhacks