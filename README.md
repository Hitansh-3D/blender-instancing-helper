# **Instancing \& Sorting Helper for Blender**

A powerful Blender addon designed to rapidly select, instance, and organize large numbers of objects in complex scenes. This tool is optimized for performance, using an advanced caching system to provide near-instantaneous selections even with thousands of objects.



## **The Problem**

Manually selecting, linking (instancing), and sorting thousands of duplicated objects is slow, repetitive, and tedious. This addon automates the entire process with optimized, one-click solutions, saving you valuable time on large-scale projects.

## **Key Features**

* **🚀 High-Performance Caching:** The first selection builds a map of your scene. All subsequent selections are nearly instantaneous.
* **🔎 Flexible Selection Methods:**

  * **By Name:** Intelligently finds objects with the same base name (e.g., selecting Cube will also find Cube.001, Cube\_copy, etc.). Includes a case-sensitive option for precise control.
  * **By Topology:** A highly accurate method that finds objects with the exact same number of vertices, edges, and faces.

* **✅ Safe, Step-by-Step Workflow:** A clear UI to **Select**, **Link**, and **Move** objects, with each action being a separate button to prevent mistakes.
* **🗂️ Effortless Organization:** Quickly move massive selections into a designated collection in one click.

## **Installation**

1. Go to the [**Releases page**](https://github.com/Hitansh-3D/blender-instancing-helper/releases) of this repository.
2. Download the latest instancing\_helper\_vX.X.zip file.
3. In Blender, go to Edit > Preferences > Add-ons.
4. Click Install... and select the .zip file you just downloaded.
5. Enable the addon by checking the box next to "Instancing \& Sorting Helper".

## **How to Use**

1. In the 3D Viewport, press the **N** key to open the sidebar.
2. Find and click on the **"My Tools"** tab.
3. **Step 1:** Choose your target collection from the dropdown menu.
4. **Step 2:** Select a single object in your scene that you want to find duplicates of. Choose your selection method (Name or Topology) and click **"Select"**.
5. **Step 3:** The addon will highlight all similar objects. To confirm, click **"Link Selected Data"** to instance them, and then **"Move to Collection"** to organize them.

## **Author \& License**

* **Author:** [HITANSH3D](https://www.artstation.com/hitansh3dartist)
* **License:** This project is licensed under the MIT License.
