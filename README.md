# MVCMovie

# CYB 206 Web Application Security

**Milin Vaniyawala**  
**W0873003**  

**Date:** 2025-01-18  

---

### 0845  
**Environment Setup**  
- VS Community 2022 17.12.0  
- .NET SDK 8.0.404  

---

### 0846  
- Created the new HelloWorld Application  

### 0850  
- Ran and tested the application; confirmed it works properly  

### 0908  
- Created `HelloWorldController`  
  - Added two methods: `Index` and `Welcome`  

### 0923  
- Updated `Welcome` method in the controller  
  - Added two parameters: `name` and `numTimes`  

### 0925  
- Tested updated method; performed code testing with custom values  

### 0932  
- Updated `Welcome` method in the controller  
  - Changed `numTimes` to `ID`  

### 0933  
- Tested the updated method and confirmed it works  

---

**Date:** 2025-01-22  

---

### 0841  
- Renamed project due to inappropriate naming  
- Created a new project named **MVCMovie**  

### 0845  
- Added a new controller: **MVC Controller - Empty** (HelloWorld)  

### 0850  
- Verified the controller is working  

### 0852  
- Modified the `Welcome` method in the controller  
  - Added two parameters: `name` and `numTimes`  

### 0853  
- Verified the new method works completely  

### 0855  
- Updated `Welcome` method in the controller  
  - Changed `numTimes` to `ID`  

### 0857  
- Tested the `name` and `ID` parameters manually in the browser  

### 0901  
- Commented out the old `Index` method  
- Added a new `Index` method for view  

### 0902  
- Verified the new `Index` method  

### 0908  
- Created a new folder in **View** -> `HelloWorld`  
  - Added `Index.cshtml` file  

### 0911  
- Verified the new view  

### 0912  
- Modified the views and layout  
  - Changed header and footer  
  - Renamed **MVCMovie** to **Movie App**  

### 0918  
- Verified the views are working  

### 0920  
- Modified the `Index` file in **View** -> `HelloWorld` directory  

### 0927  
- Updated the `Welcome` method in the controller  

### 0929  
- Created a new file in **HelloWorld View** -> `Welcome.cshtml`  

### 0931  
- Tested the code in the browser  

### 0935  
- Created a new **Model**  

### 0940  
- Added Scaffolded Item  

### 0947  
- Executed migration: `Add-Migration InitialCreate`  

### 0948  
- Updated the database: `Update-Database`  

### 0949  
- Migration timestamp: `20250122144744_InitialCreate`  

### 0951  
- Created a seeder file in the model  

### 1001  
- Modified `program.cs`  

### 1009  
- Tested the code in the browser  

### 1017  
- Web application runs successfully 🎉

---

**Date:** 2025-01-28  

---

### 1448  
- Modifying the `Index` Method in `MoviesController`  

### 1455  
- Run the modified code and check if it works – ✅ *Success*  

### 1457  
- Modifying the `Index` Method in `MoviesController` *(Change `searchString` to `id`)*  

### 1459  
- Testing URL: [`https://localhost:7257/Movies/Index/ghost`](https://localhost:7257/Movies/Index/ghost)  
  - Run the modified code and check if it works – ✅ *Success*  

### 1503  
- Modifying the `Index` Method in `MoviesController` *(Change `id` back to `searchString`)*  

### 1505  
- Modifying the `Index` View of Movies *(Added form field)*  

### 1510  
- Run the modified code and check if it works – ✅ *Success*  

### 1511  
- Added new `HttpPost` Method in `MoviesController`  

### 1515  
- Run the modified code and check if it works – ✅ *Success*  

### 1518  
- Modifying the `Index` View of Movies  

### 1519  
- Run the modified code and check if it works – ✅ *Success*  

### 1521  
- New Model Created: `MovieGenre`  

### 1527  
- Modifying the `Index` Method in `MoviesController` *(Generic Query added)*  

### 1530  
- Importing the model in `Index` view file and modifying form fields *(Added dropdown menu `[Select]`)*  

### 1535  
- Run the modified code and check if it works – ✅ *Success*  

---

**Date:** 2025-01-29  

---

### 0839  
- Modified the `Movie` Model  

### 0854  
- Added `Rating` field in `Index`, `Edit`, `Create`, `Delete`, `Details`  

### 0912  
- Updating the database table  

### 0922  
- `20250129142029_Rating` migration ran successfully  

### 0955  
- Run the modified code and check if it works – ✅ *Success*  

---

**Date:** 2025-02-04  

---

### 1139  
- Modify in Movie Model  

### 1140  
- Run the modify code and check if it works or not, it's working successfully  

### 1155  
- Modify in Movie Model  

### 1200  
- Run the modify code and check if it works or not, it's working successfully  

### 1219  
- Changes in Delete Method Post Type in Movie Controller  

### 1220  
- Run the modify code and check if it works or not, it's working successfully  
