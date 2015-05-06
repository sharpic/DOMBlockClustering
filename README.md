# Presentation Slides for - DOM Block Clustering for Enhanced Sampling and Evaluation

- Slides at: http://sharpic.github.io/DOMBlockClustering/DOMBlockClustering.html#1
- Full Paper at: http://dx.doi.org/10.1145/2745555.2746649
- References at: http://sharpic.github.io/DOMBlockClustering/DOMBlockClustering.bib

## Abstract
Large websites are difficult to evaluate for Web Accessibility compliance due to the shear number of pages, the inaccuracy of current Web evaluation engines, and the W3C stated need to include human evaluators within the testing regime. This makes evaluating large websites all-but technically unfeasible. Therefore, sampling of the pages becomes a critical first step in the evaluation process. Current methods rely on drawing random samples, best guess samples, or convenience samples. In all cases the evaluation results cannot be trusted because the underlying structure and nature of the site are not known; they are missing `website demographics'. By understanding the quantifiable statistics of a given population of pages we are better able to decide on the coverage we need for a full review, as well as the sample we need to draw in order to enact an evaluation. Our solution is to crawl a website comparing, and then clustering, the pages discovered based on Document Object Model block level similarity. This technique can be useful in reducing very large sites to a more manageable size, and allowing an 80% coverage by evaluating between approx 0.1-4% of pages; additionally, by refining our clustering algorithm, we discuss how this could be reduced further.

## Authors
Simon Harper [1], Anwar Ahmad Moon [1], Markel Vigo [1], Giorgio Brajnik [2], and Yeliz Yesilada [3]

1. School of Computer Science University of Manchester United Kingdom 
2. Dept. of Mathematics and Computer Science University of Udine
Italy
3. Middle East Technical University Northern Cyprus Campus Turkey