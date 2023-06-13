# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
<html>
<head> 
<title>Display the Results of the Learners</title> 
<script type="text/javascript"> 
function student() {
  var mark1, mark2, mark3, total, percentage; 
  mark1 = parseInt(prompt("Enter Subject-1 Marks"));
  mark2 = parseInt(prompt("Enter Subject-2 Marks"));
  mark3 = parseInt(prompt("Enter Subject-3 Marks")); 
  total = mark1 + mark2 + mark3;
  percentage = total / 3;

  if (percentage >= 91 && percentage <= 100) {
    alert("O Grade");
  }
  else if (percentage >= 81 && percentage <= 90) {
    alert("A+ Grade");
  }
  else if (percentage >= 71 && percentage <= 80) {
    alert("A Grade");
  }
  else if (percentage >= 61 && percentage <= 70) {
    alert("B+ Grade");
  }
  else if (percentage >= 51 && percentage <= 60) {
    alert("B Grade");
  }
  else {
    alert("RA Grade");
  }
}
</script>
</head>

<body>
<h1 onclick="student()">
Click here to Get the Result of the Learner
</h1>
</body>
</html>
## OUTPUT

![Screenshot (37)](https://github.com/BrindhaY/Ex06_Web-Design/assets/127816765/08f4d67c-353a-4bc9-8d5e-046711d4bffd)
![Screenshot (38)](https://github.com/BrindhaY/Ex06_Web-Design/assets/127816765/6b6fb80f-40db-4d11-90da-94e66d20e4f6)
![Screenshot (39)](https://github.com/BrindhaY/Ex06_Web-Design/assets/127816765/4caea696-69ff-4157-9e6c-b6f1067cf80f)
![Screenshot (40)](https://github.com/BrindhaY/Ex06_Web-Design/assets/127816765/3e66cea0-0b07-4a52-8cd5-a52a855f0c8d)
![Screenshot (41)](https://github.com/BrindhaY/Ex06_Web-Design/assets/127816765/3f4f9033-381a-41a0-bd30-30cdf1faa316)

## RESULT
  Student result using JavaScript is created successfully.
