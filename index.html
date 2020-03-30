<!DOCTYPE html>
<html>
 <head> 
  <title>Example 08.06 - Load OBJ model </title> 
  <script type="text/javascript" src="three-91.js"></script>
  <script type="text/javascript" src="OBJLoader.js"></script>
  <script type="text/javascript" src="STLLoader.js"></script>
  <script type="text/javascript" src="libs/jquery-1.9.0.js"></script> 
  <script type="text/javascript" src="libs/stats.js"></script> 
    <script type="text/javascript" src="tween.js"></script>
    <script type="text/javascript" src="libs/CSS3DRenderer.js"></script>

<script src="libs/orbitcontrols.js"></script>
  <!-- fallback if no WebGL
  <script src="lib/projector.js"></script>
  <script src="lib/canvasrenderer.js"></script>
  <script src="lib/jquery-2.1.3.min.js"></script>-->
  <script src="src/csg.js"></script>
  <script src="src/threecsg.js"></script>
  <script src="src/openjscad.js"></script>
  <script src="src/formats.js"></script>


  <style>
        body {
            /* set margin to 0 and overflow to hidden, to go fullscreen */
            margin: 0;
            overflow: hidden;
        }
    </style> 
  <script type="text/javascript">
  
function onload()
{
  gProcessor = new OpenJsCad.Processor(document.getElementById("viewer"),{width:"", height:""});
  
var fileUploadButton = document.getElementById('fileUploadButton');
fileUploadButton.addEventListener('change', handleFileSelect);

}

function handleFileSelect(evt)
{
    evt.dataTransfer = {};
    evt.dataTransfer.files = fileUploadButton.files;
    var file = evt.dataTransfer.files[0];
    gCurrentFile = file;
    parseFile(false,false);
}

function parseFile(debugging, onlyifchanged)
{
  if(gCurrentFile)
  {
    var reader = new FileReader();

    reader.onloadend = function(evt) {

        var jscadscript = evt.target.result;
        
          if(gProcessor && ((!onlyifchanged) || (previousScript !== jscadscript)))
          {
            var filename = gCurrentFile.name;
            filename = filename.replace(/^.*\/([^\/]*)$/, "$1");
            gProcessor.setDebugging(debugging); 
            gProcessor.setJsCad(jscadscript, filename);
						previousScript = jscadscript;
          }
    };
    reader.readAsText(gCurrentFile, "UTF-8");
  }
}


  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-19067049-1']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>
 </head> 
 <body onload="onload()">
 
 <div style="width: 10px; position: absolute; z-index: 1" id="viewer"></div>


  <div style="position: absolute; z-index: 1" id="Stats-output">
  <input type="file" id="fileUploadButton" >
  </div> 
  <!-- Div which will hold the Output --> 
  <div id="WebGL-output"> 
  </div> 
  <!-- Javascript code that runs our Three.js examples -->
  <script type="text/javascript">

  


var control = document.createElement('input');
control.type= 'text';
control.value= "0.2";
var container2 = document.getElementById("Stats-output");
        container2.appendChild(control);
  
  var table = [
        "H", "Bowl", "1.00794", 1, 1,
        "H", "Bowl Hood", "1.00794", 1, 1,
        "H", "Centripetal Pump", "1.00794", 1, 1,
        "H", "Density Ring", "1.00794", 1, 1,
        "H", "Lock Nut", "1.00794", 1, 1,
        "H", "Pump Plate", "1.00794", 1, 1,
        "H", "Ring", "1.00794", 1, 1,
        "H", "Ring Pump", "1.00794", 1, 1,
        "H", "Sensing Pump", "1.00794", 1, 1,
        "H", "Slide Lower", "1.00794", 1, 1,
        "H", "Slide Upper", "1.00794", 1, 1,
        "H", "Top Disc", "1.00794", 1, 1,
    ];
  var divs = [];

var scene2, div, renderer2;

    scene2 = new THREE.Scene();
  //HTML
  for ( var i = 0; i < table.length; i += 5 ) {
    element = document.createElement('a');
    element.setAttribute('href', 'https://www.google.com');
    element.textContent = table[i+1];
    element.className = 'three-div';
    element.style.fontSize = 'small';
    element.style.backgroundColor = 'rgba(0,127,127,' + ( Math.random() * 0.5 + 0.25 ) + ')';
    
    //CSS Object
    div = new THREE.CSS3DObject(element);
    div.position.x = 0;
    
    div.position.z = 0;
    scene2.add(div);
    
    divs.push( div );
    
    }
    
    //CSS3D Renderer
    renderer2 = new THREE.CSS3DRenderer();
    renderer2.setSize(window.innerWidth, window.innerHeight);
    renderer2.domElement.style.position = 'absolute';
    renderer2.domElement.style.top = 0;
    document.body.appendChild(renderer2.domElement);
    
    
    // once everything is loaded, we run our Three.js stuff.
    $(function () {

        var stats = initStats();

        // create a scene, that will hold all our elements such as objects, cameras and lights.
        var scene = new THREE.Scene();

        // create a camera, which defines where we're looking at.
        var camera = new THREE.PerspectiveCamera(45, window.innerWidth / window.innerHeight, 0.1, 2000);

        // create a render and set the size
        var webGLRenderer = new THREE.WebGLRenderer();
        webGLRenderer.setClearColor(new THREE.Color(0xaaaaff, 1.0));
        webGLRenderer.setSize(window.innerWidth, window.innerHeight);
        webGLRenderer.shadowMapEnabled = true;

        // position and point the camera to the center of the scene
        camera.position.x = 0;
        camera.position.y = 300;
        camera.position.z = 1000;
        camera.lookAt(new THREE.Vector3(0, 200, 0));


        // add spotlight for the shadows
        var spotLight = new THREE.SpotLight(0xffffff);
        spotLight.position.set(-150, 200, 250);
        spotLight.intensity = 1;
        scene.add(spotLight);

        // add the output of the renderer to the html element
        var container = document.getElementById("WebGL-output");
        container.appendChild(webGLRenderer.domElement);
        //$("#WebGL-output").append(webGLRenderer.domElement);

        // call the render function
        var step = 0;



        var mesh=[]; var meshA= new THREE.Group();
        var animating = false;
        var tween1;
    
    
     var position = [];
    var material = new THREE.MeshLambertMaterial({color: 0x5C3A21, transparent:true});
        var loader = new THREE.OBJLoader();
        loader.load('Purifier.obj', function (geometry) {
            
            var material2 = new THREE.MeshLambertMaterial({color: 0x222222});

            mesh = geometry.clone();


            var tween;
            var tweenBack;
            
            // geometry is a group of children. If a child has one additional child it's probably a mesh
            for (i = 0; i < 11; i++) {
                        geometry.children[i].material = material;
                        geometry.children[i].material.opacity = 0.9;
                        geometry.children[i].scale.set(500,500,500);
                        geometry.children[i].position.set(0,i*50,0);
                        //meshA.add(geometry.children[i]);
                        position.push(geometry.children[i].position);
            };

            tween = new TWEEN.Tween(geometry.children[4].position)
                        .to({y: 0}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(4000);
            geometry.children[9].rotation.set(3.1416,0,0);
            tween1 = new TWEEN.Tween(geometry.children[9].position)
                        .to({y: -10}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut);
            tween = new TWEEN.Tween(geometry.children[10].position)
                        .to({y: 0}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(2000);
            tween = new TWEEN.Tween(geometry.children[11].position)
                        .to({y: 11}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(6000);
            tween = new TWEEN.Tween(geometry.children[1].position)
                        .to({y: 5}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(10000);
            tween = new TWEEN.Tween(geometry.children[6].position)
                        .to({y: 5}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(11000);
            tween = new TWEEN.Tween(geometry.children[2].position)
                        .to({y: 25}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(12000);
            geometry.children[5].rotation.set(3.1416,0,0);
            tween = new TWEEN.Tween(geometry.children[5].position)
                        .to({y: 26}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(13000);
            tween = new TWEEN.Tween(geometry.children[8].position)
                        .to({y: 27}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(14000);
            tween = new TWEEN.Tween(geometry.children[7].position)
                        .to({y: 25}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(16000);
            tween = new TWEEN.Tween(geometry.children[3].position)
                        .to({y: 27}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(15000);

            
            camera.position *= 2;
                    
            //for (i = 0; i < position.length; i++) {

                tweenBack = new TWEEN.Tween(geometry.children[9].position)
                        .to({y: position[0].y}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut);
                                
                console.log(position[1].y);

            

            tween1.chain(tweenBack);
            
   
            //geometry.children[0].position.y=10;
            //geometry.scale.set(0.05,0.05,0.05);
            //geometry.rotation.x = -0.3;
        
            scene.add(geometry);
            render();
        });
      
        var loader = new THREE.OBJLoader();
            loader.load('Purifier2/Hood Disc/hood-disc-obj/hood-disc.obj', function (geometry) {
                        geometry.children[9].scale.set(500,500,500);
                        geometry.children[9].position.set(0,300,0);
            var tween = new TWEEN.Tween(geometry.children[9].position)
                        .to({y: 12}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(8000);
            scene.add(geometry);
        });
        var loader = new THREE.OBJLoader();
            loader.load('Purifier2/Distributor/distributor-obj/distributor.obj', function (geometry) {
                        geometry.children[4].scale.set(500,500,500);
                        geometry.children[4].position.set(0,300,0);
            var tween = new TWEEN.Tween(geometry.children[4].position)
                        .to({y: -5}, 5000)
                        .easing(TWEEN.Easing.Cubic.InOut).start(6000);
            scene.add(geometry);
        });
        
            
        var loader2 = new THREE.STLLoader();
        loader2.load('Purifier2/Distributor/distributor-stl/5-binary.stl', function (geometry2) {
            var distributor = new THREE.Mesh(geometry2,material);
            distributor.scale.set(500,500,500);

        scene.add(distributor)});

      addMouseHandler()
      

        function render() {
            stats.update();
      
            if (!animating)
            {
            tween1.start();
            }
        for (var i=0; i<11; i++) {
      
            divs[i].position.y = position[i].y;
        }

			TWEEN.update();
      
      
            /*if (mesh) {
                mesh.rotation.x += 0.002;
                mesh.scale.x += 0.001;
                mesh.scale.y += 0.001;
                mesh.scale.z += 0.001;
            }
      
            /*for (i = 0; i < mesh.children.length; i++) {
                mesh.children[i].position.x -= i*0.01;
            }*/

scene.rotation.y += parseFloat(control.value);
            // render using requestAnimationFrame
            requestAnimationFrame(render);
            webGLRenderer.render(scene, camera);
            renderer2.render(scene2, camera);
        }

        function initStats() {

            var stats = new Stats();
            stats.setMode(0); // 0: fps, 1: ms

            // Align top-left
            stats.domElement.style.position = 'absolute';
            stats.domElement.style.left = '0px';
            stats.domElement.style.top = '0px';

            //$("#Stats-output").append(stats.domElement);

            return stats;
        }
      
        function addMouseHandler()
	{
		var dom = renderer2.domElement;
		
		dom.addEventListener( 'mouseup', onMouseUp, false);
	}
    function onMouseUp	(event)
	{
	    event.preventDefault();

	    animating = !animating;
	}
    
    });

        
	

</script>  
 </body>
</html>
