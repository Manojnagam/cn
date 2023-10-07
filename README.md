# STATIC ROUTING DEMO
Our Mini-Project involves the demo of static routing. We have designed a demo that
gives us all the details regarding path travelled from source to destination routers.
User can give his source router and his destination router. Along with that user can
also provide intermediate routers according to his choice.

Here are few assumptions which are made.
1. We are assuming that the network is having 4 routers which are connected
with each other in a ring topology manner.
2. The above network is fixed.
3. IP address of the nodes that are connected to the router will not change in the
future.

Firstly, the number of networks that are connected to each router in the ring topology
manner are taken.
Secondly, IP addresses of all the networks are taken as input. Validation of each IP
addresses provided is done by the program.

Now, the program automatically detects for the intermediate routers and asks to
provide the details if any. Finally, after collecting all the necessary details it will
display all the information regarding source router, destination router, intermediate
routers, static route followed and success state of the process.

The complete program used for the static routing demo is developed in C language.
