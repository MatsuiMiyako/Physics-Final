<p align="center">
  <video width="400" autoplay loop muted playsinline controls>
    <source src="media/Steps/Step 19.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</p>
<em>A little audio sample on what the microphone sounds like.</em>

<!-- Optional: Add a fallback play button for stricter browsers -->
<button onclick="document.getElementById('step19-video').play()" 
        style="display: none; margin: 10px auto; padding: 8px 16px;"
        id="play-fallback">
  Click to play video
</button>
<script>
  // Handle autoplay restrictions
  const video = document.querySelector('video');
  const fallbackBtn = document.getElementById('play-fallback');
  
  video.addEventListener('loadeddata', () => {
    const playPromise = video.play();
    
    if (playPromise !== undefined) {
      playPromise.catch(() => {
        // Autoplay failed, show fallback button
        fallbackBtn.style.display = 'block';
        video.controls = true; // Ensure controls are visible
      });
    }
  });
</script>


<div class="step-nav" style="
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 15px;
  margin-top: 3em;
  padding-top: 2em;
  border-top: 1px solid #2a2a2a;
">
  <a href="Step 18.md" style="
    padding: 10px 20px;
    background: #2a2a2a;
    color: white;
    border-radius: 6px;
    text-decoration: none;
    font-size: 14px;
  ">← Back</a>
  
  <span style="
    padding: 10px 20px;
    color: #7b97aa;
    font-size: 14px;
    border-radius: 6px;
	font-weight: bold;
  ">Step 19</span>
  
  <a href="FAQ.md" style="
    padding: 10px 20px;
    background: #6c63ff;
    color: white;
    border-radius: 6px;
    text-decoration: none;
    font-size: 14px;
  ">Next →</a>
</div>