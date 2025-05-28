class JrDeveloper:
    def __init__(self):
        self.firstname = "Rowel"
        self.lastname = "Cababan"

    def say_hi(self):
        return f"Howdy! I am {self.firstname} and I am still working on this repo. LOL"


if __name__ == '__main__':
    me = JrDeveloper()
    print(me.say_hi())
