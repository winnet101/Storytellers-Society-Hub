<menu>
  <a href="">About Us</a>
  <a href="">Calendar</a>
  <a href="">Resources</a>
  <a href="">Contact us!</a>
</menu>

<style>
  menu {
    margin: 0;
    padding-inline-start: 0;
    display: flex;
    justify-content: space-around;
    color: rgba(255, 255, 255, 0.87);
    background-color: #242424;
  }
  a {
    color: inherit;
    text-decoration: none;
    width: max-content;
    padding: 10px;
    width: 25%;

    display: grid;
    justify-items: center;

    transition:
      0.2s background-color,
      0.2s text-shadow,
      0.2s color;
  }
  a:hover {
    background-color: black;
    color: white;
    text-shadow: 0 0 5px white;
  }
</style>
