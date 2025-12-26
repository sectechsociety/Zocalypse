## Week 4 – Zombie Chase & Attack Logic

**1. Objective**

To make zombies chase the player and perform controlled attacks.

**2. Implementation**

- Created a custom `Chase Player` event  
- Used `AI Move To` with player as the target actor  
- Added a `CanAttack` boolean to control attack state  
- Played zombie attack animation using Animation Montage  
- Reset attack state after montage completion or interruption  

**3. Logic Flow**

Zombie detects player → chases player → checks attack condition → plays attack animation.

**4. Result**

Zombie continuously chases the player and attacks when within range.

**5. Screenshots**

![WhatsApp Image 2025-12-26 at 23 04 20](https://github.com/user-attachments/assets/14dfb2a9-4289-42f6-9d4b-1eede47e8a5f)
![WhatsApp Image 2025-12-26 at 23 04 18](https://github.com/user-attachments/assets/8023fd4c-589d-4aaf-a374-329d2371453b)
![WhatsApp Image 2025-12-26 at 23 04 26](https://github.com/user-attachments/assets/eddea495-fc06-4c2d-87c9-18ba4781ce5b)
<img width="1142" height="613" alt="image" src="https://github.com/user-attachments/assets/fef651a4-05ee-4b30-96e3-5a0d6f9732a1" />


**6. Learning Outcome**

Learned AI chasing logic, animation montages, and state-based attack control.
