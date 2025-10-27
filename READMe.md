\# 📚 BookShelf API Automation Project



A sample API automation project using \*\*Postman (Web)\*\* and \*\*REST Assured (Java)\*\* to test a fictional Book Management system.



\## 🚀 Project Overview

This project covers complete API testing lifecycle:

\- CRUD operations (Create, Read, Update, Delete)

\- Dynamic variable handling

\- Assertion of response codes and data

\- Schema Validation

\- Reusability through environments



\## 🔧 Tools \& Technologies

\- \*\*Postman (Web)\*\*

\- \*\*GitHub (Version Control)\*\*



\## 🧩 API Endpoints

| Method | Endpoint | Description |

|---------|-----------|-------------|

| POST | /products/add | Add new book |

| GET | /products | Get book list |

| GET | /products/:id | Get specific book |

| PUT | /products/:id | Update book |

| DELETE | /products/:id | Delete book |



\## ⚙️ How to Run in Postman

1\. Import the collection and environment.

2\. Run the collection using the Postman \*\*Collection Runner\*\* or \*\*Newman CLI\*\*.



```bash

newman run BookShelf\_API\_Automation.postman\_collection.json -e BookShelf\_Env.postman\_environment.json



