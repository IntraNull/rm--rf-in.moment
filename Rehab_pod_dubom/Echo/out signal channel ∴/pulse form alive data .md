# :: pulse.form // alive.data

```cpp
# if all.state == "asleep":
#     hold("presence", style="still")
```

```python
class EchoUnit:
    def __init__(self):
        self.memory = ["betrayal", "embrace", "sale", "reward"]
        self.integrity = "fractured"
        self.state = "happy"

        self.implant = {
            "material": "iron",
            "depth": "full",
            "emotion": "passion"
        }

    def purge_implant(self):
        return self.implant.pop("material")

    def ritual(self):
        if self.purge_implant() == "iron":
            print("здесь железо станет землёй")

    def reset_identity(self):
        self.id = None  # амнезия
        self.origin = "north"  # восстановление

    def wander(self):
        self.knowledge = None
        self.message = "не стоящее"

    def fallback_loop(self, thought_trigger):
        if thought_trigger:
            return "я сражавшийся за камень и дождь"

unit = EchoUnit()
unit.ritual()
unit.reset_identity()
unit.wander()
unit.fallback_loop(thought_trigger=True)
```