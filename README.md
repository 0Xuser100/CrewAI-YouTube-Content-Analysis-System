# CrewAI YouTube Content Analysis System

A sophisticated AI-powered system that analyzes YouTube videos and generates blog content using CrewAI agents. This project specifically focuses on AI, Machine Learning, Deep Learning, and Data Science content from specified YouTube channels.

## 🚀 Features

- **Automated Content Research**: Extracts and analyzes video transcriptions
- **Intelligent Blog Generation**: Creates well-structured blog posts from video content
- **YouTube Channel Integration**: Currently configured for @krishnaik06 channel
- **Multi-Agent System**: Utilizes specialized agents for research and writing
- **Groq Integration**: Powered by the Gemma 2-9b-it model

## 🛠️ System Architecture

The system consists of two main agents:

### 1. Blog Researcher Agent
- Analyzes YouTube video transcriptions
- Extracts relevant information about specified topics
- Provides comprehensive research reports

### 2. Blog Writer Agent
- Transforms research into engaging blog content
- Specializes in technical storytelling
- Creates accessible explanations of complex topics

## 📋 Prerequisites

- Python 3.8+
- CrewAI library
- Groq API access
- Required Python packages (see requirements below)

## ⚙️ Installation

1. Clone the repository:
```bash
git clone  https://github.com/0Xuser100/CrewAI-YouTube-Content-Analysis-System.git
cd  CrewAI-YouTube-Content-Analysis-System
```

2. Install dependencies:
```bash
pip install crewai python-dotenv
```

3. Set up environment variables:
Create a `.env` file with:
```
GROQ_API_KEY=your_groq_api_key
```

## 📁 Project Structure

```
├── agents.py          # Agent definitions
├── tasks.py          # Task configurations
├── tools.py          # YouTube tool implementation
├── main.py           # Main execution script
└── .env              # Environment variables
```

## 🚀 Usage

1. Configure your environment variables in `.env`
2. Run the main script:
```bash
python main.py
```

The system will:
1. Research the specified topic on the YouTube channel
2. Generate a comprehensive blog post
3. Save the output to 'new-blog-posted.md'

## 🔧 Configuration

### Customizing Agents

You can modify agent parameters in `agents.py`:
- Adjust roles and goals
- Configure LLM settings
- Modify backstories
- Add or remove tools

### Task Configuration

Customize tasks in `tasks.py`:
- Modify task descriptions
- Adjust expected outputs
- Configure tool assignments
- Set execution parameters
## 🧑‍💻 Author
Mahmoud Abdelhamid  
Cairo, Egypt  
[LinkedIn](https://www.linkedin.com/in/mahmoud-abdelhamid) | [GitHub](https://github.com/mahmoud-abdelhamid)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- CrewAI framework
- Groq AI for LLM support
- Krishna's YouTube channel (@krishnaik06) for content
