# SPT Automated Reading

[**Go to the paper**](https://link-url-here.org)

The skin prick test (SPT) is performed to diagnose different types of allergies. This medical procedure requires measuring the size of the skin wheals that appear when the test is performed. However, the manual measurement method is cumbersome and suffers from intra and inter-observer errors. Thus, multiple approaches have been developed to improve the reproducibility of the test. This work aims to improve part of the automated reading of the SPT to improve the reliability of the wheal detection procedure through the use of convolutional neural networks (CNN). Our proposal starts from the 3D images of the SPT from the arm of patients. They are processed for global surface removal, and then a CNN is trained to produce an output mask that detects the wheals. Finally, the contour of each wheal and its largest diameter is obtained. Encouraging results with mean difference 0.966 mm and mean coefficient of variation 7.29% show that the proposed method provides reliable automated skin wheal detection.

![Fig 1. The stages of the classical method replaced by our proposal are enclosed in the red box.](https://imgur.com/a/2PZQ8sy)

![Fig2. Representation of the CNN architecture.](https://imgur.com/a/wWNmbS1)

![Fig2. Representation of the CNN architecture.]([http://url/to/img.png](https://imgur.com/a/dCZkNU0))
