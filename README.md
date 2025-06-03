## 👶 Infant Posture Detection System for SIDS Prevention

We're developing an AI system that detects risky sleeping postures (especially "back") in infants and triggers an alert.

### 📌 Main Approaches

- **MediaPipe-based Tracking**  
  Tracks both shoulder landmarks to detect posture changes.  
  → Detects "side" when the body shifts laterally, and "back" when a full rotation is observed.  
  (Initial logic implemented and working as a basic prototype.)


- **YOLO-based Image Classification**  
  Trains a model to classify posture directly as front / side / back from images.

### 🔧 Current Progress

- Video data collected from YouTube  
- MediaPipe-based prototype implemented  
- Preparing dataset for YOLO training
