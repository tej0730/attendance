# attendance.github.io
<html>
<head>
<style>
form{
width: 350px;
height: 450px;


}
.container{
display: flex;
justify-content: right;

align-items:center !important;
height: 100vh;
}
input[type], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 100%;
  background-color: #E1E8B3;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}


div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
  align:center;
}
</style>
<body>
<div class=container>
<form>
<img src="PIC1.jpg" height=20%><br><br>
  <label for="username">Username:</label><br>
  <input type="text" id="username" name="username" placeholder="Enter id"><br>
  <label for="pwd">Password:</label><br>
  <input type="password" id="pwd" name="pwd" placeholder="Enter password"><br><br>
  <input type="submit" value="Submit" >

</form>
</div>
</body>
</head>
</html>
