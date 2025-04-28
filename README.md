<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Partner in Crime</title>
    <style>
        /* Gaya umum untuk gambar */
        .book {
            width: 150px;
            height: auto;
            cursor: pointer;
            transition: transform 0.3s ease;
            border-radius: 10px;
        }

        .book:hover {
            transform: scale(1.1); /* Membesarkan gambar saat hover */
        }

        /* Gaya untuk kontainer gambar */
        .button-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Would you be my partner in crime forever?</h1>
    <div class="button-container">
        <div class="yes-wrapper">
            <img class="book" src="https://example.com/your-book-image.jpg" alt="Partner in Crime Book" />
        </div>
    </div>
</body>
</html>