# WebGL Weekly 6

A Three.js living-room scene with an open-front room, upholstered chair, television and console, side table, reading lamp, and two framed windows overlooking a daytime landscape. Orbit around the room to inspect the layout and lighting.

## Run locally

Because the project uses JavaScript modules, open it through a local web server instead of opening the HTML file directly.

From the project directory, run:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000/weekly6.html](http://localhost:8000/weekly6.html) in a browser.

You can also use the Live Server extension in VS Code.

## Controls

- Drag to orbit around the scene.
- Scroll to zoom.
- Resize the browser window to update the camera and renderer. The scene also adapts to smaller screens.

## Project files

- [`weekly6.html`](weekly6.html) loads the scene and defines the import map for Three.js.
- [`weekly6.js`](weekly6.js) creates the room, furniture, exterior view, lighting, controls, and render loop.

## Technologies

- [Three.js](https://threejs.org/) `0.160.0`
- JavaScript ES modules
- WebGL

## Reflection Questions
### Which lighting setup created the strongest mood?
I would say that the movie night created the strongest mood. The cold color of the lighting and the darkness creates a very spooky mood.
### Which scene felt most realistic?
The cozy evening felt the most realistic to me. Despite the strong orange color, it was mostly ambient lighting, unlike ones like the movie night where I had to position lights around certain objects and couldn't quite get it right. 
### How did lighting change the emotional feeling of the room?
The color of the light and the darkness of the lighting impacts how happy/sad and how scary the room feels.
### Why are PointLights useful indoors?
They can simulate specific objects such as lamps and TVs and can isolate light around specific points that create particular shadows/mood.
### Why are colored lights effective for storytelling?
Colors carry a lot of emotional weight, and the coloring of light can change how warm or cold a scene feels.
### Which lighting setup required the most experimentation?
Definitely the boss battle one. I had trouble getting the animated light around the TV to work. 
### How did animated lights improve the scene?
The flickering of the lightning creates a very specific tense vibe, and the animation of the boss battle lighting creates a more dynamic scene.
### If this were a real game, which scene would players remember most and why?
Probably the boss battle scene, due to the wacky light coloring and the animated light.