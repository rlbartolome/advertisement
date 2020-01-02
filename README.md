# Can we block internet advertisements?

Advertisements has always been an essential part of all businesses around the world. In particular,
internet advertisements in the form of banners in websites has been on the rise especially at the turn
of the century. However, many users do not want to be cluttered with these images. In this exercise,
we explore a dataset where we have several image features, such as size, if the site is local and on what
site it came from. Exploring the dataset, we found that it had a lot of components (1,559 variables).
As such, we performed Principal Components Analysis (PCA) to the data to decrease the number of
components. We found that (1) 110 components can explain 75% of the variance and (2) 73 components
can explain 60% of the variance, which is a massive decrease from the original number of components.
We also classified the images using Support Vector Machines, where indeed, we found that it is possible
to classify images as ads or non-ads with an accuracy of 96.2% using a Linear Kernel. This is similar to
what the original authors got at 97% accuracy.
