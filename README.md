# Date-night
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dinner Date?</title>
<style>
  body {
    font-family: "Segoe UI", sans-serif;
    background: linear-gradient(135deg, #fff3e6, #ffe0cc);
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    margin: 0;
    padding: 20px;
    text-align: center;
  }

  .card {
    background: white;
    padding: 25px;
    border-radius: 20px;
    box-shadow: 0 15px 40px rgba(0,0,0,0.15);
    width: 100%;
    max-width: 400px;
  }

  h1 {
    font-size: 24px;
    margin-bottom: 10px;
  }

  p {
    font-size: 16px;
    color: #444;
  }

  .emoji {
    font-size: 50px;
    margin: 15px 0;
  }

  button {
    margin: 10px;
    padding: 12px 20px;
    font-size: 16px;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    transition: all 0.2s ease;
  }

  .yes {
    background-color: #ff7a59;
    color: white;
  }

  .no {
    background-color: #ddd;
    color: #555;
    position: relative;
  }

  .yes:hover { background-color: #ff5a36; }

  @media (max-width: 400px) {
    h1 { font-size: 22px; }
    .emoji { font-size: 40px; }
    button { font-size: 14px; padding: 10px 16px; }
  }
</style>
</head>
<body>
<div class="card">
  <h1>Hello Handsome 👀
