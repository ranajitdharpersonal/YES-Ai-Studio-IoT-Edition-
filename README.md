# 🌟 YES Ai Studio: Agentic Multimodal Creator (IoT Edition)

> **Tuya AI Innovators Hackathon 2025 Submission** > **Track:** AI Agent Application  
> **Author:** Ranajit Dhar  

---

## 📺 Demo Video
**[👉 CLICK HERE TO WATCH THE PROJECT DEMO VIDEO](TOMAR_YOUTUBE_LINK_EKHANE_DAO)** *(Please click the link above to see the Autonomous AI Agent controlling the Tuya IoT Device in action!)*

---

## 📖 Complete Project Description

### **The Problem**
Traditional IoT systems are passive. They wait for human commands (e.g., "Alexa, turn on the lights"). They lack context, reasoning, and the ability to evaluate the quality of work. There is a disconnect between **Generative AI** (Creative Brain) and **Smart Hardware** (Physical Body).

### **The Solution: YES Ai Studio**
**YES Ai Studio** is a fully autonomous **Agentic AI System** that bridges this gap. It doesn't just generate content; it evaluates its own output quality and autonomously controls the physical environment (Studio Lighting) based on that evaluation.

**Target Users:** Smart Studio Owners, AI Developers, Content Creators, and Smart Home Enthusiasts who want logic-based automation.

---

## 🏗️ Design Principles & Architecture

The system follows a **Multi-Agent Architecture** where specialized AI agents collaborate to perform a task, culminating in a physical action via the **Tuya Cloud Bridge**.

### **System Architecture Diagram**
*(Upload your diagram image here by dragging & dropping it into the GitHub editor)*

**Workflow:**
1.  **🧭 Navigator Agent:** Plans the project workflow & researches trends (using Google Gemini).
2.  **🎨 Curator Agent:** Generates creative content (Social Media Posts, Image Prompts).
3.  **⚖️ Evaluator Agent:** Critically reviews the content and assigns a **Quality Score (1-10)**.
4.  **🔌 Tuya IoT Bridge:** The Logic Layer that connects the AI Brain to Tuya Cloud.
    * **IF Score ≥ 8:** ✅ High Quality -> **Turn ON Studio Light** (Green Signal).
    * **IF Score < 8:** 📉 Low Quality -> **Turn OFF Light** (Power Save Mode).

---

## 🛠️ Hardware & Tech Stack

### **Hardware List**
Since this is a Cloud-Native AI Agent, it is designed to be hardware-agnostic. For this hackathon demonstration, we used:
* **Device:** Tuya Virtual Wi-Fi Switch (Simulating a Smart Studio Light).
* **Connection:** TuyaOpen API (Cloud-to-Cloud).

*Note: This code works instantly with ANY physical Tuya-enabled Switch, Bulb, or Socket.*

### **Software Stack**
* **AI Core:** Google Gemini 2.5 Flash (via Kaggle).
* **IoT Platform:** Tuya Developer Platform (TuyaOpen API).
* **SDK:** `tuya-connector-python`.
* **Validation:** Pydantic (for Structured JSON Outputs).

---

## 🚀 How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/ranajitdharpersonal/-YES-Ai-Studio-Agentic-Multimodal-Creator-Capstone-Edition-](https://github.com/ranajitdharpersonal/-YES-Ai-Studio-Agentic-Multimodal-Creator-Capstone-Edition-)
    ```
2.  **Install Dependencies:**
    ```bash
    pip install tuya-connector-python google-genai pandas pydantic
    ```
3.  **Set Credentials:**
    Add your `TUYA_ACCESS_ID`, `TUYA_ACCESS_SECRET`, and `GOOGLE_API_KEY` in the notebook secrets.
4.  **Run the Notebook:**
    Execute the cells in order. The Agent will plan, create, evaluate, and finally control the virtual device based on the score.

---

### ❤️ Acknowledgements
Special thanks to **Tuya Smart** for the robust IoT API and **Google** for the Gemini AI models.
