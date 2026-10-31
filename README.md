# Solukhumbu360
Solukhumbu nature, culture and society 
<!DOCTYPE html>
<html lang="ne">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Solukhumbu360 - सोलुखुम्बु सूचना तथा सञ्चार</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f6f9; color: #333; }
        header { background: #004080; color: white; padding: 15px; text-align: center; }
        nav { background: #002b55; display: flex; justify-content: center; flex-wrap: wrap; }
        nav a { color: white; padding: 12px 18px; text-decoration: none; font-weight: bold; }
        nav a:hover { background: #0059b3; }
        .top-info { background: #e0e0e0; padding: 8px 20px; font-size: 14px; display: flex; justify-content: space-between; flex-wrap: wrap; }
        .container { width: 90%; max-width: 1100px; margin: 20px auto; }
        .section-card { background: white; padding: 20px; border-radius: 8px; margin-bottom: 25px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        h2 { color: #004080; border-bottom: 2px solid #004080; padding-bottom: 5px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
        iframe { width: 100%; height: 200px; border: none; border-radius: 5px; }
        footer { background: #002b55; color: white; text-align: center; padding: 15px; margin-top: 30px; }
    </style>
</head>
<body>

    <!-- १. माथिल्लो पट्टी: मिति, समय र मौसम -->
    <div class="top-info">
        <div>📅 मिति र समय: <span id="dateTime"></span></div>
        <div>🌤️ मौसम (सोलुखुम्बु): २५°C (घाम लागेको)</div>
    </div>

    <!-- २. मुख्य हेडर -->
    <header>
        <h1>Solukhumbu360</h1>
        <p>सोलुखुम्बुको प्रकृति, संस्कृति, समाचार र सूचना</p>
    </header>

    <!-- ३. नेभिगेसन मेनु -->
    <nav>
        <a href="#news">समाचार</a>
        <a href="#literature">साहित्य र लेख</a>
        <a href="#media">गीत, संगीत र भिडियो</a>
        <a href="#radio">रेडियो</a>
        <a href="#gallery">फोटो ग्यालरी</a>
        <a href="#about">हाम्रो बारेमा</a>
        <a href="#contact">सम्पर्क</a>
    </nav>

    <div class="container">

        <!-- ४. ताजा समाचार -->
        <div id="news" class="section-card">
            <h2>📰 ताजा समाचार</h2>
            <div class="grid">
                <div>
                    <h3>सोलुखुम्बुमा पर्यटकीय गतिविधि बढ्दै</h3>
                    <p>सगरमाथा क्षेत्रमा यस वर्ष पर्यटकहरूको चहलपहल बाक्लो भएको छ...</p>
                </div>
            </div>
        </div>

        <!-- ५. लेख रचना तथा साहित्य -->
        <div id="literature" class="section-card">
            <h2>✍️ लेख रचना तथा साहित्य</h2>
            <h3>सोलुखुम्बुको सौन्दर्य (कविता)</h3>
            <p>हिउँका चुचुरा टल्कने ठाउँ,<br>सुन्दर हाम्रो सोलुखुम्बु गाउँ...</p>
        </div>

        <!-- ६. भिडियो तथा गीत संगीत -->
        <div id="media" class="section-card">
            <h2>🎬 भिडियो तथा गीत संगीत</h2>
            <div class="grid">
                <div>
                    <h3>सोलुखुम्बु वृत्तचित्र</h3>
                    <!-- YouTube Video Link -->
                    <iframe src="https://www.youtube.com/embed/tgbNymZ7vqY"></iframe>
                </div>
            </div>
        </div>

        <!-- ७. रेडियो -->
        <div id="radio" class="section-card">
            <h2>📻 एफ.एम. रेडियो</h2>
            <p>सोलुखुम्बुका स्थानीय रेडियो कार्यक्रमहरू यहाँबाट सुन्नुहोस्:</p>
            <audio controls style="width: 100%;">
                <source src="your-audio-link.mp3" type="audio/mpeg">
                तपाईंको ब्राउजरले अडियो सपोर्ट गरेन।
            </audio>
        </div>

        <!-- ८. फोटो ग्यालरी -->
        <div id="gallery" class="section-card">
            <h2>🖼️ फोटो ग्यालरी</h2>
            <div class="grid">
                <img src="photo1.jpg" alt="Solukhumbu" style="width:100%; border-radius:5px;">
            </div>
        </div>

        <!-- ९. हाम्रो बारेमा -->
        <div id="about" class="section-card">
            <h2>ℹ️ हाम्रो बारेमा</h2>
            <p>Solukhumbu360 सोलुखुम्बुका विभिन्न गतिविधि, समाचार, कला, संस्कृति र पर्यटन प्रवर्द्धनका लागि तयार पारिएको डिजिटल प्लेटफर्म हो।</p>
        </div>

        <!-- १०. सम्पर्क -->
        <div id="contact" class="section-card">
            <h2>📞 सम्पर्क</h2>
            <p>📧 इमेल: info@solukhumbu360.com</p>
            <p>📍 ठेगाना: सोलुखुम्बु, नेपाल</p>
        </div>

    </div>

    <footer>
        <p>&copy; 2026 Solukhumbu360. All Rights Reserved.</p>
    </footer>

    <!-- मिति र समय देखाउने स्क्रिप्ट -->
    <script>
        function updateDateTime() {
            const now = new Date();
            document.getElementById('dateTime').innerText = now.toLocaleString('ne-NP');
        }
        setInterval(updateDateTime, 1000);
        updateDateTime();
    </script>

</body>
</html>
