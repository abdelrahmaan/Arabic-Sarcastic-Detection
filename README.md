## An Ensemble Transformer-based Model for Arabic Sarcasm Detection
I participated in SemEval 2022 - Task 6 (iSarcasmEval): Intended Sarcasm Detection In English and Arabic, and My paper "An Ensemble Transformer-based Model for Arabic Sarcasm Detection" is accepted and published on ACL.

### [The Conferance information and the data related](https://sites.google.com/view/semeval2022-isarcasmeval#h.t53li2ejhrh8)
### [Paper Link](https://aclanthology.org/2022.semeval-1.124/)

---

### Abstract.
Due to the widespread usage of social media sites and the enormous number of users who utilize irony implicit words in most of their tweets and posts, it has become necessary to detect sarcasm, which strongly influences understanding and analyzing the crowd’s opinions. Detecting sarcasm is difficult due to the nature of sarcastic tweets, which vary based on the topic, region, the user’s attitude, culture, terminologies, and other criteria. In addition to these difficulties, detecting sarcasm in Arabic has its challenges due to its complexities, such as being morphologically rich, having many different dialects, and having low resources.In this research, we present our submission of (iSarcasmEval) sub-task A of the shared task on SemEval 2022. In Sub-task A; we determine whether the tweets are sarcastic or non-sarcastic. We implemented different approaches based on Transformers. First, we fine-tuned the AraBERT, MARABERT, and AraELECTRA. One of the challenges that faced us was that the data was not balanced. Non-sarcastic data is much more than sarcastic. We used data augmentation techniques to balance the two classes, significantly affecting the performance. The performance F1 score of the three models was 87%, 90%, and 91%, respectively. Then we boosted the three models by developing an ensemble model based on hard voting. The final performance F1 Score was 93%.
