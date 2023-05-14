```python
class Main:
    def __init__(self):
        self.name = ".rar"
        self.projects_in_bound = ["Discord token joiner", "Discord raider", "Discord aio"]
        
    def run(self):
        print(f"Name: {self.name}")
        print("Projects:")
        for project in self.projects_in_bound:
            print(f"- {project}")
            
Main().run()
