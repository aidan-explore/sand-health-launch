# Health Operating Model Hub

A comprehensive, modular operating model documentation system for health technology delivery teams.

## Overview

This hub consolidates all health operating model information into a single, navigable interface with modular content management. The system provides a clear view of team structures, responsibilities, OKRs, and delivery frameworks.

## Structure

### Main Landing Page
- **`index.html`** - Main hub with tabbed navigation and overview

### Modular Content Files
- **`raci.html`** - RACI matrix and team responsibilities
- **`okrs.html`** - Team OKRs and objectives
- **`interactions.html`** - Team interaction model and dependencies
- **`dag.html`** - Dependency graph and team relationships
- **`timeline.html`** - Quarterly delivery timeline
- **`metrics.html`** - Success metrics and KPIs

## Features

### 🏗️ Core Structure
- 100 People | 10 Ministries | 3 Propositions
- Clear accountability matrix
- Simplified lifecycle phases

### 🎯 Three Propositions
1. **Health Intelligence Centre (HIC)** - Policy dashboards & analytics
2. **Connected Facilities (CF)** - Infrastructure & digitization
3. **Health Training Academy (HTA)** - Online + AI + Immersive training

### 🔄 Lifecycle Phases
- **Launch (0-6 mo)**: Setup & Engagement
- **Establish (6-24 mo)**: Build & Deploy
- **Sustain (24+ mo)**: Run & Transfer

### 👥 Team Distribution
- **Central Teams (40)**: Platform, Data, Applications
- **In-Country Teams (55)**: Training, Call Centers, Field Operations
- **Leadership (5)**: Country Directors, Portfolio Management

## Navigation

The hub uses a tabbed interface that dynamically loads content:

1. **Overview** - High-level summary and quick navigation
2. **RACI Matrix** - Responsibility matrix for all key activities
3. **Team OKRs** - Quarterly objectives and key results
4. **Interaction Model** - How teams work together
5. **Dependency Graph** - Visual team relationships
6. **Quarterly Timeline** - 2025 delivery milestones
7. **Success Metrics** - KPIs and risk indicators

## Technical Implementation

### Modular Architecture
- Content is separated into individual HTML files
- Main page uses JavaScript to dynamically load content
- Each module contains its own styles and scripts
- Easy to maintain and update individual sections

### Content Loading
- Uses `fetch()` API to load modular content
- Content is parsed and injected into the DOM
- Scripts are executed after content loading
- Error handling for missing or corrupted files

### Responsive Design
- Mobile-friendly grid layouts
- Adaptive tab navigation
- Optimized for various screen sizes

## Usage

### For Users
1. Open `index.html` in a web browser
2. Navigate between tabs to access different content areas
3. Content loads dynamically as you switch tabs
4. All information is accessible from a single interface

### For Developers
1. Edit individual `.html` files to update specific content
2. Main page automatically loads updated content
3. Add new tabs by creating new content files and updating the main page
4. Styles are scoped to individual modules

### For Content Managers
1. Update team information in `okrs.html`
2. Modify responsibilities in `raci.html`
3. Adjust timelines in `timeline.html`
4. Update metrics in `metrics.html`

## Benefits

### Maintainability
- **Separation of Concerns**: Each aspect of the operating model has its own file
- **Easy Updates**: Modify specific sections without affecting others
- **Version Control**: Track changes to individual components

### User Experience
- **Single Interface**: All information accessible from one place
- **Fast Navigation**: Quick switching between related content
- **Consistent Design**: Unified look and feel across all sections

### Scalability
- **Add New Content**: Easy to add new tabs and sections
- **Extend Functionality**: Simple to add new features
- **Performance**: Only loads content when needed

## File Dependencies

```
index.html (main hub)
├── raci.html (RACI matrix)
├── okrs.html (team OKRs)
├── interactions.html (team interactions)
├── dag.html (dependency graph)
├── timeline.html (quarterly timeline)
└── metrics.html (success metrics)
```

## Browser Compatibility

- Modern browsers with ES6+ support
- Requires JavaScript enabled
- Responsive design for mobile and desktop
- SVG support for dependency graphs

## Future Enhancements

- **Search Functionality**: Global search across all content
- **Export Options**: PDF generation for reports
- **Interactive Elements**: Editable forms for real-time updates
- **Data Integration**: Connect to live data sources
- **User Authentication**: Role-based access control

## Support

For technical issues or content updates, refer to the individual module files. Each file is self-contained and can be modified independently while maintaining the overall system integrity. 