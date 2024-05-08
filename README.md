
# Satellite Tracking Software

This repository was created to submit the task assigned by Atom Space for an internship opportunity. The task was to write a simple Python program to retrieve the current location of the International Space Station (ISS) and display it as output in the following format: Latitude: x.ysas and Longitude: z.ysas. 

## How to Open the Jupyter Notebook

To open this file, clone the repository and open the Jupyter notebook either in VS Code or Jupyter Labs. Run the file, and in the output, you will see the Latitude and Longitude of the ISS.

## Designing Software to Track Multiple Satellites

If tasked with designing software to track multiple satellites in orbit, I would approach the problem by collecting relevant data and implementing efficient algorithms for tracking and collision detection. Here's how I would proceed:

1. **Collecting Data:** Gather data for all satellites through API calls or web scraping. The data to collect would include:
   - Unique ID of each satellite
   - Coordinates (Latitude and Longitude)
   - Altitude
   - Velocity
   - Orientation

2. **Implement Tracking Algorithms:** Develop algorithms to track multiple satellites simultaneously. These algorithms would continuously update the positions of satellites based on their current coordinates, velocities, and orientations.

3. **Collision Detection:** Implement collision detection algorithms to identify potential collisions between satellites. This involves analyzing the trajectories of satellites and predicting if they will intersect in orbit.

4. **Visualization:** Use the collected coordinates to plot satellites on an Earth map for visualization. This will provide a graphical representation of satellite positions relative to each other and the Earth's surface.

5. **User Interface:** Develop a user interface that allows users to interact with the software. Users should be able to view information about satellites, track their movements, and receive alerts for potential collisions.

By following these steps, we can create comprehensive software for tracking multiple satellites in orbit and ensuring their safe operation.


