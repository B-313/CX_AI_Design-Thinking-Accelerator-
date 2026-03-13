# CX_AI_Design-Thinking-Accelerator-
CX AI Challenge for Pharma Company

# Web Builder

## 🛠️ Agent Pipeline

| Agent | Role | Tools (Free/Local) | Trigger |
|-------|------|--------------------|---------|
| **1: Chatbot** | Assist humans | Local FAQ JS prompts, rule-based feedback (if/then scripts) | Portal Launch |
| **2: Brief Builder** | Form → Structured spec | HTML forms → JSON templates, regex validation | User input |
| **3: Code Generator** | Spec → HTML/CSS | Templated CSS/JS (Pfizer blues: #005EB8 primary), Jinja2 fills | Brief approved |
| **4: Compliance** | Scan code parallel | WCAG: achecker.ca free API or local regex (alt text, ARIA); ABPI: regex for claims/no off-label | Code ready |
| **5: Content QA** | Grammar/links parallel | LanguageTool.org free API; Linkchecker GitHub CLI | Code ready |



# Ideation 

A. The website must have a mandatory section to capture user details to customise their workspace and save progress. 
1.	User First Name and Last Name 
2.	Contact number 
3.	Employee Number 
4.	Department (for submission of website for approval) 
B. Once user details are captured, the information is saved and the webpage greets user with their first name and takes them to their workspace. 
 
C. This workspace must have : 
1.	Preliminary Questions 
2.	Prompt bar in the center 
3.	A column on the left with sections 
4.	progress bar at the top for the full task. 
5.	A notepad on the right to write, save, copy text. 
 
D. The Preliminary questions (section 1) must have selectable button like options to customise build: 
1.	Building? website or webpage 
2.	Audience? patients, healthcare providers, channel partners or internal teams 
3.	Region: Country 
4.	Language: Languages 
5.	Translation: Ai generated translation required or not for languages other than english. 

E. Prompt bar (Section 3) loads once the user confirms the Preliminary questions, the workspace loads with a prompt bar asking user input to build their website or webpage.  

F. The prompt is articulated by ai to form a brief, preliminary questions are used to personalise this brief. Then the brief is shared with user and asked to confirm whether it is what the user is looking for. This process runs on loop until the user is satisfied with the brief. Each brief is saved in history, per session like an archive.  

G. The workspace refreshes into builder (section 4): 
1.	workspace has multiple design layout options.  
2.	user can select a layout for a particular webpage. Add webpages for website etc. 
3.	These content is automatically populated into selected layout, based on the brief. 
4.	All content is editable by the user. 
5.	A preview section to view the built work (draft not pubished) 
 
H. The builder (section 4) has a grammar checker and compliance checker running in parallel to ensure the build meets company standards. 

I. The progress bar also tracks overall progress so no steps are missed.  

J. Once the website or webpage is created, confirmed by the user, there is a review button on the left (section 5). Ai makes verification checks and shares a final preview of the website/page to the the user. 

K. Once the user validates final changes, a section for Send to Review Team opens. The user checks terms and condition and then the website/ webpage is sent to the IT reviewing team. 

L. Add "Save/Load Session" in workspace. 

M. Progress bar shows % complete + Status Update.
