# Datasets

For this project, we use the [OTIDS dataset](https://ocslab.hksecurity.net/Dataset/CAN-intrusion-dataset) published by researchers at the Hacking Countermeasure Lab at Korea University to test the performance of different RNN and CNN architectures for anomaly detection.

This dataset consists of several real CAN bus messages captured on a KIA Soul(it's a car).  The messages were captured by logging CAN traffic via the OBD-II port from a real vehicle while message injection attacks were being performed.

The researchers apply a domain specific metric that measures known properties about can messages to detect intrusions/anomalies in a CAN network.

Quoting their approach: 
> If a remote frame having a particular identifier is transmitted, a receiver node should respond to the remote frame immediately. Thus, each node has a fixed response offset ratio and the time interval in a normal state while these values vary in attack state. Using this property, we can measure the response performance of the existing nodes based on the offset ratio and time interval between request and response messages. As a result, our methodology can detect intrusions by monitoring the offset ratio and time interval, and it allows quick intrusion detection with high accuracy.

We instead design and apply a couple of simple RNN based and CNN based deep neural networks for this pupose. This may allow the network to adapt to different types of CANs, extend its learning and outlier detectoin properies to different types of messages and be able to handle newer attacks by generalizing network behavior.

Since we are working with embedded systems, we choose to optimize our neural networks to make them light enough to run on the scarce memory and compute power available in microcontrollers.

Here we post the datasets, and a cleaned, standardized version of the datasets. We will also prepare a notebook to explore the data to understand it better.


