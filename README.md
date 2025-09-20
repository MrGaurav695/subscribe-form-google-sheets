# Subscribe Form with Google Sheets Integration 🚀  

A simple **“Coming Soon” page** with a **Subscribe Form** that saves user emails directly into **Google Sheets** — no backend required!  

## ✨ Features  
- Responsive “Coming Soon” landing page  
- Email subscription form with validation  
- Data saved automatically into Google Sheets  
- Success message with auto-reset  
- Clean & modern UI with gradient background

  ---

## 🛠️ Tech Stack  
- **HTML5**  
- **CSS3**  
- **JavaScript (Fetch API)**  
- **Google Apps Script**

 --- 

## 📂 Project Structure  
📦 subscribe-form-google-sheets
┣ 📜 index.html
┣ 📜 style.css
┣ 📜 script.js (inline in HTML if needed)
┣ 📜 background.png
┗ 📜 send-icon.png

---

## ⚡ How It Works  
1. User enters their email and clicks the send button.  
2. The email is sent via `fetch()` to a deployed **Google Apps Script Web App**.  
3. The script saves the email into a **Google Sheet**.  
4. User sees a success message, and the form resets automatically.
