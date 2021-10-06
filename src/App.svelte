<script>

</script>





<main>
<link rel="preload" href="https://fonts.googleapis.com">
<link rel="preload" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">



<!-- Toolbar -->
<div class="header" role="banner">
	<h2 style="margin-left: 20px;">Webapp</h2>
		<div class="spacer"></div>
		<h2 style="margin-right: 20px;">placeholder</h2>
</div>

<div class="content" role="main">

<div class="column">
	<h2 id="title">Welcome to Webapp</h2>
</div>


<div class="column">
	<p>Already have an account?</p>
	<form>
	<input type="text" id="email" placeholder="Email address">
	<br>
	<input type="password" id="pass" placeholder="Password">
	</form>
	<div class="card-container">
		<a class="card" target="_blank" rel="noopener">
			<span>Login</span>

			<svg class="material-icons" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M10 6L8.59 7.41 13.17 12l-4.58 4.59L10 18l6-6z"/></svg>    </a>
	</div>
<br>
	<p>New here?</p>
	<div class="card-container">
		<a class="card" target="_blank" rel="noopener">
			<span>Create Account</span>

			<svg class="material-icons" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M10 6L8.59 7.41 13.17 12l-4.58 4.59L10 18l6-6z"/></svg>    </a>
	</div>

</div>




	<svg id="clouds" alt="Gray Clouds Background" xmlns="http://www.w3.org/2000/svg" width="2611.084" height="485.677" viewBox="0 0 2611.084 485.677">
		<path id="Path_39" data-name="Path 39" d="M2379.709,863.793c10-93-77-171-168-149-52-114-225-105-264,15-75,3-140,59-152,133-30,2.83-66.725,9.829-93.5,26.25-26.771-16.421-63.5-23.42-93.5-26.25-12-74-77-130-152-133-39-120-212-129-264-15-54.084-13.075-106.753,9.173-138.488,48.9-31.734-39.726-84.4-61.974-138.487-48.9-52-114-225-105-264,15a162.027,162.027,0,0,0-103.147,43.044c-30.633-45.365-87.1-72.091-145.206-58.044-52-114-225-105-264,15-75,3-140,59-152,133-53,5-127,23-130,83-2,42,35,72,70,86,49,20,106,18,157,5a165.625,165.625,0,0,0,120,0c47,94,178,113,251,33,61.112,8.015,113.854-5.72,150.492-29.764a165.62,165.62,0,0,0,110.861-3.236c47,94,178,113,251,33,31.385,4.116,60.563,2.495,86.487-3.311,25.924,5.806,55.1,7.427,86.488,3.311,73,80,204,61,251-33a165.625,165.625,0,0,0,120,0c51,13,108,15,157-5a147.188,147.188,0,0,0,33.5-18.694,147.217,147.217,0,0,0,33.5,18.694c49,20,106,18,157,5a165.625,165.625,0,0,0,120,0c47,94,178,113,251,33C2446.709,1093.793,2554.709,922.793,2379.709,863.793Z" transform="translate(142.69 -634.312)" fill="#eee"/>
	</svg>

</div>

<footer>
		Webapp &copy; 2021
</footer>
</main>

<style>
#title {
	margin: 8px;
	font-family: 'Montserrat', sans-serif;
	font-size: xx-large;
}

  :host {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
    font-size: 14px;
    color: #333;
    box-sizing: border-box;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  h1, h3, h4, h5, h6 {
    margin: 8px;
    font-family: 'Montserrat', sans-serif;
  }

  h2 {
    margin: 8px;
    font-family: 'Montserrat', sans-serif;
    font-size: x-large
  }

  p {
		font-size: 14px;
		font-weight: bold;
  }

  .spacer {
    flex: 1;
  }

  .header {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 60px;
    display: flex;
    align-items: center;
    background-color: #1976d2;
    color: white;
    font-weight: 600;

  }

  .content {
    display: flex;
    margin: 82px auto 32px;
    padding: 0 16px;
    max-width: 960px;
    flex-direction: row;
    align-items: center;
		padding-bottom: 300px;

  }



  .column {
    flex: 1;
    text-align: center;
  }

  svg.material-icons {
    height: 24px;
    width: auto;
  }


  svg.material-icons:not(:last-child) {
    margin-right: 8px;
  }

  .card svg.material-icons path {
    fill: #1976d2;
  }

  .card-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 5px;
  }

  .card {
    border-radius: 10px;
    border: 1px solid #1976d2;
    background-color: #FAFAFA;
    height: 40px;
    width: 200px;
    margin: 0 8px 16px;    padding: 16px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    transition: all 0.5s;
    line-height: 10px;
  }

  .card-container .card:not(:last-child) {
    margin-right: 0;
  }

  .card.card-small {
    height: 16px;
    width: 168px;
  }

  .card-container .card:not(.highlight-card) {
    cursor: pointer;
  }

  .card-container .card:not(.highlight-card):hover {
    transform: translateY(-3px);
    box-shadow: 0 4px 17px rgba(0,0,0, 0.35);
  }

  .card-container .card:not(.highlight-card):hover .material-icons path {
    fill: rgb(255,0,100);
  }

  .card.highlight-card {
    background-color: #1976d2;
    color: white;
    font-weight: 600;
    border: none;
    width: auto;
    min-width: 30%;
    position: relative;
  }

  .card.card.highlight-card span {
    margin-left: 60px;
  }


  a,
  a:visited,
  a:hover {
    color: #1976d2;
    text-decoration: none;
    font-size: large;
  }


  footer {
    font-size: x-small;
    position: relative;
    text-align: center;
		padding-bottom: 20px;
		bottom: 0;
  }


  svg#clouds {
    position: fixed;
    bottom: -160px;
    left: -230px;
    z-index: -10;
    width: 1920px;
  }


  /* Responsive Styles */
  @media screen and (max-width: 767px) {

    .card-container > *:not(.circle-link) ,
    .terminal {
      width: 100%;
    }

    .card:not(.highlight-card) {
      height: 16px;
      margin: 8px 0;
    }

    .card.highlight-card span {
      margin-left: 72px;
    }

    svg#rocket-smoke {
      right: 120px;
      transform: rotate(-5deg);
    }
  }

  @media screen and (max-width: 575px) {
    svg#rocket-smoke {
      display: none;
      visibility: hidden;
    }
  }

</style>
