# Topics for Literature Review

## Tensor Program Optimization

```latex
@inproceedings{feng2023tensorir,
  title={Tensorir: An abstraction for automatic tensorized program optimization},
  author={Feng, Siyuan and Hou, Bohan and Jin, Hongyi and Lin, Wuwei and Shao, Junru and Lai, Ruihang and Ye, Zihao and Zheng, Lianmin and Yu, Cody Hao and Yu, Yong and others},
  booktitle={Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2},
  pages={804--817},
  year={2023}
}

@inproceedings{ansel2024pytorch,
  title={Pytorch 2: Faster machine learning through dynamic python bytecode transformation and graph compilation},
  author={Ansel, Jason and Yang, Edward and He, Horace and Gimelshein, Natalia and Jain, Animesh and Voznesensky, Michael and Bao, Bin and Bell, Peter and Berard, David and Burovski, Evgeni and others},
  booktitle={Proceedings of the 29th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2},
  pages={929--947},
  year={2024}
}
```

## Beyond Transformer Architecture

```
@article{gu2023mamba,
  title={Mamba: Linear-time sequence modeling with selective state spaces},
  author={Gu, Albert and Dao, Tri},
  journal={arXiv preprint arXiv:2312.00752},
  year={2023}
}
```

## NPU Architecture

```latex
@inproceedings{liao2021ascend,
  title={Ascend: a scalable and unified architecture for ubiquitous deep neural network computing: Industry track paper},
  author={Liao, Heng and Tu, Jiajin and Xia, Jing and Liu, Hu and Zhou, Xiping and Yuan, Honghui and Hu, Yuxing},
  booktitle={2021 IEEE International Symposium on High-Performance Computer Architecture (HPCA)},
  pages={789--801},
  year={2021},
  organization={IEEE}
}
```

## TPU Architecture

```latex
@article{norrie2021design,
  title={The design process for Google's training chips: TPUv2 and TPUv3},
  author={Norrie, Thomas and Patil, Nishant and Yoon, Doe Hyun and Kurian, George and Li, Sheng and Laudon, James and Young, Cliff and Jouppi, Norman and Patterson, David},
  journal={IEEE Micro},
  volume={41},
  number={2},
  pages={56--63},
  year={2021},
  publisher={IEEE}
}

@inproceedings{jouppi2023tpu,
  title={Tpu v4: An optically reconfigurable supercomputer for machine learning with hardware support for embeddings},
  author={Jouppi, Norm and Kurian, George and Li, Sheng and Ma, Peter and Nagarajan, Rahul and Nai, Lifeng and Patil, Nishant and Subramanian, Suvinay and Swing, Andy and Towles, Brian and others},
  booktitle={Proceedings of the 50th Annual International Symposium on Computer Architecture},
  pages={1--14},
  year={2023}
}
```

## Collective Communication Optimization

```latex
@inproceedings{cowan2023mscclang,
  title={Mscclang: Microsoft collective communication language},
  author={Cowan, Meghan and Maleki, Saeed and Musuvathi, Madanlal and Saarikivi, Olli and Xiong, Yifan},
  booktitle={Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2},
  pages={502--514},
  year={2023}
}

@inproceedings{wu2024mccs,
  title={MCCS: A Service-based Approach to Collective Communication for Multi-Tenant Cloud},
  author={Wu, Yongji and Xu, Yechen and Chen, Jingrong and Wang, Zhaodong and Zhang, Ying and Lentz, Matthew and Zhuo, Danyang},
  booktitle={Proceedings of the ACM SIGCOMM 2024 Conference},
  pages={679--690},
  year={2024}
}
```

## In Network Aggregation

```latex
@inproceedings{lao2021atp,
  title={$\{$ATP$\}$: In-network aggregation for multi-tenant learning},
  author={Lao, ChonLam and Le, Yanfang and Mahajan, Kshiteej and Chen, Yixi and Wu, Wenfei and Akella, Aditya and Swift, Michael},
  booktitle={18th USENIX Symposium on Networked Systems Design and Implementation (NSDI 21)},
  pages={741--761},
  year={2021}
}

@inproceedings{sapio2021scaling,
  title={Scaling distributed machine learning with $\{$In-Network$\}$ aggregation},
  author={Sapio, Amedeo and Canini, Marco and Ho, Chen-Yu and Nelson, Jacob and Kalnis, Panos and Kim, Changhoon and Krishnamurthy, Arvind and Moshref, Masoud and Ports, Dan and Richt{\'a}rik, Peter},
  booktitle={18th USENIX Symposium on Networked Systems Design and Implementation (NSDI 21)},
  pages={785--808},
  year={2021}
}
```

## Fairness in ML Service

```latex
@inproceedings{ghodsi2012multi,
  title={Multi-resource fair queueing for packet processing},
  author={Ghodsi, Ali and Sekar, Vyas and Zaharia, Matei and Stoica, Ion},
  booktitle={Proceedings of the ACM SIGCOMM 2012 conference on Applications, technologies, architectures, and protocols for computer communication},
  pages={1--12},
  year={2012}
}

@inproceedings{sheng2024fairness,
  title={Fairness in serving large language models},
  author={Sheng, Ying and Cao, Shiyi and Li, Dacheng and Zhu, Banghua and Li, Zhuohan and Zhuo, Danyang and Gonzalez, Joseph E and Stoica, Ion},
  booktitle={18th USENIX Symposium on Operating Systems Design and Implementation (OSDI 24)},
  pages={965--988},
  year={2024}
}
```

## Multi-Tenant LLM Service

```latex
@article{chen2024punica,
  title={Punica: Multi-tenant lora serving},
  author={Chen, Lequn and Ye, Zihao and Wu, Yongji and Zhuo, Danyang and Ceze, Luis and Krishnamurthy, Arvind},
  journal={Proceedings of Machine Learning and Systems},
  volume={6},
  pages={1--13},
  year={2024}
}

@article{sheng2024slora,
  title={SLoRA: Scalable Serving of Thousands of LoRA Adapters},
  author={Sheng, Ying and Cao, Shiyi and Li, Dacheng and Hooper, Coleman and Lee, Nicholas and Yang, Shuo and Chou, Christopher and Zhu, Banghua and Zheng, Lianmin and Keutzer, Kurt and others},
  journal={Proceedings of Machine Learning and Systems},
  volume={6},
  pages={296--311},
  year={2024}
}
```

## Data Parallel System Optimization

```latex
@article{li13pytorch,
  title={PyTorch Distributed: Experiences on Accelerating Data Parallel Training},
  author={Li, Shen and Zhao, Yanli and Varma, Rohan and Salpekar, Omkar and Noordhuis, Pieter and Li, Teng and Paszke, Adam and Smith, Jeff and Vaughan, Brian and Damania, Pritam and others},
  journal={Proceedings of the VLDB Endowment},
  volume={13},
  number={12}
}

@inproceedings{jiang2020unified,
  title={A unified architecture for accelerating distributed $\{$DNN$\}$ training in heterogeneous $\{$GPU/CPU$\}$ clusters},
  author={Jiang, Yimin and Zhu, Yibo and Lan, Chang and Yi, Bairen and Cui, Yong and Guo, Chuanxiong},
  booktitle={14th USENIX Symposium on Operating Systems Design and Implementation (OSDI 20)},
  pages={463--479},
  year={2020}
}
```

## Data Parallel Algorithmic Optimization - Gradient Compression

```
@article{alistarh2017qsgd,
  title={QSGD: Communication-efficient SGD via gradient quantization and encoding},
  author={Alistarh, Dan and Grubic, Demjan and Li, Jerry and Tomioka, Ryota and Vojnovic, Milan},
  journal={Advances in neural information processing systems},
  volume={30},
  year={2017}
}

@inproceedings{wang2017efficient,
  title={Efficient distributed learning with sparsity},
  author={Wang, Jialei and Kolar, Mladen and Srebro, Nathan and Zhang, Tong},
  booktitle={International conference on machine learning},
  pages={3636--3645},
  year={2017},
  organization={PMLR}
}
```

## Data Parallel Algorithmic Optimization - Asynchronous Training

```
@inproceedings{zhou2018distributed,
  title={Distributed asynchronous optimization with unbounded delays: How slow can you go?},
  author={Zhou, Zhengyuan and Mertikopoulos, Panayotis and Bambos, Nicholas and Glynn, Peter and Ye, Yinyu and Li, Li-Jia and Fei-Fei, Li},
  booktitle={International Conference on Machine Learning},
  pages={5970--5979},
  year={2018},
  organization={PMLR}
}
```

## Data Parallel Algorithmic Optimization - Decentralized Communication

```
@article{lian2017can,
  title={Can decentralized algorithms outperform centralized algorithms? a case study for decentralized parallel stochastic gradient descent},
  author={Lian, Xiangru and Zhang, Ce and Zhang, Huan and Hsieh, Cho-Jui and Zhang, Wei and Liu, Ji},
  journal={Advances in neural information processing systems},
  volume={30},
  year={2017}
}
```

## Pipeline Parallel System Optimization

```
@inproceedings{qi2024zero,
  title={Zero Bubble (Almost) Pipeline Parallelism},
  author={Qi, Penghui and Wan, Xinyi and Huang, Guangxing and Lin, Min},
  booktitle={The Twelfth International Conference on Learning Representations},
  year={2024}
}

@article{lamy2023breadth,
  title={Breadth-first pipeline parallelism},
  author={Lamy-Poirier, Joel},
  journal={Proceedings of Machine Learning and Systems},
  volume={5},
  pages={48--67},
  year={2023}
}
```

## Tensor Model Parallel System Optimization

```
@article{zhuang2023optimizing,
  title={On optimizing the communication of model parallelism},
  author={Zhuang, Yonghao and Zheng, Lianmin and Li, Zhuohan and Xing, Eric and Ho, Qirong and Gonzalez, Joseph and Stoica, Ion and Zhang, Hao and Zhao, Hexu},
  journal={Proceedings of Machine Learning and Systems},
  volume={5},
  year={2023}
}
```

## Optimizer Parallel System Optimization

```
@article{zhao2023pytorch,
  title={PyTorch FSDP: Experiences on Scaling Fully Sharded Data Parallel},
  author={Zhao, Yanli and Gu, Andrew and Varma, Rohan and Luo, Liang and Huang, Chien-Chin and Xu, Min and Wright, Less and Shojanazeri, Hamid and Ott, Myle and Shleifer, Sam and others},
  journal={Proceedings of the VLDB Endowment},
  volume={16},
  number={12},
  pages={3848--3860},
  year={2023},
  publisher={VLDB Endowment}
}
```

## Long Sequence Parallel Training

```
@inproceedings{jacobs2024system,
  title={System Optimizations for Enabling Training of Extreme Long Sequence Transformer Models},
  author={Jacobs, Sam Ade and Tanaka, Masahiro and Zhang, Chengming and Zhang, Minjia and Aminadabi, Reza Yazdani and Song, Shuaiwen Leon and Rajbhandari, Samyam and He, Yuxiong},
  booktitle={Proceedings of the 43rd ACM Symposium on Principles of Distributed Computing},
  pages={121--130},
  year={2024}
}

@inproceedings{liuringattention,
  title={RingAttention with Blockwise Transformers for Near-Infinite Context},
  author={Liu, Hao and Zaharia, Matei and Abbeel, Pieter},
  booktitle={The Twelfth International Conference on Learning Representations}
}
```

## Mixture of Expert Parallel Training

```
@article{gale2023megablocks,
  title={Megablocks: Efficient sparse training with mixture-of-experts},
  author={Gale, Trevor and Narayanan, Deepak and Young, Cliff and Zaharia, Matei},
  journal={Proceedings of Machine Learning and Systems},
  volume={5},
  pages={288--304},
  year={2023}
}

@inproceedings{rajbhandari2022deepspeed,
  title={Deepspeed-moe: Advancing mixture-of-experts inference and training to power next-generation ai scale},
  author={Rajbhandari, Samyam and Li, Conglong and Yao, Zhewei and Zhang, Minjia and Aminabadi, Reza Yazdani and Awan, Ammar Ahmad and Rasley, Jeff and He, Yuxiong},
  booktitle={International conference on machine learning},
  pages={18332--18346},
  year={2022},
  organization={PMLR}
}
```

## Offloading Training System

```
@inproceedings{rajbhandari2021zero,
  title={Zero-infinity: Breaking the gpu memory wall for extreme scale deep learning},
  author={Rajbhandari, Samyam and Ruwase, Olatunji and Rasley, Jeff and Smith, Shaden and He, Yuxiong},
  booktitle={Proceedings of the international conference for high performance computing, networking, storage and analysis},
  pages={1--14},
  year={2021}
}
```

## Auto Parallelism

```
@inproceedings{zheng2022alpa,
  title={Alpa: Automating inter-and $\{$Intra-Operator$\}$ parallelism for distributed deep learning},
  author={Zheng, Lianmin and Li, Zhuohan and Zhang, Hao and Zhuang, Yonghao and Chen, Zhifeng and Huang, Yanping and Wang, Yida and Xu, Yuanzhong and Zhuo, Danyang and Xing, Eric P and others},
  booktitle={16th USENIX Symposium on Operating Systems Design and Implementation (OSDI 22)},
  pages={559--578},
  year={2022}
}

@article{miao2022galvatron,
  title={Galvatron: Efficient Transformer Training over Multiple GPUs Using Automatic Parallelism},
  author={Miao, Xupeng and Wang, Yujie and Jiang, Youhe and Shi, Chunan and Nie, Xiaonan and Zhang, Hailin and Cui, Bin},
  journal={Proceedings of the VLDB Endowment},
  volume={16},
  number={3},
  pages={470--479},
  year={2022},
  publisher={VLDB Endowment}
}
```

## Robust Training

```
@inproceedings{jang2023oobleck,
  title={Oobleck: Resilient distributed training of large models using pipeline templates},
  author={Jang, Insu and Yang, Zhenning and Zhang, Zhen and Jin, Xin and Chowdhury, Mosharaf},
  booktitle={Proceedings of the 29th Symposium on Operating Systems Principles},
  pages={382--395},
  year={2023}
}

@inproceedings{jiang2024megascale,
  title={$\{$MegaScale$\}$: Scaling large language model training to more than 10,000 $\{$GPUs$\}$},
  author={Jiang, Ziheng and Lin, Haibin and Zhong, Yinmin and Huang, Qi and Chen, Yangrui and Zhang, Zhi and Peng, Yanghua and Li, Xiang and Xie, Cong and Nong, Shibiao and others},
  booktitle={21st USENIX Symposium on Networked Systems Design and Implementation (NSDI 24)},
  pages={745--760},
  year={2024}
}
```

## LLM Inference - Weight and Activation Compression

```
@article{lin2024awq,
  title={AWQ: Activation-aware Weight Quantization for On-Device LLM Compression and Acceleration},
  author={Lin, Ji and Tang, Jiaming and Tang, Haotian and Yang, Shang and Chen, Wei-Ming and Wang, Wei-Chen and Xiao, Guangxuan and Dang, Xingyu and Gan, Chuang and Han, Song},
  journal={Proceedings of Machine Learning and Systems},
  volume={6},
  pages={87--100},
  year={2024}
}

@inproceedings{liu2023deja,
  title={Deja vu: Contextual sparsity for efficient llms at inference time},
  author={Liu, Zichang and Wang, Jue and Dao, Tri and Zhou, Tianyi and Yuan, Binhang and Song, Zhao and Shrivastava, Anshumali and Zhang, Ce and Tian, Yuandong and Re, Christopher and others},
  booktitle={International Conference on Machine Learning},
  pages={22137--22176},
  year={2023},
  organization={PMLR}
}
```

## LLM Inference KV Cache Compression

```
@article{zhang2024h2o,
  title={H2o: Heavy-hitter oracle for efficient generative inference of large language models},
  author={Zhang, Zhenyu and Sheng, Ying and Zhou, Tianyi and Chen, Tianlong and Zheng, Lianmin and Cai, Ruisi and Song, Zhao and Tian, Yuandong and R{\'e}, Christopher and Barrett, Clark and others},
  journal={Advances in Neural Information Processing Systems},
  volume={36},
  year={2024}
}

@article{xiao2023efficient,
  title={Efficient streaming language models with attention sinks},
  author={Xiao, Guangxuan and Tian, Yuandong and Chen, Beidi and Han, Song and Lewis, Mike},
  journal={arXiv preprint arXiv:2309.17453},
  year={2023}
}
```

## LLM Speculative and Parallel Decoding

```
@inproceedings{miao2024specinfer,
  title={Specinfer: Accelerating large language model serving with tree-based speculative inference and verification},
  author={Miao, Xupeng and Oliaro, Gabriele and Zhang, Zhihao and Cheng, Xinhao and Wang, Zeyu and Zhang, Zhengxin and Wong, Rae Ying Yee and Zhu, Alan and Yang, Lijie and Shi, Xiaoxiang and others},
  booktitle={Proceedings of the 29th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 3},
  pages={932--949},
  year={2024}
}

@inproceedings{caimedusa,
  title={Medusa: Simple LLM Inference Acceleration Framework with Multiple Decoding Heads},
  author={Cai, Tianle and Li, Yuhong and Geng, Zhengyang and Peng, Hongwu and Lee, Jason D and Chen, Deming and Dao, Tri},
  booktitle={Forty-first International Conference on Machine Learning}
}
```

## Offloading Inference System

```
@inproceedings{sheng2023flexgen,
  title={Flexgen: High-throughput generative inference of large language models with a single gpu},
  author={Sheng, Ying and Zheng, Lianmin and Yuan, Binhang and Li, Zhuohan and Ryabinin, Max and Chen, Beidi and Liang, Percy and R{\'e}, Christopher and Stoica, Ion and Zhang, Ce},
  booktitle={International Conference on Machine Learning},
  pages={31094--31116},
  year={2023},
  organization={PMLR}
}
```

## Disaggregate Generative Inference

```
@inproceedings{zhong2024distserve,
  title={$\{$DistServe$\}$: Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving},
  author={Zhong, Yinmin and Liu, Shengyu and Chen, Junda and Hu, Jianbo and Zhu, Yibo and Liu, Xuanzhe and Jin, Xin and Zhang, Hao},
  booktitle={18th USENIX Symposium on Operating Systems Design and Implementation (OSDI 24)},
  pages={193--210},
  year={2024}
}

@inproceedings{patel2024splitwise,
  title={Splitwise: Efficient generative llm inference using phase splitting},
  author={Patel, Pratyush and Choukse, Esha and Zhang, Chaojie and Shah, Aashaka and Goiri, {\'I}{\~n}igo and Maleki, Saeed and Bianchini, Ricardo},
  booktitle={2024 ACM/IEEE 51st Annual International Symposium on Computer Architecture (ISCA)},
  pages={118--132},
  year={2024},
  organization={IEEE}
}
```
