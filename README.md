<h1 dir="auto"><img src="https://i.gyazo.com/5d2322450b17f0692fd7d48014cc70d6.png" alt="" /></h1>
<h1 dir="auto">You must have approval from @ADMIN before installing community server to get added to the community server list</h1>
<h1 dir="auto">H1emu-community-server-install</h1>
<p dir="auto">Install H1emu community server</p>
<p dir="auto">(Tested with ubuntu 20.4 Clean install) (may work on other Distros&nbsp; this script will force install some packages &amp; upgrade old packages **use at your own risk**)</p>
<ol>
<li><code>sudo</code></li>
<li><code>apt install git -y</code></li>
<li><code>git clone https://github.com/H1emu/H1emu-community-server-install.git<br /></code></li>
<li><code>cd H1emu-community-server-install</code></li>
<li><code>chmod +x communityinstall.sh</code></li>
<li><code>./communityinstall.sh</code></li>
</ol>
<p dir="auto"></p>
<h2>Starting Community Server</h2>
<table>
<tbody>
<tr>
<td>Stop server</td>
<td>pm2 kill</td>
</tr>
<tr>
<td>Start server</td>
<td>cd /H1emu-community-server-install/h1z1-server/</td>
<td>Then sudo ./start.sh</td>
</tr>
<tr>
<td>Show server output</td>
<td>pm2 monitor</td>
</tr>
</tbody>
</table>
<h2>Setup MongoDB Settings</h2>
<p dir="auto">Open a webbrowser to <a href="http://ip:4321">http://serverip:4321</a></p>
<p dir="auto">Locate h1server in your mongo db</p>
<p dir="auto">CONTACT @ADMIN TO GET YOUR server:Id</p>
<p dir="auto">CONTACT @ADMIN TO GET YOUR nameId:**** Server Name Strings <a href="https://github.com/QuentinGruber/h1z1-string-finder/blob/main/strings.log">HERE</a></p>
<p dir="auto">Change&nbsp; ( serverAddress:"YourServerip:1117" )</p>
<p dir="auto">Change&nbsp; ( PingAddress:"YourServerip:1117" )</p>
<div class="fieldset Number ng-star-inserted">
<div class="key">&nbsp;</div>
</div>
<h2>Setup start.sh Script</h2>
<p dir="auto">Locate export WORLD_ID="*" and set to your world id issued by @ADMIN</p>
<p dir="auto"><img src="https://i.gyazo.com/9010a3af6b02b803f9d2922581f5b771.png" alt="" /></p>
<p dir="auto"><img src="https://i.gyazo.com/4775ad7f732383e520aaf5bd5b705eca.png" alt="" /></p>

<p dir="auto">&nbsp;</p>
<h2>&nbsp;</h2>
