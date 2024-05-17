# R2 Design System

This repository contains the SASS files for the R2 design system used in the "Race to End Alzheimer's" project. The design system is modular and follows the SMACSS (Scalable and Modular Architecture for CSS) methodology, making it easy to maintain and scale.

## File Structure

# R2 Design System

This repository contains the SASS files for the R2 design system used in the "Race to End Alzheimer's" project. The design system is modular and follows the SMACSS (Scalable and Modular Architecture for CSS) methodology, making it easy to maintain and scale.

## File Structure

- **_base.scss**: Contains the basic resets and foundational styles applied across the entire site. This includes global resets, HTML5 display-role resets, and base element styles.
- **_colors.scss**: Defines the color variables used throughout the project. This file helps maintain consistency and allows for easy theme changes.
- **_typography.scss**: Contains the typography styles for the project. It includes font settings for headings, paragraphs, and other text elements.
- **_layout.scss**: Defines the layout styles for the project, including spacing, alignment, and structural elements.
- **_buttons.scss**: Contains the styles for buttons and other actionable elements.

## Usage

To use these styles in your project, import the partials into your main SASS file.

```scss
@import 'base';
@import 'colors';
@import 'typography';
@import 'layout';
@import 'buttons';
