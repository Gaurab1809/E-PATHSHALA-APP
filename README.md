<!-- Logo on top --> 
<p align="center"> 
  <img src="Images/logo.png" alt="E-PATHSHALA Logo" width="600"/> 
</p> 

<!-- Title --> 
<h1 align="center"> 
  <span style="color:blue; font-size:36px; font-weight:bold;">📚 E-PATHSHALA – Smart E-Learning Platform</span> 
</h1> 
<h3 align="center"> 
  <b style="color:purple;">🎓 A Modern Android-Based Learning System for Accessible, Personalized & Interactive Education</b> 
</h3> 

<p align="center"> 
  <img src="https://img.shields.io/badge/Platform-Android-blue?style=for-the-badge"> 
  <img src="https://img.shields.io/badge/Language-Java-orange?style=for-the-badge"> 
  <img src="https://img.shields.io/badge/Backend-Firebase-yellow?style=for-the-badge"> 
  <img src="https://img.shields.io/badge/Database-Firestore-brightgreen?style=for-the-badge"> 
</p> 
  
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 

<!-- Abstract --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=📌%20Abstract&fontSize=32&width=1200&height=130&color=0:9D50BB,100:6E48AA" width="100%">

E-PATHSHALA is an Android-based e-learning platform designed to make education accessible, flexible, and engaging for learners of all ages.

The platform leverages modern technologies like Firebase and native Android development to provide seamless access to courses, interactive tools, and personalized learning experiences.

It bridges the gap between traditional education and digital learning, offering both self-paced and instructor-guided learning environments.

Keywords: E-learning, Android app, Firebase, digital education, personalized learning, online courses, AI assistant.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Introduction --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=📖%20Introduction&fontSize=32&width=1200&height=130&color=0:9D50BB,100:6E48AA" width="100%">

In today’s digital era, access to quality education is often limited by geographical, financial, and infrastructural barriers.

E-PATHSHALA addresses these challenges by providing:

🌍 Learning from anywhere  
💰 Affordable education options  
📱 Mobile-first accessibility  
🎯 Personalized learning experience  

It creates a unified environment where students and educators can connect, learn, and grow efficiently.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Objectives --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=🎯%20Objectives&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

📚 Provide quality education accessible worldwide  
🎨 Enable personalized learning experiences  
🔗 Combine traditional teaching with digital tools  
👨‍🏫 Empower educators with course creation & management tools  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Feasibility --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=📊%20Feasibility%20Study&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

### ⚙️ Technical Feasibility  
- 📱 Android Studio (Java) for native development  
- 🎨 XML for UI design  
- ☁️ Firebase for backend services  
- 🗄️ Firestore / Realtime DB for data storage  
- 🔐 Firebase Authentication for security  

### 💰 Economic Feasibility  
- 💵 Low initial development cost  
- 📦 Revenue via subscriptions & paid courses  
- 🤝 Collaboration with institutions  
- 📈 Scalable for long-term profitability  

### 🧩 Operational Feasibility  
- ✅ User-friendly interface  
- ⚡ Smooth performance  
- 🔐 Secure authentication & data handling  
- 👥 Clearly defined roles for users & instructors  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


<!-- Use Case Diagram --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=🔄%20Use%20Case%20Diagram&fontSize=32&height=120&color=0:FC5C7D,100:FF416C" width="100%"/>

<p align="center">
  <img src="android_usecase.png" width="700"/>
</p>

## 👥 Actors

1. 🌐 Visitor  
2. 🧑‍💻 Member  
3. 👨‍🏫 Instructor  

---

## 📖 Actor Descriptions

### 🌐 Visitor
A **non-registered user** who can access limited features of the platform.  
Visitors primarily explore the system before creating an account.

**Capabilities:**
- View course list  
- Browse popular courses  
- Access Kids Zone  
- Register and login  

---

### 🧑‍💻 Member
A **registered learner** who can access the platform’s full functionalities.  

**Capabilities:**
- Search courses  
- Enroll in courses  
- Upload course materials  
- Participate in discussions  
- Use chat system (real-time)  
- Access AI assistant (ChatGPT)  
- Browse content  
- View enrolled courses  
- Manage profile  

---

### 👨‍🏫 Instructor
A **registered content contributor** who can manage courses and monitor learners.  

**Capabilities:**
- Create and manage courses  
- Upload learning materials  
- Track student progress  
- Manage discussions & chat  
- Use AI assistant (ChatGPT)  

---

## 📌 Use Cases

### 🌐 Visitor Use Cases
1. Registration  
2. Login  
3. View Course List  
4. Popular Courses  
5. Kids Zone  

---

### 🧑‍💻 Member Use Cases
1. Search Courses  
2. Enroll in Courses  
3. Upload Course Material  
4. Discussion  
5. Chat  
6. ChatGPT Assistance  
7. Browse  
8. View Enrolled Courses  
9. Manage Profile  

---

### 👨‍🏫 Instructor Use Cases
1. Create / Manage Courses  
2. Upload Materials  
3. Track Student Progress  
4. Manage Discussions & Chat  
5. ChatGPT Assistance  

---

## 🔗 Relationships Between Use Cases

### 1. Discussion → Chat (Extend)
- Chat extends Discussion for deeper interaction.

### 2. Visitor → Member / Instructor Transition
- Registration/Login converts a Visitor into a Member or Instructor.

---

## ⚠️ Note

The **Use Case Diagram illustrates all actors and their core functionalities**.  
Visitor interactions are conceptually part of the system but shown outside the system boundary, while Member and Instructor use cases are fully inside the diagram.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- System Modules --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=🏗️%20System%20Modules&fontSize=32&width=1200&height=130&color=0:FC5C7D,100:FF416C" width="100%">

👤 Visitor  
📝 Register account    
🔐 Login (Firebase Authentication)  
📚 View course list  
⭐ Explore popular courses  
🧒 Access Kids Zone   
👥 Member  
➕ Add courses  
🔍 Search courses  
📤 Upload materials  
💬 Participate in discussions  
📩 Chat with users (Real-time)  
🤖 Use AI assistant (ChatGPT)   
📊 View dashboard  
👤 Manage profile  
📚 Access enrolled courses   
🔁 Common  
✅ Account verification  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Key Features --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=✨%20Key%20Features&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

📚 Comprehensive course catalog  
🧒 Dedicated Kids Zone    
💬 Chat & discussion forums (Real-time)  
🤖 AI-powered ChatGPT assistant  
📤 Course material upload system  
📊 Personalized dashboard & analytics  
👤 Custom profile management  
🔗 Content sharing features  
🔐 Secure login & verification (Firebase)  
☁️ Real-time database sync  
🔎 Advanced course search  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- App Screens --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=📱%20Application%20Screens&fontSize=32&width=1200&height=130&color=0:6A82FB,100:FC5C7D" width="100%">

🚀 Splash Screen  
📝 Registration Page  
🔐 Login Page  
🏠 Home Page  
📚 Courses Page  
🔍 Search Page  
📊 Dashboard  
📤 Upload Materials  
💬 Discussion Page  
🤖 ChatGPT Page  
👤 Profile Page  
🔗 Share App  
🚪 Logout  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


<!-- Operating Environment --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=⚙️%20Operating%20Environment&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

📱 Platform: Android  
💻 Language: Java  
🏗️ IDE: Android Studio  
☁️ Backend: Firebase  
🗄️ Database: Firestore / Realtime DB  
🖥️ OS: Windows  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


<!-- Future Work --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=🔮%20Future%20Work&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

🚀 Mobile & Web synchronization for seamless cross-platform learning  
📊 Advanced analytics dashboard for student performance tracking  
🤖 Enhanced AI tutor with personalized recommendations  
🔐 Role-based access control with improved security  
💳 Integrated payment gateway for premium courses  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


<!-- Conclusion --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=✅%20Conclusion&fontSize=32&width=1200&height=130&color=0:6A82FB,100:FC5C7D" width="100%">

E-PATHSHALA is a scalable and impactful digital learning solution that successfully integrates:

📚 Education  
📱 Technology  
🤝 Interaction  
🎯 Personalization  

It provides a strong foundation for future-ready education systems and has the potential to significantly improve learning accessibility and quality.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Author --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=👨‍💻%20Author&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

**A. K. M. Masudur Rahman (Gaurab)**   
🎓 Department of Computer Science and Engineering (CSE)    
🏫 Bangladesh Army University of Science and Technology (BAUST), Saidpur    
📧 Email: akmmasudurrahmangaurab@gmail.com  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Support --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=⭐%20Support&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

If you like this project, consider giving it a ⭐ on GitHub!
