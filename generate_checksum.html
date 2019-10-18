if(request.method == 'POST'){
			var paramarray = {};
				paramarray['MID'] = 'xxxxxxxxxxxxxx'; //Provided by Paytm
				paramarray['ORDER_ID'] = 'ORDER00001'; //unique OrderId for every request
				paramarray['CUST_ID'] = 'CUST0001';  // unique customer identifier 
				paramarray['INDUSTRY_TYPE_ID'] = 'xxxxxxxxx'; //Provided by Paytm
				paramarray['CHANNEL_ID'] = 'WAP'; //Provided by Paytm
				paramarray['TXN_AMOUNT'] = '1.00'; // transaction amount
				paramarray['WEBSITE'] = 'xxxxxxxxxxxx'; //Provided by Paytm
				paramarray['CALLBACK_URL'] = 'https://pguat.paytm.com/paytmchecksum/paytmCallback.jsp';//Provided by Paytm
				paramarray['EMAIL'] = 'abc@gmail.com'; // customer email id
				paramarray['MOBILE_NO'] = '9999999999'; // customer 10 digit mobile no.
					paytm_checksum.genchecksum(paramarray, paytm_config.MERCHANT_KEY, function (err, checksum) {
					console.log('Checksum: ', checksum, "\n");
					response.writeHead(200, { 'Content-type': 'text/json', 'Cache-Control': 'no-cache' });
					var json = {
						'MID': 'XXXXXXXXXXXXX',
						'ORDER_ID': OrderId,
						'CUST_ID': '234567',
						'INDUSTRY_TYPE_ID': 'Retail',
						'CHANNEL_ID': 'WAP',
						'TXN_AMOUNT': '1.00',
						'WEBSITE': 'Retail',
						'CALLBACK_URL': 'https://securegw-stage.paytm.in/theia/paytmCallback?ORDER_ID=' + OrderId,
						'CHECKSUMHASH': checksum
				  response.write(JSON.stringify(json));
					response.end();
				});
			}else{
				response.writeHead(200, {'Content-type' : 'text/json'});
				response.end();
			}
