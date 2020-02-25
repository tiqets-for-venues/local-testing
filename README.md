# How to test a Booking Engine locally
A template folder to set up your testing environment locally and make sure a Booking Engine is working before sending the code to a partner.

### Pre-requisites
 1. Download [VS code](https://code.visualstudio.com/download) 
 2. Download this folder as a zip [(link)](https://github.com/tiqets-for-venues/local-testing/archive/master.zip)
 3. Double click on the zip to open
 4. Make sure to move this zip in a new folder on your laptop and rename it as you please (/Desktop/BE-Code)
 5. Drag and drop the folder into the VS Code App


### Testing locally
 1. After opening the folder in VS code, go back to your folder directory
 2. Right click on the **index.html** file, and select "Duplicate" or "Copy"
 3. Rename the duplicated code into the name of the venue 
	 - "BCN-Aquarium.html" for example
	 - Make sure that the extension is **.html** or you won't be able to test
 4. In VS code, on the left sidebar, click on your new file name to open it
 5. Remove the code that you won't use in this duplicated file
	 - If you want to create a Smart button with the new implementation, remove all the other codes
6. Go to your BE entity and back-office, and look at the difference with the code you have locally
	- Change the last number of the script (usually replacing 1058.js by 2403.js)
7. Save your changes with CMD + S / CTRL + S
8. Copy paste your code in [W3C Validator](https://validator.w3.org/#validate_by_input) to check if any critical error shows up
9. Go to your folder, and double click your file {venue-name}.html or drag and drop it into Google Chrome
10. Try opening the booking engine when clicking on your targeted Button or Smart button
	- If not working
		- Open the console and check for errors
		- Based on the error, you should be able to fix it in your code or in the BO
		- Refer to the presentation *Front-End for the BE* to see if the error is common
11. Once the booking engine is opening on your local page, and you're able to get to the payment step, you're good to send the code to the venue!
