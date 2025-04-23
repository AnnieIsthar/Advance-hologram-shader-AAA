# 🔥 Advance hologram shader AAA

A powerful and customizable shader for Godot 4, combining **tinting**, **edge highlights**, **dynamic scanlines**, and **RGB split glitch effects** — perfect for retro, sci-fi, or glitch-inspired visuals.

---

## ✨ Features

- 🎨 Base texture with alpha control
- 🌈 Tint blending for vibrant visuals
- 🧱 Stylized edge lighting based on view angle
- 📺 Animated scanlines with rotation and speed
- ⚡ Glitch effects with RGB split and vertex distortion
- 🛠️ Easy customization via grouped uniforms

---

## 📸 Preview

![Advanced Hologram Shader Preview](https://github.com/AnnieIsthar/Advance-hologram-shader-AAA/blob/main/Screenshots/1.png?raw=true)
![Advanced Hologram Shader Preview](https://github.com/AnnieIsthar/Advance-hologram-shader-AAA/blob/main/Screenshots/2.png?raw=true)
![Advanced Hologram Shader Preview](https://github.com/AnnieIsthar/Advance-hologram-shader-AAA/blob/main/Screenshots/3.png?raw=true)

---

### 🎬 Preview Video

[![Watch the preview on YouTube](https://img.youtube.com/vi/NN73Fr1o3rI/hqdefault.jpg)](https://www.youtube.com/watch?v=NN73Fr1o3rI)

Click the image to watch the **Advanced Hologram Shader** in action on YouTube.

---

## 🧰 Parameters

### 🎨 Base Texture
| Parameter        | Description                          |
|------------------|--------------------------------------|
| `albedo_texture` | The base texture for the surface.    |
| `albedo_alpha`   | Global alpha transparency (0.0–1.0). |

### 🌈 Tint & Edge
| Parameter         | Description                             |
|------------------|-----------------------------------------|
| `tint_color`     | Tint color with alpha.                   |
| `edge_color`     | Highlight color for edges.               |
| `edge_power`     | Curve intensity for edge detection.      |
| `edge_size`      | Size/thickness of the edge highlight.    |
| `edge_intensity` | Intensity of the edge effect.            |

### 📺 Scanlines
| Parameter             | Description                               |
|----------------------|-------------------------------------------|
| `scanline_texture`   | Optional texture for scanlines.           |
| `scanline_tint`      | Tint color for scanlines.                 |
| `scanline_intensity` | Overall intensity of scanlines.           |
| `scanline_density`   | Line density (0.0–10.0).                   |
| `scanline_thickness` | Thickness of each scanline.               |
| `scanline_spacing`   | Spacing between lines.                    |
| `scanline_angle`     | Angle in radians (0 to 2π).               |
| `scanline_speed`     | Animation speed of scanlines.             |

### ⚡ Glitch (optional)
| Parameter            | Description                                  |
|---------------------|----------------------------------------------|
| `enable_glitch`     | Toggle the glitch effect.                    |
| `glitch_intensity`  | Overall glitch strength.                     |
| `shake_power`       | Strength of vertex shaking.                  |
| `shake_rate`        | Frequency of shake activation.               |
| `shake_speed`       | Speed of the glitch animation.               |
| `shake_block_size`  | Size of affected areas.                      |
| `shake_color_rate`  | RGB split offset intensity (0.0–1.0).        |

---

## 🚀 How to Use

1. Download the file [`Advanced_Hologram.gdshader`](./Advanced_Hologram.gdshader).
2. In Godot, create a **ShaderMaterial**.
3. Assign `Advanced_Hologram.gdshader` as the shader.
4. Apply the material to any 3D mesh.
5. Adjust the shader parameters directly from the Inspector to achieve your desired look.


---

## 🛠️ Requirements

- Godot Engine 4.x+
- Compatible with 3D spatial materials

---

## 📄 License

MIT — free to use in personal, commercial, or open-source projects. Attribution is appreciated but not required.

---

## 🧠 Author

Made with ❤️ by Annastasya Isthar.  
If you enjoy it, leave a ⭐ or fork it!
