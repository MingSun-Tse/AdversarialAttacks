# AdversarialAttacks
This repo includes recent works regarding adversarial attacks on deep neural network.

## Papers
- Attacks conducted on the *learning systems*: (In constrast, adversarial attacks here are conducted on a *fixed* model with data corruption.)
    - 2004-ACM SIGKDD-[Adversarial classification]()
    - 2006-ACM Symposium on Information, Computer and Communications Security-[Can machine learning be secure?]()
    - 2012-ICML-[Poisoning attacks against support vector machines]()
- 2012-NIPS-Learning with recursive perceptual representations
- 2012-MIT Press-Optimization for machine learning
- 2012.11-[What regularized auto-encoders learn from the data generating distribution](https://arxiv.org/abs/1211.4246)
- 2014-JMLR-[Marginalized denoising autoencoders for nonlinear representations]()
- 2014.2-[Avoiding pathologies in very deep networks](https://arxiv.org/abs/1402.5836)
- 2015-http://coxlab.github.io/ostrichinator/
- 2015-CVPRo-[Deep neural networks are easily fooled: High confidence predictions for unrecognizable images](http://www.evolvingai.org/files/DNNsEasilyFooled_cvpr15.pdf) [[Project](http://www.evolvingai.org/fooling)]
- 2015-BMVC-[Manitest: Are classifiers really invarian]()
- 2015-UAI-[Visual causal feature learning](https://arxiv.org/abs/1412.2309)
- 2015-ICLR-[Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) (FGSM)
- 2015.2-[Analysis of classifiers’ robustness to adversarial perturbations](https://arxiv.org/abs/1502.02590) (theoretical analysis: adversarial instability is due to the low flexibility of classifiers compared to the difficulty of the classification task)
- 2011-ANNML-[Transforming auto-encoders]()
- 2011-MLKDD-[Higher order contractive auto-encoder]()
- 2011-ICML-[Contractive autoencoders: Explicit invariance during feature extraction]()
- 2015-ICLRw-[Towards deep neural network architectures robust to adversarial examples](https://arxiv.org/abs/1412.5068)
- 2016-NIPS-[f-GAN: Training generative neural samplers using variational divergence minimization]()
- 2016.7-On the effectiveness of defensive distillation (1607.05113)
- 2017-[The Cramer distance as a solution to biased Wasserstein gradients]()
- 2018-ICLR-[Demystifying MMD GANs]()
- 2017-ICLR-[Neural photo editing with introspective adversarial networks]()
- 2016-NIPS-[InfoGAN: Interpretable representation learning by information maximizing generative adversarial nets]()
- 2015-NIPS-[Deep generative image models using a laplacian pyramid of adversarial networks]()
- 2015-PR-What is holding back convnets for detection
- 2018-ICLR-Many paths to equilibrium: GANs do not need to decrease a divergence at every step
- 2017-NIPS-Improved training of Wasserstein GANs
- 2017-On convergence and stability of GANs
- 2016-Megapixel size image creation using generative adversarial networks
- 2018-ICML-Which training methods for GANs do actually converge?
- 2019-ICLR-[The unusual effectiveness of averaging in gan training](https://openreview.net/forum?id=SJgw_sRqFQ)
- 2016-CVPR-[DeepFool: A simple and accurate method to fool deep neural networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/app/S12-10.pdf) [[Code](http://github.com/lts4/deepfool)]
- 2018-ECCV-[Convnets and imagenet beyond accuracy: Explanations, bias detection, adversarial examples and model criticism](https://arxiv.org/abs/1711.11443)
- 2018-ICLRw-[Attacking the Madry defense model with L1–based adversarial examples](https://arxiv.org/abs/1710.10733)
- 2016.5-Transferability in machine learning: from phenomena to black-box attacks using adversarial samples
- 2017-ICLR-Delving into transferable adversarial examples and black-box attacks
- 2017-ACMw-Zeroth order optimization based black-box attacks to deep neural networks without training substitute models
- 2018-Autozoom: Autoencoder-based zeroth order optimization method for attacking blackbox neural networks
- 2018-Query-efficient hard-label black-box attack: An optimization-based approach
- 2017-ICLR-Adversarial machine learning at scale (I-FGSM)
- 2017-CVPR-[Universal adversarial perturbations](http://openaccess.thecvf.com/content_cvpr_2017/html/Moosavi-Dezfooli_Universal_Adversarial_Perturbations_CVPR_2017_paper.html)
- 2017-ICCV-Adversarial examples for semantic segmentation and object detection
- 2017-ICML-Parseval networks: Improving robustness to adversarial examples
- 2017-SSP-**C&W**-[Towards evaluating the robustness of neural networks](https://arxiv.org/abs/1608.04644)
- 2017-ACMw-Adversarial examples are not easily detected: Bypassing ten detection methods (Notice this workshop: 10th ACM Workshop on Artificial Intelligence and Security)
- 2017-NIPS-Formal guarantees on the robustness of a classifier against adversarial manipulation
- 2017-AMACL-Attacking visual language grounding with adversarial examples: A case study on neural image captioning
- 2018-IJCAI-Generating adversarial examples with adversarial networks
- 2018-ICLR-Spatially transformed adversarial examples
- 2018-CVPR-Robust physical-world attacks on deep learning visual classification
- 2018-CVPR-Fooling vision and language models despite localization and attention mechanism
- 2018-ICML-Towards fast computation of certified robustness for relu networks
- 2018-ICLR-Evaluating the robustness of neural networks: An extreme value theory approach
- 2018-AAAI-[EAD: Elastic-net attacks to deep neural networks via adversarial examples](https://arxiv.org/abs/1709.04114)
- 2019-STAT-Universal adversarial perturbations against semantic image segmentation
- 2018-CVPR-Learning transferable architectures for scalable image recognition
- 2018-DSNw-On the limitation of magnet defense against L1-based adversarial examples
- 2018-ICLR-[Towards deep learning models resistant to adversarial attacks](https://arxiv.org/abs/1706.06083)
- 2018-ICML-[Synthesizing robust adversarial examples](https://arxiv.org/pdf/1707.07397.pdf)
- 2018-ICMLb-[Obfuscated gradients give a false sense of security: Circumventing defenses to adversarial examples](http://proceedings.mlr.press/v80/athalye18a/athalye18a.pdf) [[Supp](http://proceedings.mlr.press/v80/athalye18a/athalye18a-supp.pdf)] [[Code](https://github.com/anishathalye/obfuscated-gradients)]
- 2018-NDSS-[Feature squeezing: Detecting adversarial examples in deep neural networks](https://arxiv.org/abs/1704.01155)
- 2017.9-Ground-truth adversarial examples (1709.10207)
- 2017-Asia CCS-Practical Black-Box Attacks against Machine Learning (1602.02697) (ACM on Asia Conference on Computer and Communications Security)
- [Attacking Machine Learning with Adversarial Examples](https://blog.openai.com/adversarial-example-research/)
- 2018-ICLR-[Ensemble Adversarial Training: Attacks and Defenses](https://arxiv.org/abs/1705.07204) [[OpenReview](https://openreview.net/forum?id=rkZvSe-RZ)] (ICLR 2018 accepted at least 11 papers about adversarial attack/defense.)
- 2018-ICLR-[Stochastic activation pruning for robust adversarial defense](https://openreview.net/forum?id=H1uR4GZRZ)
- 2017.9-[Gradient Masking in Machine Learning](https://seclab.stanford.edu/AdvML2017/slides/17-09-aro-aml.pdf)

## Learned Data Augmentation
- 2017-NIPS-[Learning to Compose Domain-Specific Transformations for Data Augmentation](https://arxiv.org/abs/1709.01643)
- 2017.11-[Data Augmentation Generative Adversarial Networks](https://arxiv.org/abs/1711.04340)
- 2018-ICLR-[mixup: Beyond Empirical Risk Minimization](https://arxiv.org/pdf/1710.09412.pdf)
- 2019-ICASSP-[DADA: Deep Adversarial Data Augmentation for Extremely Low Data Regime Classification](https://arxiv.org/abs/1809.00981)
- 2019-CVPR-[AutoAugment: Learning Augmentation Strategies From Data](https://openaccess.thecvf.com/content_CVPR_2019/papers/Cubuk_AutoAugment_Learning_Augmentation_Strategies_From_Data_CVPR_2019_paper.pdf)
- 2019-NIPS-[Fast AutoAugment](https://arxiv.org/abs/1905.00397) [[Code](https://github.com/kakaobrain/fast-autoaugment)]
- 2019-NIPS=[Fixing the train-test resolution discrepancy](http://papers.nips.cc/paper/9035-fixing-the-train-test-resolution-discrepancy.pdf) [[Code](https://github.com/facebookresearch/FixRes)]
- 2019-J of Big Data-[A survey on Image Data Augmentation for Deep Learning](https://link.springer.com/content/pdf/10.1186/s40537-019-0197-0.pdf)
- 2020-ICLR-[Unsupervised Data Augmentation for Consistency Training](https://github.com/google-research/uda)

## People (in alphabeta order of first name)
- [Anish Athalye](https://www.anish.io/) @ MIT
- [Huan Zhang](http://www.huan-zhang.com/) @ UCLA