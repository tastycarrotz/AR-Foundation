# WhiskersBomb

Augmented Reality app for Android built with Unity and AR Foundation. It demonstrates plane detection, image tracking and occlusion.

## Installation

1. Go to the Releases page of this repository.
2. Download the APK and install it on an Android device compatible with ARCore (for the oclusion to happen).
3. Print or open on a screen the tracking images PDF (also in the Release) to test Activity 2.

## Usage

- **Activity 1 – Plane Detection:** Point the camera towards any flat surface to reveal your enemy
- **Activity 2 – Image Tracking:** Point the camera towards the provided images in order to trigger the appearance of a mysterious object that will help you
- **Activity 3 – Occlusion:** Tap on the screen to launch a bomb into the real world, you can now attack your enemy!

## Contributing

- Florencia Elorza: Activity 1 (anchors addition, documentation)
- Laura Garriga: Activity 2 (AR image tracking, reference image library, documentation)
- Emma Vega: Activity 3 (occlusion scene, ball prefab, documentation)

## History

The integration of plane detection and instantiation of a 3D model (cat) on a detected plane. The addition of a reference image library of 3 different images and an AR tracked image manager component to the project. The library is referenced with a new prefab of the 3D model of a bomb. Additionally the use of simple occlusion to throw that same bomb into the air that will disappear behind real objects. 


## Credits

Based on the Unity AR Foundation samples (branch 6.4): https://github.com/Unity-Technologies/arfoundation-samples

## License

"Academic project"

