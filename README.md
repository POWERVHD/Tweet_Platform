# KPTwitter - A Mini Twitter Clone 🐦

KPTwitter is a **Django-based social media application** where users can create, edit, and delete tweets. 
It includes a user authentication system, a searchable tweet list, and a contact form to submit user issues.

---

## 🚀 Features
- ✅ **User Authentication** (Signup, Login, Logout)
- ✅ **Create, Read, Update, and Delete (CRUD) Tweets**
- ✅ **Upload Photos with Tweets** 🖼️
- ✅ **Search Tweets by Keywords** 🔍
- ✅ **Contact Us Form with Database Storage** 📩
- ✅ **Bootstrap Styling for a Responsive UI** 🎨

---

## 🛠️ Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/kptwitter.git
cd kptwitter
```

### **2️⃣ Create a Virtual Environment**
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate  # Windows


### **3️⃣ Install Dependencies**

pip install -r requirements.txt


### **4️⃣ Apply Migrations & Run Server**

python manage.py makemigrations
python manage.py migrate
python manage.py runserver

## 🛠️ Project Structure
![image](https://github.com/user-attachments/assets/34229a25-8dbb-4652-9e81-a0c21b1c4505)


---

## 📧 Contact Us Form
- Users can submit their **name, email, and issue**.
- Messages are stored in the **database** using Django’s ORM.
- Admins can view the messages in **Django Admin Panel**.

## 🔍 Search Tweets
- Users can search for tweets using **keywords**.
- Implemented with Django's `icontains` filter.


