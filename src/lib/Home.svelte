<script>
  import scifi_back from "../assets/scifi-back.png"
  // TODO: DYNAMICALLY CALC FONT SIZE
</script>

<main>
  <div>
    
  </div>
  
</main>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Inter:wght@100..900&display=swap');
  main {
    margin: inherit;
    width: 100%;

  }
  img {
    opacity: 0.8;
    aspect-ratio: 1440 / 850;
    width: 100vw;
  }
  .overlay-container {
    position: relative;
  }
  .img-container {
    overflow: hidden;
    margin: 0;
  }
  .overlay {
    position: absolute;
    left: 5%;
    top: 15%;
    font-family: "Inter", monospace;
    color: white;
    position: absolute;
    font-weight: 600;
  }
  .fancy {
    font-family: "Great Vibes";
    font-weight: normal;
    color: aqua;
    font-size: clamp(60px, 8rem, 200px);
    margin-bottom: -2rem;

  }
</style>