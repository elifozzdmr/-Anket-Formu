# -Anket-Formu
HTML/CSS
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>form</title>
</head>
<body>
  <h1 id="title">Survey Form</h1>
  <p id="description">Thank you for filling out the questionnaire and helping us.</p>
  <div class="main">
    <form id="survey-form">
      NAME: <br>
      <label for="name">
        <input type="text" id="name" placeholder="Enter your name">
        <br>
        <br>
        EMAİL:<br>
        <label for="email">
          <input type="email" id="email" placeholder="Enter your Email">
          <br>
          <br>
          AGE:(optional)<br>
          <label for="number">
            <input type="number" name="age" id="number" min="10" max="99" class="form-control" placeholder="Age">
            <br>
            <br>
            Which option best describes your current role?<br>
            <select id="dropdown" style="width:13%" name="Select current role">
              <option value="Null" selected>Select current role</option>
              <option value="student">Student</option>
              <option value="fulltimejob">Full Time Job</option>
              <option value="fulltimelearner">Full Time Learner</option>
              <option value="prefernottosay">Prefer not to say</option>
              <option value="other">Other</option>
            </select>

            <br><br> Would you recommend freeCodeCamp to a friend?<br>
            <input type="radio" name="name" value="definiyely" checked>Definitely<br>
            <input type="radio" name="name" value="maybe">Maybe<br>
            <input type="radio" name="name" value="notsure">Not sure<br>
            <br>
            What is your favorite feature of freeCodeCamp?<br>
            <select style="width:13%" name="selectanoption">
              <option value="Null" selected>Select an option</option>
              <option value="challenges">Challenges</option>
              <option value="projects">Projects</option>
              <option value="community">Community</option>
              <option value="prefernottosay">Prefer not to say</option>
              <option value="opensource">Open Source</option>
            </select>

            <br><br>What would you like to see improved? (Check all that apply)<br>
            <input type="checkbox" value="frontend" name="frontendprojects"> Front-end Projects<br>
            <input type="checkbox" value="backend " name="backendprojects"> Back-end Projects<br>
            <input type="checkbox" value="datavisualization" name="datavisualization">Data Visualization<br>
            <input type="checkbox" value="challenges" name="challenges">Challenges<br>
            <input type="checkbox" value="opensourcecommunity" name="opensourcecommunity">Open Source Community<br>
            <input type="checkbox" value="gitterhelprooms" name="gitterhelprooms">Gitter help rooms<br>
            <input type="checkbox" value="videos" name="videos">Videos<br>
            <input type="checkbox" value="citymeetups" name="citymeetups">City Meetups<br>
            <input type="checkbox" value="wiki" name="wiki">Wiki<br>
            <input type="checkbox" value="forum" name="forum">Forum<br>
            <input type="checkbox" value="additionalcourses" name="additionalcourses">Additional Courses<br>
            <br>Any comments or suggestions?<br>

            <textarea style="width:30%" name="message" option value="Null" placeholder="Enter your comment here..."></textarea> <br>
            <br>
            <input type="submit" value="SUBMIT">
    </form>
  </div>
</body>
</html>
    
    
CSSS
    
body {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  font-family: Verdana, monospace, sans-serif;
  font-size: 12px;
  font-weight: bold;
  text-align: center;
  background-color: #80cbc4;
}

input[type="text"]{
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 6px;
  box-sizing: border-box;
}

input[type="email"]
{
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 6px;
  box-sizing: border-box;
}

input[type="number"]
{
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 6px;
  box-sizing: border-box;
}

.main {
  background-color: #b2dfdb;
  font-family: arial;
  font-size: 15pt;
  padding-top: 5%;
  padding-bottom: 5%;
  width: 50% !important;
  margin-bottom: 5%;
}

select {
  width: 100% !important;
  padding: 16px 20px;
  border: none;
  border-radius: 4px;
  background-color: #f1f1f1;
}

textarea {
  width: 100% !important;
  height: 150px;
  padding: 12px 20px;
  box-sizing: border-box;
  border: 2px solid #ccc;
  border-radius: 4px;
  background-color: #f8f8f8;
  resize: none;
}

input[type="submit"] {
  width: 100%;
  background-color: #558b2f;
  color: white;
  color-size: border;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  font-family: arial;
}

input[type="submit"]:hover {
  background-color: #558b2f;
}

input {
  padding: 8px 20px;
  border: 1px solid #eee;
  border-left: 3px solid;
  border-left-color: salmon;
  border-radius: 5px;
  transition: border-color 0.8s ease-out;
}

input:focus {
  outline: none;

  border: 1px solid #eee;

  border-left: 3px solid #888;
}

form {
  text-align: start;
}

h1 {
  font-family: Arial;
  font-size: 30pt;
  font-weight: bold;
  color: #ffffff;
}
p {
  font-size: 15pt;
  font-family: Arial;
  color: #ffffff;
}

.main {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%
}

    
