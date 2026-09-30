%%writefile README.md

# 📚 Multi-Agent Study Assistant

A Generative AI-based study assistant that uses **four specialized AI agents** to help students plan their studies, understand concepts, practice through quizzes, and receive personalized performance feedback.

## 🤖 AI Agents

The system contains exactly four agents:

### 1. 🗓️ Planner Agent
Creates a personalized day-by-day study plan based on the student's topic and available preparation time.

### 2. 👨‍🏫 Teacher Agent
Explains the selected topic using simple definitions, examples, important concepts, and exam-focused points.

### 3. 📝 Quiz Agent
Generates multiple-choice questions to test the student's understanding of the topic.

### 4. 🔍 Review Agent
Analyzes the student's quiz performance, identifies weak areas, and provides personalized revision recommendations.

## 🔄 System Architecture

```text
Student
   │
   ▼
Multi-Agent Study Assistant
   │
   ├── Planner Agent
   │
   ├── Teacher Agent
   │
   ├── Quiz Agent
   │
   └── Review Agent
   │
   ▼
Personalized Study Support
