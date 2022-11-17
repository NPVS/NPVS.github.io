<h1 align="center"> A unified model for conditional video synthesis </h1>

<h3 align="center"> <a href="https://github.com/NPVS/NPVS" target="_blank">Code<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="30" height="30"></a> <h3>

&nbsp;

<h2 align="left"> Uncurated Examples of the unifed model for each task of VFI, VFP, VPE and VRC </h2>

we show prediction examples of 1X fps (original fps of the dataset), 2X fps and 3X fps. 2X fps and 3X fps show the continuous prediction ability of our unified model. <em>Frames with <span style="color:red"> Red temporal coordinates </span> denote frames generated by our model.</em>


<h3 align="left">  Video interpolation (VFI) </h3>

<em><b>1X fps</b></em> 

left column: ground-truth. Right column: predicted videos

<h3 align="center"> <img src="./kth_rc_vfi_10to10_1xfps.gif" alt="KTH-RC-VFI-1xfps"> </h3>

<em><b>2X fps</b></em> (Ground-truth is not available) 

<h3 align="center"> <img src="./kth_rc_vfi_10to10_2xfps.gif" alt="KTH-RC-VFI-2xfps"> </h3>

<em><b>3X fps</b></em> (Ground-truth is not available) 

<h3 align="center"> <img src="./kth_rc_vfi_10to10_3xfps.gif" alt="KTH-RC-VFI-3xfps"> </h3>

&nbsp;

<h3 align="left"> Video future prediction (VFP) </h3>

<em><b>1X fps</b></em> 

left column: ground-truth. Right column: predicted videos 

<h3 align="center"> <img src="./kth_rc_vfp_10to10_1xfps.gif" alt="KTH-RC-VFP-1xfps"> </h3>

<em><b>2X fps</b></em> (Ground-truth is not available) 

<h3 align="center"> <img src="./kth_rc_vfp_10to10_2xfps.gif" alt="KTH-RC-VFP-2xfps"> </h3>

<em><b>3X fps</b></em> (Ground-truth is not available) 

<h3 align="center"> <img src="./kth_rc_vfp_10to10_3xfps.gif" alt="KTH-RC-VFP-3xfps"> </h3>

&nbsp;

<h3 align="left"> Video past frame extrapolation (VPE) </h3>

<em><b>1X fps</b></em> 
left column: ground-truth. Right column: predicted videos 

<h3 align="center"> <img src="./kth_rc_vpe_10to10_1xfps.gif" alt="KTH-RC-VPE-1xfps"> </h3>

<em><b>2X fps</b></em>  (Ground-truth is not available)

<h3 align="center"> <img src="./kth_rc_vpe_10to10_2xfps.gif" alt="KTH-RC-VPE-2xfps"> </h3>

<em><b>3X fps</b></em>  (Ground-truth is not available)

<h3 align="center"> <img src="./kth_rc_vpe_10to10_3xfps.gif" alt="KTH-RC-VPE-3xfps"> </h3>

&nbsp;

<h3 align="left"> Video random missing frames completion (VRC) </h3>


<em><b>1X fps</b></em> 

left column: ground-truth. Right column: predicted videos 

<h3 align="center"> <img src="./kth_rc_vrc_10to10_1xfps.gif" alt="KTH-RC-VRC-1xfps"> </h3>

<em><b>2X fps</b></em> (Ground-truth is not available) 

<h3 align="center"> <img src="./kth_rc_vrc_10to10_2xfps.gif" alt="KTH-RC-VRC-2xfps"> </h3>

<em><b>3X fps</b></em> (Ground-truth is not available)

<h3 align="center"> <img src="./kth_rc_vrc_10to10_3xfps.gif" alt="KTH-RC-VRC-3xfps"> </h3>

&nbsp;

<h3 align="left"> VRC with mixing fps (Irregular time step, Ground-truth is not available)
</h3>

Some missing frames are predicted with 1X fps, some missing frames are predicted with 2X fps, some missing frames are predicted with 3X fps.

<h3 align="center"> <img src="./kth_rc_vrc_10to10_mix_fps.gif" alt="KTH-RC-VRC-mix-fps"> </h3>

&nbsp;

<h3 align="left"> Uncurated Examples of task-specific VFI
</h3>


<em>Frames with <span style="color:red">Red temporal coordinates</span> denote frames generated by our model.</em>

<h3 align="left"> KTH and SM-MNIST (64x64) </h3>

left column: ground-truth. Right column: predicted videos. 

<h3 align="center"> <img src="./KTH_specific_vfi_55to10.gif" alt="KTH-VFI"> </h3>

<h3 align="center"> <img src="./smmnist_specific_vfi_10to5_1xfps.gif" alt="SMMNIST-VFI"> </h3>

<h3 align="left"> BAIR (64x64)  </h3>

left column: ground-truth, middle column: random prediction 1, right column: random prediction 2. 

<h3 align="center"> <img src="./bair_specific_vfi_rand_4to5_1xfps.gif" alt="BAIR-VFI"> </h3>

&nbsp;

<h3 align="left"> Uncurated Examples of task-specific VFP </h3>

<em>Frames with <span style="color:red">Red temporal coordinates</span> denote frames generated by our model.</em>


<h3 align="left"> KTH (64x64) </h3>

left column: ground-truth. Right column: predicted videos. 

<h3 align="center"> <img src="./kth_specific_vfp_10to10_1xfps.gif" alt="KTH-VFP"> </h3>

<h3 align="left"> Cityscapes (128x128) </h3>

left column: ground-truth, right column: predicted videos.

<h3 align="center"> <img src="./city_specific_vfp_2to28_1xfps.gif" alt="City-VFP"> </h3>

<h3 align="left"> BAIR (64x64) </h3>

left column: ground-truth, right column: predicted videos.

<h3 align="center"> <img src="./bair_specific_vfp_2to10_1xfps.gif" alt="BAIR-VFP"> </h3>

