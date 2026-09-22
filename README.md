# discord-wap-fxos
A simple Firefox OS app for @gtrxAC's [Discord WAP client](https://github.com/gtrxAC/discord-wap).

**NOTE:** You will need to have a Firefox-based browser which has WebIDE (for example, Firefox 45.9.0 ESR or lower, and Pale Moon 28.6.1 or lower)

## Initial setup

1. Download the [latest discord-wap-fxos release](https://github.com/klte-hype/discord-wap-fxos/releases/latest/) on a PC.
2. Unzip the ``discord-wap-fxos.zip`` file.
3. Follow [these instructions](https://ffapps.danielherr.software/sideloading/) to install it on your Firefox OS device.

### If you are hosting your own Discord WAP server, do these steps before copying the file to your KaiOS device:
1. Unzip the ``discord-wap-fxos.zip`` file.
2. Open the manifest.webapp file.
3. Change the URLs inside of ``"csp": "default-src 'self'; script-src 'self'; connect-src 'self' http://wap.gtrxac.fi; frame-src http://wap.gtrxac.fi;",`` to the URL of your server.
4. Save the file.
5. Open the ``index.html`` file.
6. Change the URL inside of ``<iframe src="http://wap.gtrxac.fi/" mozbrowser></iframe>`` to the URL of your server.
7. Save the file.

## How to use
See the "How to use" section of the [Discord WAP](https://github.com/gtrxAC/discord-wap) project page to get more information.

## Thanks
* [@gtrxAC](https://github.com/gtrxAC) for the app icon (from another one of his projects, [Discord J2ME](https://github.com/gtrxAC/discord-j2me)), and the original Discord WAP project.
