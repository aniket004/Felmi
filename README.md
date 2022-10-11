# Felmi
FeLMi: Few-shot Learning with hard Mixup, NeurIPS 2022

Authors: Aniket Roy, Anshul Shah, Ketul Shah, Prithviraj Dhar, Anoop Cherian and Rama Cheallappa.

Abstract: Learning from few examples is a challenging computer vision task. Traditionally,
meta-learning based methods have been used to solve this problem. However recent
approaches show improvements by learning a feature extractor on the abundant
base examples and transferring these to the fewer novel examples. However, the
finetuning stage is often prone to overfitting due to the small size of the novel
dataset. To this end, we propose Few shot Learning with hard Mixup (FeLMi)
using manifold mixup to synthetically generate samples which helps in mitigating
the data scarcity issue. Different from naive mixup, our approach selects the hard
mixup samples using an uncertainty based criteria. To the best of our knowledge,
we are the first to use hard-mixup for few-shot learning problem. Our approach
allows to better exploit the pseudo-labeled base examples through base-novel
mixup and entropy based filtering. We evaluate our approach on common few-
shot benchmarks, e.g., FC-100, CIFAR-FS, miniImageNet and tieredImageNet
and obtain improvement in both 1-shot and 5-shot settings. Additionally, we
experimented on cross-domain few-shot setting (miniImageNet -> CUB) and
obtain significant improvements in both 1-shot and 5-shot settings.

Code coming soon!
