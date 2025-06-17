# Computer-Organization---final-project
	(Q1) GEM5 + NVMAIN BUILD-UP (40%)     
	(Q2) Enable L3 last level cache in GEM5 + NVMAIN (15%) ( 看到 log 裡面有 L3 cache 的資訊 )
	(Q3) Config last level cache to  2-way and full-way associative cache and test performance (15%)
	(Q4) Modify last level cache policy based on frequency based replacement policy (15%)
	(Q5) Test the performance of write back and write through policy based on 4-way associative cache with isscc_pcm(15%)

# Files -

	benchmark -> provided code
	gem5-525ce650e1a5bbe71c39d4b15598d6c003cc9f9e -> gem5, benchmark code already inside the file
 	NVmain
  	Q1(build environment).txt -> how the environment was built 
   	Q2(helloWorld).txt -> how the environment is modified and how to run the code
	Q3(twoOrFull)
 	- 2-way.log -> contains how to start the code and the result of it in 2-way associativity
  	- full-way.log -> contains how to start the code and the result of it in full-way associativity
   	- statsComparison -> shows the difference in stats.txt in two ways (left -> 2-way, right -> full-way)
	Q4(LRUorLFU)
 	- frequencyBasedPolicy.log -> shows the result of the code running in LFU(Least Frequently Used) replacement policy
  	- originalPolicy.log -> shows the result of the code running in LRU(Least Recently Used) replacement policy
   	- Q4.txt -> contains what's modified and how to run the code
	- statsComparison -> shows the difference in stats.txt in two ways (left -> LRU, right -> LFU)
 	Q5(writeBackOrWriteThrough)
  	- Q5.txt -> contains what's modified and how to run the code
   	- statsComparison.txt -> shows the difference in stats.txt in two ways (left -> Write-Back, right -> Write-Through)
	- writeBack.log -> shows the result of the code running in write-back strategy
 	- writeThrough.log -> shows the result of the code running in write-through strategy
