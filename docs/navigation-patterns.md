# **Navigation Patterns**

Navigation is crucial in XR, ensuring **comfort, accessibility, and efficiency**. This section covers different movement techniques and menu placement strategies.
We will also list down the navigation patterns along with its use cases:
## **Navigation Types**
=== "Residue"
    - Residue navigation involves leaving a faint, traceable path (visual, auditory, or tactile) that users have already traversed.
    !!! success "Key Point" 
        It helps users understand where they’ve been, improving spatial orientation and ensuring a sense of progress in large or complex navigation systems
=== "Contextual Path Highlighting"
    - The path ahead is highlighted based on context, such as brighter arrows for immediate turns or larger arrows for distant but critical landmarks.
    !!! success "Key Point"
        Ensures users prioritize the right actions at the right time
=== "Pulsating Arrows"
    - Arrows that gently pulse or animate to draw attention to the correct path without being overly distracting
    !!! success "Key Point" 
        Works well in low-visibility or high-distraction environments, ensuring users notice the guidance
## **Locomotion Methods**
!!! info "**Teleportation**"
    - Best for **reducing motion sickness**.
    - Uses an arc-based pointer for destination selection.

!!! info "**Movement Provider**"
    - Joystick-controlled movement similar to traditional games.
    - Can cause motion sickness — **recommended to use vignette effects to reduce discomfort.**

!!! info "**Continuous Turn Provider**"
    - Enables **continuous rotation**, more fluid in terms of interaction and immersiveness.
    !!! Warning "May cause motion sickness"


!!! info "**Snap Turn Provider**"
    - Enables **instant rotation** in set increments, helping prevent motion sickness.
    - Generally, it is recommended to use but sacrifices on immersion.

## **Hybrid Movement**
- Combines **teleportation & joystick movement**.
- Useful for applications requiring **precise & large-scale movement**.
