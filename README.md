## NativePinInput
Native mobile PIN input.

From a security point of view, the regular input widgets are not suitable for PIN entry, because the regular onscreen keyboard could be comprimised.

This widget uses buttons and shows the number of entered digits in a readonly text box.

## Features
- Secure PIN entry
- Configurable number of digits
- Configurable icon for the delete button
- Supports validation feedback on the attribute
- On change action
- On input complete action
- Widget styling responds to dark mode setting of the device, can also be fixed on dark/normal mode
- Two basic layouts: circle buttons and a more compact numeric keyboard layout
- Styling can easily be overruled. 

## Usage
- Your entity needs to have a string attribute for the PIN value. Integer does not work because leading zero's would be lost.
- Configure the number of digits for your situation.
- Configure the action events where appropriate.
