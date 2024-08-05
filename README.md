# K-Fold-XG-Boost-Practice

![image](https://github.com/user-attachments/assets/10b8cc7a-abe0-4150-972e-daa20affcb01)
![image](https://github.com/user-attachments/assets/8debab2e-1220-46a1-923f-c0b7a7ed7652)
![image](https://github.com/user-attachments/assets/0276caff-7f22-42df-a63c-be6ddc136d56)
![image](https://github.com/user-attachments/assets/6b99075f-a9c4-4522-842e-26ddbbd26758)

# Data Set: Mushroom (Boost_mushrooms.csv)
Column Details 
1.	Class : edible=e, poisonous=p   (This is the dependent variable)
2.	cap-shape: bell=b, conical=c, convex=x, flat=f, knobbed=k, sunken=s
3.	cap-surface: fibrous=f,grooves=g,scaly=y,smooth=s
4.	cap-color: brown=n,buff=b,cinnamon=c, gray=g,green=r,pink=p,purple=u,red=e,white=w,yellow=y
5.	bruises: bruises=t,no=f
6.	odor: almond=a,anise=l,creosote=c,fishy=y,foul=f,musty=m,none=n,pungent=p,spicy=s
7.	gill-attachment: attached=a, descending=d, free=f, notched=n
8.	gill-spacing: close=c,crowded=w,distant=d
9.	gill-size: broad=b,narrow=n
10.	gill-color: black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e,white=w,yellow=y
11.	stalk-shape: t,e
12.	stalk-root: b, ?
13.	stalk-surface-above-ring: s,k
14.	stalk-surface-below-ring: s, k
15.	stalk-color-above-ring: w,p
16.	stalk-color-below-ring: w,p
17.	veil-type – Unique value
18.	veil-color- w,n
19.	ring-number- o,t
20.	ring-type- p,e
21.	spore-print-color -w,n
22.	population – v,y
23.	habitat: d,g

* Create Train and Test Model – xgboost 
   XGBoost comes with its own class for storing datasets called DMatrix. It is a highly optimized class for memory and speed. That's why converting datasets into this format 
   is a requirement for the native XGBoost API
   DMatrix is an internal data structure that is used by XGBoost, which is optimized for both memory efficiency and training speed.

