bands and dates if images

what are mandatory steps for thematic information extraction?

slide 4 very important

define the mapping approach:
==slide 10==
MMU, roster/vector map
 roster format:
 - mmu pixel size
 - feature selection
 - image classification
 - accuracy assesment

image generalization (post processing) - transform 30m pixel to 100m, (less space, faster loading)
 vector format:
 - feature selection
 - image classification
 - post-processing (generalisation + raster to vector conversion)
 - accuracy assesment 

need groups
topics:
remote sensing towards sustainable earth
remote sensing during war times
helping refugees
remote sensing for citizen
for student finishing a degree
in professional enviroment
remote sensing and AI
smart cities

how many people for a group?

stratification - split land mass into separate areas

**image segmentation to make objects/vectors**

object oriented image classification

multi resolution segmentation - from super object to sub objects

feature selection - select the bands we are going to use

semantic relationship - relationship between objects (urban-park)

inter - same year
intra - different years

ndvi - vegetation index

classification based on scatterplot clustering. BASED ON FEATURES OF PIXEL, THe values clustering, by classifier 9decision rule)

classifiers:
- supervised
	- choose training areas (almost like object detection) (tel how water pixels look like ect.)
	- minimum distance classifier (distance from center of each cloud)
- no supervised
	- BASED ON POSITION in matrix WE CAN CLASSIFY areas
	- no training

based on data distribution:
- parametric
- non-parametric (neural-networks)

hard- gives definitive answer 0 or 1
soft - range (0, 1)

paralleleepiped clssifier - create square based on values
maximum lieklihood classfier - probabilities of classifying in ranges

standart deviaion is high - paralel piped

parametric - depends on data distribution, when cannot guarantee, use non parametric

 ==silde 48== fuzzy membership

 know solf classifiers
