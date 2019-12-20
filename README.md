# Opera-Mini-Extreme-Mode-Detector
##### Use this code to detect Opera Mini Extreme Mode and redirect users to the instructions guide

###### Copy the folder "operamini" to the root of your site directory

###### Copy and paste the below code to the head of the index file 

```html
<!-- Detect Opera Mini Extreme Mode & Redirect to ./operamini -->
<script type="text/javascript">
    var isOperaExtreme = -1 < navigator.userAgent.indexOf("Opera Mini/") && -1 < navigator.userAgent.indexOf("Presto/");
    !0 == isOperaExtreme && (window.location = "operamini/");
</script>
```

###### What users will see when they visit the site in Extreme Mode

<img src="http://dev.bean.co.ke/operamini/screenshot.png" width="250">
