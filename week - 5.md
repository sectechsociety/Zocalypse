## Week 5 – AI Perception & Behavior Tree Integration

**1. Objective**

To replace simple chase logic with a structured AI system using AI Perception and Behavior Trees.

**2. Implementation**

- Created a custom `BP_AI_Controller`
- Added `AI Perception` component for player sensing
- Used `On Target Perception Updated` event to detect stimuli
- Verified detected actor using `Actor Has Tag (Player)`
- Updated Blackboard boolean key `isSeeingPlayer`
- Initialized and ran Behavior Tree on `Begin Play`

**3. Logic Flow**

AI Perception senses player → stimulus validated → Blackboard key updated → Behavior Tree reacts.

**4. Result**

Zombie AI dynamically switches between idle and chase behavior based on player visibility.

**5. Screenshots**
<img width="1600" height="646" alt="image" src="https://github.com/user-attachments/assets/73e17ced-5cfd-43c5-9126-fef2a165279e" />

<img width="1600" height="646" alt="image" src="https://github.com/user-attachments/assets/e7db9b41-f894-401a-9aa0-f88af1928a93" />


**6. Learning Outcome**

Understood AI Perception, Blackboard communication, and Behavior Tree–based decision making.
