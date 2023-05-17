# MATLAB Cheat Sheet

This cheat sheet provides a quick reference for some of the most commonly used commands and functions in MATLAB. 

## Basic Operations

### Arithmetic Operators

- `+` Addition
- `-` Subtraction
- `*` Multiplication
- `/` Division
- `^` Exponentiation
- `.` Element-wise operations (e.g., `.*`, `./`, `.^`)

### Variables and Assignment

- `=` Assignment
- `:` Range operator
- `;` Suppress output
- `ans` Last evaluated expression
- `clear` Clear all variables from workspace
- `who` List all variables in workspace
- `whos` List all variables in workspace with additional details

### Functions

- `function` Define a new function
- `@(args) expression` Anonymous function

### Control Flow

- `if`, `else` Conditional statements
- `for` Loop through a range of values
- `while` Loop while a condition is true
- `break` Exit a loop
- `continue` Skip to the next iteration of a loop

## Data Types

### Scalar Types

- `double` Double-precision floating-point number
- `single` Single-precision floating-point number
- `int8`, `int16`, `int32`, `int64` Signed integers
- `uint8`, `uint16`, `uint32`, `uint64` Unsigned integers
- `logical` Boolean value (true or false)

### Complex Numbers

- `i`, `j` Imaginary unit
- `real` Real part of a complex number
- `imag` Imaginary part of a complex number
- `conj` Complex conjugate of a number

### Strings

- `'text'` Character vector
- `string` String array
- `strcat` Concatenate strings
- `sprintf` Format strings

### Arrays

- `[a, b, c]` Row vector
- `[a; b; c]` Column vector
- `size` Size of an array
- `numel` Number of elements in an array
- `reshape` Reshape an array
- `transpose` Transpose an array
- `max` Maximum value in an array
- `min` Minimum value in an array
- `sum` Sum of values in an array
- `prod` Product of values in an array

### Matrices

- `[a, b; c, d]` Matrix
- `eye` Identity matrix
- `zeros` Matrix of zeros
- `ones` Matrix of ones
- `rand` Matrix of uniformly distributed random numbers
- `randn` Matrix of normally distributed random numbers
- `diag` Diagonal matrix
- `inv` Inverse of a matrix
- `det` Determinant of a matrix
- `eig` Eigenvalues and eigenvectors of a matrix

### Cell Arrays

- `{a, b, c}` Cell array
- `cell` Empty cell array
- `cellstr` Convert character array to cell array
- `num2cell` Convert numeric array to cell array

### Structures

- `struct` Create a structure
- `fieldnames` Field names of a structure
- `rmfield` Remove a field from a structure
- `setfield` Set the value of a field in a structure
- `getfield` Get the value of a field in a structure

## Image Processing

### Reading and Displaying Images

- `imread` Read an image from a file
- `imshow` Display an image
- `imtool` Interactive tool for exploring and analyzing images

### Image Filtering and Enhancement

- `imfilter` Filter an image
- `medfilt2` Median filter an image
- `imadjust` Adjust image intensity values
- `histeq` Enhance image contrast using histogram equalization

### Image Segmentation

- `graythresh` Determine threshold for binary image segmentation based on Otsu's method
- `im2bw` Convert image to binary using a specified threshold
- `watershed` Perform image segmentation using the watershed transform

### Feature Extraction

- `imgradient` Compute image gradient magnitude and direction
- `edge` Detect edges in an image
- `corner` Detect corners in an image
- `imhist` Compute image histogram

## Machine Learning

### Supervised Learning

- `fitcknn` Fit a k-nearest neighbor classifier
- `fitcdiscr` Fit a linear discriminant classifier
- `fitcsvm` Fit a support vector machine classifier
- `fitctree` Fit a decision tree classifier
- `predict` Predict class labels using a trained classifier
- `confusionmat` Compute confusion matrix and classification metrics

### Unsupervised Learning

- `kmeans` Perform k-means clustering
- `pca` Perform principal component analysis
- `tsne` Perform t-distributed stochastic neighbor embedding

### Model Evaluation

- `crossval` Perform cross-validation
- `kfoldLoss` Compute cross-validation loss
- `perfcurve` Compute receiver operating characteristic (ROC) curve
- `roc` Compute ROC curve and AUC

## Plotting

- `plot` Line plot
- `scatter` Scatter plot
- `bar` Bar plot
- `histogram` Histogram
- `pie` Pie chart
- `surf` Surface plot
- `imagesc` Image plot
- `contour` Contour plot
