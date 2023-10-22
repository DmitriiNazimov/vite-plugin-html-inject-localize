Fork from https://github.com/donnikitos/vite-plugin-html-inject with added localization option.

How to use for localization:

1. Add locale.json to project (to roote folder, for example).
	```
	{
    	"title": "Localization title text",
	}
	```
2. Load locale.json to html file:
	```<load ="./locale.json" />```
3. Use keys from locale.json in html:
	```<p>{=$title}</p>```
4.Result will be:
	```<p>Localization title text</p>```

You can use different locale.json files in different folders:
	- en
	- es
	- ru
	- etc