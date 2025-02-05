### **AI Code Editor: A Smart Web-Based IDE**  

The **AI Code Editor** is a web-based **IDE** that integrates **AI-powered assistance** for seamless development. It supports **intelligent code generation, live execution, and structured project management**—all within the browser.  

### **Key Features**  
- **AI Assistance** – Uses **Claude 3 (Sonnet)** for **code generation, debugging, and guidance**.  
- **Project Templates** – Automatically sets up **React or Node.js** projects.  
- **Live Code Editor** – Real-time coding with **syntax highlighting**.  
- **File Explorer & Live Preview** – Manage project files and preview applications instantly.  
- **Tab-Based Interface** – Switch between **code, preview, and project settings**.  
- **Guided Development** – Step-by-step process for building applications.  

### **Architecture**  
- **Frontend:** React (TypeScript)  
- **Backend:** Node.js/Express with **Claude AI integration**  
- **Execution:** **WebContainer API** for in-browser runtime  

### **Core Components**  
- **Builder** – Main coding workspace  
- **FileExplorer** – Manages files  
- **CodeEditor** – AI-powered editor  
- **PreviewFrame** – Live preview  
- **StepsList** – Guides project steps  

### **Backend Services**  
- `/template` – Generates project templates  
- `/chat` – AI-powered coding assistance  
- **CORS enabled** for secure API requests  

### **Technical Stack**  
- **React (TypeScript)** for frontend  
- **Express.js** backend  
- **Claude AI** for code generation  
- **WebContainer API** for live execution  
- **Axios & React Router** for API & navigation  

### **How to Run the Project**  

#### **1. Clone the Repository:**  
```bash
git clone https://github.com/your-repo/ai-code-editor.git
cd ai-code-editor
```

#### **2. Install Dependencies:**  
```bash
npm install
```

#### **3. Start the Backend:**  
```bash
cd backend
npm install
npm run dev
```

#### **4. Start the Frontend:**  
```bash
cd frontend
npm install
npm start
```

The project will be available at `http://localhost:3000`.
