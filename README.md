# 对抗样本生成工具
## 1 Cleverhans
[cleverhans](https://github.com/tensorflow/cleverhans)  
Google Inc., OpenAI, Pennsylvania State University, University of Toronto. 2016  
V4.0.0 2023.4.26  
支持JAX、PyTorch和TensorFlow 2。  
CleverHans提供了一系列易于使用的 API，供研究人员和开发人员测试和评估机器学习模型的对抗鲁棒性。  
通过提供各种攻击和防御方法，CleverHans 帮助用户了解和改进模型在面对恶意输入时的表现。  
该工具包在研究社区中广泛使用，并不断更新最新的研究成果和方法。  

## 2 Foolbox
[foolbox](https://github.com/bethgelab/foolbox)  
图宾根大学 2017  
支持PyTorch, TensorFlow，JAX框架。  
Foolbox 的设计目标是使得对抗性攻击的实现尽可能简单和高效。用户可以轻松地对模型进行攻击，并获取详细的攻击结果和统计信息。  
并且该工具在持续更新最新的研究成果和方法。  
Foolbox 的允许用户根据自己的需求进行扩展和修改，为对抗性机器学习的研究提供重要支持和参考。  

## 3 ART(adversarial-robustness-toolbox)
[ART](https://github.com/IBM/adversarial-robustness-toolbox)  
IBM Research 2018  
Adversarial Robustness Toolbox（ART）是一个用于机器学习安全的Python库。ART提供工具，使开发人员和研究人员能够保护和评估机器学习模型和应用程序免受规避、中毒、提取和推理的对抗性威胁。  
支持多个流行的机器学习框架（TensorFlow、Keras、PyTorch、MXNet、scikit-learn、XGBoost、LightGBM、CatBoost、GPy）  
支持多种数据类型（图像、表格、音频、视频等）和机器学习任务（分类、对象检测、语音识别、生成、认证等）。  

## 4 Advertorch
[advertorch](https://github.com/BorealisAI/advertorch)  
BorealisAI.Canada 2018
主要支持 PyTorch 框架，它是基于 PyTorch 实现的故强调与 PyTorch 的兼容性和优化。  
主要关注对抗攻击方法，提供少数防御方法。  
提供了易于使用的接口和丰富的对抗性攻击实现。它允许研究人员和开发者在标准化的环境下测试并比较不同攻击和防御方法的效果。  
通过该工具可以更深入地理解模型在面对不同攻击时的表现，并探索提升模型鲁棒性的方法。  

## 5 Deeprobust
[deeprobust](https://github.com/DSE-MSU/DeepRobust)  
Michigan State University 2021  
支持 PyTorch 和 TensorFlow框架。  
其优势在于涵盖了社交网络和推荐系统中的图网络鲁棒性分析。  
不仅包括了传统的图像和文本攻击算法，还扩展到图处理领域。  
设计了一套统一的接口提供所有攻击和防御任务。  
在多个数据集和不同条件下，DeepRobust 的效果和效率均达到较高水平，是一个高效准确的工具。  

## 6 adversarial-attacks-pytorch
[adversarial-attacks-pytorch](https://github.com/Harry24k/adversarial-attacks-pytorch)   
 Seoul National University 2019  
支持pytorch 图像分类任务  
设计着眼于易用性，有助于研究者和开发者快速实现和比较不同的攻击策略。提供了清晰的 API 和丰富的文档，帮助入门和对抗性训练。  
用户可以轻松定制攻击过程，如调整攻击方式的参数，或者自定义攻击算法来适应特定的需求和场景。  
与 PyTorch 的深度集成，这个库可以无缝集成到现有的 PyTorch 项目中，保持了与 PyTorch 生态系统的高度兼容性。    

## 7 BlackboxBench
[BlackboxBench]https://github.com/SCLBD/BlackboxBench  
香港中文大学（深圳）大数据安全计算实验室（SCLBD） 2023  
一个黑盒对抗攻击基准测试，涵盖了多种黑盒对抗攻击类型，包括基于查询的攻击和基于转移的攻击。  
它提供了一个统一的、可扩展的、基于模块的代码库，实现了25种基于查询的攻击算法和30种基于转移的攻击算法。  
针对 CIFAR-10 和 ImageNet 数据集上的主流模型架构评估这些算法。  

# 其他类型工具
## 1 EvalDNN
[EvalDNN](https://github.com/yqtianust/EvalDNN)  
Microsoft Asia Cloud Research Software Fellow Award 2019
支持TensorFlow、Keras、GluonCV 、PyTorch。
包括准确率、鲁棒性(foolbox)、覆盖率(NeuronCoverage)三个评价指标。
基于数据集Cifar10和Mnist.  

## 2 responsible-ai-toolbox
[responsible-ai-toolbox](https://github.com/mit-ll-responsible-ai/responsible-ai-toolbox)  
MIT Lincoln Laboratory  2022
以PyTorch为中心的工具，用于评估和增强人工智能模型的鲁棒性和可解释性。
目前用于评估和增强AI系统稳健性的大部分工具都是研究级代码。与标准API相比，这些现有工具在组合性、可扩展性和可靠性方面存在不足。  
Rai-toolbox设计了更灵活的API，并可以与其他流行的机器学习框架自然结合。    

## 3 robustbench
[robustbench](https://github.com/RobustBench/robustbench)  
University of T¨ubingen, Germany 2020  
该工具的目标是系统地跟踪对抗鲁棒性的真实进展。    
RobustBench通过提供标准化的评估方法和数据集（Imagenet），帮助消除不同攻击和防御研究工作之间的比较偏差。  
除了标准化基准测试外，RobustBench 还提供了坚固的防御模型，用于测试对抗攻击方法。  

## 5 ROBY
[ROBY](https://github.com/fmselab/roby)  
National Institute of Informatics Tokyo, Japan 2020  
用于分析神经网络分类器的鲁棒性。  
定义鲁棒性为分类器在输入数据经过特定类型变化后，其准确率保持在一个预设阈值（Θ）以上的能力。  
提出了一个近似方法，该方法涉及在可能的变化区间内采样若干等分布的点，并计算在这些点上模型准确率高于阈值的占比。  
任务类型包括医学诊断、手写数字识别、交通标志识别、MNIST音频识别。  
用户也可以指定测试数据集的位置、如何获取测试数据的正确分类以及要对输入数据应用哪些变化，从而评估不同模型的鲁棒性。  


