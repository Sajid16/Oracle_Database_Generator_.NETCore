# Oracle_Database_Generator_.NETCore

Tools that will be needed to make this project.

| #Sl       | Package Names           | Version  |
| ------------- |:-------------:| -----:|
| Package->1      | Microsoft.EntityFrameworkCore | 5.0.11 |
| Package->2      | Microsoft.EntityFrameworkCore.Tools      |   5.0.11 |
| Package->3 | Oracle.EntityFrameworkCore      |    5.21.1 |

### Steps to generate entities from existing database

```
1. Clone this project.
2. Open the console/ nuget package manager console
3. Run the following commnad inside the conole

```
<pre> Scaffold-DbContext "User Id=[database_user_id/schema_name];Password=[database_password];Data Source=[database_ip:port/schema_name];" Oracle.EntityFrameworkCore -OutputDir Entities </pre>

# test
