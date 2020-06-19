# matetr.render

const Render = Matter.Render;

var render = Render.create({
	  element: document.body,
	  engine: engine,
	  options: {
	    width: 1200,
	    height: 700,
	    wireframes: false
	  }
	});
	
	
Render.run(render);
