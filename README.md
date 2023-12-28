<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Editor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1em;
            text-align: center;
        }

        main {
            padding: 2em;
            text-align: center;
        }

        img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 5px;
            margin-bottom: 10px;
        }

        button {
            padding: 10px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Photo Editor</h1>
    </header>
    <main>
        <img id="editedPhoto" src="placeholder.jpg" alt="Edited Photo">
        <br>
        <button onclick="applyFilter()">Apply Filter</button>
    </main>

    <script>
        function applyFilter() {
            // Add your photo editing logic here
            alert("Filter applied!");
        }
    </script>
</body>
</html>
