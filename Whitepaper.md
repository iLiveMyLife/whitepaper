# whitepaper

Let's call as **'item'** a variable representing some information. For simplicity we are going to talk about the textual information down the road unless specified overwised. But context of the information is mostly irrelevant. 

As you can see, the variable **item** is defined as a bold item by wrapping the information into markdown ** 'language'.

Let's now introduce another information wrapper on top of the variable **item**, called {{item}}.

This informational operation is what we are going to discuss in this whitepaper. 

To just right to the end of the discussion I am going to specify some properties of the {{..}} operation:

* it is a operation of create an variable which has a link to the variable {{parent}}, in the case of this document it is {{whitepaper.md}}
* it is a reference to another variable {{item}}
* it is a data holder which stores all the history of changes for the variable **item**, lets say it represents a blockchain
* it is a program running by the name of 'item' and handling all the information change happening down the road with variable 'item' and all of variables who knows about the existence of 'item'
