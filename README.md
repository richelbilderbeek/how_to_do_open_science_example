# how_to_do_open_science_example

An example of how to do Open Science, shown in the videos below:
How to do Open Science research. Step 0: Why?

Step|Description|YouTube link                        |Download link
----|-----------|------------------------------------|--------------
   0|Why?       |[Here](https://youtu.be/s4hsBBhEabs)|[Here](http://richelbilderbeek.nl/how_to_do_open_science_0.ogv)
   1|Setup      |(not yet) Here                      |(not yet) Here 
   2|Hypotheses |(not yet) Here                      |(not yet) Here 
   3|Method     |(not yet) Here                      |(not yet) Here 
   4|Conclusion |(not yet) Here                      |(not yet) Here 

This example uses only gratis (free as in beer) and/or 
libre (free as in freedom) and/or open-source tools,
such as Linux, GitHub, Travis CI, R, GNU make, LaTeX.

How to do Open Science research
===============================

Step 0: Why?
------------

 * Why Open Science?
   * Better way to knowledge
   * More logical workflow

```
Hypotheses <-> Methods <-> Results <-> Conclusion

versus

Hypotheses -> Methods -> Results -> Conclusion
```

 * What is Open Science?
   * Reproducible
   * Trustworthy
 * Reproducible research is hard
   * Reproducible in 'do it again'

```
If you assume your research will not be repeated,
you can safely assume your research will not be repeated

Richèl J.C. Bilderbeek
```

 * Trustworthy research is different
   * Prevent HARKing

Step 1: Setup
-------------

 * Create GitHub repository
 * Activate Travis CI
 * Show Travis CI build badge
 * Write stub article
 * Let Travis CI build article

Step 2: Hypotheses
------------------

 * Write article
   * Abstract
   * Introduction
   * Hypotheses
   * Methods
   * Results, with stub figures 
   * Conclusion
   * Discussion
 * Add time-stamp to article
 * Ask for review
   * Do the hypotheses naturally follow the introduction?
   * Do the methods test my hypotheses?
   * Can the conlusions be drawn from my methods?
   * Does the discussion describe all weak spots?
 * Process feedback
 * Add time-stamp to article

Step 3: Method
--------------

 * Write vignette
   * Do methods on artificial data
   * Create figures from artificial data
 * Let Travis CI build vignette
 * Update article
   * Methods
   * Results
 * Add time-stamp to article
 * Ask for review
   * Is the method correct?
   * Can the details of the method be checked?
   * Do the figures show the results clearly?
 * Process feedback
 * Add time-stamp to article

Step 4: Conclusion
------------------

 * Write package to obtain real data
 * Update vignette to use real data
 * Let Travis CI build package and vignette
 * Update article
   * Results
   * Conclusion
 * Add time-stamp to article
 * Ask for review
   * Is the method correct?
   * Can the details of the method be checked?
   * Do the figures show the results clearly?
 * Add time-stamp to article
 * Submit to journal

