Adding a java based application using maven.

First we need to add maven plugin and configure it.

step-1 go to manage jenkins 

<img width="1903" height="898" alt="image" src="https://github.com/user-attachments/assets/330e3c6f-cdbf-49f3-bbe7-6f6588071b34" />

<img width="1901" height="876" alt="image" src="https://github.com/user-attachments/assets/5fdb4677-59a4-4c2a-bd1c-21801b45edb9" />

We check if any plugin wants update or not if required we have to update and restart the jenkins adding shreenshot for these.
<img width="1888" height="887" alt="image" src="https://github.com/user-attachments/assets/b5f6a632-8a2b-45c1-ac7f-be7377b1649e" />

<img width="1900" height="890" alt="image" src="https://github.com/user-attachments/assets/6aa64611-901b-4a98-85f4-fa38b170b97b" />
<img width="897" height="298" alt="image" src="https://github.com/user-attachments/assets/d22e095b-6aeb-4bcc-b11f-ffb66ecc3de0" />

<img width="1881" height="816" alt="image" src="https://github.com/user-attachments/assets/cead2d0e-35d9-4926-ac9e-51af0d4584f6" />

First plugin which we need to install in maven.

step 2- in the avibilbe pulgin search maven intgration and download.
<img width="1867" height="861" alt="image" src="https://github.com/user-attachments/assets/7695ea7b-8b2d-4cf3-abb0-c05112bf18f4" />
<img width="1867" height="861" alt="image" src="https://github.com/user-attachments/assets/57342528-bd8f-463b-a2b3-42aee5041c1e" />
<img width="1867" height="812" alt="image" src="https://github.com/user-attachments/assets/426cf347-5261-4337-be0b-3efbfc10729e" />

Now after the installations we need to configure the tool as well to use it.
<img width="1857" height="852" alt="image" src="https://github.com/user-attachments/assets/890f9783-7b56-4b48-afa9-bda9d8754aba" />

now in add maven need need to configure our downloaded maven to use it.
<img width="1883" height="880" alt="image" src="https://github.com/user-attachments/assets/16313269-306d-4b65-8b3e-39c2a6e1db02" />

now apply and save it.
<img width="1671" height="742" alt="image" src="https://github.com/user-attachments/assets/f1cfbc5c-3c1b-4728-8442-8f6ffebdc519"/>

Now we use this to any java job so that maven can we used we will create a new classic job and we will get thye code from git and will use this confgure maven to run this.

<img width="1918" height="860" alt="image" src="https://github.com/user-attachments/assets/a1bd4ef2-bfe4-4853-83f6-694641a17f9f" />
<img width="1866" height="846" alt="image" src="https://github.com/user-attachments/assets/cf80eae9-390e-4131-a478-c2c02e934404" />

we can use this ulr from git which have an java project https://github.com/rj3740/simple-java-maven-app.git.
sincve its a public repo no credinactnal are required.
<img width="1346" height="696" alt="image" src="https://github.com/user-attachments/assets/9f166b1e-5c85-4d3d-a1c4-2dab6a0c6605" />

Now in the bottom of the page in build we can add maven so the is can run java code 
<img width="1878" height="861" alt="image" src="https://github.com/user-attachments/assets/be9d88e4-fd23-4c38-99c0-d4aca17c728d" />

In the goal we have to put the target for exmaple weather we need to complie test etc then apply and save.

<img width="1886" height="883" alt="image" src="https://github.com/user-attachments/assets/4d3c2f88-8111-4cba-8457-7819dc99acf5" />










