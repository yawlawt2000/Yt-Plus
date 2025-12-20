<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One Click Download</title>
    <style>
        /* ခလုတ်ကို ပုံစံဖော်ခြင်း */
        .download-btn {
            background-color: #007bff; /* အပြာရောင် */
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            text-decoration: none;
            display: inline-block;
            transition: background-color 0.3s ease;
        }

        /* Mouse တင်လိုက်ရင် အရောင်ပြောင်းရန် */
        .download-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <h2>One Click Download Button</h2>
    
    <a href="your-file-path.zip" download="filename" class="download-btn">
        Download Now
    </a>

</body>
</html>

