# Optimprj

MVC is used. One could argue over whether a client or server side MVC would be more feasible to use. Then you could make the server a RESTful one.  
Layered is used. It is used, and it makes good sense. It is tied to security.
Client/Server makes good sense to use in this distributed system and is also chosen by the group. It is tied to authentication and authorization as non-functional requirements.
Pipe and filter is not used, and probably shouldn’t be. You could use the it for the authentication. Non-functional requirements could be security concerns.
Repository pattern could be used. The need for different clients from non-functional requirements, gives good reason for this pattern.
