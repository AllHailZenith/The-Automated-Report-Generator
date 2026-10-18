Phase 1
I created the abstract VehicleReport class with a generateReport() method that controls the order of the reporting steps. The collection and logging methods have default implementations, while formatting must be implemented by subclasses. This follows the Hollywood Principle because the parent class controls the workflow and calls the subclass method when needed.
