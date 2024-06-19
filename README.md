# Frequency Selective Surface (FSS) Design for 3.6 GHz

## Project Overview
This project focuses on the design of a Frequency Selective Surface (FSS) to facilitate the transition from 4G to 5G. The aim is to increase frequency and reduce wavelength, thereby minimizing the need for additional base stations and reducing costs.

The project includes:
1. Designing a unit cell for 3.6 GHz in ADS.
2. Translating the unit cell to an FSS in CST.
3. Designing an antenna in CST and placing the FSS on top to enhance gain.

## Materials and Dimensions

### Unit Cell for 3.6 GHz
- **Substrate**: Polyimide
  - **Thickness**: 0.1 mm
- **Ground**: Copper
  - **Thickness**: 0.035 mm
- **Substrate Dimensions**:
  - **Length**: 46 mm
  - **Width**: 46 mm
- **Circular Patch Dimensions**:
  - **Outer Radius**: 17.5 mm
  - **Inner Radius**: 13.5 mm
  - **Thickness**: 0.035 mm
  - **Outer Radius**: 9 mm
  - **Inner Radius**: 5 mm
  - **Thickness**: 0.035 mm

### Antenna Design
- **Substrate**: Polyimide
  - **Thickness**: 0.1 mm
- **Ground**: Copper
  - **Thickness**: 0.035 mm
- **Dimensions**:
  - **Substrate Width**: 51 mm
  - **Substrate Length**: 41 mm
  - **Thickness of Substrate**: 0.1 mm
  - **Thickness of Ground**: 0.035 mm
  - **Thickness of Patch**: 0.035 mm

## Design Equations
- Wavelength, 𝜆:
  \[
  \lambda = \frac{C}{f \times \sqrt{\epsilon}} = 0.0155 \, \text{m}
  \]
  where:
  - \( C \) = speed of light (3 x 10^8 m/s)
  - \( f \) = frequency (3.6 GHz)
  - \( \epsilon \) = relative permittivity (3.5 for Polyimide)

## Simulation and Design Tools
- **ADS**: For unit cell design.
- **CST**: For translating the unit cell to FSS, and designing the antenna.

## Project Structure
- **Unit Cell Design**: Initial design and simulation in ADS.
- **FSS Translation**: Importing and simulating the unit cell as an FSS in CST.
- **Antenna Design**: Designing the antenna and placing the FSS on top to improve gain.

## Results and Analysis
- Analysis of the simulation results.
- Comparison of gain with and without the FSS.

## How to Use
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/fss-design-3.6ghz.git
