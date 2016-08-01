# Instamojo Opencart Payment Gateway Plugin


## Download:

Download the latest Instamojo-OpenCart-2.x.ocmod.zip from the [releases section](https://github.com/Instamojo/Instamojo-OpenCart-2.0/releases) or download it from the [OpenCart Extensions website](http://www.opencart.com/index.php?route=extension/extension/info&extension_id=21984).

## Installation

#### Automatic Installation
1. Go to Extensions > Extension installer.
2. Click on upload and select Instamojo-OpenCart-2.x.ocmod.zip from your download directory
3. Click on Continue button. 
4. You will get the success notification if extension properly installed.

***Note: if automatic installation fails you can try further manual installation steps.***

***
#### Manual Installation:

1.  Copy the contents of `upload` directory(the folders inside upload directory in plugin) into your OpenCart installation root directory **(No files are going to be overwritten)**.

2. Navigate to Extensions > Payment from admin panel menu.
3. Look for the Instamojo in Payment List.
4. Click on green Install button(the button have + icon).
***

## Configuration
1. After installation click on edit button corresponding to Instamojo module(the button have pencil icon).
2. Fill the following details:

    - **Order Status :** This is the order of the status that you would like to set after a successful payment.

    -  **Checkout Label:** This is the label users will see during checkout, its default value is "Pay using Instamojo". You can change it to something more generic like "Pay using Credit/Debit Card or Online Banking".
      
    -  **Status:** This is the current status of the module. To use Instamojo during checkout make sure to change it to enabled.
     
    - **Client Secret And Client ID** will be available on your Instamojo account.
    
    - **Test Mode:** If enabled you can use our [Sandbox environment](https://test.instamojo.com) to test payments. Note that in this case you should use `Client Secret` and `Client ID` from the test account not production.

***
