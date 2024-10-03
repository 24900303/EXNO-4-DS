# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
```
![372368248-2b49dc3d-4fb4-480a-ac38-b57085a139e1](https://github.com/user-attachments/assets/37bd1f5c-fb86-4ddb-a543-4e6d7cc73d48)
```
![372368385-3cee7406-7e16-439c-b835-23a569fa9f35](https://github.com/user-attachments/assets/4e35e3b0-e442-4d7a-848c-dc9a627e2654)
```
![372368443-9dbff13c-3961-4372-978e-841977c07448](https://github.com/user-attachments/assets/f477a793-94f7-410a-9d5c-d526b2531b07)
```
![372368480-0b075c41-94eb-46c2-ac85-cc5c518516e0](https://github.com/user-attachments/assets/dfcba5f4-9f26-4974-b84c-9fa7189d4058)
```
![372368520-b13acb54-bfd0-49c5-8cea-092be739ea18](https://github.com/user-attachments/assets/79e3ddbc-5434-4799-a105-29b59f04df95)
```
![372368561-41a2c587-369b-41f2-ba63-7c594eeaffae](https://github.com/user-attachments/assets/d745e552-9c44-433c-a6fd-1d0cb7b3f84f)
```
![372368606-23ece262-14f0-4a3d-97e4-28cf8f43b2ab](https://github.com/user-attachments/assets/04ac410c-74ed-46f1-ae04-80a2f9e58dcc)
```
![372368648-a00d0395-93b5-4026-8250-641664af1b7c](https://github.com/user-attachments/assets/18962a76-e405-4421-9f61-2ea583ea73f8)
```
![372368688-1e34502c-382b-455c-a807-139a3e9f2d56](https://github.com/user-attachments/assets/678c828f-19f3-416f-96bc-d3e4cd6375cf)
```
![372368735-0764e2cb-04b6-4bfa-b91b-893634fdf19d](https://github.com/user-attachments/assets/31caf495-8df9-463e-80ed-da821c7644cb)
```
![372368792-15d969be-e981-46bd-9949-50350df0ca26](https://github.com/user-attachments/assets/7fc7c44b-f4af-4919-9679-6b024768e42f)
```
![372368836-c7c4e0b7-754a-4550-a5e2-2f9098a6d377](https://github.com/user-attachments/assets/466fe54e-bba4-4186-ad2b-c725bf6fc13a)
```
![372369075-2595b59f-ec9f-4346-9f38-570b22917903](https://github.com/user-attachments/assets/4a9100e4-8e02-4bfd-aab1-c8d94c025b41)
```
![372369074-7c470216-475c-4421-b9d0-4e96b5b31b59](https://github.com/user-attachments/assets/0c2040b1-ce9e-4e41-97fc-f7af06bc560b)
```
![372369133-81dbd040-5941-4290-84ec-62b74d808097](https://github.com/user-attachments/assets/c3bbf594-9c6a-449e-b32c-1b83ee224e49)
```
![372369189-76005c97-d45a-4265-9dbf-627975fd6d5c](https://github.com/user-attachments/assets/334bae29-e501-42f2-b68b-9d39868be55d)
```
![372369231-9d425ed0-f8ec-4854-917b-1cf4cf5532ca](https://github.com/user-attachments/assets/08705e8e-5b8e-447c-bc94-71339d453620)
```
![372369333-c86d5d0b-f998-440f-9bb9-2ec88f32b9de](https://github.com/user-attachments/assets/1bc23aff-b4ba-4703-a813-c2d95f38505b)
```
![372369371-78dfe827-4f5e-4e5b-ad91-b9bbede1c535](https://github.com/user-attachments/assets/774daf89-6b1a-479c-8c69-79438505d7ff)
```
![372369399-4360c48b-26c8-471a-b0fc-ebefbbcb8508](https://github.com/user-attachments/assets/3756f851-5c98-43e3-b07c-add6b3a39623)
```
![372369466-d24ffbb0-4b26-4785-978d-135fe8a602dd](https://github.com/user-attachments/assets/bf6f48d5-4d4b-4350-8ad9-af187160454d)
```
![372369537-09dfb869-fe90-4a6d-807d-4a38cf4292f8](https://github.com/user-attachments/assets/781c3ca8-e525-4d2d-a02d-afd3b5793578)
```
![372369587-7700e336-4e80-4792-8662-0de4d8633da3](https://github.com/user-attachments/assets/d47537f8-6ed7-495e-b2a3-ac451c477b24)
```
![372369862-a5636de8-a19b-49fc-9bea-4fb21666545f](https://github.com/user-attachments/assets/e65f165b-df2c-4fe9-8f7a-5af716d8a89e)
```
# RESULT:
 Thus feature scaling and selection is performed.
