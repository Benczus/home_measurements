Dataset description:
	Name: Eger House WiFi RSSI Measurements 
	Authors:
		Name: Bence Bogdándy
		Affiliation: Eszterházy Károly Catholic University.
		
		Name: Zsolt Tóth
		Affiliation: Eszterházy Károly Catholic University.
		
	Datasets:
		house_RSSI_measurements:
			Columns:
				x: pixel values on the x axis of the measurement points. The pixel values are from the wifi_test.PNG / wifi_test_grey.PNG
				y: pixel values on the y axis of the measurement points. The pixel values are from the wifi_test.PNG / wifi_test_grey.PNG
				rest of the columns: WiFi Access Points with corresponding WiFi RSSI values at the given (x,y) coordinates.
		
		house_RSSI_measurements_only_meters:
			Columns:
				x: values on the x axis of the measurement points in meters.
				y: values on the y axis of the measurement points in meters.
				rest of the columns: WiFi Access Points with corresponding WiFi RSSI values at the given (x,y) coordinates.
				
		house_RSSI_measurements_with_meters:
			Columns:
				x: pixel values on the x axis of the measurement points. The pixel values are from the wifi_test.PNG / wifi_test_grey.PNG
				y: pixel values on the y axis of the measurement points. The pixel values are from the wifi_test.PNG / wifi_test_grey.PNG
				x_m: values on the x axis of the measurement points in meters.
				y_m: values on the y axis of the measurement points in meters.
				rest of the columns: WiFi Access Points with corresponding WiFi RSSI values at the given (x,y) coordinates.
				
		house_RSSI_meters_melted:
			Columns:
				x_m: values on the x axis of the measurement points in meters.
				y_m: values on the y axis of the measurement points in meters.
				variable: name of the WiFi Access Point.
				value: value of the RSSI measurement.
				

				
