# Modeling_Ecosystem_in_Simulated_Lake_Environment
# Modeling Complex Ecosystem Dynamics and Particle Movement in a Simulated Lake Environment

## Introduction
This project simulates the complex dynamics of an ecosystem within a simulated lake environment. It employs various parameters and mathematical models to study the behavior of the ecosystem components, including temperature, nutrients, algae, sediment, oxygen, and particle movement. Researchers and modelers can use this simulation to gain insights into how different parameters influence the lake's ecological processes over time.

## Getting Started
Before running the simulation, ensure you have the necessary Python libraries installed:

- NumPy (np): A fundamental package for numerical and scientific computations in Python. It efficiently manipulates large arrays and matrices.
- Matplotlib (plt): A 2D plotting library for creating static, interactive, and animated visualizations in Python. It can be used to create line plots, scatter plots, bar plots, and histograms.

## Parameters to Be Studied and Visualized
The simulation involves a wide range of parameters, each of which influences the lake ecosystem's behavior differently. Here is an overview of these parameters:

### Basic Parameters:
- `num_cells`: Represents the number of cells or grid points in the simulation domain. Increasing the number of cells provides finer spatial resolution but increases computational complexity.
- `num_time_steps`: Indicates the number of time steps the simulation will run for. More time steps capture longer-term system behavior but require more computation.
- `diffusion_coefficient`: Reflects how substances spread or diffuse through the medium. Higher values lead to faster spreading.
- `wind_speed_base`: Represents the base wind speed affecting the system. Increasing it amplifies the impact of wind-driven processes.

### Density-driven Flow Parameters:
- `density_coefficient`: Determines the influence of density differences in fluid flow. Higher values result in stronger flow variations due to density differences.
- `gravity`: Represents the acceleration due to gravity, impacting the density-driven flow. Greater gravity leads to more pronounced vertical movements in the fluid.

### Heat Source Parameters:
- `heat_source_center_x` and `heat_source_center_y`: Define the center of the heat source in the simulation, influencing where heat impacts the system most.
- `heat_source_strength`: Indicates the intensity of the heat source. Higher values result in higher temperature gradients and more intense localized effects.

### Pollution Source Parameters:
- `pollution_source_center_x` and `pollution_source_center_y`: Specify the center of the pollution source, determining the focal point of pollution dispersion.
- `pollution_source_strength`: Indicates the strength or amount of pollution being released. Higher values increase contamination levels.
- `pollution_source_time`: Refers to the time step when the pollution source becomes active.

### Nutrient and Algae Parameters:
- `initial_nutrient_concentration`: Represents the starting concentration of nutrients. Higher values boost initial algae growth.
- `nutrient_decay_rate`: Reflects the rate at which nutrients degrade over time. Increasing it accelerates nutrient depletion.
- `max_algae_growth_rate`: Indicates the maximum rate at which algae can grow. Higher values result in faster exponential algae population growth.
- `nutrient_algae_interaction`: Represents the effect of nutrients on algae growth. A stronger interaction indicates a more sensitive dependence of algae growth on nutrient levels.

### Sediment Parameters:
- `sediment_concentration`: Represents the initial concentration of sediment in cells.
- `sediment_deposition_rate`: Indicates the rate at which sediment settles. Higher rates lead to faster sediment accumulation.
- `sediment_resuspension_rate`: Represents the rate at which sediment is stirred up. Increasing it enhances sediment disturbance in the water column.

### Vertical Stratification Parameters:
- `thermal_mixing_depth`: Represents the depth at which stratification breaks due to mixing. A larger value allows for deeper mixing before stratification breaks.
- `mixing_coefficient`: Controls the strength of vertical mixing in the system. Higher values result in more vigorous vertical mixing and reduced stratification.

### Phytoplankton Parameters:
- `max_phytoplankton_growth_rate`: Indicates the maximum rate of phytoplankton growth. Higher values lead to faster algal blooms under favorable conditions.
- `phytoplankton_nutrient_half_saturation`: Reflects the nutrient level at which growth is halved. Higher values indicate phytoplankton's sensitivity to nutrient availability.

### Oxygen Parameters:
- `oxygen_production_rate`: Indicates the rate at which oxygen is produced. A higher rate enhances oxygen levels through photosynthesis.
- `oxygen_consumption_rate`: Represents the rate at which oxygen is consumed. Increasing it leads to faster oxygen depletion.

### Particle Tracking Parameters:
- `num_particles`: Specifies the number of particles for tracking. A larger number provides a more comprehensive view of particle dispersion but requires more computation.
- `particle_positions`: Contains initial positions of the particles. The initial particle position influences the starting points for tracking and observing particle movement.

## Simulation Steps
The simulation consists of several steps, each exploring different aspects of the lake ecosystem:

1. **Simulating Lake Circulation and Temperature Distribution:** This section initializes the lake with an initial temperature distribution and simulates lake circulation over time. It visualizes temperature distribution and wind speed variation.

2. **Exploring Nutrient Dynamics and Algae Growth:** This section simulates nutrient dynamics, including nutrient decay and pollution source effects, and explores algae growth based on nutrient availability. It visualizes nutrient concentration and algae density over time.

3. **Simulating Sedimentation Dynamics:** This section simulates sediment concentration dynamics over time and visualizes trends in sediment dynamics to gain insights into ecosystem health.

4. **Exploring Phytoplankton Growth and Oxygen Dynamics:** This section simulates the interaction between phytoplankton growth and oxygen concentration, providing insights into their pivotal roles in the ecosystem. It visualizes phytoplankton density and oxygen concentration over time.

5. **Particle Tracking and Lake Dynamics with Wind Effects:** This section simulates particle tracking, including advection and diffusion, to study particle movement in response to environmental forces. It visualizes particle tracking and includes additional visualizations such as particle displacement histogram, particle density heatmap, and Voronoi diagrams.

Feel free to modify the parameters and analyze how changes affect the lake ecosystem dynamics and particle movement.

Enjoy exploring the intricate dynamics of this simulated lake environment!

Author: Anandita Kaushal
Contact: 20bce034@nith.ac.in
