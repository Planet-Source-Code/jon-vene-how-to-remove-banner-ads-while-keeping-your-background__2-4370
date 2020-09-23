<div align="center">

## How to remove Banner Ads, while keeping your background


</div>

### Description

Removes Banner Ads that appear on top of free webhosted websites.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jon Vene](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jon-vene.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |Java \(JDK 1\.1\), Java \(JDK 1\.2\), Java \(JDK 1\.3\), Java \(JDK 1\.4\), Java \(JDK 1\.5\)
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jon-vene-how-to-remove-banner-ads-while-keeping-your-background__2-4370/archive/master.zip)





### Source Code

```
I have come up with a way to fool the Script. By creating a diversion, the banner is placed before your REAL body tag.
[head]
[noembed][xmp]
[/head][body bgcolor=black][SCRIPT language=Javascript src="http://mvhosted.com/banners/mvh_header.js"][/SCRIPT]
[/noembed][/xmp][/head]
[body bgcolor=black]
By doing this, the banner is fooled in thinking that there is no [noembed][xmp] since it starts within the heading. Effectively, elimanating the banner. :)
Enjoy
P.S: Due to not being allowed to use the html, i used ['s instead of <'s. Just them to the appropriate form.
```

