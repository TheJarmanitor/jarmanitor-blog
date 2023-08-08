---
title: "Cool Statistical methods"
date: 2023-08-07
---

The clock is ticking and time is running low, study start is getting close. And while i'm not even sure if I'll be able to make it in time (I don't have my passport yet, no flight tickets and no housing) my partner and i decided to have a nice vacation before anxiety kicks in hard. 

Last week was the "International Symposium on Statistics", celebrated every year here in Colombia. It's a nice place to reunite with old friends & colleagues, attend amazing lectures by people all around the world(but mainly South America) and, most relevant to this post, learn about Statistical method you might not know.

While i work on my projects about PCG, (they're coming soon, don't worry)  i'm doing a couple posts about my experience in the Symposium: One on the technical side of things, and another one more meditative. This last week gave me so many new perspectives when it comes to Statitics and my possible future and i want to share it with you all.


# Some Context

The Symposium consists of several parts:
- Small Courses
- Selected  Lectures
- Presentations by teachers andd Students
- A poster session with small projects

Most of these follow a main "theme" that is chosen every year. Said theme could be a general idea on statistics or a specific method or application. this year's theme is actually the first  method i want to talk about

# Functional Data.

When you work on Data Analysis or Machine Learning, you'll most likely get a dataset ffor you to use for youur project.

| Variable 1    | Variable 2    | Variable 3 |
| ------------- |:-------------:| -----:     |
| 10            | 48            | 112        |
| 22            | 62            | 106        |
| 63            | 55            | 99         |

 This dataset can be represented as a matrix

$$ \begin{bmatrix} 
   10 & 48 & 112 \\
   22 & 62 & 106 \\
   63 & 55 & 99 \\
   \end{bmatrix} $$

And that's pretty much what you'll use in your work. Whether it is basic descriptive analysis or fitting a neural network, your input probably is a numerical matrix.

But this is not the only way to represent Data. Sometimes your
