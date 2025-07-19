<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My first game</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js"></script>
</head>
<body>
  <div class="container">
    <p id="resultDisplay" class="result-box"></p>
    <h1>Rock Papers Sissors</h1>
    <button onclick="
    const randomNumber = Math.random();
    let computerNumber ='';

    if(randomNumber >= 0 && randomNumber < 1/3)
    { 
      computerNumber = 'Rock';
    } else if (randomNumber >= 1/3 && randomNumber < 2/3)
    {
    computerNumber = 'papers';
    } else if (randomNumber >= 2/3 && randomNumber < 1)
    {
    computerNumber = 'Sissors';
  }

  console.log(computerNumber)

  let result = '';
  
  if(computerNumber === 'Rock'){
    result = 'Tie.';
  }else if(computerNumber === 'papers'){
    result = 'Lose';
  }else if(computerNumber === 'Sissors'){
    result = 'Win';
  }
  document.getElementById('resultDisplay').innerText = `You picked Rock, The computer picked ${computerNumber}. ${result}`;

    ">Rock</button>

    <button onclick="
    const randomNumber = Math.random();
    let computerNumber ='';

    if(randomNumber >= 0 && randomNumber < 1/3)
    { 
      computerNumber = 'Rock';
    } else if (randomNumber >= 1/3 && randomNumber < 2/3)
    {
    computerNumber = 'papers';
    } else if (randomNumber >= 2/3 && randomNumber < 1)
    {
    computerNumber = 'Sissors';
  }

  console.log(computerNumber)

  let result = '';
  
  if(computerNumber === 'Rock'){
    result = 'Lose';
  }else if(computerNumber === 'papers'){
    result = 'Win';
  }else if(computerNumber === 'Sissors'){
    result = 'Tie';
  }
  document.getElementById('resultDisplay').innerText = `You picked Sissors, The computer picked ${computerNumber}. ${result}`;
    ">Sissors</button>

    <button onclick="
    const randomNumber = Math.random();
    let computerNumber ='';

    if(randomNumber >= 0 && randomNumber < 1/3)
    { 
      computerNumber = 'Rock';
    } else if (randomNumber >= 1/3 && randomNumber < 2/3)
    {
    computerNumber = 'papers';
    } else if (randomNumber >= 2/3 && randomNumber < 1)
    {
    computerNumber = 'Sissors';
  }

  console.log(computerNumber)

  let result = '';
  
  if(computerNumber === 'Rock'){
    result = 'Win.';
  }else if(computerNumber === 'papers'){
    result = 'Tie';
  }else if(computerNumber === 'Sissors'){
    result = 'You Lose';
  }
 document.getElementById('resultDisplay').innerText = `You picked papers, The computer picked ${computerNumber}. ${result}`;
    ">papers</button>
  </div> 
  
</body>
</html>
