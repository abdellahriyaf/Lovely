<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Special Message</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400&display=swap');

        body {
            text-align: center;
            font-family: 'Poppins', sans-serif;
            background-color: #ffebf0;
            color: #8a2c55;
            padding: 20px;
        }

        h2 {
            font-family: 'Great Vibes', cursive;
            font-size: 36px;
            color: #d63384;
            margin-bottom: 10px;
        }

        p {
            font-size: 18px;
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }

        /* Rabbit Container */
        .rabbit-container {
            position: relative;
            width: 180px;
            margin: 30px auto;
        }

        .rabbit {
            position: relative;
            width: 120px;
            height: 150px;
            animation: bounce 2s infinite ease-in-out;
        }

        /* Rabbit Ears */
        .ear {
            width: 30px;
            height: 70px;
            background: white;
            border-radius: 50%;
            position: absolute;
            top: 0;
            left: 15px;
            border: 2px solid #000;
        }

        .ear.right {
            left: auto;
            right: 15px;
        }

        .inner-ear {
            width: 15px;
            height: 50px;
            background: pink;
            border-radius: 50%;
            position: absolute;
            top: 10px;
            left: 7px;
        }

        /* Rabbit Face */
        .face {
            width: 100px;
            height: 100px;
            background: white;
            border-radius: 50%;
            position: absolute;
            top: 40px;
            left: 10px;
            border: 2px solid #000;
        }

        /* Eyes */
        .eye {
            width: 10px;
            height: 10px;
            background: black;
            border-radius: 50%;
            position: absolute;
            top: 30px;
            left: 25px;
        }

        .eye.right {
            left: auto;
            right: 25px;
        }

        /* Rabbit Nose */
        .nose {
            width: 10px;
            height: 7px;
            background: pink;
            border-radius: 50%;
            position: absolute;
            top: 45px;
            left: 45px;
        }

        /* Chocolate Bar */
        .chocolate {
            width: 40px;
            height: 30px;
            background: #5C3317;
            position: absolute;
            top: 70px;
            left: 40px;
            border-radius: 5px;
            border: 2px solid #000;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-content: space-between;
            padding: 3px;
        }

        /* Chocolate Segments */
        .choco-segment {
            width: 15px;
            height: 12px;
            background: #8B4513;
            border-radius: 2px;
            border: 1px solid #000;
        }

        /* Bite Mark (Missing Segment) */
        .bite {
            width: 10px;
            height: 10px;
            background: #ffebf0;
            border-radius: 50%;
            position: absolute;
            top: -5px;
            right: 0;
        }

        /* Hands */
        .hand {
            width: 20px;
            height: 40px;
            background: white;
            border-radius: 50%;
            position: absolute;
            top: 80px;
            left: 20px;
            border: 2px solid #000;
            z-index: 1;
        }

        .hand.right {
            left: auto;
            right: 20px;
        }

        /* Love Heart Animation */
        .heart {
            position: absolute;
            top: -10px;
            left: 50%;
            transform: translateX(-50%);
            font-size: 18px;
            color: red;
            opacity: 0;
            animation: love 2s infinite;
        }

        @keyframes love {
            0% { opacity: 0; transform: translateY(0) scale(1); }
            50% { opacity: 1; transform: translateY(-15px) scale(1.2); }
            100% { opacity: 0; transform: translateY(-30px) scale(1); }
        }

        /* Rabbit Bouncing Animation */
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        /* Message Box */
        .message {
            font-size: 20px;
            font-weight: 400;
            color: #5a1d44;
            margin-top: 20px;
            background: white;
            padding: 15px;
            border-radius: 10px;
            display: inline-block;
            box-shadow: 3px 3px 15px rgba(0, 0, 0, 0.15);
            max-width: 600px;
        }

    </style>
</head>
<body>

    <h2>💖 Someone Has a Message for You 💖</h2>

    <div class="rabbit-container">
        <div class="rabbit">
            <div class="ear"><div class="inner-ear"></div></div>
            <div class="ear right"><div class="inner-ear"></div></div>
            <div class="face">
                <div class="eye"></div>
                <div class="eye right"></div>
                <div class="nose"></div>
            </div>
            <div class="chocolate">
                <div class="choco-segment"></div>
                <div class="choco-segment"></div>
                <div class="choco-segment"></div>
                <div class="choco-segment"></div>
                <div class="bite"></div>
            </div>
            <div class="hand"></div>
            <div class="hand right"></div>
            <div class="heart">❤️</div>
        </div>
    </div>

    <div class="message">
        "Someone is trying to tell you that no matter what happens,  
        he will stay loyal to your heart and never let you go.  
        He feels everything you feel—happiness, anger, pain.  
        In those moments, he faces the harsh reality of the world,  
        longing for someone to heal his wounds.  
        But he never found anyone quite like you.  
        He hopes he is treating you well—he is trying his best.  
        He also hopes you'll stay by his side,  
        because without you, he would disappear...  
        as if he was never here at all."
    </div>

</body>
</html>
