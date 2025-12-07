<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Photo Story | The Lone Horizon</title>

<style>
    body {
        margin: 0;
        font-family: "Poppins", sans-serif;
        background: #000;
        color: #fff;
        overflow-x: hidden;
    }

    /* HERO SECTION */
    .hero {
        width: 100%;
        height: 90vh;
        background: url('https://images.unsplash.com/photo-1469474968028-56623f02e42e?auto=format&fit=crop&w=900&q=80');
        background-size: cover;
        background-position: center;
        display: flex;
        align-items: flex-end;
        padding: 50px;
        box-shadow: 0 0 40px rgba(255,255,255,0.2);
    }

    .hero h1 {
        font-size: 55px;
        background: rgba(0,0,0,0.55);
        padding: 15px 25px;
        border-radius: 10px;
        backdrop-filter: blur(4px);
        box-shadow: 0 0 25px rgba(255,255,255,0.15);
    }

    /* STORY SECTION */
    .story {
        padding: 70px 10%;
        line-height: 1.8;
        font-size: 18px;
        animation: fadeIn 1.5s ease-in-out;
    }

    .story h2 {
        font-size: 36px;
        margin-bottom: 15px;
        color: #f6e05e;
    }

    .story p {
        opacity: 0.9;
        margin-bottom: 25px;
    }

    /* TIMELINE */
    .timeline {
        padding: 60px 10%;
    }

    .timeline h2 {
        font-size: 36px;
        margin-bottom: 25px;
        text-align: center;
        color: #f6e05e;
    }

    .event {
        background: #111;
        padding: 20px;
        border-radius: 12px;
        margin-bottom: 30px;
        box-shadow: 0 0 25px rgba(255,255,255,0.08);
        transition: transform .4s ease, box-shadow .4s ease;
    }

    .event:hover {
        transform: translateY(-10px);
        box-shadow: 0 0 35px rgba(255,255,255,0.15);
    }

    .event h3 {
        font-size: 24px;
        margin-bottom: 10px;
    }

    .event p {
        opacity: 0.85;
        font-size: 17px;
    }

    /* BUTTONS */
    .buttons {
        text-align: center;
        margin: 50px 0;
    }

    .btn {
        padding: 12px 28px;
        margin: 10px;
        background: transparent;
        border: 2px solid #fff;
        color: #fff;
        font-size: 17px;
        border-radius: 8px;
        cursor: pointer;
        transition: 0.4s ease;
    }

    .btn:hover {
        background: #fff;
        color: #000;
    }

    footer {
        text-align: center;
        padding: 40px 10px;
        opacity: 0.6;
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to   { opacity: 1; transform: translateY(0); }
    }
</style>

</head>
<body>

<!-- HERO -->
<div class="hero">
    <h1>The Misty Mountains</h1>
</div>

<!-- STORY SECTION -->
<section class="story">
    <h2>The Story Behind the Photograph</h2>
    <p>
        This image captures a breathtaking moment when the sun dipped low over the mountains,
        casting golden light across layer after layer of untouched wilderness.
        A lone figure stands at the summit, dwarfed by the immensity of nature — a powerful reminder
        of solitude, resilience, and the quiet beauty found in remote places.
    </p>

    <p>
        The photograph was taken during an early morning hike after hours of climbing.
        The silence, the wind, and the glow of first sunlight aligned perfectly, creating a moment
        that felt almost unreal. The tension between earth and sky, shadows and light, makes this
        image emotionally charged and visually striking.
    </p>
</section>

<!-- TIMELINE EVENTS -->
<section class="timeline">
    <h2>Photo Timeline & Key Moments</h2>

    <div class="event">
        <h3>📅 Date Captured</h3>
        <p>August 14, 2023 — just after sunrise, with fog still clinging to the valley below.</p>
    </div>

    <div class="event">
        <h3>🎯 Why It Was Captured</h3>
        <p>
            To capture the overwhelming scale of nature and the quiet power of human exploration.
            The lone figure symbolizes courage, adventure, and freedom.
        </p>
    </div>

    <div class="event">
        <h3>📸 How It Was Captured</h3>
        <p>
            Shot using a full-frame mirrorless camera at 200mm, ISO 200, f/5.6, 1/400s.  
            A tripod, remote shutter, and long-distance timing were used to create a dramatic sense of depth.
        </p>
    </div>

    <div class="event">
        <h3>🏆 Why It Was Awarded</h3>
        <p>
            This photograph received recognition for its composition, cinematic lighting,
            emotional depth, and ability to tell a story without a single word.
            The contrast of the massive landscape with the tiny human form creates a powerful narrative.
        </p>
    </div>
</section>

<!-- BUTTONS -->
<div class="buttons">
    <button class="btn" onclick="openFullscreen()">View Fullscreen</button>
    <button class="btn" onclick="downloadImage()">Download Image</button>
    </div>


<script>
function openFullscreen() {
    const imgURL = "https://images.unsplash.com/photo-1469474968028-56623f02e42e?auto=format&fit=crop&w=900&q=80";
    const newWindow = window.open("", "_blank");
    newWindow.document.write("<img src='" + imgURL + "' style='width:100%; height:auto;'>");
}

function downloadImage() {
    const link = document.createElement('a');
    link.href = "https://images.unsplash.com/photo-1469474968028-56623f02e42e?auto=format&fit=crop&w=900&q=80";
    link.download = "photo_story.jpg";
    link.click();
}
</script>

</body>
</html>
