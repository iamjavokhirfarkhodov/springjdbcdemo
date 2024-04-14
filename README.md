# API Documentation

Login is required to use the APIs. A JWT token is automatically assigned to the user upon successful login, and all subsequent requests are processed only if the token is found. Otherwise, the server will return a 403 response. <br>
<details>
	<summary><strong>Login</strong></summary>
	POST - "/login" <br>
	{<br>
		"username": "superadmin",<br>
		"password": "123456"<br>
	}<br>
	{<br>
		"username": "admin",<br>
		"password": "1234567"<br>
	}<br>
	{<br>
		".......": "......"<br>
	}<br>
</details>

The system has 3 main API routes <br>
- "api/v1/management/**" <br>
- "api/v1/students/**" <br>
- "signup/student" <br>

<br>
<details>
	<summary>Management</summary>
	"api/management/**" - only system admins can use this path. You can access the API paths available in the system and make requests to them <br>
	<details>
		<summary>Working with Users table.</summary>
	</details>
</details>
