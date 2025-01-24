![image](https://github.com/user-attachments/assets/c1cd8a5d-ca8c-4b4e-94fa-02d761231c0c)# Email Template Editor
This is an email template editor where users can create and customize email templates with a rich-text editor, upload images, and save the configuration. It includes a backend for saving templates and images to the server.

# HOW To execute 
1. Go to Backend Directory:  cd backend
2. Run the Backend Server: node server.js
3. Go to Frontend Directory (in a new terminal window): cd frontend
4. Run the React App: npm start

Now, the backend is running on http://localhost:3000, and the frontend is running on http://localhost:3001.


Technologies Used
- List the technologies, frameworks, libraries, and tools you used in the project.
Technologies Used
- Frontend : React, React Quill (rich text editor), React Dropzone (for image upload)
- Backend: Node.js, Express, Multer (file upload)
- Database : (if applicable)
- Others : CORS (for cross-origin requests)**


## Usage

1. Open the web application in your browser.
2. You can input the title, content, and footer for your email template.
3. Use the drag-and-drop uploader to add an image to the template.
4. Once you're done, you can click the "Save Template" button to store the template data.

The email template can be previewed in real-time.


## Acknowledgments
- Thanks to [React](https://reactjs.org/) for the frontend framework.
- Thanks to [Express](https://expressjs.com/) for the backend framework.
- Thanks to [Multer](https://www.npmjs.com/package/multer) for the file upload library.


Screenshots

![image](https://github.com/user-attachments/assets/9305dd89-23c8-4d63-8ac4-6532dbcd7042)
![image](https://github.com/user-attachments/assets/59806909-daa6-4165-8504-13fac970a832)
![image](https://github.com/user-attachments/assets/726db801-776c-4deb-9042-17072b22e895)
![image](https://github.com/user-attachments/assets/9ae15ef0-d1e4-4d89-acf3-a1b3cf994cd0)


Data Storage
📂 Uploads Folder
All uploaded images are stored in the uploads folder. The images are saved with unique names to avoid overwriting.

📄 JSON Configuration
The email content and configuration are saved in a emailConfig.json file, keeping all your template settings organized.






