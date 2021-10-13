<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Solution_Overview_0"></a>Solution Overview</h1>
<p class="has-line-data" data-line-start="2" data-line-end="3">Webhook-code provides the fulfillment service for Dialogflow Virtual Agent for General Motors POC</p>
<h2 class="code-line" data-line-start=4 data-line-end=5 ><a id="Setup_4"></a>Setup</h2>
<p class="has-line-data" data-line-start="6" data-line-end="7">Configurations (to be done in config file based on NODE_ENV)</p>
<p class="has-line-data" data-line-start="8" data-line-end="11">Provide the platform supported by your Virtual Agent<br>
Enable auth (recommended)<br>
Commands to run</p>
<blockquote>
<p class="has-line-data" data-line-start="11" data-line-end="16">$ npm i<br>
$ export NODE_ENV=“environment_name”<br>
$ export USERNAME=“username” (optional)<br>
$ export PASSWORD=“password” (optional)<br>
$ npm start</p>
</blockquote>
<h1 class="code-line" data-line-start=17 data-line-end=18 ><a id="Solution_Architecture_17"></a>Solution Architecture</h1>
<h3 class="code-line" data-line-start=18 data-line-end=19 ><a id="Get_Started_18"></a>Get Started</h3>
<h4 class="code-line" data-line-start=19 data-line-end=20 ><a id="Required_packages_19"></a>Required packages</h4>
<pre><code class="has-line-data" data-line-start="21" data-line-end="25">Node Engine
node: v14.17.5
npm: 6.14.14
</code></pre>
<h4 class="code-line" data-line-start=25 data-line-end=26 ><a id="Install_Dependencies_25"></a>Install Dependencies</h4>
<pre><code class="has-line-data" data-line-start="27" data-line-end="29">npm install
</code></pre>
<h4 class="code-line" data-line-start=29 data-line-end=30 ><a id="Deployment_29"></a>Deployment</h4>
<pre><code class="has-line-data" data-line-start="31" data-line-end="33" class="language-sh">gcloud app deploy
</code></pre>
<h2 class="code-line" data-line-start=33 data-line-end=34 ><a id="Automation_using_scripts_33"></a>Automation using scripts</h2>
<h3 class="code-line" data-line-start=34 data-line-end=35 ><a id="client_environment_34"></a>client environment</h3>
<p class="has-line-data" data-line-start="35" data-line-end="36">Deploying client environment using the shell script</p>
