Text-to-Math Problem Solver with Google Gemma 2 LLM Integration

## Table of Contents
1. [Project Title](#project-title)
2. [Project Description](#project-description)
3. [Key Features](#key-features)
4. [Tech Stack](#tech-stack)
5. [Setup Instructions](#setup-instructions)
    - [Prerequisites](#prerequisites)
    - [Installation Steps](#installation-steps)
6. [Usage](#usage)
7. [File Structure](#file-structure)
8. [Future Enhancements](#future-enhancements)
9. [License](#license)
10. [Contributors](#contributors)
11. [Acknowledgments](#acknowledgments)

---

## Project Title
**Text-to-Math Problem Solver with Google Gemma 2 LLM Integration**

---

## Project Description
This project is an AI-powered **Text-to-Math Problem Solver** and **Data Search Assistant** built using **Streamlit** and **Google Gemma 2 LLM**. It enables users to input natural language questions and receive detailed, step-by-step answers to mathematical and reasoning-based problems. Additionally, it integrates tools like **Wikipedia** for retrieving external data and a reasoning tool for logic-based problem-solving, creating a comprehensive problem-solving assistant.

---

## Key Features
1. **Mathematical Problem Solving**:
   - Uses Google Gemma 2 LLM to solve complex math problems step-by-step with detailed explanations.

2. **Reasoning and Logic Tool**:
   - Provides reasoning-based solutions for logic-oriented questions.

3. **Wikipedia Integration**:
   - Retrieves relevant information on topics using Wikipedia API for enhanced context.

4. **User-Friendly Interface**:
   - Built with Streamlit for an interactive, intuitive experience.

5. **Agent-Based Architecture**:
   - Combines multiple tools (math chain, reasoning chain, Wikipedia search) into a seamless assistant agent.

6. **Chat-Like Interaction**:
   - Maintains session-based chat history for a conversational experience.

---

## Tech Stack
- **Frontend**: Streamlit
- **Backend**: Python
- **AI Model**: Google Gemma 2 LLM
- **Tools**:
  - Wikipedia API Wrapper
  - LangChain Agents and Chains
- **Libraries**:
  - `streamlit`
  - `langchain`
  - `langchain_groq`

---

## Setup Instructions

### Prerequisites
1. Install Python 3.8 or later.
2. Obtain a **Groq API Key** for Google Gemma 2 LLM.
3. Ensure the following Python libraries are installed:
   - `streamlit`
   - `langchain`
   - `langchain_groq`

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/text-to-math-solver.git
   cd text-to-math-solver
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variables:
   - Add your **Groq API Key** in the application when prompted.

4. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage
1. **Start the Application**:
   - Launch the app using Streamlit.
   - Open the provided local server URL in your browser.

2. **Enter a Math Problem**:
   - Type a question in the text box (e.g., *"What is the sum of 5 and 7?"*).
   - Click the **Find my answer** button.

3. **View Results**:
   - The app will display a step-by-step solution or reasoning-based response.
   - For data-related queries, it fetches information from Wikipedia.

4. **Chat History**:
   - Interact with the assistant in a conversational style with session-based chat persistence.

---

## File Structure
```
├── app.py                # Main application script
├── requirements.txt      # Required libraries
├── README.md             # Project documentation
```

---

## Future Enhancements
1. **Advanced Data Search**:
   - Integrate additional APIs for broader data search capabilities.

2. **Expanded Reasoning Tool**:
   - Include tools for solving puzzles and more complex reasoning problems.

3. **Multilingual Support**:
   - Allow users to input questions in different languages.

4. **Mobile-Friendly UI**:
   - Enhance the Streamlit interface for better mobile compatibility.

5. **Cloud Hosting**:
   - Deploy the application on cloud platforms for wider accessibility.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contributors
- **Rishikesh**  
- LinkedIn: www.linkedin.com/in/rishikesh-a12090285
- Email: rishikesh23@kgpian.iitkgp.ac.in

---

## Acknowledgments
- [Google Gemma 2 LLM](https://groq.com)
- [LangChain](https://langchain.com)
- [Streamlit](https://streamlit.io)
