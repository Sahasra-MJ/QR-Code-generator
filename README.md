# QR-Code-generator
A simple and responsive QR Code Generator built using HTML, CSS, and JavaScript. This project allows users to enter any text or URL and instantly generate a QR code that can be scanned with any device.

![Screenshot 2025-06-29 094557](https://github.com/user-attachments/assets/6599c25d-0f3f-45cd-b1df-481c7aa08b88)

![Screenshot 2025-06-29 094612](https://github.com/user-attachments/assets/87b0873b-ca43-474c-9b5d-b7c7c33a84c2)

🚀 Features

  ✅ Generates QR code in real-time
  
  ✅ Works for text, URLs, contact info, etc.
  
  ✅ Simple and responsive UI
  
  ✅ Error handling for empty input
  
  ✅ QR code appears with smooth transition

🛠️ Technologies Used

  HTML – Markup structure
  
  CSS – Styling and animations
  
  JavaScript – Logic for QR generation and validation

🔗 API Used

  This project uses the QR Code Generator API by goqr.me:

      "https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=Example";
  It generates a 150x150 QR image with the input data.
  
  No API key required — works instantly and is free to use.

📸 How It Works

  User types input into the text box
  
  On clicking Generate, the QR code is fetched using the API
  
  If the input is empty, an error animation is shown
  
  The QR image appears in a styled box
