## Week 3 – Material Setup & AI Detection

**1. Objective**

To create weapon materials and enable zombie AI to detect the player.

**2. Implementation**

- Created weapon material using Base Color and Normal maps  
- Configured Pawn Sensing component for zombie AI  
- Used `On See Pawn` event for player detection  
- Casted detected pawn to `BP_FirstPersonCharacter`  
- Triggered movement using `AI Move To`

**3. Logic Flow**

Zombie senses player → pawn is validated → AI moves toward player.

**4. Result**

Zombie successfully detects and starts moving toward the player.

**5. Screenshots**

<img width="1600" height="688" alt="image" src="https://github.com/user-attachments/assets/9e2b96c2-c2eb-4fd3-9fb6-fcd10e681555" /> 

<img width="1600" height="757" alt="image" src="https://github.com/user-attachments/assets/f050f462-19fa-4188-9627-612960c562db" />

**6. Learning Outcome**

Understood material graphs, Pawn Sensing, and basic AI navigation.


