<!DOCTYPE html>
<html>
<head>
        <!-- metadata about the HTML document as a whole -->
 
    </head>
 
    <body>
      <h5>Hello Pizza!</h5>
        <!-- content of our page will be here! -->
         <!--I do like writing code-->
         <!--hello!-->
         <p>The most wonderful pizza</p>
 <ol>
   <li>
     <a href="https://www.pizzahut.co.uk/">Pizza Hut</a>
     </li>
   <li>
     <a href="https://www.pizzaexpress.com/">Pizza Express</a>
     </li>
   <li>
     <a href="https://www.papajohns.co.uk/">Papa John's</a>
     </li>
 </ol>
    <!-- Code injected by live-server -->
<script type="text/javascript">
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function() {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					head.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					head.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function(msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			console.log('Live reload enabled.');
		})();
	}
	// ]]>
</script>
</body>
</html>