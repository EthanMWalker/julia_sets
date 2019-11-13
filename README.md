# Julia Sets
This activity is about exploring the beauty of mathematics through creating and displaying julia sets. 

## Dynamical Systems
A dynamical system is defined by a function that ddescribes the time dependance of a point in space. In this activity we will be talking about complex dynamical systems. That is, dynamical systems of a complex variable. The systems that we will consider then are of the form ![func](https://latex.codecogs.com/gif.latex?F%3A%5Cmathbb%7BC%7D%5Cto%5Cmathbb%7BC%7D).

### Itineraries
Because Dynamical systems describe a time dependent system we can determine the iternerary of a certain point by considering the following sequence: 
![itinerary](https://latex.codecogs.com/gif.latex?%28x%5Ei%29_%7Bi%3D0%7D%5E%5Cinfty)
where:
![time dependance](https://latex.codecogs.com/gif.latex?x%5E%7Bi&plus;1%7D%20%3D%20F%28x%5Ei%29).

We call this sequence the itinerary of ![x](https://latex.codecogs.com/gif.latex?x).

To clarify notation we will also describe:
as the n<sup>th</sup> composure of ![F](https://latex.codecogs.com/gif.latex?F) with itself.

### Orbits
If for any point ![x](https://latex.codecogs.com/gif.latex?x) we have that
![orbit](https://latex.codecogs.com/gif.latex?F%5En%28x%29%20%3D%20x), then we say that ![x](https://latex.codecogs.com/gif.latex?x) is a point of period 2, or that the oribit of ![x](https://latex.codecogs.com/gif.latex?x) is order 2.

## The Quadritic Map
The dynamical system that we are interested in today is called the quadratic map. The function that describes the system is the following
![func](https://latex.codecogs.com/gif.latex?Q_c%3A%5Cmathbb%7BC%7D%5Cto%5Cmathbb%7BC%7D), defined by ![quad](https://latex.codecogs.com/gif.latex?Q_c%28z%29%20%3D%20z%5E2%20&plus;%20c).

## The Filled Julia Set
The filled Julia set ![K](https://latex.codecogs.com/gif.latex?K) of a map ![Q](https://latex.codecogs.com/gif.latex?Q_c) is the set of all points whose itinerary is bounded under ![Q](https://latex.codecogs.com/gif.latex?Q_c). In other words 
https://latex.codecogs.com/gif.latex?K%28Q_c%29%20%3D%5C%7Bz%5Cin%5Cmathbb%7BC%7D%3A%5C%3B%20%5Cleft%20%7C%20Q_c%5En%28z%29%20%5Cright%20%7C%20%3C%20%5Cinfty%20%5Ctext%7B%20as%20%7D%20n%5Cto%5Cinfty%5C%7D.

The Julia set ![J](https://latex.codecogs.com/gif.latex?J) is actually the boundary of this set: ![J](https://latex.codecogs.com/gif.latex?J%28Q_c%29%20%3D%20%5Cpartial%20K%28Q_c%29).

This boundary is where we find the beauty that we are looking for. It has fractal properties, meaning that this perimiter of a finite area is in fact infinity!

---

Enjoy the activity!