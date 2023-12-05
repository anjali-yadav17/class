# class
class Car:
    # Constructor (initializer method)
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year

    # Method to display information about the car
    def display_info(self):
        print(f"{self.year} {self.make} {self.model}")

# Creating instances of the Car class
car1 = Car("Toyota", "Camry", 2022)
car2 = Car("Honda", "Accord", 2021)

# Accessing attributes and calling methods
car1.display_info()  # Output: 2022 Toyota Camry
car2.display_info()  # Output: 2021 Honda Accord
