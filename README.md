<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
    <link href='https://fonts.googleapis.com/css?family=Roboto:400' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" href="./main.css">
</head>
<body>
<div class="container">
    <div class="log-form">
        <h2>Отправка формы в телеграм</h2>
        <form class="telegram-form">
          <input type="text" name="name" placeholder="Имя" autocomplete="off" />
          <input type="text" name="phone" placeholder="Телефон" autocomplete="off" />
          <input type="text" name="email" placeholder="Email" autocomplete="off" />
          <textarea name="text"></textarea>
          <input type="file" name="file">
          <button type="submit" class="btn">отправить</button>
        </form>
      </div>
</div>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="./main.js"></script>
</body>
</html>
