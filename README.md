# Ani:Masa
MMD shader that is specifically made for Animasa Miku model to recreate how it originally looked like in Animation:Master (A:M) program, before being ported to MMD

# Notices
- The shader has no shadow casting
- The shader shades the model based on camera angle, light direcion sliders don't affect it
- There is no color blending in the shader. The base, shade, and highlight colors are 3 independent colors. Which means if you changed the base color, the shade/highlight area would not change at all *(You can even make the shaded area brighter than the base)*
  - I chose this method so I could manually colorpick the base/shade/highlight color of each objects based on the original photo in A:M program, **to get the EXACT same colors**. If I used blending, I would have to investigate what kind of blending Animasa used, and make sure it produces accurate colors for every parts of the model, which is extra work that I don't want to deal with
 - Due to how the shader works, it's only compatible with the Animasa Miku model. If you want to use it with other Animasa characters (Rin,Len,Kaito,...), you will have to change the color values of the .fx(s). It's best that you find a photo of that character in the A:M program, and colorpick each parts, to be accurate
    - It'd be nice if you make preset of the shader for it to fit with other Animasa characters. If you want, you can contact me to include that preset to be an offical version of the shader, to expand the shader to not just Miku-only
  
# Rules
✔️ Modification is allowed, you can customize the shader, or add new features to it all you want.

✔️ Including the shader with the models you distribute is allowed.

❌ Redistributing the shader (putting the intact shader as the main focus of the DL) is not allowed, you can link this page for the viewers to download it here.

✔️ However, it's fine for you to put your modification of the shader for DL.

⚠️ The shader itself is not limited to any kind of contents. **The usage limitation completely depends on the model you are going to apply the shader to.**

⚠️ **I am not responsible for any damages that are caused by the use of the shader**, please consider carefully when you use the shader.

🗿 Please credit me, or mention the shader's name when you use it, thank you

# Credits
- Base shader: 舞力介入P
- Shader editing: KH40
- Inspiration: Animasa (あにまさ)
