+++
date = "2016-01-02T11:18:04+08:00"
draft = false
title = "How to setup a blog using Hugo for Windows"

+++

Download the appropriate version of Hugo from here: https://github.com/spf13/hugo/releases

![download](/img/download.png)
Create a directory named "Hugo" anywhere you want, create two directories named "bin" and "Sites" in it as well.

![directory](/img/directory.png)
Extract the zip file you downloaded to the "bin" directory and rename the .exe file to "hugo.exe".

![renamed](/img/renamed.png)
Open up Command Prompt and run ```hugo help``` , if you see an output that starts with ```A Fast and Flexible img Site Generator``` , you are good to go.

![installed](/img/installed.png)
Change your directory to the ```Sites``` directory.

Run ```hugo new site "your site name"```.

![newSite](/img/newSite.png)
You have just created your first site and you should be able to see a new "your site name" directory in your "Sites" folder.

Now change your directory to the "your site name" directory.

Run ```hugo new about.md```.

![newContent](/img/newContent.png)
This is your first piece of content on your blog, feel free to edit it however you like.

You would also want to install some themes for your blog by running ```git clone --depth 1 --recursive https://github.com/spf13/hugoThemes.git themes```.

![themes](/img/themes.png)
You can look up the whole list of themes at https://github.com/spf13/hugoThemes.git .

Finally, fire the server up with ```hugo server --theme="the theme you want" --buildDrafts``` and you have just created your blog with Hugo!.
![run](/img/run.png)