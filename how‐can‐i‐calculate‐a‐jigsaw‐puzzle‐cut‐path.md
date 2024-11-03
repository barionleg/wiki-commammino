https://github.com/barionleg/comamino-polymer

https://mathematica.stackexchange.com/questions/6706/how-can-i-calculate-a-jigsaw-puzzle-cut-path

![image](https://github.com/barionleg/comamino-polymer/assets/102619282/c3448777-9433-4ee5-894e-774414866607)

Just for some fun, we can actually create the tiles and shuffle them a bit. Who wants to add some code to make them draggable and rotatable?

`Graphics[
 {EdgeForm[Black],
  Texture@ExampleData[{"TestImage", "Sailboat"}], 

  GeometricTransformation[#, 
     Composition[
      TranslationTransform@RandomReal[0.1 {-1, 1}, 2], 
      RotationTransform[RandomReal[{-Pi, Pi}], Mean@First[#]]]] & /@ 
   Cases[Normal@showTiles[Rescale[pts]], 
    Polygon[p_, ___] :> Polygon[p, VertexTextureCoordinates -> p], 
    Infinity]}
 ]`

![image](https://github.com/barionleg/comamino-polymer/assets/102619282/8cf1cb3d-980e-46e1-b986-d90f8a10411f)


https://www.wolframcloud.com/objects/demonstrations/PentagonTilings-source.nb

https://demonstrations.wolfram.com/PentagonTilings/

![image](https://github.com/user-attachments/assets/34db3f34-362e-4dbf-a94b-bc3fd8228814)


https://help.bookpublishertools.com/faqs/puzzle-maker-pro-hexagons-overview

https://www.bookpublishertools.com/product/puzzle-maker-pro-jigsaw-circles/?_ga=2.215206801.708914703.1719583205-1487938630.1719583205


Puzzles collection

utracker.org/forum/viewtopic.php?t=2536427

https://katamino-polymer.firebaseapp.com/

![image](https://github.com/user-attachments/assets/78993fb6-3d09-4d14-8350-bf730e44e7e1)
