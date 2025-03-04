WORK IN PROGRESS DO NOT USE

A work-in-progress extension based on the ammo.js physics library, which is based on the C++ Bullet Physics SDK.

The goal is to provide feature-complete, advanced, and performant 3D physics in a simple-to-understand manner. This extension aims to be consistent with Box2D and Simple3D.

I expect several more months of work before this is ready for release, but I'm putting a Draft PR here just because I can :)

https://github.com/user-attachments/assets/ffaa1071-dea3-4bf6-b804-900e788113a1

Task list:

- [ ] All shape types:
    - [x] Boxes
    - [x] Spheres
    - [x] Cylinders
    - [x] Cones
    - [x] Capsules
    - [ ] Planes
    - [ ] Convex Hulls
    - [ ] Triangle Meshes
    - [ ] Compound bodies
- [x] Physical Materials (friction, restitution, etc.)
- [ ] Constraints (All types)
- [ ] Collision:
    - [x] Collision Detection
    - [x] Raycasting
    - [ ] Enable/disable collision response
- [ ] Manual Impact forces (like "push with force" block in Box2D)
- Player Management?
- Vehicle support?
- Soft bodies?

Miscellaneous Notes Mainly for Moderators:
- I'm trying to take a more object oriented approach that's more professional, hope this one is easier to review than my previous extensions.
- **_ChatGPT_** was used to **_assist_** and **_enhance_** the making of this extension, simply because I couldn't find good quality, coherent documentation of Ammo.js, and attempting to figure out how to use it via the developer inspector isn't fun. **_It did not write the code for me and I am still the main author of this extension._** It just helped me learn Ammo.js. Hope this doesn't cause conflicts.
- It includes multiple large (but minified) libraries... hope this isn't a problem
- Has some weird (but necessary) ESLint workarounds for Ammo initialization. Also hope this isn't a problem.
- I can't decide if this should go by Simple3D or Box2D in the gallery. If a moderator could give me some advice that'd be great. I put it by Box2D because they seem to fit into similar categories.
- I haven't made documentation, sample projects, etc. yet
- I'm not good at graphic design so if someone wants to make a banner/thumbnail that'd be great
- Still have to incorporate `Scratch.Cast` where necessary, right now I'm just working on functionality though
