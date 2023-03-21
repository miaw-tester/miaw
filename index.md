<html>
  <body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DSG000000Kctx',
				'Service_Messaging_for_Web_1',
				'https://signuporgtest1679432728801.test1.my.pc-rnd.site.com/SiteServiceMessagingforWeb3378',
				{
					scrt2URL: 'https://signuporgtest1679432728801.test1.my.pc-rnd.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://signuporgtest1679432728801.test1.my.pc-rnd.site.com/SiteServiceMessagingforWeb3378/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>



</body>
</html>
