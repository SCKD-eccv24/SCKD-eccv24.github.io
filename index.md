### Abstract

Novel Class Discovery (NCD) aims to discover unknown and novel classes in an unlabeled set by leveraging knowledge already learned about known classes. Existing works focus on instance-level or class level knowledge representation and build a shared representation space to achieve performance improvements. However, a long-neglected issue is the potential imbalanced number of samples from known and novel classes, pushing the model towards dominant classes. Therefore, these methods suffer from a challenging trade-off between reviewing known classes and discovering novel classes. Based on this observation, we propose a Self-Cooperation Knowledge Distillation (SCKD) method to utilize each training sample (whether known or novel, labeled or unlabeled) for both review and discovery. Specifically, the model’s feature representations of known and novel classes are used to construct two disjoint representation spaces. Through spatial mutual information, we design a self-cooperation learning to encourage model learning from the two
feature representation spaces from itself. Extensive experiments on six datasets demonstrate that our method can achieve significant performance improvements, achieving state-of-the-art performance.


### Conclusion

This paper considers a practical but long-neglected challenge in the Novel Class Discovery (NCD) task, i.e., the imbalanced number of samples from known and novel classes. The model despises the learning of novel classes when the known class dominates while the model forgets the prior knowledge of the known class when the novel class dominates. Compared to transferring knowledge by a shared representation space, we collect the model’s feature representations of known and novel classes as two disjoint representation spaces. Then we propose a SelfCooperation Knowledge Distillation (SCKD) method to utilize every sample for review and discovery. Our method is conceptually simple and intuitive and achieves top-level competitive results in numerous experiments on six datasets.

### Acknowledgements

This work is supported by the Engineering Research Center of AI & Robotics, Ministry of Education, China.

