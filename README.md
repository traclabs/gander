This paper introduces a method, Generative Adversarial Networks for Detecting Erroneous Results (GANDER), leveraging Generative Adversarial Networks to provide online error detection in manipulation tasks for autonomous robot systems. GANDER relies on mapping input images of a trained task to a learned manifold that contains only positive task executions and outcomes. When reconstructed through this manifold, the input images from successful task executions will remain largely unchanged, while the images from a failed task will change significantly. Using this insight, GANDER enables inspection and task outcome verification capabilities using a large number of positive examples but only a small set of negative examples, thus increasing the applicability of autonomous robot systems. We detail the design of GANDER and provide results of a proof-of-concept system, establishing its efficacy in an autonomous inspection, maintenance, and repair task. GANDER produces favorable results compared to baseline approaches and is capable of correctly identifying off-nominal behavior with 91.65% accuracy in our test task. Ablation studies were also performed to quantify the amount of data ultimately needed for this approach to succeed.

<object data="/gander/assets/gander.pdf" width="100%" height="100%" type="application/pdf"/>
