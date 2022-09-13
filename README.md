# Ani:Masa
MMD shader that is specifically made for Animasa Miku model to imitate how it originally looked like in Animation:Master (A:M) program, before being ported to MMD
<img src="https://i.imgur.com/nYYFcNU.png" alt="alt text">
<img src="https://i.imgur.com/Y7icqWq.png" alt="alt text"> 

# Usage
I've made all the materials needed for the standard Animasa Miku models that come with MMD. There are 2 emd files that come with the shader: **Miku_Hatsune.emd** and **Miku_Hatsune_Ver2.emd**. You just have to apply the emd to the Animasa Miku model that share the same name with it

<img src="https://i.imgur.com/Teai9LI.png" alt="alt text"> 

- The difference between the 2 emd files is just the order of the materials. Since Animasa Miku ver1 and ver2 have slightly different material order, applying the emd wrong would mess up which fx goes to which material

# Notices
- The shader has no shadow casting
- The shader shades the model based on camera angle, **light direcion sliders don't affect it**
- There is no color blending in the shader (no toon, spa). The base, shade, and highlight colors are 3 independent colors. Which means if you changed the base color, the shade/highlight area would not change at all *(You can even make the shaded area brighter than the base)*
  - I chose this method so I could manually colorpick the base/shade/highlight color of each objects based on the original photo in A:M program, **to get the EXACT same colors**. If I used blending, I would have to investigate what kind of blending Animasa used, and make sure it produces accurate colors for every parts of the model, which is extra work that might not pay off
  
  <img src="https://i.imgur.com/53VOYva.png" alt="alt text">
  
 - Due to how the shader works *(colors are manually chosen for each object)*, the current preset *(set of fx files)* is only compatible with the Animasa Miku model. If you want to use it with other Animasa characters (Rin,Len,Kaito,...), you will have to change the color values in the fx files. It's best that you dig up a photo of that character in the A:M program (not easy, I know), and colorpick each parts, to be as accurate as possible
 
   <img src="https://i.imgur.com/iGc1vEs.jpg" alt="alt text"> 
 
    - It'd be nice if you make other presets of the shader for it to fit with other Animasa characters. If you want, you can contact me to include that preset to be an offical version of the shader, to expand the shader to not just be Miku-only
  
# Rules
✔️ Modification is allowed, you can customize the shader, or add new features to it all you want

✔️ Including the shader with the models you distribute is allowed

❌ Redistributing the shader (putting the intact shader as the main focus of the DL) is not allowed, you can link this page for the viewers to download it here

✔️ However, it's fine for you to put your modification of the shader for DL

⚠️ The shader itself is not limited to any kind of contents. **The usage limitation completely depends on the model you are going to apply the shader to**

⚠️ **I am not responsible for any damages that are caused by the use of the shader**, please consider carefully when you use the shader

🗿 Please credit me *(KH40)*, or mention the shader's name *(Ani:Masa)* when you use it, thank you

# Credits
- Shader made by: [KH40](https://twitter.com/khoast40)
- Base shader: [舞力介入P](https://www.nicovideo.jp/user/282266)
- Inspiration: [Animasa (あにまさ)](https://twitter.com/animasa2)
