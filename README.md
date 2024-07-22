<html>
    <body>
      <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DS9000001FnO1',
				'WebChatDeployment',
				'https://yugroup--sivadev.sandbox.my.site.com/ESWWebChatDeployment1720769083209',
				{
					scrt2URL: 'https://yugroup--sivadev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://yugroup--sivadev.sandbox.my.site.com/ESWWebChatDeployment1720769083209/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

    </body>
</html>

