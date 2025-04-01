# Ansys-Packaging
This repository contains the Thermal Simulations of Semiconductor packaging using Ansys Electronic Desktop

Open Ansys Electronic Student Desktop Student Application and a window will pop up

![Screenshot 2025-04-01 222109](https://github.com/user-attachments/assets/9f727087-2edd-4b0a-bbb7-cc390823f2ea)

Click on Project -> Insert Icepack Design

![Screenshot 2025-04-01 222215](https://github.com/user-attachments/assets/5162fcd1-0e01-4173-b5ae-b8d5920d32cd)

Click Icepack at the top bar

![Screenshot 2025-04-01 222349](https://github.com/user-attachments/assets/8c014e23-ead5-461a-9571-822f71ef24c0)

Go to Icepack -> Toolkit -> Geometry -> Packages -> Flipchip_BGA

![Screenshot 2025-04-01 222600](https://github.com/user-attachments/assets/b6de136f-56e7-4aa9-9e06-5d73d47044f7)

A window will pop up set to the default values or if you have any data sheet give the values accordingly then click ok

![Screenshot 2025-04-01 222726](https://github.com/user-attachments/assets/fd388b4e-2bf2-4c53-a548-61b73ce19cac)

Now the 3D model is loaded in the space.

![Screenshot 2025-04-01 223747](https://github.com/user-attachments/assets/64f00b21-7a16-4643-a25a-b9a8cede2ebd)

In Models, expand the Solids to see the Substrate, Die, etc seperately

After this step Go to Project Manager -> Thermal -> Select the Power which is given While designing (here i have given 1 Watt) -> Ok

![Screenshot 2025-04-01 224653](https://github.com/user-attachments/assets/99cc70f2-5739-441f-9b67-b1d97c30d176)

In solids, select Flipchip-BGA1_substrate -> Assign Thermal -> Source

![Screenshot 2025-04-01 225307](https://github.com/user-attachments/assets/7a08ba1c-d2c6-4bc2-8182-c4ff3049386c)

A window will pop up in that Thermal condition select Ambient Temperature -> Ok

![Screenshot 2025-04-01 225011](https://github.com/user-attachments/assets/2e3b671f-7607-4caa-a9c7-25a262539950)

Now we added the Sources to the Model.

![Screenshot 2025-04-01 225617](https://github.com/user-attachments/assets/b817bb47-fd76-41a1-99a2-89c13ff7bba7)

Delete the extra flipxhip_BGA_trace1 under the thermal

![Screenshot 2025-04-01 225638](https://github.com/user-attachments/assets/ee6f8e38-b206-461c-84e7-3dd596c2ee9b)

In Solids, select Substrate -> Assign monitor -> Point 
![Screenshot 2025-04-01 225848](https://github.com/user-attachments/assets/97a83c5f-dd48-409a-96c4-0f580b44b9c2)

Tick Temperature -> Ok

Do the same for Die and Underfill too

![Screenshot 2025-04-01 225824](https://github.com/user-attachments/assets/68df51a9-6a57-45a6-b414-3b3efa2ff4db)

Go to Mesh -> Click Simulation -> Generate Mesh -> save the file -> ok

![Screenshot 2025-04-01 231040](https://github.com/user-attachments/assets/a7001165-8689-49b7-9c2b-47f21804e6a7)

In Mesh Visualization, click quality to see the results of face alignment

![Screenshot 2025-04-01 231420](https://github.com/user-attachments/assets/a0df65a2-111c-4ea8-a2b1-9f739fdf276e)

Skewness

![Screenshot 2025-04-01 231434](https://github.com/user-attachments/assets/f673a9c4-84f6-4dae-a34c-df4fd3057f1d)

Volume

![Screenshot 2025-04-01 231444](https://github.com/user-attachments/assets/41aa3fa5-11cb-4ef9-9ba1-9ff789409132)


Click on Validate in the Top bar menu. If all gets green Ticks then the setup is fine.

![Screenshot 2025-04-01 233011](https://github.com/user-attachments/assets/1aa298d4-efe5-45a6-8b72-df4f0f31a9a7)

Click on analyze all

![Screenshot 2025-04-01 233643](https://github.com/user-attachments/assets/5d82962a-f6aa-402c-8a9e-628e1a849b3e)

Select the package -> select plot field -> Temperature -> temperature

![Screenshot 2025-04-01 233730](https://github.com/user-attachments/assets/f7ddb19e-e553-4417-aa98-9cfc4be39689)

Tick the Specify name, Specify folder, Plot on Surface only

In Surface smoothening, enable Gaussian Smoothing -> ok -> Done

![Screenshot 2025-04-01 234141](https://github.com/user-attachments/assets/566e9850-821b-4e7f-9bc5-a27187605c93)

Thermal analysis of the Flipchip BGA for the power of 1 W

![Screenshot 2025-04-01 234906](https://github.com/user-attachments/assets/6731e368-ab8f-4cac-b8f1-25375d0c9a33)


![Screenshot 2025-04-01 235330](https://github.com/user-attachments/assets/7eb7b8c0-3b00-4c01-bbcc-7093412d8e7d)
