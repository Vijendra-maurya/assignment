
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>How a Webpage Loads</title>
</head>
<body>
    <h1>What Happens When You Type a URL?</h1>

    <p>
        When you type a URL into a web browser and press Enter, the browser
        first uses DNS (Domain Name System) to find the IP address of the
        website's server. It then establishes a connection with the server
        using TCP and, for HTTPS websites, performs a TLS handshake to create
        a secure connection. The browser sends an HTTP request to the server,
        which processes the request and sends back an HTTP response containing
        HTML, CSS, JavaScript, images, and other resources. The browser parses
        the HTML to build the DOM (Document Object Model), processes CSS to
        create the CSSOM (CSS Object Model), executes JavaScript, and renders
        the page. Finally, the browser displays the webpage on the screen.
    </p>
</body>
</html>
