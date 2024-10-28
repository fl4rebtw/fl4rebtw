<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <title>TODO App</title>
</head>

<body>
  <div class="container">
    <h1 class="mt-5">My TODO App</h1>
    <div class="mb-3">
      <span class="me-3">Item count: <span id="item-count">0</span></span>
      <span>Unchecked count: <span id="unchecked-count">0</span></span>
    </div>

    <button class="btn btn-primary mb-3" onClick="newTodo()">New TODO</button>

    <ul id="todo-list" class="list-group">
    </ul>
  </div>
  <script src="script.js"></script>
</body>

</html>
