<html>
  <body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DSG000000BTcz',
				'manual',
				'https://signuporgtest1676999486889.test1.my.pc-rnd.site.com/ESWmanual1679511816289',
				{
					scrt2URL: 'https://signuporgtest1676999486889.test1.my.pc-rnd.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://signuporgtest1676999486889.test1.my.pc-rnd.site.com/ESWmanual1679511816289/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
