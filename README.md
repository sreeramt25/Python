

 📊 Dataset Explanation and Tasks  

 📂 Dataset Attributes  

 🔹 Employee Table  
1. 🆔 ID - Assigned number for the Project Head in charge.  
2. 👤 Name - Person handling the project.  
3. ⚧ Gender - Male (M) / Female (F).  
4. 📍 City - Location of the project.  
5. 📅 Age - Number of years the project will be active.  
6. 📌 Status - Status of the project.  
7. 📊 Designation Level - Position of the Project Head.  
   - 🚨 Excessive failures result in a downgrade of designation.  
   - 🌟 A good reputation increases chances of promotion.  
   - Designation Scale: 
     - 1️⃣ - Highest
     - 2️⃣ & 3️⃣ - Mid-level positions  
     - 4️⃣ - Lowest
     - ❌ If an employee exceeds level 4, they lose project eligibility.  

 📝 Tasks Overview  

 ✅ Task 1: Create & Save Dataframes  
- Create three separate dataframes in Python for each table.  
- Save them as three `.csv` files.  
- From Task 2 to Task 10, use only the saved `.csv` files.  

 🔄 Task 2: Handle Missing Values  
- The cost column in the Project dataframe has missing values.  
- Replace missing values using the **running average**.  
- Use a **for loop** for this task.  

 ✂️ Task 3: Split Name Column  
- Split the name column in the Employee dataframe into:  
  - First Name  
  - Last Name  
- Remove the old name column.  

 🔗 Task 4: Merge Dataframes  
- Join all three dataframes into a single dataframe named Final.  

 💰 Task 5: Add Bonus Column  
- Add a new column Bonus in the Final dataframe.  
- Employees who have completed projects receive a 5% bonus based on project cost  

 📉 Task 6: Demote & Remove Employees  
- Demote the designation level by 1 for employees whose projects have failed.  
- Remove employees whose designation level exceeds 4.  

 🎭 Task 7: Add Titles & Drop Gender  
- Add "Mr." or "Mrs." as a prefix to the First Name column.  
- Drop the Gender column.  

 📈 Task 8: Promote Employees  
- Promote the designation level by 1 for employees above 29 years old.  

 📊 Task 9: Calculate Total Project Cost  
- Calculate the total cost of all projects handled by each employee.  
- Save the result in a new dataframe TotalProjCost with the following columns:  
  - 🆔 ID  
  - 👤 First Name  
  - 💲 Total Cost  

 🔍 Task 10: Filter Employees by City Name  
- Print details of employees whose city name contains the letter "o".  

---


