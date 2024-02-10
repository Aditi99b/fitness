---
layout: default
title: Student Blog
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parallax Scrolling</title>
    <style>
        /* Add some basic styling */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
        }
        
        .parallax-container {
            height: 200%; /* Set the height to 200% to allow for scrolling */
            width: 100%;
            overflow-x: hidden;
            overflow-y: auto;
            position: relative;
            margin-bottom: 10px; /* Leave 10px of blank space at the bottom */
        }

        .parallax-image {
            background-size: cover;
            background-position: center;
            height: calc(70vh - 3px); /* Set the height to 50% of the viewport height minus 3 pixels */
            width: 100%;
            border: 8px ;
            box-sizing: border-box;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: calc(10vh + 3px); /* Center the image vertically */
        }


        /* Create the parallax scrolling effect */
        .parallax-image {
            background-attachment: fixed;
        }

        
    </style>
</head>
<body>

<div class="parallax-container">
    <div class="parallax-image" style="background-image: url('https://w0.peakpx.com/wallpaper/595/522/HD-wallpaper-grapefruit-lemonade-pink-drink-lemon-lime.jpg')"></div>
    <div class="parallax-image" style="background-image: url('https://wallpapers.com/images/hd/heartbeat-neon-dark-pink-sdmjcfbn14ol4nvy.jpg')"></div>
    <div class="parallax-image" style="background-image: url('https://img.freepik.com/premium-photo/bed-sleep-stands-pink-clouds-good-soft-sleep_124715-2921.jpg ')"></div>
    <div class="parallax-image" style="background-image: url('https://images.squarespace-cdn.com/content/v1/5b147413a9e02837b93f4066/1587961394040-XMRUTY3OL4NT6B50TIXD/PopTennis-14x11.jpg')"></div>
    <div class="parallax-bar bar1"></div>
    <div class="parallax-bar bar2"></div>
    <div class="parallax-bar bar3"></div>
    <div class="parallax-bar bar4"></div>
</div>

</body>
</html>
