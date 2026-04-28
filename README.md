# collage-project
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Government Scheme Finder</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Government Scheme Finder</h1>
  <p>Find welfare schemes you qualify for</p>
</header>

<div class="container">
  <div class="card">
    <h2>Check Eligibility</h2>

    <input type="number" id="age" placeholder="Enter Age">
    <input type="number" id="income" placeholder="Enter Annual Income">

    <select id="occupation">
      <option value="">Select Occupation</option>
      <option value="student">Student</option>
      <option value="farmer">Farmer</option>
      <option value="worker">Worker</option>
    </select>

    <button onclick="checkScheme()">Find Schemes</button>

    <div id="result"></div>
  </div>
</div>

<script src="script.js"></script>
</body>
</html>
