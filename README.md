class Main():
    def __init__(self):
        self.name = ".rar"
        self.projects_in_bound = ["Discord token joiner", "Discord raider", "Discord aio"]
        
    def run(self):
        print(f"name: {self.name}\n")
        print("projects inbound\n")
        for i, project in enumerate(self.projects_in_bound):
            print(f"{project}")
            
if __name__ == "__main__":
    main = Main()
    main.run()
