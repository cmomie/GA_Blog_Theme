# GA_Blog_Theme
General Assembly Blog Theme Practice 
<!DOCTYPE html>
<head>
  <link href="/normalize.css" rel="stylesheet">
  <style>
    header {
      text-align: center;
      background: url('/assets/jeff-bg.png');
      background-size: cover;
      color: black;
    }
    a {
      color: white;
    }
    h1 {
      font-size: 70px;
    }
    img {
      margin: 40px 0px 0px 0px;
      border: 7px solid white;
      border-radius: 20px;
    }
    ul {
      padding: 10px;
      background: rgba(0,0,0,0.5);
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
    article {
      max-width: 500px;
      padding: 20px;
      margin: 0 auto;
    }
    @media (max-width: 500px) {
      h1 {
        font-size: 36px;
        padding: 5px;
      }
      li {
        padding: 5px;
        display: block;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ0qPo8Pya6UJIWhOIrfWdJuXSgR7J-I102OQ&usqp=CAU">
    <!╌ assets/jeff.png ╌>
    <h1>Crystal's Blog</h1>
    <ul>
      <li><a href="#">About Me</a></li>
      <li><a href="#">Projects</a></li>
      <li><a href="#">Education</a></li>
    </ul>
  </header>
  <article>
    <h2>About Me</h2>
    <p>An enthusiastic Technology Specialist and Educator with experience in Data Analysis and ﬁfteen years in Education. Proﬁcient software development skills in JavaScript and ReactJS. Automate common tasks to improve eﬃciency with an understanding of cloud communication and storage systems. A Data Specialist and problem solver that identiﬁes relevance of information. Utilizes sound judgement to make recommendations. An individual who can work in an Agile team as well as independently. Passionate about technology, creating solutions to complex problems and working in a fast-paced environment.</p>
    <button>Like</button>
  </article>
  <article>
    <h2>Projects</h2>
    <p>Weather App ○ Uses Javascript, React, and Api’s to identify updated weather for speciﬁc location</p>
    <p>Movie  App ○ Incorporates Javascript, React, and Api’s to identify updated information about selected movies</p>
    <p>COVIDNot ○ Provides COVID-19 resources and created with HTML and CSS</p>
    <button>Like</button>
  </article>
  <article>
    <h2>Education</h2>
    <p>Bachelor of Science<br> Interdisciplinary Studies<br> Prairie View A&M University<br> Graduated Fall 2005 (3.4 GPA) <br>
    <br>Master of Education <br>Counseling<br> Lamar University<br>
  Graduated Fall  2021 (3.2 GPA)
  <br>
   <br>MBA <br>Management Information Systems<br> Lamar University<br> Expected
  Graduation Spring  2023
</p>
    <button>Like</button>
  </article>
  <script>
    $("button").on("click", function() {
      alert("Clicked!");
    });
  </script>
</body>
