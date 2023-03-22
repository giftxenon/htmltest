# htmltest
learning HTML

      <form>
        <label for="username">Enter username:</label>
        <input type="text" id = "username" placeholder="enter username" required>
      </form>


      <form>
        <label for="password">Enter password:</label>
        <input type="password" id = "password" placeholder="enter password" required>
     
        <p>Select your age:</p>

          <input type="radio" name="age"  value="0-25"  id="option-1">
          <label for="option-1"> 0-25</label>

<br>
          <input type="radio" name="age"  value="25-50"  id="option-2">
          <label for="option-2">25-50</label>

<br>

        <input type="radio" name="age"  value="50+"  id="option-3">
        <label for="option-3"> 50+</label>

<br><br>

<label for="Question">Security Question:</label>


              <select name="Question" id="Question">
        <option value="Q1">What is your best dish?</option>
        <option value="Q2">which team do you support?</option>
        <option value="Q3">your best friend's friend?</option>
              </select>

<br><br>
        <label for="QuestionAnswer">Answer:</label>
        <input type="text" id="QuestionAnswer" name="QuestionAnswer" placeholder="reply here">
      <br> <br>

        <label for="bio">Enter your bio</label> <br>
        <textarea name="bio" id="bio" cols="30" rows="20" placeholder="Enter your bio..."></textarea>

        <br> <br>
        <input type="submit" value="submit the form">


        </form>
        
        h1{
            color: blueviolet;
            background-color: burlywood;
            font-size: 30px;
            text-decoration: underline;
            font-family: Arial;
            text-align: center;
        }
        p{
            color: rgb(36, 224, 108);
            text-align: right;
            line-height: 30px;
            letter-spacing: 1 px;
            column-count: 3;
            column-gap: 60px;
        }
        ul{
            border-bottom: 4px dotted crimson;
            border-left: 8px dashed crimson;
        }

        li{
            list-style-type: none;
            text-shadow: 2px 2px lightgray;
        }
