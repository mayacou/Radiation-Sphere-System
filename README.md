# Radiation Sphere System

The **Radiation Sphere System** is a portable Unity package that simulates a customizable radiation zone with interactive features such as toggling visibility, adjusting activity levels, and warnings for entering the radiation zone. This system is compatible with the **Built-In Render Pipeline** or **Universal Render Pipeline (URP)**.

---

## Features

- **Customizable Radiation Zone**:
  - Toggle the sphere's visibility on and off.
  - Adjust the activity level with a slider or input field.
  - Trigger warnings and effects when entering the radiation zone.

- **Interactive Warning System**:
  - Red haze overlay and warning text are displayed when inside the radiation zone.
  - Automatic adjustment based on sphere visibility.

---

## Requirements

- **Unity Version**: 6000.0.32.
- **Render Pipeline**: Built-In Render Pipeline or Universal Render Pipeline (URP).
- **Mixed Reality Toolkit (Optional)**: For XR/VR support.

---

## Setup Instructions

### Step 1: Create a New Project
1. Open **Unity Hub**.
2. Create a new project:
   - Template: **3D (Universal Render Pipeline)** or **3D Core**.
   - Name the Project
3. Open the newly created project.

### Step 2: Import the Package
1. Download and save the **Radiation Sphere System** package (`RadiationSphereSystem.unitypackage`).
2. In Unity, go to `Assets > Import Package > Custom Package...`.
3. Select the package file and click **Import**. Ensure all assets are selected in the import dialog.

### Step 3: Adjust the Camera
1. Select the **Main Camera** in the Hierarchy.
2. Add the following components: *Adjust settings to fit your project*
   - **Rigidbody**:
     - Uncheck **Use Gravity**. (if needed)
     - Check **Is Kinematic**.
   - **Box Collider**:
     - Check **Is Trigger**.

---

## Notes
- The **Red Haze Panel** must have **Raycast Target** unchecked in the Image component.
- Material Compatible with Unity's **Built-In Render Pipeline** or **URP**.

---
