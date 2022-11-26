# Jarkom-Modul-4-I06-2022

- Muhammad Naufal Alif - 05111942000008
- Denta Bramasta Hidayat - 5025201116
- Rahel Cecilia Purba - 5025201155

MODUL 4
---
![soal shift 4 1](https://user-images.githubusercontent.com/112471006/203229401-542b0a44-7c21-4f82-b5ad-d959b600ab44.png)

##
### VLSM

![soal shift 4 1](https://user-images.githubusercontent.com/112471006/204075156-7aab9b73-b533-4454-b974-8f19314f545a.png)

| Subnet | IP Count  | Netmask |
| ------ | --------- | ------- |
|   A1   | 1001 | /22 |
|A2 | 251 | /24 |
|A3 | 2 | /30 |
|A4 | 2 | /30 |
|A5 | 51 | /26 |
|A6 | 2 | /30 |
|A7 | 2 | /30 |
|A8 | 121 | /25 |
|A9 | 2 | /30 |
|A10 | 212 | /24 |
|A11 | 2 | /30 |
|A12 | 501 | /23 |
|A13 | 2 | /30 |
|A14 | 2 | /30|
|A15 | 271 | /23 |
|A16 | 2 | /30 |
|A17 | 121 | /25 |
|A18 | 71 | /25 |
|Total | 2618 | /20|

### VLSM Tree
![image](https://user-images.githubusercontent.com/112471006/204089293-7833555f-e890-4132-be1f-7fddf4da3a20.png)
![image](https://user-images.githubusercontent.com/112471006/204089339-8bcd6b75-f30c-44ee-a3fd-152545b26421.png)
![image](https://user-images.githubusercontent.com/112471006/204089147-dd3345e7-4a9c-4500-9716-1ff24ae7e6e3.png)
![image](https://user-images.githubusercontent.com/112471006/204089175-a279caee-1190-4f7b-9509-67b925dbe5c2.png)

### CIDR
- A2 (/24) & A3 (/30) = B1 (/23)
- A10 (/24) & A11 (/30) = B2 (/23)
- A17 (/25) & A18 (/25) = B3 (/24) 

![image](https://user-images.githubusercontent.com/112471006/204089430-ab4a0b2f-e406-4b60-bcf3-532193d38786.png)
- B1 (/23) & A1 (/22) = C1 (/21)
- B2 (/23) & A12 (/23) = C2 (/22)
- B3 (/24) & A16 (/30) = C3 (/23)

![image](https://user-images.githubusercontent.com/112471006/204089488-ce270978-a590-4039-9a15-da9e1199c079.png)
- C1 (/21) & A4 (/30) = D1 (/20)
- C2 (/22) & A9 (/30) = D2 (/21)

![image](https://user-images.githubusercontent.com/112471006/204089612-ccdacff6-b93e-47ba-a047-b57bcc4be7cf.png)
- D1 (/20) & A5 (/26) = E1 (/19)
- D2 (/21) & C3 (/23) = E2 (/20)

![image](https://user-images.githubusercontent.com/112471006/204089620-b1704e1a-684a-4c65-86c6-524b640af6aa.png)
- E1 (/19) & A6 (/30) = F1 (/18)
- E2 (/20) & A8 (/25) = F2 (/19)
- A14 (/30) & A15 (/23) = F3 (/22)

![image](https://user-images.githubusercontent.com/112471006/204089630-9cb3c22f-5835-445b-9796-8172cfe839d9.png)
- F2 (/19) & A7 (/30) = G1 (/18)
- F3 (/22) & A13 (/30) = G2 (/21)

![image](https://user-images.githubusercontent.com/112471006/204089673-9fb8d713-1b01-4943-b7bb-2a5eac8df90f.png)
- G1 (/18) & G2 (/21) = H1 (/17)

![image](https://user-images.githubusercontent.com/112471006/204089683-b19c6d4c-034d-4656-8e83-c517e116b08a.png)
- H1 (/17) & F1 (/18) = I1 (/16)

![image](https://user-images.githubusercontent.com/112471006/204089697-ca6352f6-baf2-42e4-8569-40b8eeba9d39.png)

### CIDR Tree
![image](https://user-images.githubusercontent.com/112471006/204089713-7b8a7b63-c886-4b73-a03f-deebb166130a.png)
![image](https://user-images.githubusercontent.com/112471006/204089725-31bc8c1b-63f6-490e-8cc5-61497df132ce.png)
![image](https://user-images.githubusercontent.com/112471006/204089731-f3712246-1720-49b6-b7d9-cf217253fd38.png)
![image](https://user-images.githubusercontent.com/112471006/204089741-8c0edf37-bf74-4fbb-825f-8819e95077b3.png)
![image](https://user-images.githubusercontent.com/112471006/204089747-e83c566e-6a03-46e3-8123-2fbde61d82ed.png)


