```mermaid
graph LR
%%{init:{'flowchart':{'nodeSpacing': 6, 'rankSpacing': 40}, 'theme': 'base', 'themeVariables': {'primaryColor': '#aaa0', 'primaryBorderColor': '#aaa0', 'lineColor': '#333', 'darkMode': true}}}%%

Home("<a href=https://georgegarside.com/ style='color: var(--color-accent-fg)'>🏡 Home</a>")
Blog("<a href=https://georgegarside.com/blog/ style='color: var(--color-accent-fg)'>📝 Blog</a>")
Apps("<a href=https://georgegarside.com/apps/ style='color: var(--color-accent-fg)'>🧰 Apps</a>")

Home --> Blog
	Blog --> macOS("<a href=https://georgegarside.com/blog/macos/ style='color: var(--color-accent-fg)'>💻 macOS</a>")
	Blog --> iOS("<a href=https://georgegarside.com/blog/ios/ style='color: var(--color-accent-fg)'>📱 iOS</a>")
	Blog --> Posts("<a href=https://georgegarside.com/blog/ style='color: var(--color-accent-fg)'>📑 All Posts</a>")

Home --> Apps
	Apps --> BT("<a href=https://georgegarside.com/apps/bluetooth-inspector/ style='color: var(--color-accent-fg)'>Bluetooth Inspector</a>")
	Apps --> WAI("<a href=https://georgegarside.com/apps/web-archive-inspector/ style='color: var(--color-accent-fg)'>Web Archive Inspector</a>")
	Apps --> AI("<a href=https://georgegarside.com/apps/accessibility-inspector/ style='color: var(--color-accent-fg)'>Accessibility Inspector</a>")
	Apps --> Thermals("<a href=https://georgegarside.com/apps/thermals/ style='color: var(--color-accent-fg)'>Thermals</a>")
	Apps --> Alembicue("<a href=https://georgegarside.com/apps/alembicue/ style='color: var(--color-accent-fg)'>Alembicue</a>")
