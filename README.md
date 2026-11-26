<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Kenny Mac | Computer Engineering</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter+Tight:wght@500;700;800&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@500&display=swap" rel="stylesheet">
<style>
:root{color-scheme:light dark;--bg:light-dark(#ffffff,#0a0f1c);--ink:light-dark(#10141c,#e8ecf4);--mute:light-dark(#4f5868,#a6afc2);--rule:light-dark(#d9dfea,#243049);--panel:light-dark(#f3f5fa,#111a2c);--mask:#0c2e72;--mask2:#082258;--cu:light-dark(#a85f1c,#e09a52);--cuhi:#e8a865;--silk:#eef2fa}
:root[data-theme=light]{color-scheme:light}:root[data-theme=dark]{color-scheme:dark}
*{box-sizing:border-box;min-width:0}
html{scroll-padding-top:72px;scroll-behavior:smooth;overflow-x:clip}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 Inter,system-ui,sans-serif;overflow-x:clip}
a{color:var(--cu);text-underline-offset:3px}
h1,h2,h3{font-family:"Inter Tight",Inter,sans-serif;letter-spacing:-.02em;line-height:1.08;margin:0;text-wrap:balance}
.wrap{max-width:1240px;margin:0 auto}
.band{padding-block:clamp(28px,4vw,64px);padding-left:max(5vw,16px);padding-right:max(5vw,16px)}
nav{position:sticky;top:0;z-index:5;background:color-mix(in srgb,var(--bg) 92%,transparent);backdrop-filter:blur(8px);border-bottom:1px solid var(--rule)}
nav .wrap{display:flex;flex-wrap:wrap;align-items:center;gap:6px 22px;padding:12px max(5vw,16px)}
nav b{font-family:"Inter Tight",Inter,sans-serif;font-size:17px;margin-right:auto}
nav a{color:var(--ink);text-decoration:none;font-weight:500;font-size:15px;padding:6px 0}
nav a:hover,nav a:focus-visible{color:var(--cu)}
.hero{background:var(--mask);color:var(--silk);padding-bottom:0}
.top{display:grid;grid-template-columns:minmax(0,1.3fr) minmax(0,1fr);gap:28px;align-items:end}
.hero h1{font-size:clamp(36px,5vw,56px);font-weight:800}
.hero p.lede{font-size:18px;max-width:60ch;margin:14px 0 0;color:#d3def5}
.links{display:flex;flex-wrap:wrap;gap:10px;justify-content:flex-end}
.btn{display:inline-flex;align-items:center;min-height:44px;padding:0 18px;border-radius:6px;font-weight:600;text-decoration:none;border:1.5px solid #6585c4;color:var(--silk)}
.btn.main{background:var(--cuhi);border-color:var(--cuhi);color:#1c1208}
.btn:hover,.btn:focus-visible{outline:2px solid var(--cuhi);outline-offset:2px}
.facts{display:flex;flex-wrap:wrap;gap:8px 26px;margin-top:18px;font-size:15px;color:#bccbea}
.facts span{white-space:normal}
.fig{position:relative;height:clamp(300px,34vw,400px);margin-top:28px}
.fig>svg{position:absolute;inset:0;width:100%;height:100%;display:block}
.fig
