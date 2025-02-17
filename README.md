<html>
<head>
    <title>Simple Form</title>
<style>
        body {
            font-family:"times new roman";
            background-color: lightpink;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
.container {
            width: 300px;
            padding: 20px;
	    background-color: white;
            border: 5px solid #aaa;
            border-radius: 100px;
            box-shadow: 2px 2px 12px rgba(20,5,63,1.0);
            margin: auto;
            text-align: center;
        }
</style>
</head>
<body>
<div class="container">
    <form action="submit_form.php" method="post">
	<h1 align="center">Form for Students</h1>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br><br>
        
        <label for="Branch">Branch:</label>
        <input type="Branch" id="Branch" name="Branch" required><br><br>

	<label>Year:</label>
        <input type="radio" id="1st" name="Year" value="1st" required>
        <label for="1st">1st</label>
        <input type="radio" id="2nd" name="Year" value="2nd" required>
        <label for="2nd">2nd</label>
 	<input type="radio" id="3rd" name="Year" value="3rd" required>
        <label for="3rd">3rd</label><br><br>

                
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select Country</option>
            <option value="USA">USA</option>
            <option value="UK">UK</option>
            <option value="Canada">Canada</option>
            <option value="Australia">Australia</option>
		<option value="India">India</option>	
		<option value="Russia">Russia</option>
        </select><br><br>
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label><br><br>
        <input type="submit" value="Submit">
	<input type="reset" value="Reset">
    </form>
</body>
</html>
