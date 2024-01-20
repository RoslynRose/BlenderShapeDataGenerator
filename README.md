You will want to edit the lines
  'with open('/var/home/rose/shapes/shapeData.csv', 'w', newline='') as csvfile:' and 
  'bpy.context.scene.render.filepath = f"/var/home/rose/shapes/render_{counter}.png"'
to properly point to the correct dir in your own file structure.

Be sure to change the resolution output in blender's settings so that you don't end up with thousands of 1080p images.
