<h1>IamAdren's Toll Booth Script</h1>
<p>This script is a EZ-Pass type of system to your server.</p>

## Features
- EZ-Pass type of payment system.
- If a user passes through the toll with a "unregistered" or "stolen" vehicle it will alert law enforcement.
- Discord Bot with stats command.
- 2 Included Toll Booth YMAP's

## Dependencies
- ESX (Version 1.0)

## How to install the Script
1. Import tollBooth.sql to your database
2. Add this in your server.cfg:
```
ensure tollBooth
```
3. Edit the config.lua file to your liking

## How to install the Discord Bot
1. Create a bot account at discord.com/developers and grab the token.
2. Add your token into config.js
3. Add you MySQL server connection details into config.js
4. CD into your directory
5. Type ``npm i``
6. Type ``node index.js``

## Screenshots / Preview
<img src="https://gblobscdn.gitbook.com/assets%2F-MH09NXXuXXQpVX7yfuf%2F-MHPHgqu0pPqx69EmDRQ%2F-MHPHmVJ32ian47lqY8X%2Fimage.png?alt=media&token=9cd1d0e0-c85c-4ada-a229-a82fef71cc70">
<i>Route 1 Toll Booth</i>
<br>
<img src="https://gblobscdn.gitbook.com/assets%2F-MH09NXXuXXQpVX7yfuf%2F-MHPI-6OB2nnV9vqrnoM%2F-MHPIxHzYdNQBNLIo_mu%2Fimage.png?alt=media&token=e09e00b0-97bb-457a-9134-47790de4c227">
<i>Highway 1 Toll Booth</i>
<br>
<img src='https://gblobscdn.gitbook.com/assets%2F-MH09NXXuXXQpVX7yfuf%2F-MHP7f2XxmG_726vGUuV%2F-MHP8TWk0iC6khRhznxA%2Fimage.png?alt=media&token=081ff30f-ea52-42b9-9d1f-9fcac8c94c41'>
<i>Regular Payment Example</i>
<br>
<img src='https://gblobscdn.gitbook.com/assets%2F-MH09NXXuXXQpVX7yfuf%2F-MHP7f2XxmG_726vGUuV%2F-MHP9AzGzzLA-SOUuBCP%2Fimage.png?alt=media&token=e0732c15-906e-437d-982f-13d04291e03e'>
<i>Failure to pay police alert</i>
<br>

<img src='https://gblobscdn.gitbook.com/assets%2F-MH09NXXuXXQpVX7yfuf%2F-MHP7f2XxmG_726vGUuV%2F-MHP8vUwqF4XkIgY7Uu5%2Fimage.png?alt=media&token=987dbb18-763a-4b40-bcff-bd0d16741315'>
<i>Stolen/Unregistered vehicle passing through the toll police alert</i>
<br>

## Credits
Flashing Light Effect - https://github.com/P4NDAzzGaming/esx_speedcamera<br>
*I Would use VerpiMoDz's US Mexico Border for more tolls. https://discord.gg/sn8behF*
