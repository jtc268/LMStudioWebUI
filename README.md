# LM Studio Web UI

A simple web interface for interacting with an LM Studio API server. This fork is pre-configured to connect to a publicly hosted LM Studio instance.

## Features

- Dark mode interface with purple theme
- Connect to any LM Studio server
- Save and manage multiple chat conversations
- LaTeX Math and Markdown rendering
- Code highlighting with copy-to-clipboard functionality
- Image upload support for multimodal models
- Mobile-friendly design

## Deployment on Vercel

This project can be easily deployed on Vercel for free. Just click the button below:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fjtc268%2FLMStudioWebUI)

## Usage

1. Visit the deployed website
2. The interface will automatically attempt to connect to the pre-configured LM Studio server (66.65.96.63:1234)
3. Once connected, you can start chatting with the AI
4. You can create multiple chat sessions using the sidebar
5. Right-click on chat sessions to delete them

## Screenshots 📸
![image](https://github.com/user-attachments/assets/7944a30a-6e52-467b-bf27-309f8db0bfde)
![image](https://github.com/user-attachments/assets/cecc2e50-1583-4ce6-a092-10adcb2359f3)
![image](https://github.com/user-attachments/assets/717bb8c6-ff62-4574-95e4-146909302180)
![image](https://github.com/user-attachments/assets/22275a46-f332-4ab9-b727-678a98aef7af)
![image](https://github.com/user-attachments/assets/d7cba468-166b-4d74-a98a-37ca72093b83)

## Connecting to a Different Server

If you want to connect to a different LM Studio server:

1. Click "Disconnect" if currently connected
2. Enter the new server URL (e.g., `http://localhost:1234` for local server)
3. Click "Connect"

## Local Development

To run this locally:

1. Clone the repository
2. Open `index.html` in a web browser

## Troubleshooting

- **Can't connect to server**: 
  - Ensure LM Studio Server is running on your computer.
  - Check that you're using the correct server address.
  - If accessing from another device, make sure both devices are on the same network.

- **Slow responses**: 
  - LM Studio processing speed depends on your computer's capabilities. Larger models may take longer to respond.

- **Interface not loading**: 
  - Try opening the `index.html` file with a different web browser.

## Security Note

This interface is designed for accessing your LM Studio server from a web browser. If you expose your LM Studio server to the public internet, consider implementing appropriate security measures to prevent misuse.

## Credits

This is a fork of [YorkieDev/LMStudioWebUI](https://github.com/YorkieDev/LMStudioWebUI) with modifications to connect to a publicly accessible LM Studio instance.