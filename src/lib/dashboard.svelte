<script>
    import Rs from "$lib/result.svelte";
</script>
<body>
    
    <div class="ard">
        <i>Nominate Best Game</i>
        <div class="card-container">
            <div class="card">
                <div class="con1"></div>
                    <div class="container">
                    <a href="$lib/result.svelte"><h4><b>Balatro</b></h4></a>
                    <p>Rougelike Deckbuilder</p>
                </div>
            </div>
            <div class="card">
                <div class="con1"></div>
                    <div class="container">
                    <a href="./result.svelte"><h4><b>Sea of thives</b></h4></a>
                    <p>Adventure Pirates</p>
                </div>
            </div>  
            <div class="card">
                <div class="con1"></div>
                    <div class="container">
                    <a href="./result.svelte"><h4><b>Wuthering Waves</b></h4></a>
                    <p>Open world ARPG</p>
                </div>
            </div>  
            <div class="card">
                <div class="con1"></div>
                    <div class="container">
                    <a href="./result.svelte"><h4><b>Zenless Zone Zero</b></h4></a>
                    <p>Dungeon ARPG</p>
                </div>
            </div>  
            <div class="card">
                <div class="con1"></div>
                    <div class="container">
                    <a href="./result.svelte"><h4><b>Sekiro</b></h4></a>
                    <p>Souls-Like Single Player</p>
                </div>
            </div>  
            <div class="card">
                <div class="con1"></div>
                    <div class="container">
                    <a href="./result.svelte"><h4><b>BattleField 1 Revolution</b></h4></a>
                    <p>Multiplayer FPS</p>
                </div>
            </div>  
    </div>
</body>

<style>
   body{
    background-image: linear-gradient(to top, #f9edf4, #e7dfe6, #d6d1d8, #c5c3c9, #b5b5ba, #a2a3a8, #8f9296, #7d8184, #63686b, #4a5152, #333a3b, #1e2524);
   }

   .container h4{
    cursor: pointer;
   }
   .ard{
        color: black;
        background-color: azure;
        width: auto;
        height: 665px;
        box-shadow: 2px 20px 50px #ccf9ff;
        margin-top: 12%;
        margin-bottom: 4%;
        margin-left: 15%;
        margin-right: 15%;
        border-radius: 15px;
   }

   .ard i{
        position: absolute;
        z-index: 3;
        top: 10%;
        left: 41%;
        color: aliceblue;
        width: 468px;
        font-size: 40px;
        font-weight: bold;
   }

    .card {
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
        transition: 0.3s;
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
        transition: 0.3s;
        border-radius: 5px; 
        margin-left: 8px;
        margin-top: 15px;
    }
    .card:hover {
        box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
    }
    .container {
        padding: 2px 16px;
    }

    .con1 {
        border-radius: 5px 5px 0 0;
        width: 250px;
        height: 200px;
        background-color: #515153;
    }

    .card-container{
    /* border-radius: 8px;
    box-shadow: 0px 0px 10px 3px rgba(0, 0, 0,.40); */
    position: relative;
    /* z-index: 3; */
    /* box-sizing: border-box; */
    align-items: center;
    display: flex;
    /* flex */
    top: 10%;
    justify-content: center;
    flex-direction: row;
    flex-wrap: wrap;
    }
</style>