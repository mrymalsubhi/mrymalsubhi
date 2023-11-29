html
<!DOCTYPE html>
<html>
<head>
<style>
/* Style the moving text */
@keyframes movingText {
    0% { transform: translateX(-100%); }
    100% { transform: translateX(100%); }
}

/* Style the text and set animation properties */
.text {
    color: #FF69B4; /* Set the text color */
    font-size: 24px;
    text-align: center;
    animation: movingText 8s linear infinite;
}
</style>
</head>
<body>
<h1 class="text">Welcome to my GitHub profile</h1>
<h2 class="text">I am Maryam Alsubhi</h2>
<h3 class="text">I am a data analyst</h3>
</body>
</html>
