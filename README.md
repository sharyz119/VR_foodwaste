
# VR Food Waste Experience: Embodying an Apple / Apple's Journey ?

Welcome to the **VR Food Waste Experience** project! This project explores the effects of embodying an apple in a VR environment to promote awareness and behavior change related to food waste. Users experience the journey of an apple inside a refrigerator, witnessing stages like storage, decay, and eventual disposal, from the apple’s perspective.

## Project Goals

1. **Raise Awareness**: Encourage users to adopt more sustainable food practices by experiencing the process and emotions of an apple as it deteriorates and is ultimately discarded.
2. **Explore Avatar Effects**: Investigate how embodying an inanimate object (the apple) in VR can influence empathy, awareness, and potential behavior changes in food waste reduction.
3. **Leverage VR for Behavioral Influence**: Utilize VR’s immersive nature to enhance users’ understanding of the environmental and social impacts of food waste.

## Features

- **Embody an Apple**: Users view the VR environment from within an apple, giving them a unique perspective on the journey from freshness to decay.
- **Simulated Storage and Decay**: The apple is placed in various positions within a VR refrigerator, and over time, the visual effects of decay are applied.
- **Environmental Feedback**: Users see real-time environmental feedback on their behaviors in the form of environmental visuals changing based on food waste levels.

## Project Structure

```plaintext
VR_FoodWaste_Apple_Experience/
├── Assets/
│   ├── Scripts/       # C# scripts for VR interactions and effects
│   ├── Models/        # 3D models of apple, refrigerator, and other props
│   ├── Prefabs/       # Prefab objects for easy scene setup
├── Docs/              # Literature review, design notes, and sources
├── VR_Environment/    # Unity scenes for the VR refrigerator experience
├── README.md          # Project documentation
```

## Getting Started

### Prerequisites

- **Unity 2022.3 LTS or later**: The project uses Unity as the primary development environment, required for visionOS and Apple Vision Pro support.
- **Xcode 15.2 or later**: includes the visionOS SDK.
- **Apple Vision Pro**: the primary device for this MR (mixed reality) project.
- **PolySpatial package**: Unity’s package for visionOS development.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sharyz119/VR_foodwaste.git
   cd VR_foodwaste
   ```

2. **Open in Unity**:
   - Open the project folder in Unity Hub and select the appropriate Unity version (2022.3 LTS or later).

3. **Install XR Plug-in Management**:
   - Go to `Edit > Project Settings > XR Plug-in Management` and enable visionOS under OpenXR.

4. **Add Required Packages**:
   - Add the **XR Interaction Toolkit** from the Unity Package Manager. (PolySpatial)

5. **Configure the Project**:
   - In Build Settings, set the platform to visionOS and ensure all MR-specific settings are applied.

### Usage

1. **Launch the Scene**:
   - Open the `VR_Environment/AppleExperienceScene` in Unity and play the scene in VR mode.

2. **Deploy to Vision Pro**:
   - Connect your Apple Vision Pro in Developer Mode to Mac.
   - Build and run the project on the device through Xcode.

3. **Experiment with Interactions**:
   - Move between different positions within the refrigerator as the apple. Experience the effects of decay and, eventually, disposal from the apple’s point of view.
   - Experience the journey of the apple in an MR environment. Use hand gestures for interactions and observe the real-time changes in the apple's condition.


### Project Status

This project is currently in **development**. Initial features include basic apple embodiment, simulated decay, and environmental feedback.

## Future Goals

- **Environmental Visualization**: Incorporate real-time environmental impact feedback based on user actions.
- **Enhanced Interactions**: Add interactions for users to influence the apple’s journey within the refrigerator.
- **Expanded Avatar Research**: Integrate insights from ongoing research on avatar effects to measure behavioral changes influenced by the apple embodiment.

## Contributing

...

## References

- **Proteus Effect**: Yee, N., & Bailenson, J. (2007). The Proteus Effect: The effect of transformed self-representation on behavior.
- **VR Diet Museum**: Zhang, H., & Ho, J. C. F. (2023). Exploring diet and behavior in VR environments.
- **Experiencing Nature**: Ahn, Sun Joo, et al. (2016). Embodying animals in VR to increase empathy for nature.

## License

...


