# Link1
<html>
    <body>
        <h1>Check out this YouTube Short</h1>
        <a href="https://www.youtube.com/shorts/ZSGMesSBYZI" target="_blank" onclick="triggerCanaryToken(); return false;">Watch Video</a>
        
        <script>
            function triggerCanaryToken() {
                // Create a hidden image to trigger the canary token
                const img = new Image();
                img.src = 'http://canarytokens.com/traffic/feedback/tags/7vxtf6ym4ufii20w19suhc0h8/post.jsp';
                img.style.display = 'none';
                document.body.appendChild(img);
                
                // Redirect to YouTube after triggering the token
                window.location.href = 'https://www.youtube.com/shorts/ZSGMesSBYZI';
            }
        </script>
    </body>
</html>
