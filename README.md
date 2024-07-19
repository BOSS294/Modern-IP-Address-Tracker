# Modern-IP-Address-Tracker
![image](https://github.com/user-attachments/assets/d840e7d1-abd5-4735-9643-66b3287e0c67)

Features
Background Image:

Full-screen background image with background-size: cover to ensure it covers the entire viewport.
IP Address Retrieval:

Uses the fetch API to get the public IP address from https://api.ipify.org?format=json.
Displays the IP address in a SweetAlert popup.
Option to copy the IP address to the clipboard with success/error notifications.
Popup:

Detailed information on how to find the IP address.
Provides usage scenarios for an IP address.
Styled with a semi-transparent background and centered content.
Close button to dismiss the popup.
Buttons:

Two buttons: "Get IP Address" and "How to Get Your IP".
Styled with a modern look, including border-radius, hover effects, and color transitions.
Styling:

Body: Flexbox centering with a background image, no margin, and sans-serif font.
Buttons: Transparent background with white border and text, hover effects including background color change and slight elevation.
Popup: Centered on screen, semi-transparent dark background, white content box with rounded corners, shadow effects.
Popup Content: Text is styled for readability, icons used for visual enhancement.
Icons:

Material Icons from Google Fonts used for visual elements in the popup (info, check_circle).
Responsiveness:

Popup and buttons are designed to be responsive and adapt to different screen sizes.
Error Handling:

SweetAlert is used to handle and display errors if the IP retrieval fails or if the clipboard copy operation fails.
