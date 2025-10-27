# 📚 BookShelf API Automation


## **Project Overview**
This project demonstrates **API automation testing using Postman** for the BookShelf API.  
It is designed to highlight **best practices in API testing**, including:

- Status code validation  
- Mandatory field checks  
- Schema validation  
- Dynamic data handling (environment variables)  
- Manual execution workflow (no CLI/Newman required)

---

## **Folder Structure**
BookShelf-API-Automation/
├── NewProj/
│ ├── BookShelf API Automation-poojak.postman_collection.json
│ └── BookShelf.postman_environment.json
| |__Result Run.png
| |__Result Screenshots.png
└── README.md


---

## **Manual Execution Steps**
1. **Open Postman** (Web or Desktop).  
2. **Import Collection**  
   - Click `Import` → Choose `BookShelf API Automation-poojak.postman_collection.json`.  
3. **Select Environment**  
   - Click `Environment` → Import `BookShelf.postman_environment.json`.  
4. **Run Requests**  
   - Open a request → Click **Send** → Observe response.  
5. **Check Test Results**  
   - Go to **Tests tab / Test Results** in Postman.  
   - Passed tests appear **green**, failed tests **red**.  

---

## **Implemented Test Scenarios**

### 1️⃣ Status Code Validation
```javascript
pm.test("Status code is 200", () => pm.response.to.have.status(200));
