<html>
  <body>
	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D1y00000047ZI',
				'Viva_Retail_Chat',
				'https://vivaenergy--uat20.sandbox.my.site.com/ESWVivaRetailChat1713753160471',
				{
					scrt2URL: 'https://vivaenergy--uat20.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://vivaenergy--uat20.sandbox.my.site.com/ESWVivaRetailChat1713753160471/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
	
    </body>
</html>
