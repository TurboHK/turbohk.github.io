<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="x-ua-compatible" content="ie=edge">
<title>TurboHK</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<script>

        function doAjaxInit() {
            var xhttp = new XMLHttpRequest();

            xhttp.onreadystatechange = function() {
            };

            xhttp.open("POST", 'https://res.windscribe.com/res/init'+window.location.search, true);
            xhttp.setRequestHeader("Content-type", "application/x-www-form-urlencoded");
                        xhttp.send("wsref="+document.referrer);
            
        }

        doAjaxInit();

    </script>
