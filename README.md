# README
This is document recopiles settings required to compile and execute weebhook script without problems.

# Description
All variables and comments are described below

## Options
This table show detailed options related about script

| Titles		| Description       	   |
| ------ 		| ------ 		   |
|  az_lead_extract_auth | `linkedln account`       | 
|  sh_global_search	|   `to search everywhere` |

<details>
set up  module sh_global_search 
```sh
https://www.youtube.com/watch?v=rbkWI9j0XN0
```

```sh
https://www.youtube.com/watch?v=fjXGrHcR1X0&list=PL-zDV7_rrd2onNkmb5weffcFiGQxWynaT
```	
</details>


| Titles| Description|
| ------ | ------ |
|  tmx_fleet|   TMX Drivers Module, Mexican Module |  
|  Techn.158|   `Q.4558.abc` |
| custom_api_module       | `It brings customers from PP, into contacts module`|
|        | `Before install requires: Go to: sudo nano /etc/odoo-server.conf, then set or add(if not exists)at the end of the file the line: limit_time_real = 1800` |
|        | `That will allow a proccess be active for max: 30minutes(1800 seconds)` |
|        | `After install it, Requires go to: Settings/API Token/ and enter` |
|        |`Custom URL: https://api1-tmx.app.portpro.io/v1/customer/ API Token: token(kind of token is beared but bearer word is not required) After that requires go to Settings/Technical/Automation/Scheduled Actions, and the action: "Automatic GET Request : Every 1 days run get request."will be created automatically by the installation process` |

```sh 
pip install readmeai
```

####Javascript　

```javascript
function test(){
	console.log("Hello world!");
}
 
(function(){
    var box = function(){
        return box.fn.init();
    };

    box.prototype = box.fn = {
        init : function(){
            console.log('box.init()');

			return this;
        },

		add : function(str){
			alert("add", str);

			return this;
		},

		remove : function(str){
			alert("remove", str);

			return this;
		}
    };
    
    box.fn.init.prototype = box.fn;
    
    window.box =box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```

<details><summary>Lista desplegable</summary>
	
</details>

```sh
https://www.youtube.com/watch?v=rbkWI9j0XN0
```
