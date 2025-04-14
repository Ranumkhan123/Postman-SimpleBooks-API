# 📚 Simple Books API – Postman Collection

A complete, beginner-to-intermediate level API testing project using Postman, covering real-world test flows like authentication, dynamic ordering, response validation, and automation-style chaining.

---

## 🌟 Features Covered

- ✅ Token Generation with Random Client
- 📦 Dynamic Book ID Fetch
- 🛒 Order Book using Book ID and Random User
- 🔁 Retry Logic for Out of Stock Handling
- 🧾 Order Flow: Create → Verify → Update → Cancel
- 🧪 Custom Test Scripts
- 📊 Console Logs & Validations
- 💡 Bonus Flows (Check Stock, Book Type, Availability)

---

# 📂 Collection Structure

📦 Simple Books API
 ┣ 📁 Auth
 ┃ ┗ 📌 Authentication
 ┣ 📁 Books
 ┃ ┣ 📌 Get All Books
 ┃ ┣ 📌 Random Book ID → In Stock / Out of Stock
 ┃ ┣ 📌 Random Book ID → Fiction / Non-Fiction
 ┃ ┣ 📌 Get Book by BookID
 ┣ 📁 Orders
 ┃ ┣ 📌 Place Book Order
 ┃ ┣ 📌 Retry Order on Fail (Auto Retry)
 ┃ ┣ 📌 Get Order Details
 ┃ ┣ 📌 Update Customer Name
 ┃ ┗ 📌 Cancel Order

---

## 🔧 Tech Stack

- **Tool**: Postman
- **Collection Type**: REST API
- **Language**: JavaScript (Tests & Pre-request Scripts)
- **Variables Used**: Collection Variables & Random Data Generators

---

# 🧠 Notable Features

**🌀 Dynamic Book Logic**
Fetches a random bookId and stores its metadata for reuse

**⚙️ Reusability via Collection Variables**
Every key value like bookId, customerName, orderId, etc., is saved and reused across requests.

**🔁 Retry on Failure**
If a book is out of stock, the order automatically retries using postman.setNextRequest() logic.

---

# 📝 How to Run
Import Simple Books API.postman_collection.json into Postman

Set base URL variable:
**BooksURL = https://simple-books-api.glitch.me**

Run requests step-by-step or as a collection

Open Console to view logs

---

# 🧠 Author & Learning Goals
This project is built by Ranum Khan as part of her API Testing Practice Portfolio while learning automation from scratch.

---

# 📬 Feedback
If you like this collection,if this helped or inspired you, do give a ⭐ star or fork it! and connect via LinkedIn(https://www.linkedin.com/in/ranum-khan-qaengineer/).
PRs and suggestions are welcome!




