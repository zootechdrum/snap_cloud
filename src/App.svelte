<script>
</script>

<section>
  <div class="card shadow-2xl">
    <div>
      <img
        src="http://dev.fleetwoodusa.net/wp-content/uploads/2018/04/fleetwood-logo-horizontal-color-400.png"
        alt="Fleetwood logo"
      />
    </div>
    <div class="flex justify-center flex-col">
    	<h2>SnapCloud</h2>
		<div class="justify-center flex">
			<img class="cloud" src="images/cloud.png" alt="cloud-icon">
		</div>
    </div>
     <form>
		<div class="input-field">
			<input type="text" id="name" required />
			<label for="name">Your name:</label>
		  </div>
		  <div class="input-field">
			<input type="password" id="name-2" required />
			<label for="name-2">Password:</label>
		  </div>
    </form>
    <div class="button-container">
      <button class="p-1">Login</button>
    </div>
  </div>
</section>

<style>
	.cloud {
		width:70px;
		height:70px;
	}
  h2 {
    text-transform: uppercase;
    font-size: 1.7rem;
    letter-spacing: 4px;
    color: black;
    padding-bottom: 35px;
    text-align: center;
  }
  section {
    height: 90vh;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .card {
    min-width: 400px;
    max-width: 450px;
    border: 1px solid #0000;
    font-family: "Oswald", sans-serif;
    letter-spacing: 2px;
    font-size: 1.5rem;
    display: flex;
    flex-direction: column;
    padding: 30px;
	padding-top:60px;
	padding-bottom: 40px;
	height:630px
  }
 	.card-header {
		 text-align:center;
	 } 
  .button-container {
    padding-top: 50px;
	display:flex;
	justify-content: center;
  }
  button {
	width:100%;
    background-color: #154396;
    cursor: pointer;
    color: white;
	border-radius: 5px;
  }
  .card-logo {
    justify-content: center;
    display: flex;
  }
  img {
    height: 100px;
    width: auto;
  }
  .input-field {
    position: relative;
    width: 100%;
    height: 64px;
    line-height: 44px;
  }
  .input-field-2 {
    position: relative;
    width: 100%;
    height: 44px;
    line-height: 44px;
  }
  .input-2 {
    width: 100%;
    border: 0;
    outline: 0;
    border-bottom: 2px solid #d3d3d3;
    box-shadow: none;
    color: #111;
  }
  label {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    color: #d3d3d3;
    transition: 0.2s all;
    cursor: text;
	font-size:1rem;
  }
  input {
    width: 100%;
    border: 0;
    outline: 0;
    border-bottom: 2px solid #d3d3d3;
    box-shadow: none;
    color: #111;
  }
  input:invalid {
    outline: 0;
  }
  input:focus,
  input:valid {
    border-color: #00dd22;
  }
  input:focus ~ label,
  input:valid ~ label {
    font-size: 14px;
    top: -24px;
    color: #00dd22;
  }
</style>
