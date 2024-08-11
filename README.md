# ReachInbox-Assignment 

Gmail service web app built with **Vite**, **React**, **Redux**, and **Tailwind CSS**. This application offers a sleek user experience with features like login, data management, keyboard shortcuts, a custom text editor, and seamless light/dark mode switching.
Login using google.




### 1. **Clone the Repository**
   ```bash
   git clone https://github.com/saadakbar1/ReachInbox.git
   cd reachinbox-assinment


2. Install dependencies:
  
   npm install
  

3. Run the development server on http://localhost:5173/
 
   npm run dev


4. Build for production:
  
   npm run build
   

5. Preview the production build**:
  
   npm run preview
 

## API Endpoints

- **Fetch Onebox List**: 
  - Method: `GET`
  - Endpoint: `/onebox/list`

- **Fetch Thread Details**: 
  - Method: `GET`
  - Endpoint: `/onebox/:thread_id`

- **Delete Thread**: 
  - Method: `DELETE`
  - Endpoint: `/onebox/:thread_id`

- **Send Reply**: 
  - Method: `POST`
  - Endpoint: `/reply/:thread_id`
  - Payload:
    ```json
    {
      "from": "email",
      "to": "email",
      "subject": "",
      "body": "<html></html>"
    }
    ```

The app supports both light and dark modes.

