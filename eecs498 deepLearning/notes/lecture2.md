# Lecture2 Image Classification
## definition
Input: image
Output: categories
## main challenge
Semantic Gap 
situations:
1. viewpoint variation
    once changes the angle or other, the whole matrix will change in a 
2. Intraclass Variation
3. fine-grained categories
4. background clutter
5. Illumination changes
   1. daylight
   2. dark
   3. etc.
6. Deformation
   1. different poses
7. occlusion
   1. hidden and so on
   2. requires real world knowledge background

## data sets
1. image net
   1. object
   2. 1000 categories
2. mit places
   1. scenes
3. CIFAR
4. omniglot
   1. low shot learning

## algorithm
1. nearest neighbor
   1. comparison function
      1. L1 distance  
      2. dicision boundries
        
   2. 