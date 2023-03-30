# Manual CHORDS data manipulation   

One of the easiest ways to get data is to use the in-browser plugin
called RestMan (or similar other tools).

It essentially simulates making calls to the server and provides
a well formatted output of the response from the server
so you can inspect it more closely.

It is beyond the scope of this tutorial how HTTP works and
how APIs are created, but the fundamentals are represented
in the image below:


The _client_ makes a **request** to the _server_ and if the request
is understood, the server sends back a **response** to the client.

It's that simple (but a lot of things go on under the hood to make it 
all happen in milliseconds over large geographic distances).  It isn't
magic (though it might seem that way), but it is indeed very complex and many
layers are involved to make it all work!

We will quickly follow the steps below to demonstrate the use of RestMan:

1. connect to your CHORDS account
2. open RestMan 
3. run http API call in RestMan to **get data**
4. review data