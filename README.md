# Tzeva Adom Auto Refresh

This widget automatically refreshes the page every 5 seconds to redirect to the Tzeva Adom website.

```html
<html>
<head>
    <meta name="js-widget-title" content="Tzeva Adom Auto Refresh">
    <script type="text/javascript">
        function __wweb2JsWidgetTitle() {
            return "Tzeva Adom Auto Refresh";
        }

        function reloadPage() {
            window.location.href = "https://www.tzevaadom.co.il";
        }

        setTimeout(reloadPage, 5000);

        __wweb2Log("Page will refresh every 5 seconds.");
    </script>
</head>
<body>
    <h1>Redirecting to Tzeva Adom...</h1>
</body>
</html>