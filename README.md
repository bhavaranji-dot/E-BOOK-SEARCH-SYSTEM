📚 E-Book Chapter and Section Search System
📌 Project Overview

The E-Book Chapter and Section Search System is a Flask-based Information Retrieval application that allows users to upload PDF books and search for relevant content at the chapter and section level.

The system extracts text from uploaded PDFs and applies TF-IDF and Cosine Similarity to retrieve the most relevant sections for a user's query.

Each user works within their own session, ensuring uploaded books are not shared between users.

🚀 Live Application

🔗 Live Demo
https://e-book-search-system-1.onrender.com/

🔗 GitHub Repository
https://github.com/bhavaranji-dot/E-BOOK-SEARCH-SYSTEM.git

✨ Features

📤 Upload PDF Books

📚 Automatic Chapter & Section Detection

🔍 Intelligent Search using TF-IDF

📊 Cosine Similarity Ranking

📄 Page Number Display

🗂 Library View of Uploaded Books

❌ No-Match Handling

🔐 Session-Based User Isolation

🛠 Technologies Used

Python

Flask

PyPDF2

Scikit-learn

HTML

CSS

JSON

Git & GitHub

Render (Deployment)  
)


⚙️ Installation
Clone the Repository
git clone https://github.com/bhavaranji-dot/E-BOOK-SEARCH-SYSTEM.git
Navigate to the Folder
cd E-BOOK-SEARCH-SYSTEM
Install Dependencies
pip install -r requirements.txt
▶ Run the Application
py app.py

Open your browser and go to:

http://127.0.0.1:5000
🧠 Algorithms Used
TF-IDF (Term Frequency – Inverse Document Frequency)

Used to determine the importance of words in documents.

Cosine Similarity

Measures similarity between the user query vector and document vectors to rank the most relevant sections.

📂 Project Workflow
Upload PDF
     ↓
Extract Text
     ↓
Detect Chapters & Sections
     ↓
Create TF-IDF Vectors
     ↓
Process User Query
     ↓
Calculate Cosine Similarity
     ↓
Rank Results
     ↓
Display Relevant Sections
👩‍💻 Author

RANJINI . J

Team Members

Pavithra . B

Monika

Tanushri . V

⭐ Conclusion

This project demonstrates how Information Retrieval techniques such as TF-IDF and Cosine Similarity can be applied in a Flask web application to perform efficient chapter-level search in E-Books.

The system provides fast, relevant, and structured search results with session-based isolation for multiple users.
