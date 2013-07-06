Vectors and spaces



Vectors



Linear combinations and spans



Linear dependence and independence



Subspaces and the basis for a subspace



Vector dot and cross products



Matrices for solving systems by elimination



Null space and column space

































Matrix Transformations



Functions and linear transformations



A more formal understanding of functions


What's the more formal definition of a function? How's this different from the traditional definition?||A ____ is a relation between the members of one set and another set. In the original understanding of ____ most people learn, people think that they are taking an input and CHANGING that input to produce an output (like putting meat through a sausage machine), whereas the new idea is that you are ASSOCIATING an inputted number with another number (like associating the picture of a house on a map with the real house that it represents).||double-sided




What's "mapping" refer to?||Relating / associating the member of one set to the member of a second set.||double-sided




What's the notation used to describe mapping from one set to another set?||

Example:
g: R2 --> R1 (the domain and codomain of the function)
g: x1, x2 |--> 2 (the function definition)
Note the colon and two different kinds of arrow. R2 is the set of all real 2-tuples, R1 is the set of all real numbers. When you're writing out the mapping from the domain to the codomain you use an arrow WITHOUT a little line in back; when you're writing out the function definition you use an arrow WITH a little line on the back end of it. I guess this is to distinguish when you're talking about sets (eg R1) and when you're talking about individual numbers (eg x1). Sal explains this distinction in the "Vector Transformations" video.




What's a "domain"?||When mapping from one set to another set, _____ is the set of numbers that you're mapping FROM. It's all the numbers that you can input into the function.||double-sided




What's a "codomain"?||When mapping from one set to another set, _____ is the type of numbers that you're mapping to, eg "the real numbers" or "R2" or "the imaginary numbers".||double-sided




What's the difference between the range and the codomain?||The range is the subset of the codomain that a given function ACTUALLY maps to. So for example, f: x --> x^2 will not map to any values less than 0, so the range won't include negative numbers. But the codomain DOES include negative numbers because the codomain is R1, the real numbers.||




What's a scalar-valued function?||A function that maps to a one-dimensional space. It's also known as a real-valued function.||double-sided




What's a real-valued function?||A function that maps to a one-dimensional space. It's also known as a scalar-valued function.||double-sided




What's a vector-valued function?||A function that maps to a higher-than-one-dimensional space (eg R2, R3, etc). This is in contrast to scalar/real-valued functions, which are those that map to R1.||double-sided





Linear transformation examples



Transformations and matrix multiplication



Inverse functions and transformations



Finding inverses and determinants



More determinant depth



Transpose of a Matrix



Transpose of a Matrix


transpose||The _______ of a matrix is basically when you swap the rows and columns in a particular way.||double-sided




How do you generate the transpose of a matrix?||You can create ______ if you rotate a matrix 90 degree clockwise and then flip it horizontally (over the y axis). So if the old position of an element was (x, y), the new position will be (y, x).||double-sided




What happens if you take the transpose of the transpose of a matrix?||You get the original matrix.||

























Alternate coordinate systems (bases)



Orthogonal complements



Orthogonal projections



Change of basis



Orthonormal bases and the Gram-Schmidt Process


==Eigen-everything





Introduction to Eigenvalues and Eigenvectors


What is an eigenvector?||




What is an eigenvalue?||




Why are eigenvalues / eigenvectors useful?||They make for better basis vectors; it's easier to do computations with them, and they make for better coordinate systems.||







Proof of formula for determining Eigenvalues


Prove the formula for determining eigenvalues||1)We're looking for eigenvalues/vectors that will satisfy this formula: Av = lambda(v), where v is a vector, A is the transformation matrix we're trying to find eigenvalues for, and lambda is the eigenvalue (scaling factor for the eigenvector). It's really helpful to imagine the simple example he came up with: if you've got a matrix/transformation that flips a vector over the line y=x, then a vector that is perpendicular to that line will just be scaled up or down; it won't change direction. So multiplying that vector by the transformation will be the same as multiplying it by a scaling factor. Or in other words, Av = lambda*v.
2) The first obvious vector would be the zero vector (0), but that isn't really useful, so we're going to stipulate that we're looking for non-zero vectors.
3) Subtract Av from both sides of the equation, and you'll have the zero vector (0) = lambda*v - Av. Now, on the first part of the expression (lambda*v), you can observe that the vector v is the same as the identity matrix times that vector (we'll represent the identify matrix by In, where n is the dimension of the vector). So you can rewrite the entire equation to look like this: lambda*In*v - Av = 0.
4) Now note that you have (a matrix times a vector) minus (a matrix times the same vector), and matrix-vector products have the distributive property, so you can rewrite the equation as (lambda*In - A)*v = 0.
5) Now we have the whole equation set up as a single matrix times a vector equal to zero, and we're assuming that the vector is not zero. Now remember the definition of the nullspace of a matrix B: it's the set of all vectors v where Bv = 0.  So we know that the vector v in the equation above must be a member of the nullspace of the matrix it is being multiplied by (lambda*In - A).