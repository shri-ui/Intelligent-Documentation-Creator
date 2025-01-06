# Intelligent-Documentation-Creator


To create a unique README file for the same project, I will rephrase the content, reformat sections, and adjust the structure while retaining the original essence. Here's a rewritten version:

---

# 🧠 Intelligent Documentation Creator  

## Overview  

The **Intelligent Documentation Creator** is an innovative AI-driven solution tailored to simplify and automate software documentation processes. By analyzing source code and its architecture, this tool produces well-organized documentation, featuring summaries, technology breakdowns, dependencies, and detailed component analyses.  

---

## 🛠️ Problem Space  

### 🚧 The Issues  

Creating and managing accurate documentation for software projects presents numerous hurdles:  

- **⏳ Labor-Intensive**: Crafting detailed documentation for complex projects is time-consuming.  
- **🔀 Inconsistency**: Lack of standardization often leads to uneven quality and structure in documentation.  
- **💡 Knowledge Bottlenecks**: Important information can remain siloed, limiting team productivity.  
- **🏃‍♂️ Onboarding Hurdles**: Inadequate documentation hampers new members' understanding of the project.  

### 🚀 Our Solution  

The **Intelligent Documentation Creator** addresses these concerns through:  

- **⏱️ Efficiency**: Automating the generation process to save valuable time.  
- **📝 Standardization**: Producing uniform, high-quality documentation.  
- **🌐 Knowledge Sharing**: Documenting the entire codebase to eliminate information gaps.  
- **📈 Accelerated Onboarding**: Equipping teams with accessible and organized documentation.  

---

## ✨ Features  

- **📄 Instant Documentation**: Drag, drop, and document your project in seconds.  
- **🤖 AI Insights**: Leverages AI for insightful analysis of codebases.  
- **🌎 Multi-Language Support**: Compatible with Python, JavaScript, Java, and more.  
- **🔍 Comprehensive Reports**: Covers technologies, dependencies, and code summaries.  

---

## 📖 How to Use  

1. **Upload**: Submit your project files via the interface.  
2. **Analyze**: Allow the tool to analyze and compile structured documentation.  
3. **Download or Share**: Export the documentation for distribution or personal use.  

---
## 🚀 Images and Previews  

1. ![User Interface](images/ui_overview.png)  
   *This image shows the user interface of the Documentation Generator tool, where users can upload their project folders to generate comprehensive documentation.*  

2. ![Projects Section](images/projects_section.png)  
   *This image showcases the "Projects" section of the Documentation Generator tool. It displays a list of uploaded projects, each with its name, status, and action buttons. The user can view or delete each project from this interface.*  

3. ![Generated Documentation](images/generated_docs.png)  
   *This image shows the generated documentation for the "project-genai-cold-email-generator-main" project. It provides a detailed overview of the project, including its key features, technical details, and main components.*  

4. ![Technologies and Dependencies](images/tech_and_dependencies.png)  
   *This image displays the "Technologies Used" and "Dependencies" sections of the generated documentation for the "project-genai-cold-email-generator-main" project. It provides a detailed breakdown of the programming languages, frameworks, tools, libraries, and dependencies used in the project.*  

5. ![Functions and Classes Breakdown](images/functions_classes_breakdown.png)  
   *This image provides a detailed breakdown of the file's functions and classes, including their parameters and purposes. Additionally, it highlights the absence of documentation for some functions and classes, suggesting potential areas for improvement in the future.*  

6. ![Code Metrics Analysis](images/code_metrics_analysis.png)  
   *This image provides a detailed breakdown of the code's metrics, including the number of lines of code, comments, and documentation coverage. Additionally, it offers recommendations for improvement, such as optimizing the code, increasing commenting, and creating documentation.*  

---

## 🔧 Tech Stack  

### Frontend:  
- React.js  
- Material UI  
- JavaScript  

### Backend:  
- Python  
- FastAPI  
- Google Gemini AI  
- LangChain  

### Additional Tools:  
- Git  
- Node.js  
- npm/yarn  

---

## 🏁 Getting Started  

### Prerequisites  

Ensure the following are installed:  
- Python (v3.8 or newer)  
- Node.js (v16 or newer)  
- npm or yarn  
- Google Cloud API Key  

### Steps  

#### Clone and Navigate  

```bash
git clone https://github.com/shri-ui/Intelligent-Documentation-Creator.git
cd AI-Powered
```

#### Backend Setup  

1. Go to the `backend` directory:  
   ```bash
   cd backend
   ```

2. Create and activate a virtual environment:  
   ```bash
   python -m venv venv  
   source venv/bin/activate  # For Linux/macOS  
   venv\Scripts\activate     # For Windows  
   ```

3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

4. Add a `.env` file with your API key:  
   ```
   GOOGLE_API_KEY=your_api_key
   ```

5. Start the backend server:  
   ```bash
   uvicorn app.main:app --reload
   ```

#### Frontend Setup  

1. Navigate to the `frontend` directory:  
   ```bash
   cd frontend
   ```

2. Install dependencies:  
   ```bash
   npm install
   ```

3. Launch the frontend:  
   ```bash
   npm run dev
   ```

Access the tool at:  
- **Frontend**: [http://localhost:5173](http://localhost:5173)  
- **Backend API**: [http://localhost:8000](http://localhost:8000)  

---

## Conclusion  

The **Intelligent Documentation Creator** revolutionizes project documentation by automating repetitive tasks, promoting standardization, and bridging knowledge gaps. Its powerful AI capabilities make it an essential tool for modern software development teams.  

---
