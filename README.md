# LED_control_using_web

## Project Overview

This project demonstrates controlling an LED using the Bolt IoT platform and the Bolt Cloud. The primary objective is to remotely manage an LED via a web interface, enabling users to turn the LED on and off with just a click of a button. This can be particularly useful in various scenarios, such as controlling lights in a room without leaving the comfort of a couch.

## Requirements

- Bolt IoT module (ESP-12E)
- LED
- USB cable for power
- Bolt Cloud account
- Internet connectivity

## Project Steps

### Step 1: Create a Product on Bolt Cloud

1. Navigate to [Bolt Cloud](https://cloud.boltiot.com) and log in.
2. Create a new product by selecting the product type as `Output Device` and the interface type as `GPIO`.
3. Configure the product and proceed to the code tab.

### Step 2: Write the Control Code

The code to control the LED using Bolt Cloud involves setting up a simple web interface with buttons to turn the LED on and off. Please refer 'LED_control.html' for the complete code.

- The script includes a JavaScript file from Bolt Cloud that provides functions like `digitalWrite`.
- The `setKey` function initializes the API key and device name.
- Two buttons are added within the `<body>` tag to control the LED state.

### Step 3: Save the Code

1. Save the code with the file name `ledcontrol` and the file extension as `html`.
2. Ensure that the code is correctly saved by checking the editor.

### Step 4: Link the Product to the Bolt Device

1. In the products tab, select the created product and link it to the Bolt device by clicking on the link icon and selecting the appropriate device.
2. Click on the 'Done' button to complete the linking process.

### Step 5: View and Test the Web Interface

1. Click on the view device icon to access the webpage.
2. Use the `ON` and `OFF` buttons to control the LED.

### Step 6: Troubleshooting

If the LED does not respond as expected, follow these steps:

1. Ensure the code is correctly saved in the product configuration page.
2. Verify the LED connections.
3. Check the pin number in the `digitalWrite` function matches the connection.
4. Ensure the API key is enabled and valid.

## Example Output

Please refer to 'Buttons_in_webpage.png' and 'LED_control_ON_state.png' for understanding.

## Conclusion

This project successfully demonstrates how to use the Bolt IoT platform to control an LED through a web interface. The steps outlined provide a clear and systematic approach to achieving the desired functionality. By following these steps, users can expand their understanding of IoT applications and control various devices remotely.
Developers are requested to use the concepts of this project as per their own project necessities. Hope this helps.

