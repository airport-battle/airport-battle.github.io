## Welcome to Airport Battle (alpha)

Do you have what it takes to handle a lot traffic? Try it out. Aiport battle let's you manage an airport as an ATC (air traffic controller)

## Current Stage
Game is currently in alpha stage and under heavy development.

## The Game

<script>
    var loadFrame = function() {
        var htmlString = '<iframe src="airportbattle/index.html" style="width: 1400px; height: 900px; border: 0px; position: absolute; left: 0; right: 0; margin: auto;" allow="autoplay; fullscreen"></iframe>'
        var div = document.getElementById( 'game-container' )
        div.insertAdjacentHTML( 'beforeend', htmlString )
        document.getElementById('game-loader').remove()
    }   
</script>
<a id="game-loader" onclick="loadFrame()" style="border: 1px solid black;padding: 10px;margin: 5px;background-color: red;color: white;cursor: pointer;">Load Game</a>
<div id="game-container" style="display:block; height: 900px"></div>

Tips:
- use mouse drag for camera movement and mouse wheel for zoom, use key 'f' for fullscreen
- you can toggle radar on/off 
- aircraft are selectable by click on the map and the radar

###  Contact or Support

You like the game? Or you don't? Drop us a note, we're happy to hear from you :)

Feel free to request features, report bugs or anything else on your mind.

Contact us via [airportbattle@gmail.com](mailto:airportbattle@gmail.com)

