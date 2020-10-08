# Blacklist Bot Setup

## How to install the Blacklist Bot

Here is a set by set guide to setting up the blacklist bot

{% hint style="info" %}
First, unzip the file using something like Winrar or 7zip
{% endhint %}

Now we need to edit the .env file

```
TOKEN=(Fill Bot Token in here)
PREFIX=(Put Prefix here)
```

{% hint style="info" %}
 If you don't know how to make a bot token follow this: [https://www.writebots.com/discord-bot-token/](https://www.writebots.com/discord-bot-token/)
{% endhint %}

**Step 2**

Install the latest version of Node.JS

{% hint style="info" %}
Head over to [https://nodejs.org/en/](https://nodejs.org/en/) on windows or mac, if you are using a vps refer to google
{% endhint %}

Now we are going to need to install the required packages \(You are going to need to know the path of the folder

```text
cd (File name)
```

```text
npm install
```

{% hint style="info" %}
If you are just updating the bot and want to use the same database from your old one move the  json.sqlite to the new file before running this command
{% endhint %}

**Step 3**

Installing PM2 to have this run in our background

```text
npm i pm2
```

**Step 4**

Starting our bot

```text
pm2 start index.js
```

{% hint style="info" %}
If the bot doesn't go online do node . and see want error you get and contact GATA Tech Support with that error and we will be happy to help
{% endhint %}

