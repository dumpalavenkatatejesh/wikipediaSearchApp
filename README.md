**🌐 Wikipedia Search Application**
This is a simple and responsive web application that allows users to search Wikipedia using a keyword. Results are fetched in real-time using the CCBP Wiki Search API.

![image](https://github.com/user-attachments/assets/72676c2c-f75a-4fd7-9a8f-e22c1b7848d7)

**Deployment LINK**

(searchcc.ccbp.tech)  paste this link in browser


**🚀 Features**
Real-time Wikipedia search using Fetch API

Displays title, link, and description for each result

Spinner loader during search

Responsive and clean UI with Bootstrap 4

Keyboard event-based search (Enter key triggers fetch)

**🛠️ Technologies Used**
HTML5
CSS3
JavaScript (ES6)
Bootstrap 4
Font Awesome (optional, for icons)

**🧾 How to Use**
Clone the repository or copy the code files into your own project folder.

Make sure the project contains the following files:

index.html

style.css (or CSS in <style> tag inside index.html)

script.js (or JavaScript in <script> tag inside index.html)

Open the index.html file in a browser.

In the input field:

Type a search term (e.g., "India", "Technology")

Press Enter to trigger the search

View the results displayed below the search bar.

**📂 File Structure**
graphql
Copy
Edit
wiki-search-app/
├── index.html         # Main HTML file
├── style.css          # Optional: Styles if external
└── script.js          # Optional: JavaScript if external
🔗 API Endpoint
URL: https://apis.ccbp.in/wiki-search?search=<search_term>

Method: GET

Returns: JSON with list of search results including title, link, and description.

📌 **Notes**
Ensure internet access since the API is external.

Bootstrap and API links are loaded via CDN.

No server or database is required.

🙌 **Acknowledgments****
CCBP Wiki API

Bootstrap CDN

Wikipedia

