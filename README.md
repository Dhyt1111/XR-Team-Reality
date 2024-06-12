# Team Reality
# Stickiemaps: Enhanced Military Training with HoloLens (Defence - City Shield)

## Project Overview
Stickiemaps is a cutting-edge augmented reality application designed to enhance military training and operations. Leveraging the Microsoft HoloLens 2, our solution provides a hands-free, interactive Heads-Up Display (HUD) that allows squad commanders to access real-time information, visualise 3D maps, and manage operational data seamlessly.

## Installation Instructions

### Prerequisites
Before you begin, ensure you have the following installed:
- **Unity Hub**: [Download Unity Hub](https://unity3d.com/get-unity/download)
- **Unity Editor**: We recommend using Unity 2020.3 LTS or later. You can install it through Unity Hub.
- **Visual Studio**: For scripting in C#. Make sure to include the necessary workloads for Unity development.
- **Microsoft Mixed Reality Toolkit (MRTK)**: [Download MRTK](https://docs.microsoft.com/en-us/windows/mixed-reality/mrtk-getting-started)
- **Vuforia SDK**: [Download Vuforia](https://developer.vuforia.com/downloads/sdk)
- **Photon Unity Networking (PUN 2)**: Available in the Unity Asset Store or [Photon website](https://www.photonengine.com/en-US/PUN).

### Cloning the Repository
Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/Dhyt1111/XR-Team-Reality.git
```

### Setting Up the Project
1. Open **Unity Hub** and click on **Add** to include the cloned repository.
2. Select the folder where the Stickiemaps project is located.
3. Open the project in Unity Editor.

### Importing Dependencies
1. In Unity, go to **Window** > **Package Manager**.
2. Import the **Mixed Reality Toolkit** and **Photon PUN 2** by searching for them and clicking **Import**.
3. Download and import **Vuforia** by following the [Vuforia setup guide](https://library.vuforia.com/getting-started/getting-started-vuforia-engine-unity).
4. Ensure all necessary plugins and SDKs are correctly installed and configured.

### Building and Deploying to HoloLens 2
This application is intended to be deployed on Microsoft Hololens 2. Refer to these following steps for proper installation and documentation of how use it.
1. **Build Settings**:
   - Go to **File** > **Build Settings**.
   - Select **Universal Windows Platform** and click **Switch Platform**.
   - Set **Target Device** to **HoloLens**.
   - Ensure **Architecture** is set to **x86** or **ARM** (based on your device).
2. **Player Settings**:
   - Click on **Player Settings** in the **Build Settings** window.
   - Under **XR Settings**, check the box for **Virtual Reality Supported**.
   - Add **Windows Mixed Reality** to the list of **Virtual Reality SDKs**.
3. **Build and Run**:
   - Click **Build** and select a folder to save the build files.
   - Once the build is complete, deploy it to your HoloLens 2 device using the **Device Portal** or **Visual Studio**.

### Running the Application
1. Put on the HoloLens 2 and launch the Stickiemaps application.
2. Use the Vuforia-enabled stickers to view and interact with the 3D maps and HUD elements.
3. Navigate through the application using hand gestures and eye gaze to explore the various features.

## Development Tools Used
- **Unity**: Primary development environment for creating the AR application.
- **Vuforia**: For image recognition and generating 3D prefabs based on physical markers.
- **Microsoft HoloLens 2**: Target hardware for deployment.
- **MRTK2 (Mixed Reality Toolkit)**: This SDK provides tools and frameworks for building mixed reality experiences.
- **Photon PUN 2 (from Photon Immersal)**: Initial exploration for multiplayer functionality, though currently focused on single-user interactions.
- **Visual Studio**: For C# scripting and debugging.
- **Programming Languages**: C#, C++, JavaScript for interactive components; ShaderLab, GLSL, HLSL for visual effects.

## Licensing
The source code developed during the hackathon is open source and licensed under the [MIT License](LICENSE). Please refer to the `LICENSE` file in the repository for more details.

## Contact Information
For any queries or contributions, feel free to reach out to our team at ch0002ic@gmail.com or open an issue in the GitHub repository.
