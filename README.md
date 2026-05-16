# Burj Khalifa Digital Experience (2026)

> ⚠ **Status: Work In Progress (WIP)** > This project is currently under active development. Some features might be incomplete, and the code structure is continuously being refactored for performance and scalability.

An immersive 3D interactive web experience featuring the Burj Khalifa, built using Next.js, React Three Fiber, and Three.js.

## Built With
- **Framework:** Next.js (App Router)
- **3D Graphics:** Three.js / React Three Fiber (@react-three/fiber)
- **Helpers & Controls:** @react-three/drei (ScrollControls, MeshTransmissionMaterial)
- **Styling:** Tailwind CSS
- **Language:** TypeScript

## Roadmap & Progress
- [x] Integrate 3D Burj Khalifa generative geometry.
- [x] Implement smooth smooth scrolling interpolation (`damp`).
- [x] Separate 3D logic (`BurjModel.tsx`) from UI display (`InfoScene.tsx`).
- [x] Support bi-directional text animations (Arabic from Right, English from Left).
- [x] Implement seamless Day/Night transition cycle based on scroll position.
- [x] Optimize 3D assets and shaders for production build.
