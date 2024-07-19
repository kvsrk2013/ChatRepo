<html>
  <body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D5h00000932o6',
				'MessageFlowDeployment',
				'https://forcecom146-dev-ed.develop.my.site.com/ESWMessageFlowDeployment1718028642963',
				{
					scrt2URL: 'https://forcecom146-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://forcecom146-dev-ed.develop.my.site.com/ESWMessageFlowDeployment1718028642963/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
