---
title: "Home"
---

![Your Image](images/image.png)

# Cesario Silva

[Home](#) | [Blog](posts) | [Projects](projects)

## Recent Blog Posts

{{ range first 3 .Site.RegularPages }}

<h2><a href="{{ .Permalink }}">{{ .Title }}</a></h2>
<p>{{ .Summary }}</p>
{{ end }}
