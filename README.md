# PersonalRepos 🖥️
# About Me!!

class SoftwareStudent:
    def __init__(self, name, age, university, field):
        self.name = name
        self.age = age
        self.university = university
        self.field = field
    
    def __str__(self):
        return f"Hello, I'm {self.name}, {self.age} years old, studying {self.field} at {self.university}."

# Instantiate "me" as an object
me = SoftwareStudent(
    name="Ghiyath Ali",
    age=25,
    university="VIA College, Denmark",
    field="Software Engineering"
)

print(me)
