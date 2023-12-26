
<h1 align="center" style="font-size: 200px; color: #FFA500;">Hi 👋, I'm Jedex♨</h1>


<div align="center">
  <img src="https://i.pinimg.com/originals/52/29/40/5229407d4cd3ac735c96abc7a8a78458.gif" alt="IMG_8072_Original">
</div>

<h3 align="center" style="font-size: 200px; color: #FFA500;">newbie three point o</h3>

#######

<p align="center">
    <a href="https://github.com/devicons/devicon/releases">
        <img alt="GitHub release (latest by semver)" src="https://img.shields.io/github/v/release/devicons/devicon?color=%2360be86&label=Latest%20release&style=for-the-badge&sort=semver">
    </a>
    <a href="/LICENSE">
        <img alt="GitHub" src="https://img.shields.io/github/license/devicons/devicon?color=%2360be86&style=for-the-badge">
    </a>
    <a href="https://github.com/devicons/devicon/graphs/contributors">
        <img alt="GitHub contributors" src="https://img.shields.io/github/contributors-anon/devicons/devicon?color=%2360be86&style=for-the-badge">
    </a>
    <a href="https://github.com/devicons/devicon/actions">
        <img alt="GitHub branch checks state" src="https://img.shields.io/github/checks-status/devicons/devicon/master?color=%2360be86&style=for-the-badge">
    </a>
    <a href="https://github.com/devicons/devicon/issues?q=is%3Aopen+is%3Aissue+label%3Arequest%3Aicon">
        <img alt="GitHub issues by-label" src="https://img.shields.io/github/issues/devicons/devicon/request:icon?color=%2360be86&label=icon%20requests&style=for-the-badge">
    </a>
    <a href="https://github.com/devicons/devicon/stargazers">
        <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/devicons/devicon?color=%2360be86&label=github%20stars&style=for-the-badge">
    </a>
</p>
<br />
<div align="center">
    <a href="https://github.com/devicons/devicon">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/devicon/devicon-original-wordmark.svg" alt="Devicon Logo" height="140" />
    </a>
    <h5 align="center">
        devicon aims to gather all logos representing development languages and tools.
    </h5>
    <p align="center">
        <a target="_blank" href="https://devicon.dev">Demo</a>
        &middot;
        <a target="_blank" href="https://github.com/devicons/devicon/issues/new?assignees=&labels=request%3Aicon&template=icon-request.md&title=Icon+request%3A+%5BNAME%5D">Request Icon</a>
        &middot;
        <a href="#contribute">Contribute</a>
    </p>
</div>

<h2>TL;DR;</h2>

```html
<!-- in your header -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">

<!-- in your body -->
<i class="devicon-devicon-plain"></i>
```

<h2>Table of Contents</h2>
<ol>
    <li><a href="#about">About the project</a></li>
    <li><a href="#getting-started">Getting started</a></li>
    <li><a href="#request-icon">Requesting icon</a></li>
    <li><a href="#contribute">Contributing</a></li>
    <li><a href="#discord-server">Discord server</a></li>
    <li><a href="#develop-vs-master"><code>develop</code> vs <code>master</code></a></li>
    <li><a href="#stale-prs">Stale pull requests</a></li>
    <li><a href="#build-yourself">Go build yourself</a></li>
</ol>

<h2 id="about">About the project</h2>
<p>
    Devicon aims to gather all logos representing development languages and tools.
    Each icon comes in several versions: font/SVG, original/plain/line, colored/not colored, wordmark/no wordmark.
    Devicon has 150+ icons. And it's growing!<br />
</p>
<p>
    See the <a href="/devicon.json">devicon.json</a> or <a href="https://devicon.dev">our website</a> for complete and up to date reference of 
    all available icons.
</p>
<sub>
    All product names, logos, and brands are property of their respective owners. All company, product and service 
    names used in this website are for identification purposes only. Use of these names, logos, and brands does not 
    imply endorsement. Usage of these logos should be done according to the company/brand/service's brand policy.
</sub>
<p>
    Thank you to our contributors and the <a href="https://icomoon.io/#home">IcoMoon app</a>. Devicon would not be possible without you.
</p>


<h2 id="getting-started">Getting started</h2>
<p>
    For a super fast setup go check <a href="https://devicon.dev">devicon.dev</a>.<br />
    You can either <a href="#getting-started-svg">use the raw SVG</a> icons or our <a href="#getting-started-font">devicon font</a> (which is 
    also available via CDN).
</p>

<h4 id="getting-started-font">Use the <code>devicon</code> font (recommended)</h4>
<p>
    You can install devicon as a dependency to your project either with <code>npm</code> or <code>yarn</code>:
</p>

```bash
npm install --save devicon
yarn add devicon
```

<p>
    If you don't want to use a package manager you can also download
    and include <a href="/devicon.min.css">devicon.min.css</a> next to the <a href="/fonts">font files</a> to your project.
    See <a href="https://devicon.dev">devicon.dev</a> for details about how to add devicon to your project via
    a CDN.
</p>
<p>
    After setting up you just have to include the stylesheet in your header
    to get started:
</p>

```html
<link rel="stylesheet" href="devicon.min.css">
```

<p>Start using icons with <code>&lt;i&gt;</code>-tag</p>

```html
<!--  for devicon plain version -->
<i class="devicon-devicon-plain"></i>

<!--  for devicon plain version with wordmark -->
<i class="devicon-devicon-plain-wordmark"></i>

<!--  for devicon plain version colored with devicon main color -->
<i class="devicon-devicon-plain colored"></i>

<!--  for devicon plain version with wordmark colored with devicon main color -->
<i class="devicon-devicon-plain-wordmark colored"></i>
```

<p>
    An alternate way to use <code>devicon</code> is by copy/paste the raw SVG code
    to your project.
</p>
<h4 id="getting-started-svg">Copy/paste SVG code (from the <a href="https://github.com/devicons/devicon/tree/master/icons">svg folder</a> or the <a href="https://devicon.dev">project page</a>)</h4>



######

<p align="left"> <img src="https://komarev.com/ghpvc/?username=jedex2&label=Profile%20views&color=ff144f&style=flat" alt="jedex2" /> </p>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://instagram.com/jjksy__" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="jjksy__" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=jedex2&show_icons=true&theme=tokyonight&title_color=832525&locale=en" alt="jedex2" /></p>
