### How To Use
---
1. Import XR Into Your Project
2. Import The OtherInputs Package
3. Thats It!
---
# Functions
---
# PrimaryPressed(yourHand)
example | if (OtherInputs.PrimaryPressed(YourHand))
              gameObject.SetActive(true)
---
# SecondaryPressed(yourHand)
example | if (OtherInputs.SecondaryPressed(YourHand))
              gameObject.SetActive(true)
---
# MenuButtonPressed()
example | if (OtherInputs.MenuButtonPressed)
              gameObject.SetActive(true)
---
# TriggerFloat(yourHand)
example | float ExampleFloat = OtherInputs.TriggerFloat()
---
# GripFloat(yourHand)
example | float ExampleFloat = OtherInputs.GripFloat()
---
