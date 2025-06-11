# lashes-by-stefany-menu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>S.O. Aesthetics - Service Menu</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ff69b4, #ff1493, #da70d6);
            font-family: 'Georgia', serif;
            color: #2c2c2c;
            min-height: 100vh;
            position: relative;
            overflow-x: hidden;
        }

        /* Glitter animation */
        .glitter {
            position: absolute;
            width: 4px;
            height: 4px;
            background: silver;
            border-radius: 50%;
            animation: fall linear infinite;
            opacity: 0.8;
        }

        .glitter.pink {
            background: #ff69b4;
        }

        .glitter.silver {
            background: silver;
        }

        @keyframes fall {
            0% {
                transform: translateY(-100vh) rotate(0deg);
                opacity: 1;
            }
            100% {
                transform: translateY(100vh) rotate(360deg);
                opacity: 0;
            }
        }

        .container {
            max-width: 600px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
            overflow: hidden;
            position: relative;
            z-index: 10;
            margin-top: 20px;
            margin-bottom: 20px;
        }

        .header {
            background: linear-gradient(135deg, #ff69b4, #da70d6);
            padding: 30px;
            text-align: center;
            color: white;
            position: relative;
        }

        .business-name {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .tagline {
            font-size: 1.1em;
            font-style: italic;
            margin-bottom: 15px;
            opacity: 0.9;
        }

        .address {
            font-size: 1em;
            margin-bottom: 5px;
        }

        .phone {
            font-size: 1.2em;
            font-weight: bold;
        }

        .content {
            padding: 30px;
        }

        .section {
            margin-bottom: 40px;
        }

        .section-title {
            font-size: 1.8em;
            font-weight: bold;
            text-align: center;
            margin-bottom: 20px;
            color: #ff1493;
            border-bottom: 3px solid #ff69b4;
            padding-bottom: 10px;
        }

        .service-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 0;
            border-bottom: 1px solid #f0f0f0;
        }

        .service-item:last-child {
            border-bottom: none;
        }

        .service-name {
            font-size: 1.1em;
            font-weight: 500;
        }

        .service-price {
            font-size: 1.2em;
            font-weight: bold;
            color: #ff1493;
        }

        .note {
            text-align: center;
            font-style: italic;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 2px solid #ff69b4;
            color: #666;
        }

        .booking-info {
            text-align: center;
            margin-top: 20px;
            font-weight: bold;
            color: #ff1493;
            font-size: 1.1em;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .container {
                margin: 10px;
                border-radius: 15px;
            }
            
            .business-name {
                font-size: 2em;
            }
            
            .content {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <!-- Glitter particles -->
    <div class="glitter silver" style="left: 10%; animation-duration: 3s; animation-delay: 0s;"></div>
    <div class="glitter pink" style="left: 20%; animation-duration: 4s; animation-delay: 0.5s;"></div>
    <div class="glitter silver" style="left: 30%; animation-duration: 3.5s; animation-delay: 1s;"></div>
    <div class="glitter pink" style="left: 40%; animation-duration: 4.5s; animation-delay: 1.5s;"></div>
    <div class="glitter silver" style="left: 50%; animation-duration: 3s; animation-delay: 2s;"></div>
    <div class="glitter pink" style="left: 60%; animation-duration: 4s; animation-delay: 2.5s;"></div>
    <div class="glitter silver" style="left: 70%; animation-duration: 3.5s; animation-delay: 3s;"></div>
    <div class="glitter pink" style="left: 80%; animation-duration: 4.5s; animation-delay: 3.5s;"></div>
    <div class="glitter silver" style="left: 90%; animation-duration: 3s; animation-delay: 4s;"></div>
    <div class="glitter pink" style="left: 15%; animation-duration: 4s; animation-delay: 4.5s;"></div>
    <div class="glitter silver" style="left: 25%; animation-duration: 3.5s; animation-delay: 5s;"></div>
    <div class="glitter pink" style="left: 35%; animation-duration: 4.5s; animation-delay: 5.5s;"></div>
    <div class="glitter silver" style="left: 45%; animation-duration: 3s; animation-delay: 6s;"></div>
    <div class="glitter pink" style="left: 55%; animation-duration: 4s; animation-delay: 6.5s;"></div>
    <div class="glitter silver" style="left: 65%; animation-duration: 3.5s; animation-delay: 7s;"></div>
    <div class="glitter pink" style="left: 75%; animation-duration: 4.5s; animation-delay: 7.5s;"></div>
    <div class="glitter silver" style="left: 85%; animation-duration: 3s; animation-delay: 8s;"></div>
    <div class="glitter pink" style="left: 95%; animation-duration: 4s; animation-delay: 8.5s;"></div>

    <div class="container">
        <div class="header">
            <div class="business-name">Lashes by Stefany</div>
            <div class="tagline">Luxury Lash & Beauty Studio ✨<br>Where detail meets distinction</div>
            <div class="address">📍 Morristown, TN</div>
            <div class="phone">+(423) 231-6930</div>
        </div>

        <div class="content">
            <div class="section">
                <div class="section-title">Full Sets</div>
                <div class="service-item">
                    <div class="service-name">Angel</div>
                    <div class="service-price">$110</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Light-Volume</div>
                    <div class="service-price">$115</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Volume</div>
                    <div class="service-price">$120</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Mega-Volume</div>
                    <div class="service-price">$125</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Wispy Volume</div>
                    <div class="service-price">$130</div>
                </div>
            </div>

            <div class="section">
                <div class="section-title">Weekly Fills</div>
                <div class="service-item">
                    <div class="service-name">Angel</div>
                    <div class="service-price">$40</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Light-Volume</div>
                    <div class="service-price">$45</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Volume</div>
                    <div class="service-price">$50</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Mega-Volume</div>
                    <div class="service-price">$55</div>
                </div>
            </div>

            <div class="section">
                <div class="section-title">2 Week Fills</div>
                <div class="service-item">
                    <div class="service-name">Angel</div>
                    <div class="service-price">$50</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Light-Volume</div>
                    <div class="service-price">$55</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Volume</div>
                    <div class="service-price">$60</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Mega-Volume</div>
                    <div class="service-price">$65</div>
                </div>
            </div>

            <div class="section">
                <div class="section-title">Lash Add-ons</div>
                <div class="service-item">
                    <div class="service-name">Lash Removal</div>
                    <div class="service-price">$30</div>
                </div>
                <div class="service-item">
                    <div class="service-name">Color & Glitter Lashes</div>
                    <div class="service-price">10+</div>
                </div>
            </div>

            <div class="note">
                Note: Prices are subject to change
            </div>

            <div class="booking-info">
                By appointment only | DM to book 📦💋
            </div>
        </div>
    </div>

    <script>
        // Add more dynamic glitter
        function createGlitter() {
            const glitter = document.createElement('div');
            glitter.className = Math.random() > 0.5 ? 'glitter silver' : 'glitter pink';
            glitter.style.left = Math.random() * 100 + '%';
            glitter.style.animationDuration = (Math.random() * 3 + 2) + 's';
            glitter.style.animationDelay = Math.random() * 2 + 's';
            document.body.appendChild(glitter);

            // Remove glitter after animation
            setTimeout(() => {
                if (glitter.parentNode) {
                    glitter.parentNode.removeChild(glitter);
                }
            }, 6000);
        }

        // Create new glitter every 500ms
        setInterval(createGlitter, 500);
    </script>
</body>
</html>
