# Authentication-and-Authorization-In-Apex
APEX Authentication &amp; Authorization (Starter Guide) with Login system having multiple users, role-based access (Admin / User) and Protected pages

1️⃣ Create Application

Create a new application named:
👉 Authentication & Authorization

Then open the application.

<p align="center"> <img src="authentication%20%26%20authorization%20app.png" width="700"/> </p>
2️⃣ Navigate to Shared Components

Go to:
👉 Shared Components

<p align="center"> <img src="app%20shared%20components.png" width="700"/> </p>
3️⃣ Configure Authentication Scheme
Open Authentication Schemes
Create a new scheme
Use Custom Function for validation
<p align="center"> <img src="authentication%20schemes.png" width="700"/> <br/><br/> <img src="user%20authentication.png" width="700"/> <br/><br/> <img src="login%20page%20backend.png" width="700"/> </p>
4️⃣ Create User Info Table

Create a table with:

Username
Password
Role (Admin/User)
<p align="center"> <img src="user%20info%20table.png" width="700"/> </p>
5️⃣ Configure Authorization Schemes

Create two schemes:

✅ Admin Access
✅ User Access
<p align="center"> <img src="authorization%20schemes.png" width="700"/> <br/><br/> <img src="admin%20authorization.png" width="700"/> <br/><br/> <img src="user%20authorization.png" width="700"/> </p>
6️⃣ Run the Application

Run the application and test login.

<p align="center"> <img src="home%20page.png" width="700"/> </p>
7️⃣ Invalid Login Attempt

Enter incorrect credentials → ❌ Login Failed

<p align="center"> <img src="invalid%20login%20credentials.png" width="700"/> </p>
8️⃣ Successful Login

Enter correct credentials → ✅ Login Successful

<p align="center"> <img src="login%20page%20front%20end.png" width="700"/> <br/><br/> <img src="login%20successfull.png" width="700"/> </p>
9️⃣ Employee Record Access (Admin & User)

Both users can access Employee Records.

<p align="center"> <img src="emp%20record.png" width="700"/> <br/><br/> <img src="admin%20user%20sucess%20view%20emp%20record.png" width="700"/> <br/><br/> <img src="user%20success%20view%20emp%20record.png" width="700"/> </p>
🔟 Department Record Access (Admin Only)
Admin ✅ Access Allowed
User ❌ Access Denied
<p align="center"> <img src="dept%20record.png" width="700"/> <br/><br/> <img src="admin%20user%20sucess%20view%20dept%20record.png" width="700"/> <br/><br/> <img src="user%20access%20denied%20dept%20record.png" width="700"/> </p>
🎯 Final Result
✅ Authentication implemented
✅ Role-based authorization working
✅ Secure page access control achieved
