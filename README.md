# [oc-robots-plugin / devnull.robot](https://github.com/gerekper/octobercms-robot) #
Generator for OctoberCMS

## What is it ##
As the title says, it allows you to generate [humans.txt](http://humanstxt.org/Standard.html) and [robots.txt](http://www.robotstxt.org/orig.html) for your web app.

## Installation ##

#### Manual Installation ####
Some advanced users might prefer to use manually install the plugin. This can be done using the command line. CD into your OctoberCMS project folder and paste these commands. It will execute one after another:
```
cd plugins
mkdir -p devnull/robot && cd $_
git clone https://github.com/gerekper/oc-robots-plugin.git ./
composer update

```
Logout from your backend and login again. This will create the necessary tables for the plugin to work. You have now installed Devnull.Robot! Enjoy!!!

## Features ##
- Manage Robots.txt
- Manage Humans.txt
- Manage Logs from accessing to Robots and Humans
- Manage Agents
- System settings

| Function      | Public    | Admin     | Create    | Update    | Delete 
| :------------ |:------:   | :------:  | :------:  | :------:  | :------:
| Robots.txt    | :o:       | :o:       | :o:       | :o:       | :o:
| Humans.txt    | :o:       | :o:       | :o:       | :o:       | :o:
| Robot Logs    | :x:       | :o:       | :x:       | :x:       | :o:
| Agents        | :x:       | :o:       | :o:       | :o:       | :o:
| Robot Traps   | :o:       | :o:       | :o:       | :o:       | :o:


## Todo ##
- Robot Traps
- Optimization of code
- Agents Scrapping using simple scrapping technology based on <h1> on html  
    1. http://www.user-agents.org/index.shtml
    2. http://www.useragentstring.com/pages/useragentstring.php
    
## Thanks ##

* [Alexey Bobkov and Samuel Georges](http://octobercms.com) for OctoberCMS.
* [Scott Bedard](https://github.com/scottbedard) for HasMany Widget.
* [Saifur Rahman Mohsin](https://github.com/SaifurRahmanMohsin/) for Txt Generator.
* [James Healey](https://github.com/jayhealey) for Robots class/Service Provider.