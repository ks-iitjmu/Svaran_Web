# Svaran: IIT Jammu Chatbot

Svaran is a smart chatbot designed to assist IIT Jammu students, faculty, and visitors by providing instant and accurate information. Built using cutting-edge technologies, Svaran aims to bridge the information gap and enhance the user experience on campus.

## Features
- **Natural Language Understanding**: Powered by RASA for advanced conversational AI.
- **Comprehensive Information**: Covers topics like library policies, faculty details, academic schedules, and more.
- **User-Friendly Interface**: Built with React and TypeScript for a responsive and intuitive frontend.
- **Secure and Private**: Ensures user data privacy with no storage or retention of prompts.

## Technologies Used
### Backend
- **RASA**: For natural language processing and dialogue management.
- **Python**: Backend logic and integration.

### Frontend
- **React**: For building the user interface.
- **TypeScript**: Ensures type safety and better code quality.
- **CSS3**: For styling and animations.
- **Vite**: For fast development and optimized builds.

## Installation
### Prerequisites
- Node.js and npm installed.
- Python 3.10.
- Virtual environment setup (optional but recommended).

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Svaran_Web
   ```

2. Set up the backend:
   ```bash
   cd backend
   python3 -m venv myvenv
   source myvenv/bin/activate  # On Windows: myvenv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Set up the frontend:
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

4. Run the backend server:
   ```bash
   cd ../backend
   rasa run --enable-api
   ```

5. Access the application:
   Open your browser and navigate to `http://localhost:3000`.

## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push to your fork.
4. Submit a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For suggestions or feedback, reach out to us at [chatbot-support@iitjammu.ac.in](mailto:chatbot-support@iitjammu.ac.in).