# Home-Assistant
My personal Home Assistant setup. This setup is what currently works for me on Hassio version 0.99.3.

Currently I have running an Ultralink Smart Wi-Fi Light Bulb as well as a Merkury Smart Outlet Switch. Instead of using these items respective apps, I am using an app called 'Smart Life' which connects and controls these items perfectly and I would assume controls other Ultralink and Merkury branded items. All you need to configure this is to add your own Smart Life username and password that you create from the app in the configuration.yaml file.

In my configuration.yaml file that is hosted on this Github, I have Dark Sky as a sensor on here for weather input which works great for weather, All you need to configure this is your own API key that you get for free from https://darksky.net/dev. Once you have your own API key then copy and paste the API key in the configuration.yaml file where it says 'YOUR_API_KEY'.

I also have https://www.speedtest.net/ as a sensor in my configuration.yaml file but commented out. The reason for doing this is that in my experience running a Speedtest uses a good bit of internet data. Seeing as I do not have an unlimited data cap I have it commented out.

After doing any of these things I strongly recommend Checking your config from LoveLace UI Server Controls then restarting from Server Controls.
