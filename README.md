# **The Open Systems Interconnection Model (OSI Model)**
#### **Blake Miller**
#### **10 December 2021**

## **Introduction**

>The Open Systems Interconnection Model (OSI Model) is a representation of the networking framework that serves to direct the protocols that make up the internet.
 The OSI Model consists of 7 layers which depict the processes taking place when a user interacts with a machine (computer), and then the result of that interaction. 
 The OSI Model helps us understand how the machines work, their capabilities and limitations, and furthermore, the machines potential. 

>This tutorial was made with the intent of providing a brief and enjoyable way to learn about the OSI Model! This tutorial was made for people of any and all ages.
 An interest to learn will be largely helpful. :wink:

## **History**

A brief history of the OSI Model can be found by clicking [here.](https://youtu.be/uPIZs6k6DRo) (00:00 - 03:27)

Pretty interesting stuff right? 🌞


## **Layers**

>As mentioned previously, the OSI Model is made up of layers.
  
>>In order from top to bottom, here is a list of the 7 layers that make up the OSI Model:  
  > 1. Physical Layer (bottom layer)
  > 2. Data Link Layer
  > 3. Network Layer
  > 4. Transport Layer
  > 5. Session Layer
  > 6. Presentation Layer
  > 7. Application Layer (top layer)
  

![OSI Model](https://miro.medium.com/max/700/1*17Zz6v0HWIzgiOzQYmO6lA.jpeg)

### **The Physical Layer**

The Physical layer is responsible for transmitting data bits using electrical pulses and signals. That is, taking the data and breaking it down into its rawest form
so that it may be transported. 
I like to explain the physical layer through familiraztion with the components that it includes.
Several components used in networking like ethernet cables, network interface cards (NICs), and hubs, are all components of the physical layer.

When the physical layer is on the receiving end of a data package, it does all of this in reverse, it receives the package and then puts it into a format
that is compatible with viewing on the user's display. 

### **The Data Link Layer**

The Data Link Layer can be thought of as the big brother of the physical layer. First, this layer manages physical addressing schemes to include MAC addresses.
Access controller is a helpful way of conceptualizing this layer. While it serves its own purpose, the data link layer also filters and checks the data packages
prepared by the physical layer (little brother). In the event of an error in the data package, the data link layer will correct or reroute the package.

### **The Network Layer**

After data has passed through the  data link layer and makes it to the third layer of the OSI Model, the network layer, data is double checked for proper addressing. 
Imagine a worker at the post office examining a letter and confirming the sending and recieving address before the post is put into a truck for shipping/delivery. 
This is much like what is going on in the network layer. The network layer's goal is to prepare the data into packets for the transport layer. 

An interesting feature of the network layer is that it is what we often refer to as, connectionless. What this means when you hear it in regard to the network layer
is that data is sent from the sender to recipient without any prior connection, handshake, or acknowledgement. The network layer also performs as a phone book of sorts
in that it has the capability to store and maintain addresses in a cache. 

### **The Transport Layer**

Once a data packet reaches the transport layer it is fully prepped and ready for delivery. The transport layer is the layer where the data packet begins its journey 
through the network to reach its destination. There are several protocols that exist to support data transmissions. A few of them, such as Transmission Control Protocol (TCP)
were developed decades ago, and have been used frequently since. A protocol is a set of rules governing the exchange or transmission of data between devices. 

The transport layer works more efficiently when working in a connection-oriented communication, unlike the connectionless capabilities we see in the network layer. This
is not to say that the tranpsort layer is incapable, rather, a strong connection is preferred. TCP is connection-oriented. 

### **The Session Layer**

The fifth layer, the session layer, is the means for creating and maintaining simple and complex connections over networks. The session layer facilitates a connection, or ***"SESSION"*** between two or several parties. The session layer can be confusing so as always, it's helpful for us to relate it to something we have a better understanding of. I like to think of the session layer as an event coordinator. 

Imagine you are planning a major event such as a wedding, ball, auction, party...literally any big event. To plan evertyhing for yourself could be extremely time consuming and challenging. An even coordinator will take care of tasks such as contacting and making a reservation (session) with other parties who are needed to execute the event. The session layer is doing precisely this when you are sending or receiving data from across the network.  

### **The Presentation Layer**

The presentation layer, also known as the syntax layer, is the second to last layer of the OSI model. At this point the data has gone through five layers and is at the doorstep, ready for delivery. Before the data package can moved forward, it must be converted into a standard that is compatible with the intended display method. It is at the presentation layer that this takes place. 

### **The Application Layer**

The application layer is the last layer of the OSI Model and is responsible for specifying the shared communications protocols and interface methods used by hosts in a communications network. To help understand the application layer I like to think of our event coordinator example. Much like the network layer, the application layer has to ensure flawless communication so that data transmissions can continue working properly. The key differences are that instead of trying and hoping for results, the application layer demands or dictates the protocols to be used in the data transmission. 

---------------------------------

References: Information obtained for this tutorial can be found at the following websites:
>* https://www.lifewire.com/layers-of-the-osi-model-illustrated-818017
>* https://en.wikipedia.org/wiki/OSI_model
