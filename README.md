Process-Injector in c#
programmer : Mr Black Zero

telegram me : @Mr_BlackZero
--------
Description:
-------
step 1=>generate shellcode with msfvenom

![1](https://user-images.githubusercontent.com/63192240/127989732-c5b22ed8-1b32-4bfe-85d5-8341e6c5d6bd.PNG)

your ip in LHOST= Example(192.168.1.1) 


![2](https://user-images.githubusercontent.com/63192240/127990056-c250323f-124b-479d-be41-dfe06bba925b.PNG)
--> copy shellcode (Proposal copy shellcode in txt file)


![3](https://user-images.githubusercontent.com/63192240/127990145-9ad26a6d-88fc-4d2f-a789-be3a74c8fade.PNG)

--> sudo msfconsole -q


![4](https://user-images.githubusercontent.com/63192240/127990526-a099d19b-c613-405f-8a07-28abec3c5315.PNG)

-->Enter your ip(ip payload Example(192.168.1.1))


![5](https://user-images.githubusercontent.com/63192240/127991114-b878394a-be7f-4320-80bb-b1429cd0c92e.PNG)

->your ip in lport= Example(443)-> lport payload 


![6](https://user-images.githubusercontent.com/63192240/127991463-2b9edbee-0064-4cd1-92c3-5ed34d99b2f3.PNG)

-> set payload


![7](https://user-images.githubusercontent.com/63192240/127991537-e1711d5c-9296-44b7-87e6-984c91c3f455.PNG)


![8](https://user-images.githubusercontent.com/63192240/127991558-7ab878ce-bdb3-445d-9734-e01d6b1002bf.PNG)
-----------------------
step2 => configuration Visual Studio

![3](https://user-images.githubusercontent.com/63192240/127992114-18a0dc0e-5ed8-4b86-a3c6-af84ccdba093.PNG)

![4](https://user-images.githubusercontent.com/63192240/127992165-07e93e21-3785-4e21-a807-6e49248d87b0.PNG)

=>>>>Note I have already added x64

![10](https://user-images.githubusercontent.com/63192240/127995085-af91de86-df7a-4d1b-aaaf-1d0933dc9ca5.png)


![9](https://user-images.githubusercontent.com/63192240/127992409-c0e1d368-e121-4dcb-af99-70fc48c8e506.PNG)
--> paste shellcode 

![6](https://user-images.githubusercontent.com/63192240/127992537-1f050c54-c669-4dc6-b2a2-f0aabf6ec2e6.PNG)
-> open folderProject /Process Injection in Csharp\Process Injection in Csharp\bin\x64\Release
