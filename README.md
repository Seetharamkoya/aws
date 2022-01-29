# aws
AWS-notes/IMP key-points

What is Datacenter

```
A datacenter is a dedicated space where companies maintain and opeare most of the ICT infracture that support the business.
```

Traditional CAPEX/OPEX

```
CAPEX model: Buy the dedicated hardware and depreciate it over the a period of time.

Opex model: use a shared cloud infrastcture and pay as one uses it(greater flexibility to decrease/increase capacity).
```

Why we are moving to cloud

cpax and opex

### 

### RTO/RPO 

RTO is more broader scope and covers the whole business and systems involved while
(hiah avilibilty - How quickly we can able to restore our application) 

RPO is more directly related to internal of backup to take to avoid data loss.
(backup plan for data recovery) 

### Functional/Non-functional requirements:

![image](https://user-images.githubusercontent.com/38424194/151648755-5f1c41f8-5e5b-4454-b5ab-04643b5b23b4.png)

![image](https://user-images.githubusercontent.com/38424194/151649495-a67e9270-02f9-4803-b5dc-81547d489fbe.png)

Functional:
How it works (expections) who/what/confirmation mail(welcome mail)

### Non-functional:

Restrictions to show case the application is running, user privacy \
Realibility: \
probability: \
security: \
scalibility: \ 
Performane: \
Horziontal/Vertical scaling: \
Reusability: \
Flexiblity: Global variables

### Hybrid Cloud
private cloud (when we need it to expand it to public, we move to public cloud) + Public Cloud = Hybrid


![image](https://user-images.githubusercontent.com/38424194/151649434-1a00342f-4b3b-4ee2-b5e6-5f299b86d82e.png)


### Use case:
currently, we have 10000 req and next week we are going to increase 50000(expectations) req how many VM's we need?

![image](https://user-images.githubusercontent.com/38424194/151650193-ed45f73c-d504-4a5b-b033-95f9a281d2f9.png)

1. page size (app. 90kb)


Prarameters to define:
1. utilization
2. No:requests
3. peak time and non-peak time hours

