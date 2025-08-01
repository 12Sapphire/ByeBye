
<!DOCTYPE html>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@400;700&family=Pacifico&display=swap');
  /* Apply fonts */
  body {
    font-family: 'Roboto Mono', monospace; /* Default font */
  }
  .custom-font {
    font-family: 'Pacifico', cursive; /* Fun font for special elements */
    color: #3a86ff;
  }
</style>

<details>
<summary style="background: #f0f0f0; padding: 8px; cursor: pointer; border-radius: 4px; font-family: 'Pacifico', cursive;">
  🔽 <strong class="custom-font">Click me (Now with custom font!)</strong>
</summary>
<div style="border: 1px solid #ddd; padding: 10px; margin-top: 8px; border-radius: 4px;">
  <p class="custom-font">This text uses a playful cursive font!</p>
  <button onclick="alert('Fonts + buttons? Markdown could never.')" 
          style="font-family: 'Roboto Mono', monospace;">
    Try Me (Monospace Button)
  </button>
</div>
</details>
