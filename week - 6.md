## Week 6 – Advanced AI Behavior & Gameplay Validation

**1. Objective**

To implement multiple AI states and validate zombie behavior inside the playable FPS environment.

**2. Implementation**

- Designed Selector-based Behavior Tree architecture
- Implemented `Wonder Sequence` when player is not detected
- Implemented `Chase Sequence` when `isSeeingPlayer` is set
- Created custom Behavior Tree tasks:
  - `BT_Task_Wonder`
  - `BT_Task_ChasePlayer`
- Used Wait nodes for realistic idle behavior
- Tested AI logic with multiple zombies simultaneously

**3. Logic Flow**

Player not visible → zombie wanders → player detected → chase task activates → continuous pursuit.

**4. Result**

Multiple zombies intelligently wander and chase the player in real time.

**5. Screenshots**

<img width="1600" height="757" alt="image" src="https://github.com/user-attachments/assets/a6d76a55-3d66-497a-b9a4-8917c511f1cf" />

<img width="1600" height="721" alt="image" src="https://github.com/user-attachments/assets/1c6b4ed5-ba89-453c-a90a-f6475fbfd303" />

<img width="1600" height="676" alt="image" src="https://github.com/user-attachments/assets/3589ebe2-1826-4057-b6f8-86291508339f" />


**6. Learning Outcome**

Gained hands-on experience with scalable AI design and real-time gameplay validation.
