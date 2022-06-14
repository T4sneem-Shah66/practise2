# practise2
The 2nd Half Practice
https://t4sneem-shah66.github.io/practise2/
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pracrise2</title>
</head>

<body>
  Menu bar:
  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact US</a>
  </nav><br><br>


  Highlights the <mark>text</mark><br><br><br>


  <p>This is some <u>mispeled</u> text.</p><br><br>

  <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos maiores <wbr> perferendis sunt magni fuga provident nam eligendi possimus, nobis adipisci.</p>
  <br><br>

  <small>smaller text</small><br><br><br>


  Superceript: x<sup>2</sup><br><br><br>


  Subscript: H<sub>2</sub>O <br><br><br>

  <ruby>
    漢 <rp>(</rp>
    <rt>ㄏㄢˋ</rt>
    <rp>)</rp>
  </ruby>

  <p><s>25% OFF</s> <br>
    NOW 50% OFF
  </p><br><br><br>


  We all know the famous quote: <br><br>
  <q>Time is money</q>
  <br><br><br>


  <label for="grade">Grade Scale: </label>
  <meter id="grade" value="60" min="0" max="70">60 out of 70</meter><br><br>

  <form oninput="x.value=parseInt(a.value)+parseInt(b.value)">
    <input type="range" id="a" value="50"> + <input type="number" id="b" value="2"> = <output name="x"
      for="a b"></output>
    <!--here the input type number brings the arrow-->
  </form>
  <br><br>


  <!-- <noframes>an alternate content for frames</noframes> -->

  <section>
    <object data="mountain2.jpg" class="obj obj1" width="300"></object><br><br>
    <object data="horse.wav" class="obj2">
      <param name="autoplay" value="true">
      <!--param is the parameter for object element-->
    </object><br><br>
    Play the following sound <br>
    <audio controls>
      <source src="horse2.ogv">
    </audio><br><br>
    Resize the page for multiple pictures <br>
    <picture class="pic">
      <source media="(min-width:1000px)" srcset="img_pink_flowers.jpg">
      <source media="(min-width:600px)" srcset="img_white_flower.jpg">
      <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
    </picture>
    <br><br>
  </section>
  <br>

  The Following Video and Audio doesn't work
  <br><hr>
  <video width="320" height="240" controls>
    <track src="./Clapping.mp3">
    <track src="./Video2.mp4">
  </video>
  <hr><br>

  <svg>
    <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
  </svg>



  <ol>
    Ordered List:
    <li>apple</li>
    <li>apple</li>
    <li>apple</li>
  </ol>

  <ul>
    Unordered List:
    <li>apple</li>
    <li>apple</li>
    <li>apple</li>
  </ul><br><br>

  <form>
    <fieldset>
      <legend>Dog Form</legend>
      <label for="dogs1">Choose a dog:</label>
      <select name="Dogs" id="dogs1">
        <optgroup label="Swedish Dogs">
          <option value="Bamse">Bamse</option>
          <option value="Alice">Alice</option>
        </optgroup>
        <optgroup label="German Dogs">
          <option value="Blitz">Blitz</option>
          <option value="Ahren">Ahren</option>
        </optgroup>
      </select>
      <br><br>
      <textarea>Any Suggestions? Type Away!!</textarea>
      <br><br>
      <input type="submit" value="Submit"><br><br>
      <label for="file">File Completion:</label>
      <progress id="file" value="50" max="100"> 50% </progress>
    </fieldset>
  </form><br><br>


  Pre-element texts shows the exacxt text format: <br>
  <pre>
    Lorem ipsum dolor sit amet.
    Lorem ipsum dolor sit amet.
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, exercitationem.
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laborum saepe velit ipsam tempora quam.
  </pre>
  <br><br>


  <table>
    <caption>Students Database</caption>
    <colgroup>
      <col span='2' style="background-color:red">
      <col style="background-color:yellow">
    </colgroup>
    <thead>
      <tr>
        <th>Name</th>
        <th>Roll</th>
        <th>Score</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>XXX</td>
        <td>0011</td>
        <td>70</td>
      </tr>
      <tr>
        <td>YYY</td>
        <td>0012</td>
        <td>50</td>
      </tr>
    </tbody>
    <tfoot>
      <tr>
        <td>Total</td>
        <td></td>
        <td>120</td>
      </tr>
    </tfoot>
  </table>
  <br><br>


  Sleeping Time: <time datetime="22:00">22:00</time><br><br>

  <!--
  <wbr>	Defines a possible line-break
  -->


  <script>
    document.write("Goodbye World!")
  </script>
  <noscript>Your browser does not support JavaScript!</noscript><br><br>

  <button onclick="DisplayContent()">Click Here</button>
  <template>
    <img src="img_orange_flowers.jpg" alt="Flowers">
  </template>
  <script>
    function DisplayContent(){
      var Flwr = document.getElementsByTagName("template")[0];
      var clon = Flwr.content.cloneNode(true);
      document.body.appendChild(clon);
    };
  </script><br><br>

</body>

</html>



