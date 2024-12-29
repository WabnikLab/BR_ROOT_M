![image](https://github.com/user-attachments/assets/3b783d8c-295f-4f93-bce9-f91085e2515c)# RootModel with BR control

Requirements: MorphoGraphX
https://morphographx.org/morphodynamx/ (Maintained by Richard Smith, JIC)
https://doi.org/10.7554/eLife.72601

After installing MorphoDynamX, the model can be compiled by typing:

make -B

If compiling is successfull, the modle can be run with:

MorphoDynamX  '--model' 'Model/Root/01 Root' '--addlibrary' 'usrLibRoot.so' Root_Brassinosteroid.mdxv
