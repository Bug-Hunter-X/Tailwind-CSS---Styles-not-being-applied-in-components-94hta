# Tailwind CSS - Styles Not Applied

This repository demonstrates a common issue when using Tailwind CSS: styles not being applied to components. The problem arises from an incorrect or missing `content` array in the `tailwind.config.js` file, which tells Tailwind where to find your components' source code to extract class names and apply the styles accordingly. 

The `bug.js` file showcases the incorrect configuration, leading to the styling issue. The `bugSolution.js` file provides the corrected configuration. 

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` to install the necessary dependencies.
3. Observe that the styles in `index.html` are not applied because of a missing or incorrect path.
4. Refer to `bugSolution.js` for the correct configuration to resolve the issue.  
