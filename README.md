Download Link: https://assignmentchef.com/product/solved-csci2275-assignment-5-buffered-communication-between-towers
<br>
In the Lord of the Rings trilogy, there is a scene where the first beacon is lit in the towers of Minas Tirith. The second beacon then sees the fire, and knows to light its fire to send a signal to the third beacon, and so forth. This was a means of communicating in the days before telegraphs were invented as it was much faster than sending a human rider to deliver a message. Communication towers were equipped with signaling mechanisms, such as mirrors, that could spell out messages using the positions of the mirrors.

In many current communications networks, data buffers are used to temporarily store data as it is read in from an input device before being transferred to an output device. For example, videos downloaded from the Internet can be buffered before they are displayed onscreen to improve the quality of the picture you see. Buffers are implemented by storing the incoming data in a First In First Out queue to maintain the integrity of the order in which the data was received. We discussed queues in lecture and looked at a few examples of how to implement one using an array or a linked list.

<strong>Build your own (buffered) communications network</strong>

I n this assignment, you’re going to build on the cities network you implemented in Assignment 4 by adding a queue to serve as an input buffer for the message being read in. You will read data in from a text file and store it in a queue, and then transmit it through the network of cities and back again. You will use a circular array queue for temporary storage, and then send the queue when the user selects “Dequeue” or “Send Entire Message” from the menu. In this assignment, you don’t need to implement the add city and remove city features, but if they already exist in your code, you will not be marked down for having them.

<strong>Include the following cities in your network:</strong>

Los Angeles

Phoenix Denver Dallas

St. Louis Chicago Atlanta Washington, D.C.

New York

Boston