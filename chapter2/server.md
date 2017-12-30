## The server-side

It seems appropriate to start with the server-side (sometimes called the ***backend***) since this is broadly the first part of a web application involved in handling a request from a user.

The term "server-side" refers to software that is run on a computer or computers that are remote from the client. The computers may be owned and managed by the organisation behind whatever website or tool is being used but increasingly these days its likely the hardware itself will be managed by a Cloud provider and a particular organisation will focus more on the code that provides whatever service they offer. We'll talk more about the Cloud in [Chapter 12](../chapter12/README.md).

Whether a company owns its own servers (like Google) or whether its using a Cloud provider the point is it is a different computer to the one you are using that is responsible for providing the Google home page. The details of how the hardware is set up will vary depending on the website being accessed and is a little outside of the scope of this book. Examples range from a single computer, just like yours, set up in someone's bedroom to a server-farm with potentially thousands of purpose-built machines ready to serve the world's largest websites (think the Facebooks and Googles of the world.)

#### Serving websites to your browser

When you type `http://www.google.com` into a web browser like Chrome it is one of Google's server-side applications that responds to you. We'll go into more detail as to what's involved in this request in [Chapter 5](../chapter5/README.md). Even in complex web applications a given request can be traced to one individual computer which is ultimately responsible for responding in some manner and that computer could be called a ***server***.

Typically this server will actually be responsible for delivering any client-side code to the user's browser. It or another server will then handle any subsequent requests from the client that may be generated for example by a user clicking on a link.

#### Serving anything to anything

The example of a server being effectively the thing that responds to your browser when you request a website is a useful one because that situation is something we have all experienced (at least I assume if you have gotten as far as reading The Web Developer's Handbook you've used the internet before.) The term server however is, properly speaking, more generic than that.

It really denotes any computer that responds in some way to a request from any other computer. For example, in order to fulfil a request from a client, say your browser, a server may need to retrieve some information from a database. To illustrate this consider signing into Facebook and being presented with a stream of your friends' latest activities. Your browser requests the Facebook application from one of their servers and in order to respond it has retrieved your activity feed from a database. As far as you or your browser are concerned both the server and the database may be considered as two parts of the wider Facebook ***server-side*** or ***backend***. But if we look just at the interaction between the server computer and the database we could correctly define the database as the ***server*** and the server computer as the ***client***.

We will say more about the [database](chapter2/database.md) later in this chapter.
