<!DOCTYPE html>
<html>
<head>
    <title>Background Image Example</title>
    <style>
        body {
            background-image: url('logo.png');
            background-position: bottom right;
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-color: lightgray;
        }

        p {
            font-size: 16px;
            color: blue;
            text-indent: 2em;
            font-family: Arial, sans-serif;
        }

        .logo {
            font-family: Arial, sans-serif;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <p>
        This example uses the background-image, background-position and background-attachment
        styles to place the <span class="logo">Deitel & Associates, Inc.</span> logo in the
        bottom-right corner of the page. Notice how the logo
        stays in the proper position when you resize the
        browser window. The background-color fills in where
        there is no image.
    </p>
</body>
</html>
