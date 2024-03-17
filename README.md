
![工作流合集封面](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/9127e40b-4014-49f0-a1e6-738f0dab0572)


<div align="center">
   
# ComfyUI Workflows ZHO
   
我的 ComfyUI 工作流合集 | My ComfyUI workflows collection


<div align="left">

## 目录（14类 36项）

- [1️⃣ Stable Cascade（4）](#1️⃣-stable-cascade4)
- [2️⃣ 3D（3）](#2️⃣-3d3)
- [3️⃣ LLM + SD（5）](#3️⃣-llm--sd5)
- [4️⃣ Differential Diffusion（2）](#4️⃣-differential-diffusion2)
- [5️⃣ YoloWorld-EfficientSAM（2）](#5️⃣-yoloworld-efficientsam2)
- [6️⃣ Portrait Master 简体中文版（4）](#6️⃣-portrait-master-简体中文版4)
- [7️⃣ ArtGallery | Prompt Visualization（1）](#7️⃣-artgallery--prompt-visualization1)
- [8️⃣ InstantID-ZHO（3）](#8️⃣-instantid-zho3)
- [9️⃣ PhotoMaker-ZHO（5）](#9️⃣-photomaker-zho5)
- [1️⃣0️⃣ SVD-ZHO（1 WIP）](#1️⃣0️⃣-svd-zho1-wip)
- [1️⃣1️⃣ I2VGenXL（2）](#1️⃣1️⃣-i2vgenxl2)
- [1️⃣2️⃣ More Models（2）](#1️⃣2️⃣-more-models2)
- [1️⃣3️⃣ TravelSuite-ZHO（1）](#1️⃣3️⃣-travelsuite-zho1)
- [1️⃣4️⃣WordCloud（1）](#1️⃣4️⃣-wordcloud1)





## 1️⃣ Stable Cascade（4）

![Dingtalk_20240317192159](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/d87ef742-5250-4bfd-92d1-27d4a373aa82)


<details>
<summary>展开 | Expand</summary>

### 1) [Stable Cascade Standard](https://drive.google.com/file/d/1L0A7yHrE4KeqvNAzm1vjMqNpLMGyUnsA/view?usp=sharing)

   ![Dingtalk_20240317182319](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/7865009d-227d-4912-91f8-6a8a03f61c0b)


### 1) [Stable Cascade Canny ControlNet](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/blob/main/Stable%20Cascade%20Canny%20ControlNet%E3%80%90Zho%E3%80%91.json)

   ![SCCN](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/c59819b9-bf43-4b80-822e-3001b7141232)


### 2) [Stable Cascade Inpainting ControlNet](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/blob/main/Stable%20Cascade%20Inpainting%20ControlNet%E3%80%90Zho%E3%80%91.json)

   ![SCCN2](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/5306a1d4-f634-46d0-ada7-ffef74b42ddc)

### 3) [Stable Cascade Img2Img](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/blob/main/Stable%20Cascade%20Img2Img%E3%80%90Zho%E3%80%91.json)

   ![Dingtalk_20240308004442](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/4a59b45a-1166-47d3-8981-590591dfe68a)

</details>


## 2️⃣ 3D（3）

![S232](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/641a10bf-d82a-40e7-8672-e046f37ba1fe)


<details>
<summary>展开 | Expand</summary>
   
### 1) [CRM Comfy 3D](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/blob/main/CRM%20Comfy%203D%E3%80%90Zho%E3%80%91.json)
   
   [Colab：Comfy 3D](https://colab.research.google.com/drive/17hsO4_ktv_g8-NQhMU3MCV_iXSXB3cWT?usp=sharing)
   
   ![C3DCOLAB](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/0c36da32-7147-44d6-b36c-c77e0d26be68)

### 2) [Sketch to 3D](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/blob/main/Sketch%20to%203D%E3%80%90Zho%E3%80%91.json)

   ![Dingtalk_20240316231428](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/69c12f87-cc72-49ae-96fb-c7b4de215fa4)
   
   https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/153b6e8e-7567-4e2b-aa90-bc8ea3544523

   【Sketch to 3D】使用说明：
   
   - 使用模型：
      - [Playground v2.5](https://huggingface.co/playgroundai/playground-v2.5-1024px-aesthetic)
      - [ControlNet](https://huggingface.co/diffusers/controlnet-canny-sdxl-1.0)

   - 使用插件：
      - 草图画板：[AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
      - 背景去除：[BRIA_AI-RMBG](https://github.com/ZHO-ZHO-ZHO/ComfyUI-BRIA_AI-RMBG)
      - TripoSR 3D生成：[TripoSR-ZHO](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Flowty-TripoSR-ZHO)

### 3) [LayerDIffusion + TripoSR V1.0](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Flowty-TripoSR-ZHO/blob/master/TRIPOSR-ZHO%20WORKFLOWS/NEW%20V1.0%20LayerDIffusion%20%2B%20TripoSR%E3%80%90Zho%E3%80%91.json)

   ![Dingtalk_20240309193351](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Flowty-TripoSR-ZHO/assets/140084057/99f1f03b-6873-42f1-ba7b-03082aa043d6)

   - 使用插件：
      - [LayerDIffusion](https://github.com/huchenlei/ComfyUI-layerdiffuse)
      - [TripoSR-ZHO](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Flowty-TripoSR-ZHO)

</details>


## 3️⃣ LLM + SD（5）

![Dingtalk_20240130191521](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Qwen-VL-API/assets/140084057/5d10adba-90a6-48e0-94de-33d10b5d32f9)


<details>
<summary>展开 | Expand</summary>
   
### 1) [Qwen-VL V1.0](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Qwen-VL-API)

   ![Dingtalk_20240130200115](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Qwen-VL-API/assets/140084057/bae0447b-a4bf-45a3-ad27-c496a02bd6d2)

### 2）[Gemini-pro](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Gemini/blob/main/Gemini_workflows/Gemini-pro%E3%80%90Zho%E3%80%91.json) 

   ![Dingtalk_20231220183708](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Gemini/assets/140084057/7f0e222a-2de4-4c5b-883a-2172667d1d5b)

### 3）[Genimi-pro-vision](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Gemini/blob/main/Gemini_workflows/Gemini-pro-vision%E3%80%90Zho%E3%80%91.json)

   ![Dingtalk_20231220192932](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Gemini/assets/140084057/db4f4bf6-a0cf-42af-ac5a-7e2afd1bda93)

### 4）[Gemini-pro Chatbot](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Gemini/blob/main/Gemini_workflows/Gemini-pro%20Chatbot%E3%80%90Zho%E3%80%91.json)

   ![image](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Gemini/assets/140084057/8a38f437-0148-4777-b872-e88995dd53d2)

### 5) [All-in-One LoRa Training](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Gemini/blob/main/Gemini_workflows/All-in-One%20LoRa%20Training%E3%80%90Zho%E3%80%91.json)

   https://github.com/ZHO-ZHO-ZHO/ComfyUI-Gemini/assets/140084057/d461f656-6888-48a8-b4f8-b70b7e46504d


</details>


## 4️⃣ [Differential Diffusion](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Differential_Diffusion-Workflows)（2）

![DD封面图](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Differential_Diffusion-Workflows/assets/140084057/5b47d771-c057-4c01-8b38-c74f3ae60441)


<details>
<summary>展开 | Expand</summary>

### 1）[简单 DD 重绘 | Simple Inpainting with Differential Diffusion](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Differential_Diffusion-Workflows/blob/main/Differential%20Diffusion%20Workflows/Playground2.5%2BDifferential%20Diffusion%E3%80%90Zho%E3%80%91.json)

   ![Dingtalk_20240304191711](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Differential_Diffusion-Workflows/assets/140084057/14655d3b-2282-4f7d-b047-eb57a21af2d4)


### 2）[文生图 + DD 重绘 | Text2Image + Inpainting with Differential Diffusion](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Differential_Diffusion-Workflows/blob/main/Differential%20Diffusion%20Workflows/T2I%2BPlayground2.5%2BDifferential%20Diffusion%E3%80%90Zho%E3%80%91.json)

   ![Dingtalk_20240304195830](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Differential_Diffusion-Workflows/assets/140084057/67d9b424-346d-4077-9abb-45ffd24e8193)

</details>


## 5️⃣ [YoloWorld-EfficientSAM](https://github.com/ZHO-ZHO-ZHO/ComfyUI-YoloWorld-EfficientSAM)（2）

![ywes_](https://github.com/ZHO-ZHO-ZHO/ComfyUI-YoloWorld-EfficientSAM/assets/140084057/fff48236-8feb-48d6-946e-ba429111427f)


<details>
<summary>展开 | Expand</summary>

### 1) [V2.0 图片检测+分割](https://github.com/ZHO-ZHO-ZHO/ComfyUI-YoloWorld-EfficientSAM/blob/main/YOLO_World_EfficientSAM_WORKFLOWS/YoloWorld-EfficientSAM%20V2.0%20IMG%20%E3%80%90Zho%E3%80%91.json)

   ![Dingtalk_20240224154535](https://github.com/ZHO-ZHO-ZHO/ComfyUI-YoloWorld-EfficientSAM/assets/140084057/c23e6a1a-28e7-4612-afde-256f9b782051)


### 2) [V2.0 视频检测+分割](https://github.com/ZHO-ZHO-ZHO/ComfyUI-YoloWorld-EfficientSAM/blob/main/YOLO_World_EfficientSAM_WORKFLOWS/YoloWorld-EfficientSAM%20V2.0%20VIDEO%20%E3%80%90Zho%E3%80%91.json)

   ![Dingtalk_20240317184123](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/d0e1e2d8-49e7-4398-aad2-94e9f94414dd)


</details>


## 6️⃣ [Portrait Master 简体中文版](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn)（4）


![Dingtalk_20231221171244](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/assets/140084057/f14a31f6-56f0-4e3e-9bf0-5a7a209175bd)


<details>
<summary>展开 | Expand</summary>

### 1) [V2.2 For SD1.5 or SDXL](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/blob/main/workflows/Portrait%20Master%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E7%89%88%20V2.2%E3%80%90Zho%E3%80%91.json)

  ![Dingtalk_20231221171315](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/assets/140084057/f36c43f7-5381-470b-a5f5-8abed834e2e2)

### 2) [V2.0 For SD1.5 or SDXL](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/blob/main/workflows/Portrait%20Master%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E7%89%88%20V2.0%E3%80%90Zho%E3%80%91.json)

  ![Dingtalk_20231218163927](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/assets/140084057/606e1ef4-429c-4f8d-99fb-0a19f2350d0e)

### 3) [V2.0 For SDXL Turbo（non-commercial）](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/blob/main/workflows/Portrait%20Master%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E7%89%88%20SDXL%20Turbo%20V2.0%E3%80%90Zho%E3%80%91.json)

  ![Dingtalk_20231218165449](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/assets/140084057/e0b188af-7d0a-47b8-8327-13dd630cea91)

### 4) [V2.0 for SAG + SVD 视频工作流](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/blob/main/workflows/Portrait%20Master%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E7%89%88%20V2.0%20%2B%20SAG%20%2B%20SVD%E3%80%90Zho%E3%80%91.json)

https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/assets/140084057/8e3915be-2d45-4f94-af0c-0a270378712b

![Dingtalk_20231218185612](https://github.com/ZHO-ZHO-ZHO/comfyui-portrait-master-zh-cn/assets/140084057/e9316a7a-dbe5-4e20-bd50-1e622551c7ab)

</details>


## 7️⃣ [ArtGallery | Prompt Visualization](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ArtGallery)（1）

![artgallery新项目图](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ArtGallery/assets/140084057/e7f2fde4-d138-4f32-80d1-50cda798992a)


<details>
<summary>展开 | Expand</summary>

### 1) [V1.0 For SD1.5 or SDXL](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ArtGallery/blob/main/ArtGallery%20Workflows/ArtGallery%20V1.0%E3%80%90Zho%E3%80%91.json)

  ![ArtGallery](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ArtGallery/assets/140084057/bd3673b6-16b0-46ee-92ee-6b5ebf446bb5)

</details>


## 8️⃣ [InstantID-ZHO](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID)（3）

![ISID_](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID/assets/140084057/01393483-3145-4691-9daa-7ce9035c9bd0)


<details>
<summary>展开 | Expand</summary>

### 1) [V2.0 InstantID_pose_ref + ArtGallery](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID/blob/main/INSTANTID%20WORKFLOWS/V2.0%20InstantID_pose_ref%20%2B%20ArtGallery%20%E3%80%90Zho%E3%80%91.json)

  ![Dingtalk_20240124232833](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID/assets/140084057/99be9592-775d-4c33-bafc-5bd5c95a7222)


### 2) [V2.0 自动下载 huggingface hub](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID/blob/main/INSTANTID%20WORKFLOWS/V2.0%20InstantID_fromhub_pose_ref%E3%80%90Zho%E3%80%91.json)

  ![Dingtalk_20240124230145](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID/assets/140084057/95c4a1dd-864d-4a46-8c45-a48866aef29f)


### 3) [V2.0 InstantID_locally_pose_ref](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID/blob/main/INSTANTID%20WORKFLOWS/V2.0%20InstantID_locally_pose_ref%E3%80%90Zho%E3%80%91.json)

  ![Dingtalk_20240124230609](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID/assets/140084057/d4c22389-f853-44bd-9ea2-568b2ac7ed06)

</details>


## 9️⃣ [PhotoMaker-ZHO](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker-ZHO)（5）

![Dingtalk_20240117201201](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker/assets/140084057/6bbcfcf9-9027-4c6f-9be1-750971b7848c)


<details>
<summary>展开 | Expand</summary>

### 1) [V2.5 Disney-Character_PhotoMaker + DragNUWA](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker/blob/main/PhotoMaker%20Workflows/Disney-Character_PhotoMaker%2BDragNUW%E3%80%90Zho%E3%80%91.json) 🆕

  https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker/assets/140084057/ca2bfff4-701c-4960-ac11-b893f90c044c


### 2) [V2.5 lora + batch](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker/blob/main/PhotoMaker%20Workflows/PhotoMaker_lora_batch%E3%80%90Zho%E3%80%91.json) 🆕

  ![Dingtalk_20240119202403](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker/assets/140084057/b862b89f-1609-43d9-84a1-5f11a2d1ab2d)


### 3) [V2.5 portraitmaster + styler + lora](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker/blob/main/PhotoMaker%20Workflows/PhotoMaker_lora_portrait_styler%E3%80%90Zho%E3%80%91.json) 🆕

  ![Dingtalk_20240119201125](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker/assets/140084057/38e01035-139e-4a89-8982-6f7168684045)

### 4) [V2.5 本地模型 locally](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker/blob/main/PhotoMaker%20Workflows/V2.5%20PhotoMaker_locally%E3%80%90Zho%E3%80%91.json)

### 5) [V2.5 自动下载 huggingface hub](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PhotoMaker/blob/main/PhotoMaker%20Workflows/V2.5%20PhotoMaker_fromhub%E3%80%90Zho%E3%80%91.json)


</details>


## 1️⃣0️⃣ [SVD-ZHO](https://github.com/ZHO-ZHO-ZHO/ComfyUI-SVD-ZHO)（1 WIP）

![SVD11_](https://github.com/ZHO-ZHO-ZHO/ComfyUI-SVD-ZHO/assets/140084057/687ef467-ac9e-476a-b161-9e6f3b989220)


<details>
<summary>展开 | Expand</summary>

### 1) SVD1.1(WIP)

  ![Dingtalk_20240204195736](https://github.com/ZHO-ZHO-ZHO/ComfyUI-SVD-ZHO/assets/140084057/93ba4ae8-7dff-4084-b5b0-b60ddf34a010)

</details>


## 1️⃣1️⃣ [I2VGenXL](https://github.com/ZHO-ZHO-ZHO/ComfyUI-I2VGenXL)（2）

![I2V_](https://github.com/ZHO-ZHO-ZHO/ComfyUI-I2VGenXL/assets/140084057/3d2acebe-b4b4-417a-8257-427b3fd33680)


<details>
<summary>展开 | Expand</summary>

### 1)[V1.0 Standard 标准版](https://github.com/ZHO-ZHO-ZHO/ComfyUI-I2VGenXL/blob/main/I2VGENXL%20WORKFLOWS/I2VGENXL_Standard%E3%80%90Zho%E3%80%91.json)
  
  ![Dingtalk_20240206191614](https://github.com/ZHO-ZHO-ZHO/ComfyUI-I2VGenXL/assets/140084057/05c9a690-110b-4f42-b4a3-aa8f7a0f3e3f)

### 2)[V1.0 Simple 基础版](https://github.com/ZHO-ZHO-ZHO/ComfyUI-I2VGenXL/blob/main/I2VGENXL%20WORKFLOWS/I2VGENXL_Simple%E3%80%90Zho%E3%80%91.json)

  ![Dingtalk_20240206193817](https://github.com/ZHO-ZHO-ZHO/ComfyUI-I2VGenXL/assets/140084057/d33f3238-d6ad-4e00-b1de-a36f156e7485)

</details>


## 1️⃣2️⃣ More Models（2）

![PA封面图](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PixArt-alpha-Diffusers/assets/140084057/cd5f98a2-baa4-4825-8dd9-132559f7dc04)


<details>
<summary>展开 | Expand</summary>

### 1）[PixArtAlpha Standard V1.0](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PixArt-alpha-Diffusers/blob/main/PixArtAlpha%20Workflows/PixArtAlpha%20Standard%E3%80%90Zho%E3%80%91.json)

   ![Dingtalk_20240308211946](https://github.com/ZHO-ZHO-ZHO/ComfyUI-PixArt-alpha-Diffusers/assets/140084057/d372554e-bb5b-4f34-9480-47d4629c8a96)

### 2) [V1.0 SegMoE](https://github.com/ZHO-ZHO-ZHO/ComfyUI-SegMoE/blob/main/SEGMOE%20WORKFLOWS/SegMoE%20V1.0%E3%80%90Zho%E3%80%91.json)
  
  ![Dingtalk_20240205034132](https://github.com/ZHO-ZHO-ZHO/ComfyUI-SegMoE/assets/140084057/f09b11b1-1259-4f99-9870-c092dd7348c1)


</details>


## 1️⃣3️⃣ [TravelSuite-ZHO](https://github.com/ZHO-ZHO-ZHO/ComfyUI_TravelSuite_Zho)（1）

![Dingtalk_20240317191556](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/f6e2b10c-054f-41e6-aee4-922e57c3b8ad)


<details>
<summary>展开 | Expand</summary>
   
### 1）[Latent_travel_workflow【Zho】.json](https://github.com/ZHO-ZHO-ZHO/ComfyUI_TravelSuite_Zho/files/13271012/Latent_travel_workflow.Zho.json)

  ![9b2a5aa4875c678c95da6ffd80fb5512](https://github.com/ZHO-ZHO-ZHO/ComfyUI_TravelSuite_Zho/assets/140084057/829b7730-4579-4575-8f3a-f873062a58b0)

### 2）[Latent_travel_compare2composite_workflow【Zho】.json](https://github.com/ZHO-ZHO-ZHO/ComfyUI_TravelSuite_Zho/files/13271090/Latent_travel_compare2composite_workflow.Zho.json)

  ![image](https://github.com/ZHO-ZHO-ZHO/ComfyUI_TravelSuite_Zho/assets/140084057/6ca11fbb-a5b0-41e0-8f1a-d6edd990239a)

</details>


### 1️⃣4️⃣ WordCloud（1）

![Dingtalk_20240317192659](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/a3e8d91f-1709-4df2-849b-90598e20a43e)


<details>
<summary>展开 | Expand</summary>

### 1)[WordCloud](https://drive.google.com/file/d/1vKbZAnaaA9CTVVvTEIip4rNRrBtAs0Tn/view?usp=sharing)

  ![Dingtalk_20240317192616](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO/assets/140084057/ecbc3706-d762-4591-ba35-3f897bd08549)


</details>



## 更新日志

- 20240316

  整理我之前所有已公开的工作流，共 14 大类，36 个工作流

- 20240316

  新增 LayerDIffusion + TripoSR V1.0 工作流

  新增 Sketch to 3D 工作流 + 使用说明

- 20240314

  新增 CRM Comfy 3D 工作流 + Comfy 3D Colab 云部署
  
- 20240307

  新增 Stable Cascade Img2Img 工作流

- 20240307

  新增 Stable Cascade Inpainting ControlNet 工作流

- 20240306

  新增 Stable Cascade Canny ControlNet 工作流

  创建项目 


## Stars 

[![Star History Chart](https://api.star-history.com/svg?repos=ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO&type=Date)](https://star-history.com/#ZHO-ZHO-ZHO/ComfyUI-Workflows-ZHO&Date)
