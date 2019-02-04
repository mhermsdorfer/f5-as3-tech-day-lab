# F5 AS3 Tech Day Lab


## Lab Environment

UDF Blueprint: AS3 PS Techday Lab Jan 2019

### Networks
VLAN | Subnet
---- | ------
Management | 10.1.1.0/24
Subnet 10  | 10.1.10.0/24

### Component Info & Credentials

| Host              | Management IP | Subnet 10 IP    | Username      | Password    |
| ----------------- | ------------- | --------------- | ------------- | ----------- |
| BIG-IP 1          | 10.1.1.4      | 10.1.10.11      | admin         | admin       |
| BIG-IP 2          | 10.1.1.5      | 10.1.10.12      | admin         | admin       |
| Linux WebServer   | 10.1.1.6      | 10.1.10.100-105 | ubuntu        | key-only    |
| Windows Jump Host | 10.1.1.7      | 10.1.10.200     | Administrator | xn78LcHCtMc |


## AS3 Reference Links

* [AS3 Docs](https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/)
* [AS3 Composing a Declaration](https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/userguide/composing-a-declaration.html)
* [AS3 Example Declarations](https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/declarations/)
* [AS3 Schema Reference](https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/refguide/schema-reference.html)
* [AS3 GitHub Page](https://github.com/F5Networks/f5-appsvcs-extension)


## Lab Guide 

### Start UDF Lab Environment

Once the environment has been started, confirm you are able to login to windows and big-ip instances with credentials above.

#### Clone this git repo

From the windows host:
1. Open cmd or bash git console, which ever your prefer.
2. Clone repo with the following command: ``` git clone https://github.com/mhermsdorfer/f5-as3-tech-day-lab.git ```
3. This will clone this repository into the current working directory, which is likely: ```C:\User\Administrator```.
4. navigate a file explorer to the newly created folder: ```C:\Users\Administrator\f5-as3-tech-day-lab```


#### Setup Postman Environment

1. Open up Postman.
2. Click Import button in top left, to import the postman collection.
3. Drag and drop the ```AS3-Tech-Day-2019-02.postman_collection.json``` file into the import window.
4. Click Import button in top left, to import the postman environment.
5. Drag and drop the ```AS3-Tech-Day-2019-02.postman_environment.json``` file into the import window.

Alternatively, you can import from link using the following:
Postman Collection: ```https://raw.githubusercontent.com/mhermsdorfer/f5-as3-tech-day-lab/master/AS3-Tech-Day-2019-02.postman_collection.json```
Postman Environment: ```https://raw.githubusercontent.com/mhermsdorfer/f5-as3-tech-day-lab/master/AS3-Tech-Day-2019-02.postman_environment.json```

Next, set the environment and start exploring the collection:
1. In the dropdown at the top right, where it says "No Environment" select: "AS3 Tedch Day Lab - UDF"
2. On the left hand side, where you see History & Collections, select Collections, and expand out AS3 Tech Day collection.

Your screen should look like the following:
![alt text](https://raw.githubusercontent.com/mhermsdorfer/f5-as3-tech-day-lab/master/postman_setup.png "Postman Screenshot")

### Install AS3 Extension



### Deploy first application




