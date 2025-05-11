# Farmers Scheme Chatbot

**An AI-powered chatbot providing information on government schemes for farmers.**

This chatbot is designed to assist farmers by providing accurate and timely information about various government schemes. Built using the Rasa framework, it leverages Natural Language Processing (NLP) to understand user queries and deliver relevant responses.

---

## Features

- **Government Scheme Information**: Offers details about various agricultural schemes, including eligibility criteria, benefits, and application procedures.
- **Natural Language Understanding**: Utilizes Rasa's NLU capabilities to comprehend user intents and extract relevant entities.
- **Custom Actions**: Implements custom actions to fetch and present dynamic information based on user queries.
- **Multilingual Support**: Capable of understanding and responding in multiple languages to cater to a diverse user base.
- **Interactive Conversations**: Engages users in a conversational manner, ensuring a user-friendly experience.

---

## Tech Stack

- **Framework**: [Rasa](https://rasa.com/)
- **Programming Language**: Python
- **NLP Libraries**: spaCy
- **Deployment**: Compatible with various platforms supporting Python applications

---

## Project Structure

```
Farmers_scheme_chatbot/
├── actions/                # Custom action scripts
├── data/                   # Training data for NLU and stories
├── models/                 # Trained Rasa models
├── tests/                  # Test cases for the chatbot
├── config.yml              # Model configuration
├── credentials.yml         # Credentials for external services
├── domain.yml              # Domain definition including intents, entities, slots, and responses
├── endpoints.yml           # Configuration for action endpoints
├── final_mini_project_report.pdf  # Comprehensive project report
└── README.md               # Project documentation
```

---

## Installation

1. **Clone the repository**:

```bash
git clone https://github.com/SudharsaaX/Farmers_scheme_chatbot.git
cd Farmers_scheme_chatbot
```

2. **Create and activate a virtual environment**:

```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On Unix or macOS
source venv/bin/activate
```

3. **Install the required packages**:

```bash
pip install -r requirements.txt
```

*Note: Ensure that you have Python 3.7 or higher installed.*

---

## Usage

1. **Train the model**:

```bash
rasa train
```

2. **Run the action server**:

```bash
rasa run actions
```

3. **Start the chatbot**:

```bash
rasa shell
```

*The chatbot is now ready to interact. Type your queries to receive information about various government schemes.*

---

## Testing

To run the test cases and ensure the chatbot's functionalities are working as expected:

```bash
rasa test
```

---

## Project Report

For a detailed understanding of the project's objectives, design, implementation, and results, please refer to the comprehensive project report:

[final_mini_project_report.pdf](https://github.com/SudharsaaX/Farmers_scheme_chatbot/blob/main/final_mini_project_report.pdf)

---

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:

```bash
git checkout -b feature/YourFeature
```

3. **Commit your changes**:

```bash
git commit -m "Add YourFeature"
```

4. **Push to the branch**:

```bash
git push origin feature/YourFeature
```

5. **Open a Pull Request**.

---

## Acknowledgments

Special thanks to [@Tamil157](https://github.com/Tamil157) for valuable support and contributions to this project.
