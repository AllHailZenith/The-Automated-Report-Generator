Phase 1
I created the abstract VehicleReport class with a generateReport() method that controls the order of the reporting steps. The collection and logging methods have default implementations, while formatting must be implemented by subclasses. This follows the Hollywood Principle because the parent class controls the workflow and calls the subclass method when needed.

Phase 2
I created TruckReport and BikeReport with different formatting methods. Both classes use the same collection and logging methods from the parent class. I learned how inheritance helps reduce duplicated code while allowing each vehicle to have its own behavior.

Phase 3
I added a boolean hook to control whether a maintenance check runs. Trucks override the hook to return true, while bikes use the default false value. I learned that hooks make it possible to add optional behavior without forcing every subclass to implement it.