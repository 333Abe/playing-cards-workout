# playing-cards-workout
### Task List for *Playing-Cards-Workout* App

#### **1. Initial Setup**
   - [ ] Set up a Kivy project in GitHub repository.
   - [ ] Create the app's basic structure with Kivy's `App` and `ScreenManager` for navigation.

#### **2. Core Features**
   1. **Card Deck Management**:
      - [ ] Create a virtual deck of 52 playing cards.
      - [ ] Implement a shuffle function for the deck.
      - [ ] Track cards remaining and cards spent.
   2. **Exercise Assignment**:
      - [ ] Allow users to assign exercises:
        - [ ] To individual suits.
        - [ ] To card colors (red/black).
        - [ ] To specific cards.
        - [ ] To combinations of suits and colors.
      - [ ] Support multiple exercises per card.
   3. **Repetition Rules**:
      - [ ] Default reps = card value (A, K, Q, J = 10).
      - [ ] Allow setting a minimum value for all cards.
      - [ ] Allow individual card values to be overridden.
   4. **Workout Tracking**:
      - [ ] Display the current card, its exercises, and reps.
      - [ ] Show a button to "turn the card" and advance to the next.
      - [ ] Track progress by cards completed.
      - [ ] Display a target time for completing the deck.
      - [ ] Show whether the user is ahead or behind the desired speed.

#### **3. User Interface**
   - [ ] Design a main screen with:
     - [ ] Current card display.
     - [ ] Assigned exercises and reps.
     - [ ] Buttons for:
       - Turning the card.
       - Viewing remaining/spent cards.
     - [ ] Indicator for progress relative to target time.
   - [ ] Create a settings screen for:
     - [ ] Assigning exercises.
     - [ ] Adjusting rep rules (minimum values, individual overrides).
     - [ ] Setting the target completion time.
   - [ ] Include a summary screen showing workout results (time, reps, etc.).

#### **4. Timer and Speed Indicator**
   - [ ] Implement a timer to track workout duration.
   - [ ] Calculate and display whether the user is ahead or behind the desired speed.

#### **5. Data Persistence**
   - [ ] Save user settings and progress to ensure the app remembers them between sessions.

#### **6. Testing and Debugging**
   - [ ] Test the app thoroughly for different workout configurations.
   - [ ] Debug and optimize for performance.

#### **7. Stretch Goals (Optional Enhancements)**
   - [ ] Include a feature to save and load custom workout configurations.
   - [ ] Add animations for turning cards.
   - [ ] Implement a stats screen for tracking historical performance.