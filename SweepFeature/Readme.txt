  SweepFeature Sample
  =======================
  
This sample demonstrates the creation of a sweep feature. Firstly, a path is created for the sweep. The sweep path contains a combination of 2D and 3D sketch elements that are contiguous. Creation of 3D sketch lines and bends are demonstrated in creation of the path. The path comprises a 2D arc and two 3D lines connected by a bend. Next, a workplane is created at the start point of the 2D arc, normal to the arc at the point. The sweep profile is created on a sketch placed on this workplane.
 
  
  How to run this sample:
 
  1) Copy Autodesk.SweepFeature.Inventor.addin into one of below folders:
		a) Inventor Version Dependent
		Windows 11:
			%ProgramData%\Autodesk\Inventor [version]\Addins\

		b) Inventor Version Independent
		Windows 11:
			%ProgramData%\Autodesk\Inventor Addins\

		c) Per User Override
		Windows 11:
			%AppData%\Autodesk\Inventor [version]\Addins\

  2) Copy bin\SweepFeature.dll into Inventor bin folder(For example: C:\Program Files\Autodesk\Inventor 20XX\Bin).

  3) Startup Inventor, Click on 'Create Sweep Feature' command which will be displayed on the Add-Ins->General panel.
  
  Language/Compiler: C++
  Executable /DLL : SweepFeature.dll
  Server: Inventor.

 