## Knottingham
<img src="https://fi-le.net/images/knottingham.gif">

is a tool that lets you draw and manipulate knot diagrams, sporting a clean yet somewhat hand-made look. 
You can:
1. Draw a knot from scratch & Have its intersections calculated for you
2. Adjust it as a Bezier curve
3. and Export it to TikZ/SVG/JSON!

other features include:
- Computing the Alexander Polynomial
- Undoing
- Styling
- Non-Reidemeister Move detection


<img src="https://fi-le.net/images/knot.svg">

You can give it a go yourself over [here](https://fi-le.net/knottingham).

 **Heritage**
 ---
**Knottingham** was inspired by two cool tools for drawing and identifying knots, namely the [Knot Identification Tool](https://joshuahhh.com/projects/kit/) by Joshua Horowitz and [KnotFolio](https://kmill.github.io/knotfolio/index.html) by Kyle Miller. For the feature of producing a minimal orthogonal knot diagram, it uses the PyPi Module [spherogram](https://github.com/3-manifolds/Spherogram) after compilation to Webassembly to be compatible with [pyodide](https://github.com/pyodide/pyodide). Spherogram is licensed under [GNU-2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt).
Knottingham renders with [paper.js](https://github.com/paperjs/paper.js). Many thanks to the authors!

 **In the Future**
 ---
These features are planned:
*   Redo
*   Proven Non-Reidemeister Move-Detection
*   Some more styling options

 **License**
 ---
**Knottingham** is free software and licensed under MIT.

Any and all feedback is appreciated! You can mail to [developer/at/fi-le.net](mailto:developer/at/fi-le.net).
