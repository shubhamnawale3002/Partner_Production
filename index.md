<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHr0000098CT7',
				'Sonim',
				'https://in1727428111461.my.site.com/ESWSonim1727680152499',
				{
					scrt2URL: 'https://in1727428111461.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://in1727428111461.my.site.com/ESWSonim1727680152499/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
