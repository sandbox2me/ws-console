ws-console
==========

Remote JScript & VBScript code execution tool based on <a href="https://github.com/joewalnes/websocketd">websocketd</a>.<br/>
<b>Warning:</b> Running this on a system allows a system to be remotely controlled without authorization. Ensure it only runs on a private trusted network.

How to
----------

To get started <a href="https://github.com/joewalnes/websocketd/wiki/Download-and-install">download websocketd</a>, I'd recommend <a href="http://download.websocketd.com/releases/websocketd/0.2.8/windows_amd64/websocketd.exe">v0.2.8</a>.

Create <a href="https://github.com/dab00/ws-console/blob/master/console.cmd">console.cmd</a> and 
<a href="https://github.com/dab00/ws-console/blob/master/console.js">console.js</a> (for JScript) or 
<a href="https://github.com/dab00/ws-console/blob/master/console.vbs">console.vbs</a> (for VBScript).

Run app:
<pre>websocketd --port 8081 console.cmd</pre>

<a href="https://dab00.gweb.io/WS-console.html">Open ws-console</a>, copy your code and execute it:

<a href="https://github.com/dab00/ws-console/raw/master/screenshot.jpg" target="_blank">
<img src="https://github.com/dab00/ws-console/raw/master/screenshot.jpg" alt="screenshot" style="max-width:100%;">
</a>

<a href="http://www.daspot.ru/2013/12/websocket.html">Read details...</a>
