## **Information**

This project was designed to display in real time the amount raised on an Ulule project during a Twitch stream via OBS.

## **Setup**
### **Server**

- NodeJS is required to create a proxy server, and is zipped directly into the `nodejs` folder so it doesn't need to be downloaded
- `CORS` add headers to the proxied request, it is neccesary for the tool to function (see [CORS Anywhere GitHub](https://github.com/Rob--W/cors-anywhere) for more information)
- Unzip these two fodlers next to the .bat file
- Start `start_server.bat` to launch a local server, it needs to stay open as long as the tool is needed
  
### **proxy.html**

- the Ulule API key is located in the confidentiality section of the account settings
- the project slug is the name of the project, it can be found at the end of the URL of the project page concerned
- it is possible to change the font and the background image by placing them in their corresponding folders and changing the path at the top of the script
- the refresh rate can be changed at the end of the script

## **Example**

<img src="https://github.com/user-attachments/assets/18305e44-8788-42d5-b0d9-4eb1648dbeee" width=40% height=40%>
