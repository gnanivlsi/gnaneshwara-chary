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


# gnaneshwara-chary
Packaging Lab 
LAB 2:

Lab 2: Package Design and Modelling
Open The AEDT application. Go to Project -> Q3D extractor Design
 ![image](https://github.com/user-attachments/assets/72d64c8e-679f-49aa-afd3-e4c02222d91f)

Click Rectangle and draw it with the required values.
 ![image](https://github.com/user-attachments/assets/9aa4658a-abe0-4a8c-aaae-5ed610c7926c)







Click on the rectangle -> Modeler -> Surface -> Thicken Sheet. Set the thickness to 0.2mm
 ![image](https://github.com/user-attachments/assets/ebf12b01-3a83-4050-b98e-632f11f2ce32)


 name the rectangle as Die.
 
![image](https://github.com/user-attachments/assets/01084090-d02a-4713-8bda-2e5375f4cd1d)







Select the material as silicon.
![image](https://github.com/user-attachments/assets/693c3760-1845-4b15-bfad-9b7127c74d57)

 
Draw another rectangle which is bigger than the previous one.
 ![image](https://github.com/user-attachments/assets/3cb3a7b8-ed9c-4083-8d99-5f55fc2a2e26)







Select the required dimensions.
 ![image](https://github.com/user-attachments/assets/05a699ae-40d3-4368-bbb8-51a91b24b2b5)


Set the thickness to -0.5mm
 ![image](https://github.com/user-attachments/assets/cf86fabc-f1ec-437c-81c4-d17bd99faa27)

Change the name as Substrate and assign FR4_epoxy material. Also change the position of substrate accordingly.
![image](https://github.com/user-attachments/assets/efc34434-c1d1-4963-87ae-38504b2b4ea2)

 

Draw another rectangle over the die with the same dimensions.
 

![image](https://github.com/user-attachments/assets/d306c420-8c5d-4d91-9e1b-0c469c070616)






Set the required dimensions and position and set thickness to -0.1mm
![image](https://github.com/user-attachments/assets/0369db50-a0b7-41c5-8fd8-06c470157993)

 

Change the name to DieAttach and assign modified_epoxy material.
 

![image](https://github.com/user-attachments/assets/45bee403-383b-4aca-b3ba-873d8fe5bec2)




Draw a small rectangle on the Die and set the required position and dimensions. Set thickness as 0.005mm


 ![image](https://github.com/user-attachments/assets/bd1ae572-ae45-4445-8d66-73928f3dd523)


Similarly, draw a small rectangle on the substrate.
 
![image](https://github.com/user-attachments/assets/68fb3046-7d7a-4131-807e-e81d78b4da75)




Set the required position and dimensions.
 
![image](https://github.com/user-attachments/assets/1cc1a586-cd98-46c7-8972-97dbfaae1aa5)

Change the name of rectangle on die as Diebondpad and similarly change the name of rectangle on substrate as Substratebondpad.

 
![image](https://github.com/user-attachments/assets/4ac97ead-a031-40d5-9297-f49401b02130)




Click on Bondwire and draw from center of Diebondpad to center of Substratebondpad.
 ![image](https://github.com/user-attachments/assets/82fef4cd-9b56-471b-8e46-e45756d2efcc)

Assign material of bondwire as gold and change the color.
 
![image](https://github.com/user-attachments/assets/bf2ea130-71df-49ed-966a-326d55c30ef9)







Click on Diebondpad -> Edit -> Duplicate -> Along Line
 ![image](https://github.com/user-attachments/assets/dad47783-c9aa-4ead-98c2-7527424b67dd)


Set the number to 7.
 ![image](https://github.com/user-attachments/assets/824c731f-aa72-4956-9f5e-6768a68e79b0)







Duplicate the Substratebondpad and bondwires.
 ![image](https://github.com/user-attachments/assets/cf9da0a4-baff-4b6d-901e-361268a65f34)

Repeat on the remaining 3 sides.
 
![image](https://github.com/user-attachments/assets/7a4099c4-fe47-4432-999a-4be59c82ba09)








Draw a rectangle on the substrate with the same dimensions and set the thickness to 1.2mm

 ![image](https://github.com/user-attachments/assets/2d7f9029-e653-4dee-9ec5-eba7839e3a08)


Change the name as MoldCompound and assign epoxy_Kevlar_xy material.
 
![image](https://github.com/user-attachments/assets/72919d9b-f3fe-435d-b32b-1bdf97ac5949)





The final package is obtained
 
 ![image](https://github.com/user-attachments/assets/af1d7bf9-4303-4426-a630-4a2d28189fac)


![image](https://github.com/user-attachments/assets/2573a3bb-263c-4bbc-b305-1c08a5b51b15)













