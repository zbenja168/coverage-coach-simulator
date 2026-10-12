# Coverage coach simulator

A browser demo of an ultrasound "completeness coach": an education tool that shows a learner which parts of a
target organ (here a simulated thyroid) they have not imaged yet.

Open it here: https://zbenja168.github.io/coverage-coach-simulator/

Your cursor is the probe on a simulated neck (left). A synthetic ultrasound image shows what the probe sees
(middle), and the coach's coverage map fills in as you sweep (right). Switch between probe-tracking methods,
block the camera, and watch how the map's accuracy changes.

Controls: move the mouse to scan, Q / E rotate the probe, A / D or Shift + scroll tilt it, hold B to block the
camera, scroll to change depth.

This is a teaching toy, not a medical device. The anatomy, image, and tracking noise are approximate. It does
not detect findings, make diagnoses, or tell anyone how to move a real probe.

Single HTML file, no build step, no dependencies beyond Google Fonts.
