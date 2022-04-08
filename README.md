# CBIR-GAN
**CBIR-GAN: A Triplet Generative Adversarial Network for Content-based Image Retrieval**

**Image embedding algorithm in SnapMod project : https://www.snapmode.ir/**

**Unfortunately, due to the commercial nature of the product, I can not share its code. Please Find the paper at this URL: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4057354** 

# Abstract 

Content-based image retrieval systems have become popular in various fields such as computer vision and artificial intelligence. Deep neural networks, especially CNNs, have frequently been employed in visual representations; however, they require large amounts of labeled data, which are hard, costly, and sometimes impossible to obtain. Moreover, since these methods rely only on semantically discriminative representations, they fail to yield significant outputs in instance-level image retrieval systems. Therefore, this paper proposes a triplet generative adversarial network (GAN) based on the idea of integrating deep metric learning methods with GANs to benefit from the advantages of both at the same time. In this model, three generator networks that use a triplet loss function are responsible for learning a similarity measure over objects and embedding images in an appropriate vector space. In these networks, a CNN-based perceptual loss function is also employed to force the generators to adhere a certain type of structural features in intermediate layers. Since only triplets must be used as network inputs in the proposed method, the learning process is performed in a semi-supervised way. According to the results of comprehensive experiments conducted on four datasets in comparison with several state-of-the-art methods, the proposed method was efficient in terms of precision and computational complexity. For the real-life implementation of the proposed method, a distributed large-scale fashion image retrieval platform, called SnapMode1, has been developed through big data tools such as Apache Storm, Kafka, Solr, and Milvus. 

**The schematic view of the CBIR-GAN**
![image](https://user-images.githubusercontent.com/41056415/162425967-c0c17ba2-697e-4ff9-bc49-14cc19757e41.png)

**Evaluation Results of Baseline methods on Different Datasets**
![image](https://user-images.githubusercontent.com/41056415/162426886-7d066692-5482-4af4-afa6-4fa65c2e9e46.png)

![image](https://user-images.githubusercontent.com/41056415/162427283-158b4d2e-e617-4b3e-b350-6b1f7c57b916.png)

![image](https://user-images.githubusercontent.com/41056415/162427311-aaab17ca-0ac5-4f0d-9ad4-94575fabbc41.png)

**Generator and Discriminator Networks**

![image](https://user-images.githubusercontent.com/41056415/162426007-c2e0ed81-b386-4a5a-ba6e-a9bd635df9ab.png)

**Comparing the Efficiency of the Proposed Model in Image Generation Task**
![image](https://user-images.githubusercontent.com/41056415/162426063-bb4a4209-f068-4bed-8141-46616864dae5.png)

**Qualitative Results Comparing Our Proposed Model VS Other State-Of-The-Art CNN Models on Deepfashion2**
![image](https://user-images.githubusercontent.com/41056415/162426123-6f3d375a-7a56-4905-8421-20ae8dbdab49.png)

**Examples of Images retrieved by Proposed Model from Eight Iranian Fashion Website**

![image](https://user-images.githubusercontent.com/41056415/162426162-13629d67-b0b6-49e3-969b-99463cd7af0d.png)

