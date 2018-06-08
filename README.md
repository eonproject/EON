# EON
EON MainNode, providing API interface to access the node's functionality.

# Brief Intrudction to EON 
EON is an intelligent high-speed blockchain operating system. Flexible and intelligent allocation of the entire network computing power 
instantly synchronizes node load and cloud network and enables the average TPS of the entire network to reach over 100,000. Thus all 
network requests will be completed at the same time, which solves the problem of a mere 4000 TPS caused by numerous network requests 
generated in a single EOS transaction . As the number of nodes increases in the future, our TPS will eventually reach more than 1 million. 
TPS is the foundation for determining all other functions and ideas of a public chain like EOS.

# Repository Structure
Folder structure

		root
	 	|
		+ application    // main application's source to build the main node on various platforms
		|
		+ api            // programatically manipulating the EON blockchain node.
		|
		+ documentation  // documentation for new comers to understand the source code hirearchy and the interface design philosophy
		|
		+ tools          // tools for people use main functionality of the EON blockchain, like wallet, smart contract IDE, etc.
		|
		+ samples        // sample code for smart contracts and apis
