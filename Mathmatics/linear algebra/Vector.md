A shit that contains length and direction. In coordinate space, the arrow represent direction and the  tuples represent the length of the vector. The length is determine by the n number of coordinate that the vector has to move. For instance, in 2D space, the vector has to move by x and y coordinate. In 3D, its x y and z and so on. The vector is extended from the origin in the coordinate space.

## Addition of vector
2 vector can be added. In order to imagine it, imagine taking out the vector that is being added and putting the tail to the end point of the one to which that has to add. The newly creted length from the origin is the sum of those two vector.
![[Pasted image 20261001092415.png]]

## Unit vector
The vector having  value of 1 in one of n cordinate in the space is unit vector. For instance, in the case of 2D vector, unit vector can be [1,0] or [0,1].

## Basis
Addition of scaler of unique unit vector which results in the formation of new vector. To sum it up, it is the basis of all possible coordinate in the space since addition of those two unique scaler vector covers every possible space in the coordinate. It doesn't have to be unit vector, as long as two vectors are linearly independent in 2D scape, it can be basis since linear independent coordinate has capacity to cover enitre space.
## Linear coordinate

Addition of n number of vector that scale in n space. For instance, addition of "4w + 5x" is the linear coordinate in 2D space where w and x vector is scaled and then added to each other to form new point in the space.

## Span
The area covered by the vector in the coordiate space. In the case of vector that doesn't fall on the same line, its every point in the coordiate space i.e. in the case of 2D vector, if 2 vector doesn't fall on the same line, its every point in 2D space. In the case of 3D, if all 3 are in different line, then all possible point in 3D space and so on.

## Linear Dependence and independence
When a vector can be deprived by the liner combination of existing vector, then the vector is linearly dependent. The liner dependent vector either can be achieved from the linear combination or one to n-1 number of vector in n number of space sitting of top of one or many vector. In this case, one or more vector that lines up on top of a vector is redundent sicne they have 0 contribution in the span. 

Since the linearly dependent vector falls on the same span as one of many existing vector, the vector can be obtained from combination of existing vectors. For instance, v1​=(1,0),v2​=(0,1),v3​=(3,4). Although v3 doesn't falls on top of existing vector, it can be achieved by the lienar combination of v1 and v2 i.e.  v3​=3v1​+4v2​. 

The quesiton regarding linear independence is always can the current vector be acieved by existing vector and if yes then it is linear dependent. To make this question easier, the maximum possible linear in-dependent vector in n number of space is always going to be n i.e. 2 in 2D space and 3 in 3D becuase as long as all existing vector doesn't fall on same line, the linear combination can cover up entire dimension resulting in reaching the n+1 vector in one way or another.


## Determinant of Matrix
Used for calculating the area covered by the linear transformation.  In generic term, calculated for determining the factor by which the area of region increases or decreases. The factor by which linear transformation changes any area is called determinant of transformation.

For 2D matrix  The area is determined by 4 points in the coordinate. Origin, 1st matrix column, 2nd matrix column and sum of 1st and 2nd matrix column. The area that falls inside those 4 points is determinant of matrix. The formulae to calculate is ad - bc (where a,b,c,d is a11, 12, a21 and a22 respectively).

Considering the grid line in coordinate system is evenly spaced and parallel, the linear transformation happening at one area happens at every area in the space because of which, the object that is not in the shape of transformed area can be covered with the combination of lots of transformed area and be scaled.

The determinant can also be 0 or negative. When negative, it means that the shape is formed in the opposite direction of the space whereas, when 0, it means that the space collapse in lower dimension. In 2D space, the collapse is either 1D line or a point, in 3d space its either plane, line or a point. The change into lower dimension can be observed by rank of matrix.