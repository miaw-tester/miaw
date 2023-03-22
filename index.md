<html>
  <body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DRO000000NwIg',
				'Service_Messaging_for_Web',
				'https://testcom43.test1.my.pc-rnd.site.com/SiteServiceMessagingforWeb0452',
				{
					scrt2URL: 'https://testcom43.test1.my.pc-rnd.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://testcom43.test1.my.pc-rnd.site.com/SiteServiceMessagingforWeb0452/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>



</body>
</html>
