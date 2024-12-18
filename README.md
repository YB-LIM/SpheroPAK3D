# SpheroPAK3D
A Plug-in for Generating Periodic Composite Cells with Random Sphere Inclusions in Abaqus/CAE

Developer: Youngbin LIM <br>
Contact: lyb0684@naver.com

![Github_Fig](https://github.com/user-attachments/assets/bb6609c8-fb16-44e2-9507-a87ced5df065)

# Supported versions
Abaqus 2022 and higher

# Installation
Download the contents in SpheroPAK3D and put those files in one folder. Move the folder to the abaqus_plugins directory (ex: C:\Users\User_Name\abaqus_plugins). Restart the Abaqus/CAE and the plug-in will be available whenever the Abaqus/CAE is running. The plug-in is activated for all modules and can be found in Plug-ins drop down menu.

# Geometry and Mesh
Spheres with random sizes are generated based on user-defined parameter (avaerage radius and standard deviation of radius) <br>
Periodic images of spheres are generated as well, thus, geometry is fully periodic <br> However, free meshing is applied and the mesh is not periodic. <br> 
Thus, surface elements with regular mesh is generated and tied with the cell surface to enforce the periodic boundary condition <br>

# Disclaimer
The author do not represent DASSAULT SYSTEMES SIMULIA CORP (Collectively "DS") and the plug-in is not part of official product provided by DS. Your use of this download shall be at your sole risk. No support of any kind of the download is provided by DS. Regarding the inquiries on the plug-in, please contact developer.
