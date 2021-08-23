# whitepaper

## Abstract

People more and more realize that email is not a good tool for collaboration and move away to chats like Slack, Discord or even Telegram for managing projects or even companies.  
But those are not ideal either. Yes, some tools have a basic ability to devide communication into different topics but at the end chats become overloaded with messages and useful knowledge is lost in history.

With our solution we want to suggest a more flexible communication model where communication happens at the same time as building documentation into knowledge graph.

## Background

Despite the fact that email remains a popular tool for productive communication, many consider it to be outdated technology, insufficient to use when collaborating among team members. However, moving to the popular chat platforms such as Slack, Discord or even Telegram, also proves to be a poor strategy with regards to the tools lacking some essential productivity and information organizational features. Those tools try to separate chats into different topics but in the end channels/rooms become overloaded with messages while useful information becomes lost in noise without a practical way to resurface it. iLiveMyLife helps team members organize information in a variety of self documenting approaches. The main approach is conducted via promotion of the information hierarchy suggested to participants when they start and plan out the project at the high level. In addition, machine learning algorithms help promote and audit informational hierarchies as the project evolves, while suggesting to the participants when their structures can be optimized.

-------
Here you need to give some background to that will explain the key problem with the currently existing solutions. For instance, applications are utilizing Kafka as a message brokery system, however it's interface is... and there are many other different solutions which are doing the same, but it's not enough, hence you decided to build something siginificantly better.

## Solution

What are you doing? How are you doing it? And etc...

## Why do you think you are better than others?


## Competitve analysis or Related work

Who are competing applications? What are they doing different? Why are you better?



The text below you wrote, I do not understand how is it related to the messaging or MQ service and all discussion we had about Kafka?

---------------

Let's call as **'item'** a variable representing some information. For simplicity we are going to talk about the textual information down the road unless specified overwised. But context of the information is mostly irrelevant. 

As you can see, the variable **item** is defined as a bold item by wrapping the information into markdown ** 'language'.

Let's now introduce another information wrapper on top of the variable **item**, called {{item}}.

This informational operation is what we are going to discuss in this whitepaper. 

To just right to the end of the discussion I am going to specify some properties of the {{..}} operation:

* it is a operation of create an variable which has a link to the variable {{parent}}, in the case of this document it is {{whitepaper.md}}
* it is a reference to another variable {{item}}
* it is a data holder which stores all the history of changes for the variable **item**, lets say it represents a blockchain
* it is a program running by the name of 'item' and handling all the information change happening down the road with variable 'item' and all of variables who knows about the existence of 'item'
