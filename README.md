##### About "isPieceOut" method

Previous "isPieceOut" method was checking whether the "piece" has found the exit by looking at it's "top" and "left" properties which are dynamically set.

Since this application uses queue as a way to visualize how "piece" is making it's way to the end initial implementation of "isPieceOut" method is kind of useless.

I'm not sure if I'm allowed to do this or not, but I changed the way how "isPieceOut" method checks if "piece" is standing on the exit cell by utilizing the "position" object from "createPiece" function.
