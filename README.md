# SnurbO-Matic
An inward raytracer implemented in LSL with an offgrid service node.
—————————
Introduction  :::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

 The SnurbO'Matic is an on-grid way of creating molds from objects.  These molds can then be used to create a sculpted texture map.  Some of the project goals are to help define  suitable methods for sculpted mesh manipulation in world.  The tools must be easy enough for everyone to produce exciting results, yet rich enough that the more one learns, the finer the detail can be.

The starting form is a large sphere, with all 3 axis clearly displayed.    When looking at this sphere, the blue line thru the middle, the Z axis, is where the poles form.    Around the outside of this sphere is where the mesh is formed.  Objects to be molded are placed fully inside the sphere, making sure the axis cross thru the object.  Placement is key to a good mold.    The object is then scanned and the data fed off grid to a backend that creates the final texture.
