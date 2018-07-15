# MoMath Hackathon 2018: Bézier Curve 2018

- _Math Square behavior_
- Micah Lorenz, Henry Zhou, May Lee

## The Math

This project demonstrates the mathematical concept of the Bézier curve, which is a parameterized curve represented by a finite set of control points. The resultant curve takes the form of a segment of a polynomial of degree one less than the size of the control set. The curve begins tangent to the line between the first and second points and transitions smoothly to end tangent to the line between the final two control points. These curves are an example of how math can be applied to artistic fields as Bézier curves are used in various illustration programs in order to create images that maintain fidelity at many scales and resolutions, as well as in animation to help movement appear smoother through time.

## The Submission

The behaviour animates the contruction of a Bézier curve from a set of four control points through a recursive method based on the structure of Bézier curves. In its default state, the program selects four random points and draw lines according to the recursive process for cunstructing a Bézier curve so as to gradually construct the curve. Then after it finishes drawing the curve, a new set of points is generated. When a user steps onto the floor, one of the four points is assigned to that user and they can move around in order to see how moving a control point affects the resultant curve. When there is a user on the floor, the program will not randomly select new point and will instead repeatedly draw the same curve. This behaviour should appeal to many people who find math courses disinteresting and instead elect to doodle in their math notebooks because it is very similar in structure to a common doodle that people draw on graph paper. This behaviour can accomodate up to four users.

## Additional Notes
No additional notes.



