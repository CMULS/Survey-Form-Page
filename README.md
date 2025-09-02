<html>
<title>CMulzSurveyForm</title>
  <body>
<h1 id="title">CMulzSurveyForm</h1>
<main>
<p id="description">Thank you for taking the time to help us improve the platform</p>
<h4>Name</h4>  
<form action="Chibesa" id="survey-form">
  <label id="name-label" for="name" >Enter your name:</label>
  <input id="name" name="Please fill in this field" required type="text" placeholder="Enter your name">
  </form>

<h4>Email</h4>
<form action="mulengachibesa8@gmail.com" id="survey-form">
  <label for="email"Enter your email id="email-label">Enter your email:</label>
  <input id="email" name="Please fill in this field" required type="email"
  placeholder="Enter your email">
  </form>
<h4>Age(optional)</h4>
<form action="21" id="survey-form">
  <label for="number"Age id="number-label">Age:</label>
  <input id="number" min="20" max=" 40" type="number"
  placeholder="Age">
  </form>
<h4>Which option best describes your current role</h4>
<form action="" id="survey-form">
  <select id="dropdown">
    <option value="student">Student</option>
    <option value="full-time worker">Full-time worker</option>
    </select>
  <input id="role" type="text"
  placeholder="Select current role">
<h4>Would you recommend CMulz to a friend?</h4>
<h4><label for="definitely"><input id="definitely" value="definitely" type="radio" name="group1"/>Definitely
<input id="definitely" type="radio" value="definitely" name="group1"/>Definitely</label></h4>
<h4><label for="maybe"><input id="maybe" value="maybe"    type="radio" name="group2"/>Maybe
<input id="maybe" type="radio" value="maybe" name="group2"/>Maybe</label></h4>
<h4><label for="not sure">
  <input id="not sure" value="not sure"
  type="radio" name="group3"/>Not sure
  <input id="not sure" type="radio" value="not sure" name="group3"/>Not sure</label></h4>
<h4>What is your favorite feature of CMulz?</h4>
<form action="" id="survey-form">
  <select id="dropdown">
    <option value="projects">Projects</option>
    <option value="challenges">Challenges</option>
    </select>
  <input id="dropdown" type="text"
  placeholder="select an option">
<h4>What would you like to see improved?(Check all that apply)</h4>
<h4><label for="front-end projects"><input id="front-end projects" value="front-end projects" type="checkbox" name="project">Front-end projects</label>
<h4><label for="back-end projects"><input id="back-end projects" value="back-end projects" type="checkbox" name="project">Back-end projects</label>
<h4><label for="challenges"><input id="challenges" value="challenges" type="checkbox" name="challenge">Challenges</label></h4>
<h4><label for="forum"><input id="forum" value="forum" type="checkbox" name="forum">Forum</label></h4>
<h4>Any comments or suggestions?</h4>
<form action="">
  <textarea <input type="text" placeholder="Enter your comment here..."></textarea>
<h5><button id="submit" type="submit">Submit</button></form></h5>
<link rel="stylesheet" href="styles.css">








</main>

<style>
  
  #title {
  }
  body {
    background-color: brown;
  } 
  #description {
  }
  #survey-form {
  }
  #name {
  }
  
</style>
</html>
