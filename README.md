

<h1 align="center"> A unified model for conditional video synthesis </h1>

<h3 align="center"> <a href="https://github.com/NPVS/NPVS" target="_blank">Code<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="30" height="30"></a> <h3>

# Uncurated Examples of the unifed model
For each task of VFI, VFP, VPE and VRC, we show prediction examples of 1X fps (original fps of the dataset), 2X fps and 3X fps. 2X fps and 3X fps show the continuous prediction ability of our unified model. <em>Frames with **<span style="color:red">Red temporal coordinates</span>** denote frames generated by our model.</em>



## Video interpolation (VFI)
### **1X fps**
left column: ground-truth. Right column: predicted videos

![KTH-RC-VFI](./img/kth_rc_vfi_10to10_1xfps.gif)

### **2X fps** (Ground-truth is not available)

![KTH-RC-VFI-2xfps](./img/kth_rc_vfi_10to10_2xfps.gif)

### **3X fps** (Ground-truth is not available)

![KTH-RC-VFI-3xfps](./img/kth_rc_vfi_10to10_3xfps.gif)

## Video future prediction (VFP)
### **1X fps**
left column: ground-truth. Right column: predicted videos

![KTH-RC-VFP](./img/kth_rc_vfp_10to10_1xfps.gif)

### **2X fps** (Ground-truth is not available)

![KTH-RC-VFP-2xfps](./img/kth_rc_vfp_10to10_2xfps.gif)

### **3X fps** (Ground-truth is not available)

![KTH-RC-VFP-3xfps](./img/kth_rc_vfp_10to10_3xfps.gif)

## Video past frame extrapolation (VPE)
### **1X fps**
left column: ground-truth. Right column: predicted videos

![KTH-RC-VPE](./img/kth_rc_vpe_10to10_1xfps.gif)

### **2X fps** (Ground-truth is not available)
![KTH-RC-VPE-2xfps](./img/kth_rc_vpe_10to10_2xfps.gif)

### **3X fps** (Ground-truth is not available)

![KTH-RC-VPE-3xfps](./img/kth_rc_vpe_10to10_3xfps.gif)


## Video random missing frames completion (VRC)
### **1X fps**
left column: ground-truth. Right column: predicted videos

![KTH-RC-VRC](./img/kth_rc_vrc_10to10_1xfps.gif)

### **2X fps** (Ground-truth is not available)
![KTH-RC-VRC-2xfps](./img/kth_rc_vrc_10to10_2xfps.gif)

### **3X fps** (Ground-truth is not available)

![KTH-RC-VRC-3xfps](./img/kth_rc_vrc_10to10_3xfps.gif)

### **VRC with mixing fps (Irregular time step, Ground-truth is not available)**
Some missing frames are predicted with 1X fps, some missing frames are predicted with 2X fps, some missing frames are predicted with 3X fps.

![KTH-RC-VRC-mix-fps](./img/kth_rc_vrc_10to10_mix_fps.gif)



# Uncurated Examples of task-specific VFI

### KTH and SM-MNIST (64x64)

left column: ground-truth. Right column: predicted videos. <em>Frames with **<span style="color:red">Red temporal coordinates</span>** denote frames generated by our model.</em>

![KTH-VFI](./img/kth_specific_vfi_10to10_1xfps.gif)

![SMMNIST-VFI](./img/smmnist_specific_vfi_10to5_1xfps.gif)

&nbsp;
### BAIR (64x64)
left column: ground-truth, middle column: random prediction 1, right column: random prediction 2. <em>Frames with **<span style="color:red">Red temporal coordinates</span>** denote frames generated by our model.</em>
![BAIR-VFI](./img/bair_specific_vfi_rand_4to5_1xfps.gif)

# Uncurated Examples of task-specific VFP

### KTH (64x64)
![KTH-VFP](./img/kth_specific_vfp_10to10_1xfps.gif)

&nbsp;

### BAIR (64x64)
left column: ground-truth, middle column: random prediction 1, right column: random prediction 2. <em>Frames with **<span style="color:red">Red temporal coordinates</span>** denote frames generated by our model.</em>
![BAIR-VFP](./img/bair_specific_vfp_rand_2to10_1xfps.gif)

