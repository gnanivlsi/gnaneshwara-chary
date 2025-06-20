# gnaneshwara-chary
Packaging Lab 
Lab 1: Thermal Simulation of Semiconductor Packages with ANSYS
Open Ansys Electronics Desktop. Go to Project -> Insert Icepack Design
 
An Icepack Project will appear.
 
![image](https://github.com/user-attachments/assets/d73dcf45-88e6-4948-aed6-7f34cbbbe23d)

Go to Icepack -> Toolkit -> Geometry -> Packages -> FilpChip_BGA. A tiny window will appear where you can customize the dimensions of the package.

 ![image](https://github.com/user-attachments/assets/d147e4dc-5f1e-4cda-a37a-dbcdaf59b5d0)


The model of the package is loaded. Go to Model to see the package.

 ![image](https://github.com/user-attachments/assets/e7e976dc-2480-4da5-9b59-42a89029db07)






Go to Project Manager -> Thermal -> Select the Power -> OK

 ![image](https://github.com/user-attachments/assets/7f061677-6fc5-44e0-a326-3c7ed53840ec)

Go to solids -> Flipchip-BGA2_substrate -> Assign Thermal -> Source
 ![image](https://github.com/user-attachments/assets/5385fefc-a798-46a7-aacb-ace5d11aff78)


A window will pop up. Here, select Ambient Temp and Finish.
 ![image](https://github.com/user-attachments/assets/0040d9ac-5c99-4671-ba55-72099ba519b0)

Go to solids -> Flipchip-BGA2_substrate -> Assign Monitor -> Point
 ![image](https://github.com/user-attachments/assets/fe18053c-a355-4336-932d-b8e819e80ca6)






A window will pop up. Here, under Thermal select Temperature. Repeat this process for Die and Underfill also.
 ![image](https://github.com/user-attachments/assets/89f82688-7792-4eb6-9eb5-827c8165092b)

Go to Mesh ->  Simulation -> Generate Mesh -> save the file -> OK. Go to Quality and click on Face alignment.
 
![image](https://github.com/user-attachments/assets/848998f6-18f7-4157-97d5-f860eee8869b)

Similarly, check Skewness.
 ![image](https://github.com/user-attachments/assets/b4781a3c-c4ce-4eea-a1e0-c78aa14b9265)

Go to Project Manager -> Analysis -> Add Solution Setup. A window will pop up. Click OK.
 
![image](https://github.com/user-attachments/assets/45573df5-ff78-4a6c-b89f-af0104635f5f)




	
Click on Validate. If all the parameters have green ticks then there are no errors and you can proceed.  
![image](https://github.com/user-attachments/assets/3dedc479-4195-4bea-b819-854457f66ec3)

Click on Analyze All.
 
![image](https://github.com/user-attachments/assets/3e6e7a74-85a9-44d9-817a-a61e2eb060a4)




	

Go to Solids -> Flipchip_BGA2_die_underfill -> Assign Mesh Region -> select die -> OK -> again click OK on popped up window. 
 ![image](https://github.com/user-attachments/assets/7bb376af-881f-4cda-9382-781b3b12a78f)

Select the package -> Plot Fields -> Temperature -> Temperature
 
![image](https://github.com/user-attachments/assets/75989e98-2298-46dc-a298-7ec8f1009f8a)

	



Click on Specify Name and Specify Folder, Select Plot on surface only and in Surface Smoothing, enable Guassian Smoothing and click Done.
 ![image](https://github.com/user-attachments/assets/1f068e45-e6a7-4822-80ce-c7d97e7988ae)

Thermal Analysis of the package is obtained.

 
![image](https://github.com/user-attachments/assets/061c9926-7c97-4b3d-9351-e15b2426b583)









