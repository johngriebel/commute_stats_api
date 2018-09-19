# Commute Stats API
At a high level, the idea behind this project is to create an application that tracks and analyzes
data about your daily commute, so that you can better anticipate changing traffic conditions. For 
example, Google Maps may indicate that route A will take 30 minutes to complete, but in reality
traffic worsens as you are on the route. This application will (in theory) account for that.

## Initial Roadmap
This is a preliminary, general list of features to be implemented.
- [ ] OAuth with Google, Facebook
- [ ] Integrate with Google Maps API for directions and traffic information
- [ ] For each commute, track the following information (at least):
    - [ ] start time
    - [ ] end time
    - [ ] route, meaning what roads were taken, and for how long
- [ ] Initial set of statistics to generate:
    - [ ] average commute time
    - [ ] average start time
    - [ ] average end time
    - [ ] Break down by day of week, and time splits (past week, month, 3 months, etc.)