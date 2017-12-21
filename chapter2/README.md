# A Typical Web Application

In order to help give a bit of context to the chapters to follow we will start by attempting to define what a typical web application might look like. In some respects this is a difficult task. There are a plethora of applications out their on the web. Any given website or tool is likely to have a different kind of architecture implemented using a different set of technologies. Its probably not too controversial however to say that a typical web app will likely consist of three broad components: The client-side, the server-side and the database.

### The server-side

It seems appropriate to start with the server-side (sometimes called the backend) since this is usually the first part of a web application involved in handling a request from a user.

The term "server-side" refers to software that is run on a computer or computers that are remote from the client. The computers may be owned and managed by the organisation behind whatever website or tool is being used but increasingly these days its likely the hardware itself will be managed by a Cloud provider and a particular organisation will focus more on the code that provides whatever service they offer. We'll talk more about the Cloud in [Chapter 12](../chapter12/README.md).

When you type `http://www.google.com` into a web browser like Chrome or Firefox (or Internet Explorer, I suppose) it is one of Google's server-side applications that responds to you. We'll go into more detail as to what's involved in this request in [Chapter 5](../chapter5/README.md)
