<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-04 ~ 2026-06-02
- 运行时间：2026-06-02 08:04:44 UTC
- 运行状态：成功
- 本次总论文数：20
- 精读区：11
- 速读区：9

### 今日简报（AI）
本期精读扩散模型风格控制与归一化等变性去噪，速览多模态分割、纹理分类、颜色恒常等前沿  
最值得关注：文本驱动细粒度风格属性注入潜在扩散模型，以及归一化等变性让任意骨干去噪时保持结构一致  
建议尝试将归一化等变性推广至其他底层视觉任务，探索可控生成在创意工具中的落地
- 详情：[/20260504-20260602/README](/20260504-20260602/README)

### 精读区论文标签
1. [Stylistic Attribute Control in Latent Diffusion Models](/20260504-20260602/2605.02583v1-stylistic-attribute-control-in-latent-diffusion-models)  
   标签：评分：9.0/10、query:cp
   evidence：学习解耦的风格属性编辑方向，同时保持语义
2. [Normalization Equivariance for Arbitrary Backbones, with Application to Image Denoising](/20260504-20260602/2605.08193v1-normalization-equivariance-for-arbitrary-backbones-with-application-to-image-denoising)  
   标签：评分：9.0/10、query:cp
   evidence：强制全局对比度和亮度等变性，在光照变化下保持语义内容
3. [Segment Anything with Robust Uncertainty-Accuracy Correlation](/20260504-20260602/2605.10603v1-segment-anything-with-robust-uncertainty-accuracy-correlation)  
   标签：评分：9.0/10、query:cp
   evidence：通过扰动纹理的风格-变形攻击训练以增强外观偏移下的鲁棒性
4. [Physics-Grounded Adversarial Stain Augmentation with Calibrated Coverage Guarantees](/20260504-20260602/2605.13889v1-physics-grounded-adversarial-stain-augmentation-with-calibrated-coverage-guarantees)  
   标签：评分：9.0/10、query:cp
   evidence：在染色参数空间中进行对抗增强以提升对颜色变化的鲁棒性
5. [SHED: Style-Homogenized Embedding Alignment for Domain Generalization](/20260504-20260602/2605.16973v1-shed-style-homogenized-embedding-alignment-for-domain-generalization)  
   标签：评分：9.0/10、query:cp
   evidence：从CLIP嵌入中移除域特定风格中心，分离风格(颜色)与语义
6. [Content-Style Identification via Differential Independence](/20260504-20260602/2605.17827v1-content-style-identification-via-differential-independence)  
   标签：评分：9.0/10、query:cp
   evidence：通过微分独立性解耦内容与风格，直接适用于颜色/形状分离
7. [PERL: Parameter Efficient Reasoning in CLIP Latent Space](/20260504-20260602/2605.18464v1-perl-parameter-efficient-reasoning-in-clip-latent-space)  
   标签：评分：9.0/10、query:cp
   evidence：在 CLIP 潜在空间中进行迭代推理以实现自适应
8. [Lighting-aware Unified Model for Instance Segmentation](/20260504-20260602/2605.20436v1-lighting-aware-unified-model-for-instance-segmentation)  
   标签：评分：9.0/10、query:cp
   evidence：光照感知适配器在特征层面增强实例分割对光照变化的鲁棒性
9. [Certified Robustness from Approximate Gaussian Mixture Structures in Pretrained Latent Spaces](/20260504-20260602/2605.25352v1-certified-robustness-from-approximate-gaussian-mixture-structures-in-pretrained-latent-spaces)  
   标签：评分：9.0/10、query:cp
   evidence：利用预训练表示中的潜在结构设计可认证鲁棒分类器
10. [Transfer learning RGB models to hyperspectral images with trainable tensor decompositions](/20260504-20260602/2605.28331v1-transfer-learning-rgb-models-to-hyperspectral-images-with-trainable-tensor-decompositions)  
   标签：评分：9.0/10、query:cp
   evidence：提出可训练张量分解分离卷积滤波器中的空间（形状）与光谱（颜色）分量，以将RGB模型迁移至高光谱图像
11. [One Channel to Rule Them All: Rethinking Input Representation for Visual Place Recognition](/20260504-20260602/2606.00936v1-one-channel-to-rule-them-all-rethinking-input-representation-for-visual-place-recognition)  
   标签：评分：9.0/10、query:cp
   evidence：研究去除颜色对视觉地点识别的影响；在场景变化下灰度常优于RGB

### 速读区论文标签
1. [Chaotic Contrastive Learning for Robust Texture Classification](/20260504-20260602/2605.05012v1-chaotic-contrastive-learning-for-robust-texture-classification)  
   标签：评分：8.0/10、query:cp
   evidence：通过混沌增强学习不变表示来解决对颜色和形状特征的过度依赖，从而解耦纹理与颜色/形状
2. [UniTriGen: Unified Triplet Generation of Aligned Visible-Infrared-Label for Few-Shot RGB-T Semantic Segmentation](/20260504-20260602/2605.14626v1-unitrigen-unified-triplet-generation-of-aligned-visible-infrared-label-for-few-shot-rgb-t-semantic-segmentation)  
   标签：评分：8.0/10、query:cp
   evidence：在可见光与红外模态间生成语义一致的三元组
3. [White-Balance First, Adjust Later: Cross-Camera Color Constancy via Vision-Language Evaluation](/20260504-20260602/2605.19613v1-white-balance-first-adjust-later-cross-camera-color-constancy-via-vision-language-evaluation)  
   标签：评分：8.0/10、query:cp
   evidence：VLM评估引导的迭代白平衡校正，保持不同光照下物体颜色一致性
4. [TsallisPGD: Adaptive Gradient Weighting for Adversarial Attacks on Semantic Segmentation](/20260504-20260602/2605.03405v1-tsallispgd-adaptive-gradient-weighting-for-adversarial-attacks-on-semantic-segmentation)  
   标签：评分：7.0/10、query:cp
   evidence：提出了一种新的语义分割对抗攻击方法，可潜在地应用于颜色扰动
5. [Lightweight Unpaired Smartphone ISP Transfer with Semantic Pseudo-Pairing](/20260504-20260602/2605.07495v1-lightweight-unpaired-smartphone-isp-transfer-with-semantic-pseudo-pairing)  
   标签：评分：7.0/10、query:cp
   evidence：语义伪配对在RAW和RGB色彩不对齐下保持语义含义
6. [Hystar: Hypernetwork-driven Style-adaptive Retrieval via Dynamic SVD Modulation](/20260504-20260602/2605.10009v1-hystar-hypernetwork-driven-style-adaptive-retrieval-via-dynamic-svd-modulation)  
   标签：评分：7.0/10、query:cp
   evidence：通过SVD调制动态适应查询样式的模型权重
7. [Segment Anything with Robust Uncertainty-Accuracy Correlation](/20260504-20260602/2605.10603v2-segment-anything-with-robust-uncertainty-accuracy-correlation)  
   标签：评分：7.0/10、query:cp
   evidence：针对纹理偏差捷径并通过扰动纹理/外观来促进以形状为中心的处理，与颜色-形状解耦一致
8. [Towards Fine-Grained Robustness: Attention-Guided Test-Time Prompt Tuning for Vision-Language Models](/20260504-20260602/2605.19956v1-towards-fine-grained-robustness-attention-guided-test-time-prompt-tuning-for-vision-language-models)  
   标签：评分：6.0/10、query:cp
   evidence：提出注意力引导的测试时提示微调，一种应对对抗攻击的语义保持方法，可扩展到颜色扰动
9. [Deep Attention Reweighting: Post-Hoc Attention-Based Feature Aggregation in CNNs for Disentangling Core and Spurious Features under Spurious Correlations](/20260504-20260602/2605.20732v1-deep-attention-reweighting-post-hoc-attention-based-feature-aggregation-in-cnns-for-disentangling-core-and-spurious-features-under-spurious-correlations)  
   标签：评分：6.0/10、query:cp
   evidence：特征重赋权以解耦核心与虚假特征，增强鲁棒性


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
