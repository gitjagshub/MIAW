<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHn00000199Q7',
				'Git_MIAW',
				'https://jkota-new-demo.my.site.com/ESWGitMIAW1712542265597',
				{
					scrt2URL: 'https://jkota-new-demo.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://jkota-new-demo.my.site.com/ESWGitMIAW1712542265597/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
