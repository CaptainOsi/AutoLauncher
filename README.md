# AutoLauncher

![N|Solid](http://imgur.com/dyw3PTt.png)

AutoLauncher is a programm which can execute an autohotkey script uploaded on a website.

> With the autolauncher you can execute an autohotkey script which is upload on Internet. With this you can update
> your script and the users can have the updates instantaneously.

## Installation

First you have to upload your script on the internet.

Second, you can download the autolauncher.ahk file. And you just have to change the url by your url.

```sh
urlscript := "http://url"
```

You can remplace by : 

```sh
urlscript := "http://your_url_that_contains_ur_script"
```

## Note

The script includes an exe (autohotkey) to execute the script without autohotkey installed.
You can easily remplace this part by :

```sh
UrlDownloadToFile, URL, Filename
```

Or You just have to have the autohotkey.exe in the folder of your script.

###Distributing your script

After, you can create an executable and distributing to your users. 
When you change the script which has uploaded, the users can have the updates.

License
----

MIT


**Get Fun !**
