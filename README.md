## 📘 Skill Share Hub – Learning Plan Module

**🎯 Role:** Full-Stack Developer (Learning Plan Feature)
**🛠️ Technologies:** Spring Boot (Java), React.js
**🔧 Tools:** Visual Studio Code

### 📄 Description:

Developed the **Learning Plan Module** for Skill Share Hab, enabling users to create, manage, and track personalized learning plans with rich content and visual progress tracking.

### 🔧 Backend Features (Spring Boot):

* Implemented RESTful APIs to support **CRUD operations** (Create, Read, Update, Delete) for learning plans.
* Stored plans in a `"Learning Plans"` collection with metadata such as title, description, duration, and image.
* Enforced **user-level access control** – only the plan creator can edit or delete their learning plans.
* Integrated **user-specific tracking** for plan progress: `Read`, `Completed`, and `Incomplete`.

### 💻 Frontend Features (React.js):

* Designed and developed a responsive interface to:

  * Create new learning plans.
  * Track progress in real-time.
  * Conditionally render edit/delete buttons based on user ownership.
* Included **status filtering**, **visual progress indicators**, and **intuitive navigation** for better usability.

### ✅ Key Functionalities:

* 📘 Create & customize learning plans with title, content, duration, and image.
* 🔁 Track user progress for each learning plan (`Read`, `Completed`, `Incomplete`).
* 👤 Display only the owner’s plans with edit/delete rights.
* 🎯 Filter plans based on progress status for personalized dashboards.
* 📊 Real-time UI updates for a seamless experience.
