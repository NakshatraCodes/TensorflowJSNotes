# Tensorflow JS Notes

![TensorflowJS](https://www.tensorflow.org/site-assets/images/project-logos/tensorflow-js-logo-social.png)

### Recap

#### Important underlying concepts in ML

- *Regression* vs *Classification* (Identifying the problem type)
	- Regression - when theres an range of labels with infinite values
	- Classification - when the labels are discrete and limited
- *Features* vs *Labels*
- *Test* vs *Training* sets of data
- Feature *normalization*
- Feature *selection*
- Understanding datastructures

#### Moving from Lodash to Tensorflow **WHY?**

- Using Lodash is extremely slow and not *Numbers* focused. Also, some things are harder to do in Lodash.
- Tensorflow JS has an API similar to Lodash.
- It is extremely fast for numeric calculations.

#### **Best way to learn Tensorflow JS**

- Learn some fundamentals around Tensorflow.
- Go through some exercises on Tensorflow.
- Implement already implemented algorithms in Tensorflow for practice.
- Try to build other algorithms with Tensorflow.

### The Tensorflow Library

#### Starting with TFJS

**Some common terms:**
- **Tensors** - They are JS objects that wraps an array of numbers.
- **Dimensions** - How many directions a tensor extends. 
- **Shape**(property) - An array of the *length* of each *Dimension* of a Tensor (Visualize .length property from top level) 

- Shapes are always interpreted as **[Rows, Columns]**


## Linear Regression

- We try to figure out a relationship between independent and dependent variables.
- It's faster than K-Nearest Neighbor, as you train it once and then can use to to predict values.
- It uses methods which are important in much more complicated Machine Learning practices.
- Gradient descent is a way to implement Linear Regression
- MSE of (Mean Squarred Error) should be as low as possible.
 
