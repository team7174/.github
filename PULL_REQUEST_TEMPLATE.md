## Description
<!-- Provide a detailed description of the changes. What problem does this solve? -->
**Resolves Issue:** #<!-- Insert issue number if applicable -->

## Type of Change
- [ ] 🐛 Bug Fix
- [ ] ✨ New Feature
- [ ] 🔧 Tuning / Calibration
- [ ] ♻️ Refactor / Code Cleanup
- [ ] 🗺️ Auto Pathing Update

## Testing & Verification
**How was this tested?**
- [ ] WPILib Build (`./gradlew build`) passes successfully with no new warnings.
- [ ] WPILib Simulation runs.
- [ ] Tested on Physical Robot.
    - **Robot:** <!-- e.g., Comp Bot, Practice Bot, Swerve Chassis -->
    - **Subsystems Active:** <!-- e.g., Intake, Shooter, DriveTrain -->

## Developer Checklist (Author)
- [ ] I have commented my code, particularly in hard-to-understand or math-heavy areas.
- [ ] Magic numbers and ports have been extracted to `Constants.h`.
- [ ] Memory Management: I have favored smart pointers (`std::unique_ptr`, `std::shared_ptr`) or references over raw pointers where applicable to prevent memory leaks.
- [ ] Unused variables, dead code, and `#include` clutter have been removed.
- [ ] I have tested that these changes do not break existing autonomous routines.

## Code Owner / Reviewer Checklist (For @team7174/Lead-Reviewers)
- [ ] Hardware interactions (motors, solenoids, sensors) are safe and will not cause physical damage on startup or enable.
- [ ] WPILib Command-Based framework is used correctly (e.g., Commands do not block the main robot loop with `while` loops).
- [ ] No obvious segmentation fault risks or null pointer dereferences.
- [ ] Code style matches the team's standard conventions.
