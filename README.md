**HeroExtractor**<br/>
Save Configuration and STL of https://www.heroforge.com/

**Usage**
<br/>Go to https://www.heroforge.com/
<br/>Open the Javascript Console [F12], then click on Console
<br/>Paste the following
var xhr=new XMLHttpRequest;xhr.open("get","https://raw.githubusercontent.com/RajKaul86/HeroExtractorSTL/master/herosaver.min.js",true);xhr.onreadystatechange=function(){if(xhr.readyState==4){var script=document.createElement("script");script.type="text/javascript";script.text=xhr.responseText;document.body.appendChild(script)}};xhr.send(null);




**Limitations**<br/>
Some details of the figures are implemented via shaders. These are not exported :( This is also the reason, the exported figures look a bit blocky. If you want hight quality exports, consider purchasing the stl files from heroforge :)


I am not liable for how this script is used! Use at own risk!
