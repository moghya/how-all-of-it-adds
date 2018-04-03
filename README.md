# What all happened when you visited this page.

We'll try to cover state of processor, memory, data-packet at each stage during entire process of sending request and receiving response.

 - Fired up a Computer
	 - 
	 - [Booted an Operating System](booting-operating-system.md)
	 
 - Opened a Web Browser
	 - 
	 - [A process is created for Web Browser](process-creation-of-web-browser.md)
	
 - You Requested a Resource
	 - 
	 - [As per your your request - an Application Layer Packet is created](application-layer-packet-creation.md)
	 - [From Application layer Packet is propagated down-to physical layer](packet-from-application-to-physical-layer.md)
	 
 
 - Journey of the Request Packet 
(Actions on packet by Intermediate nodes)
	 - 
	 - Network Layer to Data Link Layer
	 - Data Link Layer to Physical Layer
	 - We might have to loop on some of above steps.
	 
 - Packet is received at Destination Host (Computer that serves the resource)
	 - 
	 - [Packet is at Physical layer so it is propagated up-to the Application layer to be handled](packet-from-physical-to-application-layer.md)
	 - [Packet is parsed and understood (exact request is understood)](at-server-site-parsing-of-packet-at-application-layer.md)
	 - [As per request and specifics sent by you, response is generated. An Application Layer Packet is created](response-generation-and-packet-creation.md)
	 - [From Application layer Packet is propagated down-to physical layer](packet-from-application-to-physical-layer.md)
	 
- Journey of Response Packet   
(actions on packet by Intermediate nodes)
	- 
	- Network Layer to Data Link Layer
	- Data Link Layer to Physical Layer
	- We might have to loop on some of above steps.
	
- Packet is received at Source Host (Your Computer)
	- 
	- [Packet is at Physical layer so it is propagated up-to the Application layer to be handled](packet-from-physical-to-application-layer.md)
	 - [Packet is parsed and understood(exact response is understood)](at-client-site-parsing-of-packet-at-application-layer.md).
	 - [Content in packet is rendered, resources linked to Content are requested (e.g img-tag we link in html etc)](conten-rendering.md)
	 
 - Rendering of HTML
	 - 
	 -[parsing and rendering](html-rendering.md)

