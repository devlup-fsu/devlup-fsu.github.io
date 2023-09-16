---
layout: links
title: 🔗links🔗
permalink: /links
published: true
---

<style>
.logo {
    font-size: 3rem;
    font-weight: $base-font-weight-bold;
    color: var(--link-color);

    .logosvg {
        height: 4rem;
        font-size: 3rem;
        -webkit-filter: var(--invert-logo-color);
    }
}
<style>
.l- {
    position: relative;
    border-style: solid;
}
.l-Tile {
    clip-path: inset(0% 0% 0% 0% round 10px);
    background-color: #451b24;
    position: relative;
    text-align: center;
    display: block;
    width: 100%;
    opacity: 1;
    transition: scale 0.2s, opacity 0.2s;
}
.l-Tile:hover {
    box-shadow: 1000px 10px;
    scale: 1.05;
    opacity: 1;
}
.l-Tile-label {
    display: flex;
    align-items: center;
    justify-content: center;
}
.icon {
    border-style: none;
    position: relative;
    top: 12px;
    left: 18px;
}
a.fill-div {
    display: block;
    height: 100%;
    width: 100%;
    text-decoration: none;
}

@media (max-width: 770px) {
    .logo {
      margin-bottom: 10rem;
    }
}

</style>

<header>
<div>
        <div class="logo" style="text-align: center;">
        <a href="{{ '/' | prepend: site.baseurl }}">{{ site.blog.title }}</a>
      </div>
      <div class="logo" style="text-align: center;">
        <object type="image/svg+xml" style="fill: #ceb888;" data="{{ site.blog.logo_path | relative_url }}" class="logosvg">Your browser does not support svg images</object>
      </div>
</div>
</header>

<h2 style="text-align: center;">links will open in a new tab: </h2>

<div class="l-">
    <div class="l-Tile">
        <a href="https://discord.gg/VY5WnDRne7" class="fill-div" target="_blank">
            <h1 class="l-Tile-label">Discord </h1>
        </a>
    </div>
</div>

<div class="l-">
    <div class="l-Tile">
        <a href="https://nolecentral.dsa.fsu.edu/organization/devlup" class="fill-div" target="_blank">
            <h1>Nole Central</h1>
            <i class="fa fa-external-link-square disabled"></i>
        </a>
    </div>
</div>

<div class="l-">
    <div class="l-Tile">
        <a href="/" class="fill-div" target="_blank">
            <h1>Continue to our website</h1>
            <i class="fa fa-external-link-square disabled"></i>
        </a>
    </div>
</div>