### Cheng Guo (郭铖/Andre) 👋
- 📕 Research interests: HDR (High Dynamic Range), Inverse Tone-mapping, Tone-mapping, WCG (Wide Color Gamut), Gamut Mapping, IQA (Iamge Quality Assessment)
- 📫 Concact: guocheng@cuc.edu.cn, guocheng50655@qq.com, guocheng50655@gmail.com
- 🔭 Ph.D. (Expected Jun. 2024) at State Key Laboratory of Media Convergence and Communication (MCC), Communication University of China (CUC), Beijing, China
- 🌱 **Currently**: Visiting student at Peng Cheng Laboratory (PCL), Shenzhen, China

<body>
<table id="tbl" border=1 width="75%" rules=none frame=void>
  <td><img src="https://github-readme-stats.vercel.app/api?username=andreguo&show_icons=true&hide=issues&theme=dark&hide_title=false" ></td>
  <td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=andreguo&layout=compact&theme=dark&hide_title=false" ></td>
</table>
<a href="https://clustrmaps.com/site/1byto"  title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=iy7jYIXQNVb1iNdYojK10gphv9Ehd64poFK31f-rnIk&cl=ffffff"/></a>
</body>

<!--
**AndreGuo/andreguo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### Main Projects
### 1. ITM, inverse tone-mapping (SDR image to HDR/WCG):
#### **CVPR2023**: [Learning a Practical SDR-to-HDRTV Up-conversion using New Dataset and Degradation Models](https://github.com/AndreGuo/HDRTVDM)
+ A luminance segmented network (***LSN***) AI model with channel decoupled self-attention, for inverse tone-mapping.
+ New ***HDRTV4K*** training set and test set (SDR-HDR/WCG image pairs).
+ New subjective metrics and objective assessment method on inverse tone-mapped HDR/WCG content.

#### **CVMP2023**: [Redistributing the Precision and Content in 3D-LUT-based Inverse Tone-mapping for HDR/WCG Display](https://github.com/AndreGuo/ITMLUT)
An efficient AI inverse tone-mapping for edge devices:
+ AI learning of look-up table (LUT) content, and self-adaptability (LUT content will alter with input image) by the AI merging of basic LUTs.
+ Run with fewer LUT size on higher-bit-depth (10/12bit) HDR/WCG, by discriminative non-uniform sampling of 3 smaller LUTs.

### 2. SI-HDR, single-image HDR reconstruction (SDR to HDR luminance)
#### **ACCV2022**: [LHDR: HDR Reconstruction for Legacy Content Using a Lightweight DNN](https://github.com/AndreGuo/LHDR)
+ An AI model for single-image HDR reconstruction, with partial convolution and condition.
+ Lightweight design using mixed precision of network parameters etc.

### 3. TM, tone-mapping (HDR luminance to commom SDR image)
#### **IEEE Access 2021**: [Deep Tone-Mapping Operator Using Image Quality Assessment Inspired Semi-Supervised Learning](https://github.com/AndreGuo/IQATM)
+ An AI model for tone-mapping, with Laplacian Pyramid decomposition.
+ Introducing IQA (image quality assessment) concept and metrics to unsupervised and semi-supervised training.
