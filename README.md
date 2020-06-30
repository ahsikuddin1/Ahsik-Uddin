<!DOCTYPE html>
<head>
  <link href="/normalize.css" rel="stylesheet">
  <style>
    header {
      text-align: center;
      background: url('https://www.state.gov/wp-content/uploads/2019/04/Bangladesh.jpg');
      background-size: cover;
      color: Pink;
    }
    a {
      color: red;
    }
    h1 {
      font-size: 60px;
    }
    img {
      margin: 50px 0px 0px 0px;
      border: 7px solid white;
      border-radius: 20px;
    }
    ul {
      padding: 10px;
      background: green;
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
    article {
      max-width: 400px;
      padding: 3px;
      margin: 0 auto;
    }
    @media (max-width: 400px) {
      h1 {
        font-size: 28px;
        padding: 8px;
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
    <img src="https://i.imgur.com/fdsm34K.jpg">
    <h1>Ahsik's Bangladesh Blog</h1>
    <ul>
      <li><a href="#">About Me</a></li>
      <li><a href="#">Contact Info</a></li>
    </ul>
  </header>
  <article>
    <h2>VHS umami pop-up trust fund</h2>
    <p>Marfa church-key kitsch bicycle rights, 8-bit mixtape cardigan gentrify Echo Park. Street art swag brunch, next level roof party Schlitz hella organic keffiyeh selfies. You probably haven't heard of them polaroid hashtag +1, meggings biodiesel Portland High Life cray tumblr retro.</p>
    <button>Like</button>
  </article>
  <article>
    <h2>Sartorial synth Echo Park, roof party</h2>
    <p>chambray you probably haven't heard of them pour-over viral selvage umami skateboard VHS post-ironic selfies. Wes Anderson gentrify fanny pack twee, bicycle rights bitters blog keffiyeh plaid flannel. Tonx irony cliche sustainable mlkshk bitters. Four loko leggings chambray Vice.</p>
    <button>Like</button>
  </article>
  <article>
    <h2>Forage food truck keytar master cleanse</h2>
    <p>ethical thundercats sustainable locavore quinoa Neutra. Aesthetic tacky sweater single-origin coffee, bicycle rights organic lo-fi street art american apparel ennui four loko ethnic Brooklyn small batch. Forage YOLO polaroid</p>
    <button>Like</button>
  </article>
  <script>
    $("button").on("click", function() {
      alert("Clicked!");
    });
