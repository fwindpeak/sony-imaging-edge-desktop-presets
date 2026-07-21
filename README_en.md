# Sony Camera & RapidRAW Presets Collection

[中文](./README.md)

---

A collection of custom image processing configuration files for Sony RAW photography and digital darkroom processing:
* `.xml` preset files tailored for **Sony Imaging Edge Desktop (Edit)**
* `.rrpreset` preset bundle files for **RapidRAW** cross-platform RAW processor

---

### Presets in this Repository

#### 1. Sony Imaging Edge Desktop Presets (`.xml`)
*   [spring.xml](./spring.xml): A fresh and lively spring-themed tone. Enhances the green channel, boosts saturation with soft lighting adjustments to bring out spring vitality.
*   [summer.xml](./summer.xml): A bright, warm summer vibe tone. It boosts clarity and saturation while adjusting the color temperature and tone curves to deliver a vibrant and warm look.
*   [autumn.xml](./autumn.xml): A warm, golden, and high-contrast autumn tone. It increases red and yellow saturation and tweaks red/blue curves to yield a nostalgic golden hour look.
*   [winter.xml](./winter.xml): A cold, clean, and crisp winter tone. Reduces overall saturation, adds a cold blue cast to shadows, and controls highlights for a snowy winter aesthetic.
*   [fl2.xml](./fl2.xml): **FL2 Simulation (Suitable for older cameras like A7C2)**. Built on top of the native FL base look, it boosts contrast, lowers saturation, deepens shadows, and adjusts red/blue tone curves to emulate the heavy, nostalgic filmic aesthetic of FL2 from newer camera models.

#### 2. RapidRAW Presets ([all_presets.rrpreset](./rapidraw-presets/all_presets.rrpreset))
Designed for **RapidRAW**, including custom tuned styles and featured community presets:

*   **Featured & Custom Presets:**
    *   **日系小清新 (Japanese Clean Tone)**: Crisp and bright cool tone. Boosts shadows & exposure, lowers highlights, adds blue teal tones in shadows for clean portraits and scenery.
    *   **人文浓郁对比 (Street Rich Contrast)**: High clarity and high contrast street documentation style. Deep shadows with warm highlight/midtone color grading for depth and storytelling.
    *   **人文室内 (Indoor Documentary)**: Optimized for low-light/indoor documentary shots. Boosts shadows and exposure slightly while keeping natural warm tones and sharp details.
    *   **Summer Days**: Warm sun-drenched summer film aesthetic with warm color temperature, color grading, and subtle film grain.
*   **Community Presets Group:**
    *   **Cinematic**: Cinematic grade with teal blue shadows, warm midtones, and rich tonality.
    *   **Vintage Film**: Classic vintage film style with soft contrast, desaturated tones, and organic grain.
    *   **Urban Teal & Orange**: Vibrant street style with high contrast and iconic teal/orange color separation.
    *   **Moody Forest**: Dark, moody forest aesthetic with subdued saturation and cool blue shadows.
    *   **Film Inspired P400UC _rev2**: Kodak Portra 400UC inspired look with high exposure, soft highlights, and fine film grain.
    *   **Hyper exposed**: High-key exposure style with strong contrast and warm midtones.
    *   **AVOR - Dynamic Velvia**: Emulates classic Fujifilm Velvia with vivid colors, strong dynamic response, and rich shadows/highlights.
    *   **ARP Fizz**: Soft retro look with fine grain and warm highlight casts.

---

### How to Use

#### 📷 Using Sony Imaging Edge Desktop Presets (`.xml`)

##### 1. Applying a Preset to a Single Image
To apply one of the presets to an active photo in the **Edit** application:
1. Open your RAW photo (`.ARW`) in the **Edit** window of Imaging Edge Desktop.
2. From the menu bar, navigate to **[Edit]** > **[Image Processing Settings]** > **[Load and Apply Settings...]**.
3. Select the desired preset file (e.g., [summer.xml](./summer.xml)) and click **[Open]**. The settings will be applied immediately.

##### 2. Batch Applying Presets to Multiple Images
To apply a preset to multiple photos during export:
1. In the **Viewer** application, select all the images you want to apply the settings to.
2. Click the **[Output]** (or **[Export]**) icon in the toolbar, or go to **[File]** > **[Output...]**.
3. In the export settings window, check the box for **[Apply the selected image processing settings to each RAW file]**.
4. Click **[Browse...]** next to the settings field, select your downloaded `.xml` preset file, and click **[Continue]** to run the batch output.

##### 3. Copying & Pasting Parameters
If you want to copy settings between images without saving a file:
*   **Copy:** In the **Edit** window, display the adjusted image and go to **[Edit]** > **[Image Processing Settings]** > **[Copy]** (or press `Cmd + C` / `Ctrl + C`).
*   **Paste:** Select the target image and go to **[Edit]** > **[Image Processing Settings]** > **[Paste]** (or press `Cmd + V` / `Ctrl + V`).

##### 4. Saving Your Own Presets
To save your own adjustments as a preset file:
*   Click the dropdown arrow next to the **[Save]** (disk) icon in the toolbar of the **Edit** window and select **[Save image processing settings]**.
*   *Alternatively*, go to **[Edit]** > **[Image Processing Settings]** > **[Save...]**, choose a folder, name your preset, and save.

---

#### 🚀 Using RapidRAW Presets (`.rrpreset`)

1. Open **RapidRAW** application.
2. Go to the **Presets** panel.
3. Click the **[Import / 导入预设]** button.
4. Choose [all_presets.rrpreset](./rapidraw-presets/all_presets.rrpreset) from this repository.
5. Once imported, you can preview and apply any of the presets with a single click.
