# AutoClock.Luogu

A plugin of [AutoClock](https://github.com/ReturnNefe/AutoClock).

AutoClock.Luogu can send an email when when plugins failed to clock-in.

## Installing

1. Download plugin file from [Releases](https://github.com/ReturnNefe/AutoClock.Luogu/releases).
2. Unzip the file into ``AutoClock/plugins/Luogu``.
3. Configure ``config.txt`` by reading **Configuration**.

## Configuration

Edit ``config.txt`` in the base directory.

```
{
    // Don't change the value of these three options.
    "getTokenUrl": "https://www.luogu.com.cn/",
	"punchUrl": "https://www.luogu.com.cn/index/ajax_punch",
	"referer": "https://www.luogu.com.cn/",
	
    // You can customize the value of UserAgent.
    "user-agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/100.0.4896.127 Safari/537.36 Edg/100.0.1185.50",
	
    // The users who need to auto clock-in.
    "users": [
        {
            // The cookie of the user.
            // You can get the value in Network Tab of DevTools of the browser you use.
            "cookie": ""
        }
    ]
}
```