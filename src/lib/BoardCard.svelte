<script lang="ts">
  export let name: string;
  export let grade: number;
  export let desc: string;
</script>

<div class="card">
  <div class="img-container">
    <img height=200 class="img">
    <div class="grade">{grade}</div>
  </div>
  <div class="heading">{name}</div> 
  <div>{desc}</div>
</div>

<style>
  .card {
    display: flex;
    flex-direction: column;
    border: solid white 2px;
    border-radius: 10px;
    width: 220px;
    height: 300px;
    padding: 10px;
    margin: 10px
  }
  
  .heading {
    width: max-content;
    display: inline;
    font-weight: bold;
    font-size: 1.5em;
  }

  .img-container {
    position: relative;
    border: b
  }

  .img {
    background: white;
  }

  .grade {
    background-color: green;
    width: 40px;
    height: 35px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    border-radius: 5px;
    position: absolute;
    right: 10px;
    bottom: 10px;
  }
  
</style>