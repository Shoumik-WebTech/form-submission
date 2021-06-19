<!DOCTYPE HTML>
<html>
<head>
  <title>Registration Form</title>
</head>
<body>
 <form action="insert.php" method="POST">
  <table>
   <tr>
    <td>Enter your Name :</td>
    <td><input type="text" name="username" required></td>
   </tr>
   <tr>
    <td>Enter First Name :</td>
    <td><input type="text" name="Firstname" required></td>
   </tr>
   <tr>
    <td>Enter Last Name :</td>
    <td><input type="text" name="Lastname" required></td>
   </tr>
    <td>Gender :</td>
    <td>
     <input type="radio" name="gender" value="m" required>Male
     <input type="radio" name="gender" value="f" required>Female
    </td>
   </tr>
   <tr>
    <td>Date of Birth :</td>
    <td><input type="date" name="DOB" required></td>
  </tr>
  <tr>
    <td>Religion :</td>
    <td>
      <input type="dropdown" name="religion" value="Mus" required>Muslim
      <input type="dropdown" name="religion" value="Hin" required>Hindu
      <input type="dropdown" name="religion" value="Chr" required>Christian
      <input type="dropdown" name="religion" value="Budd" required>Buddha
      <input type="dropdown" name="religion" value="Oth" required>Others
    </td>
  </tr>
   <tr>
    <td>Email :</td>
    <td><input type="email" name="email" required></td>
   </tr> 
   <tr>
    <td>Phone no :</td>
    <td><input type="phone no" name="phone no" required></td>
   </tr>
   <tr>
    <td>Present Address :</td>
    <td><input type="textarea" name="Present Address" required></td>
  </tr>
  <tr>
    <td>Permanent Address :</td>
    <td><input type="textarea" name="Permanent Address" required></td>
  </tr>
  <tr>
    <td>Website Link :</td>
    <td><input type="url" name="Personal Website Link" required></td>
  </tr>
  <tr>
    <td>Account Information :</td>
    <td><input type="text" name="username" required></td>
    <td><input type="password" name="password" required></td>
  </tr>
   <tr>
    <td><input type="submit" value="Submit" name="submit"></td>
   </tr>
  </table>
 </form>
</body>
</html>