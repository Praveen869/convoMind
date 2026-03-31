# ConvoMind AI 🤖

ConvoMind AI is a modern, responsive, and highly interactive AI chatbot application built with Django and powered by AI via the OpenRouter API. It features a premium dark-mode SaaS aesthetic, customizable AI personas, and smooth message handling.

---

## 📸 Screenshots

*(Add your screenshots here! Simply take screenshots of your app, place them in your repository, and update the paths below)*

| Main Chat Interface | AI Persona Settings |
|:---:|:---:|
| <img src="https://via.placeholder.com/600x400/181920/a855f7?text=Chat+Interface+Screenshot" width="400" alt="Main Interface" /> | <img src="https://via.placeholder.com/600x400/1f212a/a855f7?text=Sidebar+Settings+Screenshot" width="400" alt="Sidebar Settings" /> |

---

## ✨ Features

- **Premium UI/UX:** Sleek dark-mode design, centered floating interface, and modern typography (using the Inter font).
- **Customizable AI Roles:** Choose from pre-configured personas (Storyteller, Professor, Travel Guide, Tech Architect) or write your own custom system instructions on the fly.
- **Responsive Layout:** Beautiful pill-shaped inputs, glowing focus states, and seamless mobile scaling.
- **Secure Backend:** A Django-powered Python backend acting as a secure proxy to the AI API, completely hiding and protecting your API keys from the frontend client.

## 🚀 Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites
- Python 3.8+
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Praveen869/convoMind.git
   cd convoMind
   ```

2. **Create and activate a virtual environment:**
   ```bash
   # On Windows
   python -m venv venv
   venv\Scripts\activate
   
   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure your Environment Variables:**
   Create a new file named `.env` in the root directory (alongside `manage.py`) and add the following keys securely:
   ```env
   OPENROUTER_API_KEY="your_openrouter_api_key_here"
   SECRET_KEY="your_secure_django_secret_key"
   DEBUG=True
   ```

5. **Apply Database Migrations:**
   *(Since the local local database is ignored by git, you'll need to create a fresh one)*
   ```bash
   python manage.py migrate
   ```

6. **Start the Development Server:**
   ```bash
   python manage.py runserver
   ```
   
   **That's it!** Open your web browser and navigate to `http://127.0.0.1:8000` to start chatting!

## 🛠️ Technology Stack
- **Frontend:** Pure HTML5, Vanilla CSS3 (CSS Variables, Flexbox), JavaScript, [Phosphor Icons](https://phosphoricons.com/)
- **Backend:** Python, Django
- **AI Integration:** OpenRouter API 

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
