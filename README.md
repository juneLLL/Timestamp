
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Timestamp microservice</title>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
  <meta name="description" content="Timestamp microservice">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="shortcut icon" href="/favicon.ico">
  <link rel="apple-touch-icon" href="/apple-touch-icon.png">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
  <link rel="stylesheet prefetch" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
</head>

<body>
  <div class="container-fluid">
    <h1 class="header">
      FreeCodeCamp API: Timestamp Microservice
    </h1>
    <blockquote>
      User stories:
      <ul>1) I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016)</ul>
      <ul>2) If it does, it returns both the Unix timestamp and the natural language form of that date.</ul>
      <ul>3) If it does not contain a date or Unix timestamp, it returns null for those properties.</ul>
    </blockquote>
    <h3>Example usage:</h3>
    <code>https://r282-timestamp-api.herokuapp.com/December%2015,%202015</code>
    <br>
    <code>https://r282-timestamp-api.herokuapp.com/1450137600</code>
    <h3>Example output:</h3>
    <code>
      { "unix": 1450137600, "natural": "December 15, 2015" }
    </code>
  </div>
</body>

</html>
