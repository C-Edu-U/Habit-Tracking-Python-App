# Habit-Tracking-Python-App

A basic skeleton for the habit tracking app in Python. This includes the main components and structure of the app:

The tasks attribute is removed from the Habit class initialization, as it will be managed dynamically by the add_task method.

In the HabitTracker class, the save_data method now converts the Habit instances to dictionaries before saving them to JSON, and the load_data method reconstructs Habit instances from the loaded dictionaries.
