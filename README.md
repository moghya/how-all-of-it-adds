# how-all-of-it-adds

# What all happened when you visited this page.

We'll try to cover state of processor, memory, data-packet at each stage during entire process of sending request and receiving response.

 - Fired up a Computer
	 - 
	 - Booted an Operating System
	 
 - Opened a Web Browser
	 - 
	 - A process is created for Web Browser
	
 - You Requested a Resource
	 - 
	 - As per your your request - an Application Layer Packet is created
	 - From Application layer Packet is propagated down-to physical layer
	 
 
 - Journey of the Request Packet 
(Actions on packet by Intermediate nodes)
	 - 
	 - Network Layer to Data Link Layer
	 - Data Link Layer to Physical Layer
	 - We might have to loop on some of above steps.
	 
 - Packet is received at Destination Host (Computer that serves the resource)
	 - 
	 - Packet is at Physical layer so it is propagated up-to the Application layer to be handled
	 - Packet is parsed and understood (exact request is understood)
	 - As per request and specifics sent, response is generated. an Application Layer Packet is created
	 - From Application layer Packet is propagated down-to physical layer
	 
- Journey of Response Packet   
(actions on packet by Intermediate nodes)
	- 
	- Network Layer to Data Link Layer
	- Data Link Layer to Physical Layer
	- We might have to loop on some of above steps.
	
- Packet is received at Source Host (Your Computer)
	- 
	- Packet is at Physical layer so it is propagated up-to the Application layer to be handled
	 - Packet is parsed and understood.
	 - HTML in packet is rendered, resources linked to HTML are requested (img-tag we add in html etc)
	 
 - Rendering of HTML
	 - 
	 - parsing and rendering

