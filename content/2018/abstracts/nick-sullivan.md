The encrypted web is built on top of a few fundamental protocols: HTTP, TLS, and DNS. These protocols were written with some assumptions about the architecture of the internet in mind, like the idea that different IP addresses correspond to physical and separate machines. However, some of these assumptions are changing, and quickly. The popularity of technologies like IP anycasting, layer 4 load balancing, and the consolidation of massive portions of the web behind a small set of reverse proxy services mean that the architecture of the web today is very different than what is taught in computer networking classes. In this talk, we will examine some of the impacts of these changes and how internet standards such as HTTP/2 are being adapted to take advantage of the new architecture. We will also debate the tradeoffs between the complexity added by these changes and the privacy and latency benefits they provide to users of the web.