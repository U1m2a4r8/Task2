# GitHub User Search

A simple web page that allows users to search GitHub profiles using the GitHub Users API.  
Enter a username and the app displays matching GitHub users with their avatar, username, and a link to their profile.

---

## 🛠 Technologies Used
- HTML  
- CSS  
- JavaScript  
- GitHub REST API  

---

## 📡 API Used
This project uses the **GitHub Users API** to fetch user profiles.  
API Documentation: [GitHub REST API - Search Users](https://docs.github.com/en/rest/search?apiVersion=2022-11-28#search-users)

**Example Request:**
```http
GET https://api.github.com/search/users?q={username}
