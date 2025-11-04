# **Ex. No. 7 – Develop a Prompt-Based Application Tailored to Personal Needs**

# **Date:** 04/11/2025

# **Register No.:** 212223060291

---

### **Aim:**

To develop a prompt-based application using **Lovable AI** — demonstrating how to create a personalized **Task Management App** that organizes daily tasks, manages reminders, and tracks progress using structured and context-aware prompt design.

---

### **Introduction**

This report presents the implementation and outcomes of the lab exercise (Ex. No. 7) focused on designing a **prompt-based Task Management Application** using **Lovable AI**, a no-code AI app creation platform.
The aim was to explore **prompt engineering techniques** to transform a general-purpose language model into a **smart personal assistant** capable of managing tasks, categorizing priorities, and scheduling reminders naturally through conversation.

This exercise helps bridge the gap between theoretical knowledge of LLMs and their **practical problem-solving applications**. By tailoring the model’s responses to specific personal requirements—such as productivity tracking and motivation—the project enhances creativity and demonstrates the power of structured prompting in real-world scenarios.

---

### **AI Tools Required**

| **Tool Category**        | **Specific Tool (Example)**     | **Requirement Details**                                                        |
| :----------------------- | :------------------------------ | :----------------------------------------------------------------------------- |
| **Primary LLM Platform** | **Lovable AI (OpenAI-based)**   | Used to design and deploy the Task Management App with a custom system prompt. |
| **Interface**            | **Lovable AI App Builder**      | Enables drag-and-drop app design integrated with AI responses.                 |
| **Supporting Tools**     | **ChatGPT / Gemini (Optional)** | For refining prompt logic and testing multi-turn dialogue flow.                |
| **Documentation**        | **Google Docs / MS Word**       | For recording procedures, outputs, and final report preparation.               |

---

### **Explanation**

The project centers on designing a **Smart Task Manager Assistant (STMA)** within Lovable AI.
Through **system-level prompts**, the assistant behaves as an intelligent planner capable of understanding commands such as *“Add meeting at 3 PM,”* *“Show today’s tasks,”* or *“Remind me to submit the report.”*

The assistant is not a conventional checklist app—it adapts its tone, remembers task context, and provides productivity feedback.

---

#### **Prompt Design Strategy**

The prompt was structured into three logical layers:

1. **Role Definition:** Assign the AI the persona of a *“Smart Productivity Assistant.”*
2. **Functional Scope:** Define its capabilities (task creation, scheduling, reminders, progress tracking).
3. **Response Format and Tone:** Ensure friendly, professional communication and bullet-style summaries.

---

#### **The Master Prompt Used in Lovable AI:**

> “You are **SmartTask**, a helpful and organized task management assistant.
> You help users create, prioritize, and track their tasks.
> Each response must include:
>
> * A friendly acknowledgment
> * A structured list of active tasks with deadlines
> * Daily productivity tips or reminders.
>   Maintain a concise, motivating tone and adapt to user’s ongoing schedule.”

---

### **Progression from Simple to Advanced Prompting**

| **Level**        | **Prompt Type**         | **Example**                                                                     | **Impact on Output**                                                      |
| :--------------- | :---------------------- | :------------------------------------------------------------------------------ | :------------------------------------------------------------------------ |
| **Simple**       | Command                 | “Add a meeting tomorrow.”                                                       | Adds a basic entry, no categorization or time tracking.                   |
| **Intermediate** | Contextual              | “Add a high-priority project review meeting at 10 AM tomorrow.”                 | Captures time, category, and urgency level.                               |
| **Advanced**     | Structured & Role-Based | “Show my pending work tasks and schedule a reminder for the report submission.” | Generates a full-day summary with priorities and reminders automatically. |

---

### **Procedure**

1. **Open Lovable AI platform.**
2. **Select “Create New App.”**
3. Assign a **system prompt** (Master Prompt) to define AI’s role.
4. Configure **UI sections**: Task List, Add Task, Reminders, Progress Overview.
5. Add **input fields and buttons** for user commands (e.g., *Add Task*, *Mark as Done*).
6. Test the assistant by giving sample prompts.
7. Observe and document outputs for simple and advanced prompt cases.

---

### **Expected Output and Analysis**

#### **Output Screens**

**Home Page:**
<img width="1323" height="922" alt="image" src="https://github.com/user-attachments/assets/e844e254-655e-4726-bb65-c6616f88f560" />
<img width="1294" height="911" alt="image" src="https://github.com/user-attachments/assets/8f3bca43-a876-4120-8eff-c973ec9f6d0f" />


**Task Entry Page:**
<img width="1301" height="874" alt="image" src="https://github.com/user-attachments/assets/a2d8f3f2-f6c2-4e15-b14b-635b426b3464" />
<img width="1293" height="438" alt="image" src="https://github.com/user-attachments/assets/1415824b-09c6-4575-b270-69ad3ea981b9" />


**Progress Dashboard:**
<img width="1295" height="922" alt="image" src="https://github.com/user-attachments/assets/50697389-8641-4064-be93-7b449a88460c" />


---

#### **Detailed Feature Breakdown:**

* **Task Manager:** Enables adding tasks with deadlines and categories (Work, Study, Personal).
* **Smart Scheduler:** Detects time conflicts and suggests alternate slots.
* **Progress Tracker:** Calculates daily completion percentage and highlights overdue tasks.
* **Motivational Feedback:** Provides short encouragement messages like *“You’ve completed 80% of your goals today — keep going!”*

---

### **Prompt Engineering Techniques Utilized**

* **Role-based Prompting:** Gave SmartTask a clear identity and purpose.
* **Context Retention:** The assistant remembers recent tasks and deadlines in session memory.
* **Constraint-based Prompting:** Used phrases like “summarize briefly” and “categorize by priority” to enforce structured responses.
* **Iterative Refinement:** Adjusted prompts to improve clarity and prevent generic replies.
* **Few-shot Guidance:** Demonstrated output formats in the initial setup for consistent replies.

---

### **Example Interactions**

**User:** “Add ‘Complete IoT project report’ as high priority due tomorrow.”
**SmartTask:**
✅ Task Added: *Complete IoT project report*
📅 Due: Tomorrow (High Priority)
💡 Tip: Block 2 hours in the evening to finish without rush.

---

**User:** “Show today’s schedule.”
**SmartTask:**
🗓️ **Today’s Tasks:**

* [✔] Attend embedded systems lecture – 9 AM
* [ ] Submit IoT report – Due 5 PM
* [ ] Call teammate for review – 6 PM
  ⚡ *Productivity Tip:* Group similar tasks together for better focus.

---

### **Conclusion**

The prompt-based Task Management App successfully demonstrated the potential of **Lovable AI** to build intelligent productivity assistants without traditional coding. By using structured and adaptive prompts, the assistant could understand natural language commands, generate organized task lists, and interact conversationally.

This experiment highlights that **LLMs can be transformed into functional personal assistants** through precise prompt engineering, improving productivity and user engagement.

---

### **Result:**

The exercise was successfully completed.
Students were able to:

* Create a working prototype of a **Task Management App** using **Lovable AI**.
* Understand and apply **prompt engineering** techniques effectively.
* Customize the app for real-world use (task organization, scheduling, reminders).
* Demonstrate creativity in adapting AI capabilities for daily personal needs.

