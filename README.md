# JuryDB
## A public domain jury pool selection platform
It's an unfortunate truth that jury selection tools by third party vendors and in-house solutions have often fallen short of their requirements. This project is an attempt to add transparency and accuracy to the jury selection process. As the sphere of influence of technology becomes greater, constituents should be critical of what algorithms and data are being used for important judicial ceremonies.

## Main Goals
### Minimizing Bias
Even after the Civil Rights Act was passed, Jim Crow states easily purged black jurors from jury pools. In some cases, names that were drawn for juries had different colors for white and black citizens, and so only white names were ever chosen ([source, page 10](https://eji.org/wp-content/uploads/2019/10/illegal-racial-discrimination-in-jury-selection.pdf)).

While practices like these are not commonplace any more, there are intentional and unintentional biases that are in effect to this very day. [Iowa](https://ilr.law.uiowa.edu/print/volume-101-issue-5/no-records-no-right-discovery-and-the-fair-cross-section-guarantee/) counted the 'd' in hometown names to mean 'deceased' (which included Iowa's two biggest and most diverse cities). [Louisiana](https://www.washingtonpost.com/opinions/2019/07/10/this-louisiana-courtroom-statistically-improbable-jury-pools-give-prosecutors-an-advantage/) only allows land owners and car drivers into the jury pool, disproportionately ignoring citizens of New Orleans. [This county](https://law.justia.com/cases/indiana/supreme-court/2002/11220204-trb.html) chose jurors by picking random intervals along an alphabetical list of township names until it reached N=1500, so nobody from Wayne township was ever chosen - where the vast majority of black citizens lived.

JuryDB must be designed to select jurors in the most random and unbiased way that is freely availible.

### Ease of Use
Public officials are not hired for their knowledge of GUI navigation. There must be little ambiguity of how the program operates at every step of the process.

### Flexibility
Data comes in many formats. JuryDB must work with as many common datatypes as possible.

## The Future of JuryDB
### Development
The process of public review and comprehensive testing must be done before the software is used in real situations.
### Adoption
Leveraging civic action to convince local governments to use JuryDB.
