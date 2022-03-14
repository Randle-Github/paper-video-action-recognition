# paper-video-action-recognition

This is the repository of Randle's paper in video action recognition.

In this repository, following the advice of my mentor, I create this repository to record what I read and give a general description about this area. I mainly divide this area into *general video understanding* and *interaction*(human-object detection, compositional action recognition).

```latex
root/
	|--general video understanding/
		|--2d-cnn-based/
			|--2016 Temporal Segment Networks: Towards Good Practices for Deep Action Recognition
			|--2019 Collaborative Spatiotemporal Feature Learning for Video Action Recognition
			|--2019 TSM: Temporal Shift Module for Efficient Video Understanding
		|--3d-cnn-based/
			|--2015 (C3D)Learning Spatiotemporal Features With 3D Convolutional Networks
			|--2016 Two-Stream Convolutional Networks for Action Recognition in Videos
			|--2017 (I3D)Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset
			|--2019 SlowFast Networks for Video Recognition
		|--gnn-based/
			|--2018 Videos as Space-Time Region Graphs
			|--2021 Spatially Conditioned Graphs for Detecting Human–Object Interactions
		|--transformer-based/
			|--2019 Video Action Transformer Network
			|--2021 Is Space-Time Attention All You Need for Video Understanding?
			|--2021 Video Transformer Network
			|--2021 ViViT: A Video Vision Transformer
	|--interaction/
		|--2017 The “something something” video database for learning and evaluating visual common sense
		|--2018 Detecting and Recognizing Human-Object Interactions
		|--2018 Non-local Neural Networks
		|--2018 iCAN: Instance-Centric Attention Network for Human-Object Interaction Detection
		|--2019 Long-Term Feature Banks for Detailed Video Understanding
		|--2019 Transferable Interactiveness Knowledge for Human-Object Interaction Detection
		|--2020 Understanding Human Hands in Contact at Internet Scale
		|--2020 Something-Else: Compositional Action Recognition with Spatial-Temporal Interaction Networks
		|--2021 Hand-Object Interaction Reasoning
		|--2021 Revisiting spatio-temporal layouts for compositional action recognition
		
```

# general video understanding

### 2d-cnn-based

#### 2016 Temporal Segment Networks: Towards Good Practices for Deep Action Recognition

<img src="README.assets/1-16472660334671.png" alt="1" style="zoom:60%;" />

​	The main idea is to divide a video into $K$ segments, and extract $1$ of each and make fusion of the logits. In this model, the TSN model ultilize both spatial and temporal feature of frames.

​	The result: UCF101(94.2%), HMDB51($69.4\%$) 

#### 2019 Collaborative Spatiotemporal Feature Learning for Video Action Recognition

<img src="README.assets/3.png" alt="3" style="zoom:67%;" />

​	The result:  Moments in Time($32.4\%$), Kinetics($77.5\%$)

#### 2019 TSM: Temporal Shift Module for Efficient Video Understanding



### 3d-cnn-based



#### 2015 (C3D)Learning Spatiotemporal Features With 3D Convolutional Networks



#### 2016 Two-Stream Convolutional Networks for Action Recognition in Videos



#### 2017 (I3D)Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset



#### 2019 SlowFast Networks for Video Recognition



### gnn-based

#### 2018 Videos as Space-Time Region Graphs



#### 2021 Spatially Conditioned Graphs for Detecting Human–Object Interactions



### transformer-based

#### 2019 Video Action Transformer Network



#### 2021 Is Space-Time Attention All You Need for Video Understanding?



#### 2021 Video Transformer Network



#### 2021 ViViT: A Video Vision Transformer



## interaction

#### 2017 The “something something” video database for learning and evaluating visual common sense

#### 2018 Detecting and Recognizing Human-Object Interactions

#### 2018 Non-local Neural Networks



#### 2018 iCAN: Instance-Centric Attention Network for Human-Object Interaction Detection
​		

#### 2019 Long-Term Feature Banks for Detailed Video Understanding

#### 2019 Transferable Interactiveness Knowledge for Human-Object Interaction Detection
		#### 2020 Understanding Human Hands in Contact at Internet Scale

#### 2020 Something-Else: Compositional Action Recognition with Spatial-Temporal Interaction Networks

#### 2021 Hand-Object Interaction Reasoning

#### 2021 Revisiting spatio-temporal layouts for compositional action recognition

