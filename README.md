```mermaid
---
title: Sitemap
---
graph LR
%%{init:{'flowchart':{'nodeSpacing': 6, 'rankSpacing': 40}, 'theme': 'base', 'themeVariables': {'primaryColor': '#aaa', 'primaryBorderColor': '#aaa0', 'lineColor': '#333', 'darkMode': true}}}%%

Home("<a href=https://georgegarside.com/>🏡 Home</a>")
Blog("<a href=https://georgegarside.com/blog/>📝 Blog</a>")
Apps("<a href=https://georgegarside.com/apps/>🧰 Apps</a>")

Home --> Blog
	Blog --> macOS("<a href=https://georgegarside.com/blog/macos/>💻 macOS</a>")
	Blog --> iOS("<a href=https://georgegarside.com/blog/ios/>📱 iOS</a>")
	Blog --> Posts("<a href=https://georgegarside.com/blog/>📑 All Posts</a>")

Home --> Apps
	Apps --> BT("<a href=https://georgegarside.com/apps/bluetooth-inspector/>Bluetooth Inspector</a>")
	Apps --> WAI("<a href=https://georgegarside.com/apps/web-archive-inspector/>Web Archive Inspector</a>")
	Apps --> AI("<a href=https://georgegarside.com/apps/accessibility-inspector/>Accessibility Inspector</a>")
	Apps --> Thermals("<a href=https://georgegarside.com/apps/thermals/>Thermals</a>")
	Apps --> Alembicue("<a href=https://georgegarside.com/apps/alembicue/>Alembicue</a>")
