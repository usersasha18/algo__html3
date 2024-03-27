# киноафиша

```html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Приложение заметок</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
  }
  .header {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
  }
  .sidebar {
    width: 200px;
    background-color: #f1f1f1;
    position: fixed;
    height: 100%;
    overflow: auto;
  }
  .note-card {
    border: 1px solid #ddd;
    margin: 10px;
    padding: 10px;
    border-radius: 5px;
  }
  .main-content {
    margin-left: 210px;
    padding: 10px;
  }
</style>
</head>
<body>

<div class="header">
  <h1>Приложение заметок</h1>
</div>

<div class="sidebar">
  <h2>Мои заметки</h2>
  <!-- Здесь будут карточки заметок -->
</div>

<div class="main-content">
  <div class="note-card">
    <h2>Заметка 1</h2>
    <p>Содержимое заметки 1...</p>
  </div>
  <div class="note-card">
    <h2>Заметка 2</h2>
    <p>Содержимое заметки 2...</p>
  </div>
  <!-- Добавьте здесь больше заметок -->
</div>

</body>
</html>



```
