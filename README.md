# Case Presenter--Ablation/Mapping Procedures

### [demo](https://case826.netlify.app/)

## Overview

Case Presenter is a mockup page designed specifically for the presentation of AFIB ablation procedures. The platform guides users through a comprehensive procedural flow to ensure all relevant data and activities are captured and presented in a structured manner.
![image](https://github.com/metatatt/handChecker/assets/100538673/68c6a5b8-3539-4c1e-b7c4-d6fe479fd332)

## Procedural Flow

The app supports the following flow:

1. **Integration with CPT Codes**: Leverage the Current Procedural Terminology (CPT) provided by AAPC to standardize and reference procedures.
2. **Upload Mapping Videos**: Users can upload their mapping videos which may include both the map wavefront log video and the associated log text.
3. **Identify EP Activities**: Highlight and document EP activities that take place in the lesion loci.
4. **Mapping Signal Types**: The platform supports various mapping signal types such as voltage, activation, and charge density.
5. **Optional Transseptal Access**: Depending on the procedure and user preference, transseptal access can be included.
6. **Post Ablation Mapping Video**: Capture and upload post-ablation videos to document results.
7. **Case Summary**: At the end of the flow, users can generate a summary of the entire case for review or presentation.

![image](https://github.com/metatatt/case826/assets/100538673/84eab349-273a-45a4-b1ae-0fb664d27bfa)

## Environment

The Case Presenter is built upon the following foundational structures and methodologies:

- **Single Page Application (SPA) Structure**: Ensuring seamless user experience, the application loads and dynamically updates a single HTML page, preventing the need for constant page refreshes.
- **JavaScript Bundling**: To optimize performance, JavaScript modules are bundled together. This not only reduces the number of HTTP requests but also enhances load times.
- **CSS Bundling**: Just like our JavaScript, stylesheets are also bundled to ensure the app loads efficiently, offering a streamlined user experience.

## Getting Started

(You might want to include instructions on how to set up, install, or use your app here. Example:)

1. Clone the repository.
2. Navigate to the directory.
3. Install required dependencies.
4. Run the app.
